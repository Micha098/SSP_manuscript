<div align="center">
  <table>
    <tr>
      <td align="left" width="33%">
        <img src="./images/BGU_logo.png" width="200"/>
      </td>
      <td align="center" width="50%">
        <h1></h1>
      </td>
      <td align="right" width="33%">
        <img src="./images/Simons_logo.png" width="200"/>
      </td>
    </tr>
  </table>
</div>


# Simons Sleep Project (SSP) Analysis Tools

## Overview
The Simons Sleep Project (SSP) is a comprehensive open resource designed to accelerate sleep research in autism and other neurodevelopmental conditions. The project contains data collected from 102 autistic adolescents and 100 of their non-autistic siblings, offering unique insights into sleep patterns and their relationship with neurodevelopmental symptoms.

## Dataset Description

### Multi-Device Recording System
The SSP utilizes three complementary devices selected for their ability to record and save raw sensor-level data:

1. **Dreem3 EEG Headband (Beacon Inc.)**
   - Electroencephalogram (EEG) recordings
   - Head movement data
   - Enables direct identification of sleep stages and sleep architecture

2. **EmbracePlus Smartwatch (Empatica Inc.)**
   - Multi-sensor recordings including:
     - Accelerometer data
     - Electrodermal activity
     - Skin temperature
     - Blood volume pulse

3. **Withings Sleep Mat**
   - Non-contact sleep monitoring
   - Breathing patterns
   - Movement detection
   - Heart rate

### Additional Data Sources
- Daily sleep diary entries
- Nine parent questionnaires completed at baseline
- Comprehensive demographic and clinical information

## Repository Contents

This repository provides Python notebooks and scripts for:
1. Basic data exploration and visualization of summarized sleep metrics
2. Demographics analysis of the study population
3. Assessment of recording coverage across devices

## Sample Characteristics
- Age range: 10-17 years
- Balanced sex distribution
- Includes siblings living in the same household
- Documentation of ADHD comorbidity
- Over 3,600 nights of recordings

## Getting Started
The Jupyter notebooks in this repository demonstrate:
- Basic demographic analysis of the study population
- Visualization of recording coverage across devices
- Initial exploration of sleep metrics
- Cross-device comparison of key sleep parameters


**Important Note:** The visualizations and analyses in this repository are conducted on summarized sleep metrics (e.g., total sleep time, wake after sleep onset, sleep onset latency) and demographic data. The raw sensor data (EEG signals, accelerometer data, etc.) are not included in these basic visualization tools but are available in the complete dataset.
