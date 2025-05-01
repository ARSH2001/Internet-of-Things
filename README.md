# Smart Electricity Consumption Monitoring System - 2021 ⚡️📡

[![Made With](https://img.shields.io/badge/Made%20with-Python%2C%20LoRa-blue)](https://shields.io/)
[![Course](https://img.shields.io/badge/Course-Internet%20of%20Things-red)](https://shields.io/)

---

## 📚 Table of Contents

- [About The Project](#about-the-project)
- [Project Components](#project-components)
  - [System Overview](#system-overview)
  - [Data Types and Applications](#data-types-and-applications)
  - [Urban Network](#urban-network)
  - [Home Network](#home-network)
  - [Urban Energy Consumption Data Analysis](#urban-energy-consumption-data-analysis)
- [How to Use](#how-to-use)

---

## 📖 About The Project

This repository contains the implementation of a smart electricity consumption monitoring system developed during the **Internet of Things** course in the Spring semester of 2021 at **Isfahan university of technology**. The system focuses on real-time monitoring of electricity usage through an online platform, leveraging **LoRa** communication technology and a mesh network architecture to enable efficient data collection and analysis.

---

## 📝 Project Components

### System Overview

This section provides a detailed description of the system, its components, and its functionality:

| Component | Description |
|-----------|-------------|
| **System Design** | An online platform for monitoring electricity consumption in urban and home environments. |
| **Functionality** | Collects and analyzes energy usage data, providing insights for optimization. |

> 📄 Detailed system specifications are available in the [System directory](https://github.com/ARSH2001/Smart-Electricity-Monitoring/tree/main/System).

### Data Types and Applications

This section outlines the types of data used in the system and their potential applications:

| Component | Description |
|-----------|-------------|
| **Data Types** | Includes electricity consumption metrics, timestamps, and device identifiers. |
| **Applications** | Enables energy optimization, demand forecasting, and user behavior analysis. |

> 📄 Data documentation is available in the [Data directory](https://github.com/ARSH2001/Smart-Electricity-Monitoring/tree/main/Data).

### Urban Network

This section covers the urban network infrastructure, divided into three subtopics:

| Component | Description |
|-----------|-------------|
| **Communication Technology** | Utilizes LoRa for primary communication, with NB-IoT as a backup, due to their low power and long-range capabilities. |
| **Network Data** | Transfers consumption metrics, device status, and environmental data over the network. |
| **Network Architecture** | Employs a mesh network to ensure robust data transmission and scalability. |

> 📄 Network details and configurations are available in the [Urban-Network directory](https://github.com/ARSH2001/Smart-Electricity-Monitoring/tree/main/Urban-Network).

### Home Network

This section explores the implementation of the system within a home network:

| Component | Description |
|-----------|-------------|
| **Home Integration** | Monitors electricity usage at the household level, addressing challenges like device compatibility and data privacy. |

> 📄 Home network setup instructions are available in the [Home-Network directory](https://github.com/ARSH2001/Smart-Electricity-Monitoring/tree/main/Home-Network).

### Urban Energy Consumption Data Analysis

This section provides an analysis of energy consumption data, divided into two subtopics:

| Component | Description |
|-----------|-------------|
| **Impact of Age and Building Size** | Analyzes how factors like building age and size influence energy consumption patterns. |
| **Data Variations** | Compares data from multiple sources to assess consistency and system performance. |

> 📄 Analysis scripts and results are available in the [Analysis directory](https://github.com/ARSH2001/Smart-Electricity-Monitoring/tree/main/Analysis).

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ARSH2001/Smart-Electricity-Monitoring.git
   cd Smart-Electricity-Monitoring
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the LoRa communication module:
   - Configure LoRa devices according to the provided firmware in the `Urban-Network` directory.
4. Deploy the monitoring system:
   - Follow setup scripts in the `System` directory to initialize the platform.
5. Analyze consumption data:
   - Run analysis scripts in the `Analysis` directory to generate insights.

---
