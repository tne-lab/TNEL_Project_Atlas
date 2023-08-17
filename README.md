# TNEL Project Atlas
This serves as an entrance to a realm of sought-after code, capable of resolving one of your challenges. Make a prudent selection to foster your wisdom.


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
| Plugin GUI | TNE's version of the Open Ephys GUI  | [tnel-master](https://github.com/tne-lab/plugin-GUI) |

| **SOURCES**| |  |
| Neuralynx | Receives data from neuralynx. | [master](https://github.com/tne-lab/neuralynx-plugin.git)|
| LSL-inlet | Receives data and event markers through the [LSL protocol](https://labstreaminglayer.org/#/). | [master](https://github.com/tne-lab/LSL-inlet) <br /> [v6 downgrade](https://github.com/tne-lab/LSL-inlet/tree/v6-downgrade) |
| Network Events | Receiving events from other components. | [main](https://github.com/open-ephys-plugins/network-events.git) |
| NWBFormat | A format to record to files based on the Neurodata Without Borders 1.0 specification.| [master](https://github.com/tne-lab/NWBFormat.git)|

| **FILTER**| |  |
| Phase Calculator (TORTE) | Estimates the phase of inputs within a specified passband in real time. | [main](https://github.com/tne-lab/TORTE.git)
| Crossing Detector | Detects when signals rise and fall across thresholds. Typically used in combination with the phase calculator.  | [master](https://github.com/tne-lab/crossing-detector) |
| Mean Spike Rate | Estimates an exponentially-weighted recent spike rate over time and channels. | [master](https://github.com/tne-lab/mean-spike-rate/tree/master) |
| Sample Math | Performs simple samplewise arithmetic on continuous channels  | [master](https://github.com/tne-lab/sample-math/tree/master) |
| Independent component analysis | This plugin for the Open Ephys GUI allows you to decompose incoming data using ICA | [master](https://github.com/tne-lab/ica-plugin.git) |
| continuous-stats | Plugin for the Open Ephys GUI to compute the exponentially weighted sliding mean or standard deviation of incoming continuous data. | [master](https://github.com/tne-lab/continuous-stats.git) |

| **SINKS**| |  |
| Coherence Spectrogram Viewer | Plots coherance and spectrogram (power vs. frequency)  | [master](https://github.com/tne-lab/Coherence-Spectrogram-Viewer) |
| Event broadcaster | Sending events to other software communicating with open ephys | [main](https://github.com/tne-lab/event-broadcaster.git) |

## Analysis tool
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Set Shift project**| |  |
|Set Shift project|The code Ellie and Evan generally use for Setshift related things|[main](https://github.com/tne-lab/ee-lib)|
| **Device project**| |  |
|ASIC project|Code related to ASIC device|[main](https://github.com/tne-lab/ASIC-testing-v2.git)|
|Device data pipeline|Code related to device project data analysis|[master](https://github.com/tne-lab/device-data-pipeline.git)|
|mtm coh|Code related to device project data analysis|[main](https://github.com/tne-lab/mtm-coh.git)|
| **Addiction project**| |  |
|Addiction project|Addiction project|[master](https://github.com/tne-lab/addiction_project2)|
| **Data fetching and TFR analysis**| |  |
| matlab-tnel-analysis-code | Code to calculate the time frequency analysis in matlab | [main](https://github.com/tne-lab/matlab-tnel-analysis-code.git) |
| **LabVIEW Stim**| |  |
| Closed loop stim | This repository mainly houses LabVIEW code for receiving TTL events from the Open Ephys GUI and outputting stimulation pulses on an NI DAQ in response. There are also general VIs for interfacing with Open Ephys in other ways.| [main](https://github.com/tne-lab/closed-loop-stim.git) |
| **Real time ERP**| |  |
| real-time-ERP| This repository contains a plugin for the Open Ephys GUI. This plugin provides the user with the ability to visualize and calculate event related potentials in real time from a variety of event sources.| [master](https://github.com/tne-lab/real-time-ERP.git) |

## Phase calculator
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Phase calculator simulations**| MTALAB version of our TORTE phase calculator. (hilbert_transformer_phase.m) | [matlab code](https://github.com/tne-lab/closed-loop-matlab/blob/master/simulation/hilbert_transformer_phase.m) |

## Pybehav
| Project Name | Description | Active branch(es) |
| --- | --- | --- |
| **Python behaviour code (old)** | This repository houses the code to control the behavior chamber, this is one older version. | [exp-class](https://github.com/tne-lab/py-behav-box.git) |
| **Python behaviour code version 2** | This repository houses the code to control the behavior chamber, this is newer version. | [master](https://github.com/tne-lab/py-behav-box-v2.git) |

## Libraries
| Library | Description | Active branch(es) |
| --- | --- | --- |
| **Fieldtrip** | Fieldtrip library. | [download](https://www.fieldtriptoolbox.org/download/) |
| **analysis-tool** | This repository contains code to read and convert open ephys data to matlab. | [master](https://github.com/tne-lab/analysis-tools.git) |
| **py-tools** | Code includes analysis of open ephys data in python, along with code for controlling other components such as camera. | [master](https://github.com/tne-lab/py-tools.git) |
| **npy matlab**| Code to read and write NumPy's NPY format (.npy files) in MATLAB. | [master](https://github.com/tne-lab/npy-matlab.git) |
| **compass toolkit py**| Code for the compass toolkit for the encoding and decoding of the states in python. | [main](https://github.com/tne-lab/compass-toolkit-python.git) |
| **OpenEphysFFTW**| This is a small library to wrap FFTW functionality useful for Open Ephys. | [master](https://github.com/tne-lab/OpenEphysFFTW.git) |
| **OpenEphysHDF5Lib**| A common library for all formats that write HDF5 files. | [master](https://github.com/tne-lab/OpenEphysHDF5Lib.git) |
| **KWIKFormat**| A plugin to record to and read from files based on the KWIK specification. | [master](https://github.com/tne-lab/KWIKFormat.git) |

## Lab Papers
| Paper | Description |
| --- | --- | 
| [Olsen et al. (2020, Frontiers in Human Neuroscience) Analysis.](https://github.com/tne-lab/Olsen-et-al-2020.git)| This script produces most of the figures in this article. The article details the case report of the first participant in this clinical trial.| 
| [MSIT-Nature-Biomedical-Engineering](https://github.com/tne-lab/MSIT-Nature-Biomedical-Engineering.git) | MSIT-Nature-Biomedical-Engineering paper  |
| [DBSParameterOptimization2022](https://github.com/tne-lab/DBSParameterOptimization2022.git) | Code for simulation of DBS optimization. | 
| [Headstage-accelerometry-paper-2022](https://github.com/tne-lab/Headstage-accelerometry-paper-2022.git) | Code for simulation of Headstage-accelerometry-paper-2022. |
| [Widge-Tractography-2021 ](https://github.com/tne-lab/Widge-Tractography-2021.git) | Analysis code for the Widge tractography 2021 paper.|
