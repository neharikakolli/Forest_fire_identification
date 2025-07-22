# Forest_fire_identification
This project aims to develop an automated forest fire detection system that an real-time video footage from Unmanned Aerial Vehicles (UAVs) using Python-based computer vision and machine learning techniques. The system enhances early detection capabilities, enabling rapid response to minimize environmental and economic damage caused by wildfires.

# 🚁 Forest Fire Identification Using UAV Video Monitoring

A real-time forest fire detection system using Unmanned Aerial Vehicles (UAVs) and advanced image processing techniques. This project leverages motion analysis, color feature extraction, and wavelet transformation to identify fires in aerial surveillance video footage.

## 📌 Project Overview

This system is designed to monitor forest environments using UAVs and automatically detect potential fire outbreaks from captured video. Early detection of forest fires plays a crucial role in minimizing environmental and economic damages and improving response times.

## 🎯 Objectives

- Develop a real-time fire detection system based on UAV video footage.
- Use image processing techniques to identify fire patterns.
- Reduce false alarms by analyzing motion, color, and texture features.
- Integrate machine learning models like EfficientNet with classifiers (BiLSTM, SVM, RF).

## 🧠 Features

- 🔥 Real-time fire and smoke detection from aerial video.
- 🎯 Motion Detection using Optical Flow.
- 🎨 Fire region detection using HSV color filtering.
- 📊 Texture & wavelet feature analysis to reduce false positives.
- 📍 GPS-based geo-tagging (planned feature).
- 📈 Confusion matrix and performance metrics display.
- 🧪 Tested on sample UAV fire datasets.

## 🖼️ System Architecture

- **Video Input** → **Motion Detection** → **Color Feature Analysis** → **Wavelet & Texture Extraction** → **Fire Detection Decision**

## ⚙️ Technologies Used

| Category           | Tech Stack                         |
|--------------------|------------------------------------|
| Language           | Python 3.x                         |
| GUI                | Tkinter                            |
| Image Processing   | OpenCV                             |
| ML Models          | EfficientNet + BiLSTM, SVM, RF     |
| Video Analysis     | Dense Optical Flow                 |
