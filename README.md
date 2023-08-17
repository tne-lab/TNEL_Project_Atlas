# TNEL Project Atlas
Please add project name, clear description (please be brief), and links to relevant GitHub folder. Kindly indicate active branch. This ensures accurate, up-to-date information for a comprehensive understanding of the project. Thank you.


## Table of Contents
* [Open ephys installation](#open-ephys-plugins)
* [Open ephys plugins](#open-ephys-installation)
* [Analysis tool](#analysis-tool)
* [PyBehav](#pybehav)
* [Libraries](#libraries)
* [Lab Papers](#lab-papers)

## Open ephys installation
| Installation | Description |
| --- | --- | 
| [Open Ephys installation](https://github.com/tne-lab/oep-installation.git) | Scripts for easy installation of Open Ephys and useful plugins.

## Open ephys plugins
| Plugin Name | Description | Active branch(es) |
| --- | --- | --- |
| **Overall GUI**| |  |
| Plugin GUI | TNE's version of the Open Ephys GUI  | [link](https://github.com/tne-lab/plugin-GUI) |
| **SOURCES**| |  |
| Neuralynx | Receives data from neuralynx. | [link](https://github.com/tne-lab/neuralynx-plugin.git)|
| LSL-inlet | Receives data and event markers through the [LSL protocol](https://labstreaminglayer.org/#/). | [link](https://github.com/tne-lab/LSL-inlet) <br /> [v6 downgrade](https://github.com/tne-lab/LSL-inlet/tree/v6-downgrade) |
| **FILTER**| |  |
| Phase Calculator (TORTE) | Estimates the phase of inputs within a specified passband in real time. | [link](https://github.com/tne-lab/TORTE.git)
| Crossing Detector | Detects when signals rise and fall across thresholds. Typically used in combination with the phase calculator.  | [link](https://github.com/tne-lab/crossing-detector) |
| Mean Spike Rate | Estimates an exponentially-weighted recent spike rate over time and channels. | [link](https://github.com/tne-lab/mean-spike-rate/tree/master) |
| Sample Math | Performs simple samplewise arithmetic on continuous channels  | [link](https://github.com/tne-lab/sample-math/tree/master) |
| Independent component analysis | This plugin for the Open Ephys GUI allows you to decompose incoming data using ICA | [link](https://github.com/tne-lab/ica-plugin.git) |
| **SINKS**| |  |
| Coherence Spectrogram Viewer | Plots coherance and spectrogram (power vs. frequency)  | [link](https://github.com/tne-lab/Coherence-Spectrogram-Viewer) |

## Analysis tool
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Set Shift project**| |  |
|Set Shift project|The code Ellie and Evan generally use for Setshift related things|[link](https://github.com/tne-lab/ee-lib)|
| **Device project**| |  |
|ASIC project|Code related to device project|[link](https://github.com/tne-lab/ASIC-testing-v2.git)|
|Device data pipeline|Code related to device project data analysis|[link](https://github.com/tne-lab/device-data-pipeline.git)|
|mtm coh|Code related to device project data analysis|[link](https://github.com/tne-lab/mtm-coh.git)|
| **Addiction project**| |  |
|Addiction project|Addiction project|[link](https://github.com/tne-lab/addiction_project2)|
| **Data fetching and analysis**| |  |
| matlab-tnel-analysis-code | Code to calculate the time frequency analysis in matlab | [link](https://github.com/tne-lab/matlab-tnel-analysis-code.git) |

## Phase calculator
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| Phase calculator simulations| MTALAB version of our TORTE phase calculator. (hilbert_transformer_phase.m) | [link](https://github.com/tne-lab/closed-loop-matlab/blob/master/simulation/hilbert_transformer_phase.m) |

## Pybehav
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Python behaviour code (old)**| |  |
| py-behav-box | This repository houses the code to control the behavior chamber, this is one older version. | [link](https://github.com/tne-lab/py-behav-box.git) |
| **Python behaviour code version 2**| |  |
| py-behav-box-2 | This repository houses the code to control the behavior chamber, this is newer version. | [link](https://github.com/tne-lab/py-behav-box-v2.git) |

## Libraries
| Library | Description | Active branch(es) |
| --- | --- | --- |
| **Fieldtrip**| |  |
| Fieldtrip | Fieldtrip library. | [link](https://www.fieldtriptoolbox.org/download/) |
| analysis-tool | This repository contains code to read and convert open ephys data to matlab. | [link](https://github.com/tne-lab/analysis-tools.git) |
| py-tools | Code includes analysis of open ephys data in python, along with code for controlling other components such as camera. | [link](https://github.com/tne-lab/py-tools.git) |
| **For plugin development**| |  |
| JUCE| List of function readilly available to be used in the plugin. | [link](https://docs.juce.com/develop/index.html) |
| **Compass Toolkit TNEL**| |  |
| compass-toolkit-python| Code for the compass toolkit for the encoding and decoding of the states in python. | [link](https://github.com/tne-lab/compass-toolkit-python.git) |

## Lab Papers
| Paper | Description |
| --- | --- | 
| [Olsen et al. (2020, Frontiers in Human Neuroscience) Analysis.](https://github.com/tne-lab/Olsen-et-al-2020.git)| This script produces most of the figures in this article. The article details the case report of the first participant in this clinical trial.| 
| [MSIT-Nature-Biomedical-Engineering](https://github.com/tne-lab/MSIT-Nature-Biomedical-Engineering.git) | MSIT-Nature-Biomedical-Engineering paper  |
| [DBSParameterOptimization2022](https://github.com/tne-lab/DBSParameterOptimization2022.git) | Code for simulation of DBS optimization. | 
| [Headstage-accelerometry-paper-2022](https://github.com/tne-lab/Headstage-accelerometry-paper-2022.git) | Code for simulation of Headstage-accelerometry-paper-2022. |
