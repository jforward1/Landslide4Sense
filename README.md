# Landslide4Sense Modeling

## Overview
This project aims to build a U-Net++ deep learning model to segment landslides from relevant imagery. Remotely sensed data from Sentinel-2 is used, along with slope and DEM, to train the model to identify regions that have been affected by landslide activity. There is a start to using the model as a means to predict regions most susceptible to landslides as well.

---

# Research Questions
Through this project I aim to answer the following:
- Can we train a machine learning model to segment regions affected by landslides?
- Can we use the model to predict locations that are most likely to be affected by landslides?
- Can we achieve similar results on less input data/bands from the imagery?

# Data Description
- **Data Source:** [Landslide4Sense](https://github.com/iarai/Landslide4Sense-2022?tab=readme-ov-file#landslide4sense-2022)
- **14 Bands/Channels Total**
  - 12 From Sentinel-2
  - Slope
  - Digital Elevation Model (DEM)
