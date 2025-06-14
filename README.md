# Brain-Computer Interface for Computer Interaction

A system to acquire and store raw brain activity data while users perform computer actions (e.g., opening an app, clicking the mouse), enabling research and development of brain-controlled interfaces.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Components](#components)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Contact](#contact)

## Overview

This project collects raw brain activity data (e.g., EEG signals) while users perform specific computer actions such as opening applications or clicking the mouse. The goal is to enable the development of brain-controlled interfaces by providing a robust dataset for signal processing and machine learning research.

## Features

- **Raw Data Collection:** Captures and stores unprocessed brain activity signals during user actions.
- **Action Synchronization:** Logs timestamps of computer events (app launch, mouse click) alongside brain data.
- **Data Export:** Saves data in standard formats (e.g., .csv, .edf) for analysis.
- **User-Friendly Interface:** Provides a simple GUI or script for starting/stopping data collection.
- **Calibration:** Allows system calibration for individual users to improve data quality.

## Components

1. **Signal Acquisition Device:** EEG headset or other non-invasive sensor.
2. **Processing Unit:** Computer to run the data collection software.
3. **Data Logger:** Software module to record brain signals and event timestamps.
4. **Output Handler:** Optional module to trigger computer actions or log user events.

