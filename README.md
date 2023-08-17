# TNEL Project Atlas
Please add project name, clear description (please be brief), and links to relevant GitHub folder. Kindly indicate active branch. This ensures accurate, up-to-date information for a comprehensive understanding of the project. Thank you.


## Table of Contents
* [Open ephys installation](#open-ephys-plugins)
* [Open ephys plugins](#open-ephys-installation)
* [Analysis tool](#analysis-tool)
* [COMPASS toolkit](#compass-toolkit)
* [PyBehav](#pybehav)
* [Libraries](#libraries)
* [Lab Papers](#lab-papers)

## Open ephys installation
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| Open Ephys installation | Scripts for easy installation of Open Ephys and useful plugins. | [master](https://github.com/tne-lab/oep-installation.git)

## Open ephys plugins
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Overall GUI**| |  |
| Plugin GUI | TNE's version of the Open Ephys GUI  | [master](https://github.com/tne-lab/plugin-GUI) |
| **SOURCES**| |  |
| LSL-inlet | Receives data and event markers through the [LSL protocol](https://labstreaminglayer.org/#/). | [master](https://github.com/tne-lab/LSL-inlet) <br /> [v6 downgrade](https://github.com/tne-lab/LSL-inlet/tree/v6-downgrade) |
| **FILTER**| |  |
| Phase Calculator (TORTE) | Estimates the phase of inputs within a specified passband in real time. | [master](https://github.com/tne-lab/TORTE.git)
| Crossing Detector | Detects when signals rise and fall across thresholds. Typically used in combination with the phase calculator.  | [master](https://github.com/tne-lab/crossing-detector) |
| Mean Spike Rate | Estimates an exponentially-weighted recent spike rate over time and channels. | [master](https://github.com/tne-lab/mean-spike-rate/tree/master) |
| Sample Math | Performs simple samplewise arithmetic on continuous channels  | [master](https://github.com/tne-lab/sample-math/tree/master) |
| Independent component analysis | This plugin for the Open Ephys GUI allows you to decompose incoming data using ICA | [master](https://github.com/tne-lab/ica-plugin.git) |
| **SINKS**| |  |
| Coherence Spectrogram Viewer | Plots coherance and spectrogram (power vs. frequency)  | [master](https://github.com/tne-lab/Coherence-Spectrogram-Viewer) |

## Analysis tool
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
|Set Shift project|The code Ellie and Evan generally use for Setshift related things|[master](https://github.com/tne-lab/ee-lib)|
|Device project|Code related to device project|[master](https://github.com/tne-lab/ASIC-testing-v2.git)|
|device-data-pipeline|Code related to device project data analysis|[master](https://github.com/tne-lab/device-data-pipeline.git)|
|mtm-coh|Code related to device project data analysis|[master](https://github.com/tne-lab/mtm-coh.git)|
|addiction_project|Addiction project |[master](https://github.com/tne-lab/addiction_project2)|

| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| matlab-tnel-analysis-code | Code to calculate the time frequency analysis in matlab | [master](https://github.com/tne-lab/matlab-tnel-analysis-code.git) |

## Phase calculator
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| Phase-calculator-maltab| MTALAB version of our TORTE phas calculator. (hilbert_transformer_phase.m) | [master](https://github.com/tne-lab/closed-loop-matlab/blob/master/simulation/hilbert_transformer_phase.m) |

## COMPASS toolkit
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| compass-toolkit-python| Code for the compass toolkit for the encoding and decoding of the states in python. | [master](https://github.com/tne-lab/compass-toolkit-python.git) |


## Pybehav
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| py-behav-box | This repository houses the code to control the behavior chamber, this is one older version. | [master](https://github.com/tne-lab/py-behav-box.git) |
| py-behav-box-2 | This repository houses the code to control the behavior chamber, this is newer version. | [master](https://github.com/tne-lab/py-behav-box-v2.git) |

## Libraries
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| Fieldtrip | Fieldtrip library. | [master](https://www.fieldtriptoolbox.org/download/) |
| analysis-tool | This repository contains code to read and convert open ephys data to matlab. | [master](https://github.com/tne-lab/analysis-tools.git) |
| py-tools | Code includes analysis of open ephys data in python, along with code for controlling other components such as camera. | [master](https://github.com/tne-lab/py-tools.git) |
| JUCE| List of function readilly available to be used in the plugin. | [master](https://docs.juce.com/develop/index.html) |


## Lab Papers
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| DBSParameterOptimization2022 | Code for simulation of DBS optimization. | [master](https://github.com/tne-lab/DBSParameterOptimization2022.git) |
