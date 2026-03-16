# Source Code Documentation Collinearity Model

This repository contains the source code for:

Beuth and Kowerko (2026). “On the Transfer of Collinearity to Computer Vision”.

It provides a model of collinearity.

## Author(s):
Frederik Beuth (Dr. Frederik Beuth, frederik.beuth@posteo.de).

## Quickstart
A Linux/GNU operating system is required to run the model. Windows might work too, but it is not tested.

The model is programmed in Matlab, and tested with versions as Matlab 2018a or newer. Requirements and toolboxes: None

From the main folder, you can then run main.m as a demonstration example, or experimentLineLength.m as an experiment example from the research manuscript.

## Demonstration example
This Matlab script, main.m, provides a demonstration example of the collinearity model. After opening Matlab, you should be able to run main.m. It uses an image as a toy example, and shows on it the model responses of each layer. The main.m file contains the full model, i.e. Gabor layer, pool layer, and collinearity layer. The input image can be changed, see the beginning of the file. The file contains a GUI showing all the layers and information. 

## Experiment example
Secondly, there is a full experiment as shown in the manuscript provided. After opening Matlab, you should be able to run experimentLineLength.m. The experiment examines the influence of the line length on the collinearity influence by systematically vary its length, and it is is illustrated in Fig. 9. The experiment example might serve as a blueprint for other experiments. 

## Further usage
For more in-depth instructions, please read the documentation in the docuSourcecode/ directory by opening the index.html file. This includes information about:
- Installing and setting up the model in different environments
- General instructions about the usage of the model
- Overview for the folder structure of this repository and some descriptions for important files

## Directory structure
- root directory: main files for the collinearity model
- docuSourcecode/: Documentation ([Link](https://fbeuth.github.io/collinearity/docuSourcecode/index.html))
- data/: Data directory
- matlabLibs/: Helper Matlab Files
## License
The model is licensed under the Apache License 2.0 License. You should have received a copy of the License along with this program. If not, see https://www.apache.org/licenses/
