# Cloud-Detection-in-Area-of-Taiwan-and-Southeast-China
Using IRIS and CNN (Supervised model_Convolutional Neural Networks) for Cloud Detection in Area of Taiwan and Southeast China
---

## Project Overview
Recently, a 7.3-magnitude earthquake occurred in the waters near Hualien, Taiwan, causing huge damage to property and people. Some studies have shown that before an earthquake occurs, local clouds will have characteristics that allow forecasters to make predictions (Guangmeng & Jie, 2013).

Therefore, this project aims to use IRIS and CNN model to detect the cloud in in area of Taiwan and Southeast China.


## Background
A recent study highlighted the potential of using satellite cloud images for earthquake prediction, citing specific cloud characteristics observable before seismic events. This project uses data from the Copernicus Sentinel-3 satellite, which is equipped with instruments suitable for maritime, land, and atmospheric monitoring.

## Dataset
The IRIS dataset includes labeled images classified into 'Clear' and 'Cloud' categories, used for training our CNN model.

### Sentinel-3 Satellite Details
- **Altitude:** 814.5 km
- **Inclination:** 98.65 degrees
- **Orbit Period:** 100.99 minutes
- **Operational Lifetime:** 7 years, extendable to 12 years with onboard propellant

### Instruments
- **OLCI:** Used for screening the ocean and land surfaces.
- **SLSTR:** Employed for maritime and land monitoring, atmospheric studies, and climate research.
- **Altimetry:** Analyzes ocean topography, sea level, wave height, and ocean currents.

## Model Architecture
The CNN model used in this project consists of:
- **Convolution Layers:** Extract features by sliding filters across the image.
- **Pooling Layers:** Reduce spatial dimensions (width and height) of the feature map.
- **Fully Connected Layers:** Integrate information from feature maps to make final classification decisions.

## Installation
```bash
git clone https://github.com/LiningChen/Cloud-Detection-in-Area-of-Taiwan-and-Southeast-China
cd cloud-detection-cnn
```

## Usage
Run the detection model using:
```bash
python detect_clouds.py
```

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments
- **Guangmeng G. & Jie Y.** for their foundational research on earthquake prediction using satellite images.
- **Copernicus Sentinel-3** data used under the European Space Agency (ESA) data policy.
---
