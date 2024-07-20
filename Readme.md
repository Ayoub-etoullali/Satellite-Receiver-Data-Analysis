# Satellite Receiver Data Analysis

This project involves the analysis of a dataset containing measurements related to the satellite receiver of the Azrou center. The dataset includes various metrics and states for audio levels, decoder resets, buffer levels, and transport stream errors, among others.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Analysis](#analysis)
  - [Descriptive Statistics](#descriptive-statistics)
  - [Correlation Analysis](#correlation-analysis)
  - [Time Series Analysis](#time-series-analysis)
  - [Anomaly Detection](#anomaly-detection)
- [Insights](#insights)

## Project Overview

This project aims to explore and analyze a dataset from the Azrou center's satellite receiver system. The primary focus is on audio-related features, including audio levels, decoder resets, buffer levels, and transport stream errors. By examining these features, we aim to gain insights into the system's performance and identify any potential issues.

## Dataset Description

The dataset consists of multiple columns, including:

- **Audio Levels:** `audioLevel1`, `audioLevel2`, `audioLevel3`, `audioLevel4`
- **Audio Decoder Resets:** `audioDecoderResets1`, `audioDecoderResets2`, `audioDecoderResets3`, `audioDecoderResets4`
- **Audio Buffer Levels:** `audioBufferlevel1`, `audioBufferlevel2`, `audioBufferlevel3`, `audioBufferlevel4`
- **Audio Transport Stream Errors:** `audioTsError1`, `audioTsError2`, `audioTsError3`, `audioTsError4`

These features provide valuable insights into the audio performance and potential issues in the satellite receiver system.

## Analysis

### Descriptive Statistics

Descriptive statistics provide a summary of the central tendencies, dispersion, and distribution of the audio features. The key statistics calculated include the mean, median, standard deviation, minimum, and maximum values for each feature.

### Correlation Analysis

Correlation analysis helps in understanding the relationships between different audio features. By examining the correlation matrix, we can identify which features are closely related and how changes in one feature might affect others.

### Time Series Analysis

Time series analysis involves plotting the audio features over time to observe trends, patterns, and any seasonality. This helps in understanding how the system's performance changes over time and identifying any long-term trends or irregularities.

### Anomaly Detection

Anomaly detection focuses on identifying outliers or unusual patterns in the data. By calculating the z-scores for each audio feature, we can detect significant deviations from the norm, indicating potential issues in the system.

## Insights

- **Audio Levels:** The mean and standard deviation of audio levels indicate the typical range and variability in audio performance.
- **Decoder Resets:** Frequent resets might indicate stability issues with the audio decoders.
- **Buffer Levels:** Consistent buffer levels are crucial for smooth audio playback. Variability might indicate buffering issues.
- **Transport Stream Errors:** High error rates can affect audio quality and indicate potential issues in data transmission.

<kbd>Enjoy Code</kbd> 👨‍💻
[My portfolio](https://ayoub-etoullali.netlify.app/)
