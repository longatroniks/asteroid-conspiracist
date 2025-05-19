# Asteroid Conspiracist

A mobile application that provides real-time data on near-Earth asteroids and preparedness tools for cosmic threats.

## Overview

Asteroid Conspiracist delivers critical information about potential asteroid threats to Earth. The app combines NASA's open data with community features to help users stay informed and prepared for possible cosmic events.

## Features

### Asteroid Tracking
- **Asteroid Browser**: View comprehensive data on near-Earth asteroids, including orbit details, size, and trajectory
- **Impact Probability Analysis**: Visual representation of potential impact risks through interactive pie charts
- **Distance Tracking**: Track asteroid distance from Earth over time with detailed bar graphs
- **Detailed Information**: Access comprehensive data about each asteroid's physical properties

### Community Features
- **UFO Sighting Reports**: Report and share unidentified object sightings with the community
- **Interactive Map**: View reported sightings with geolocation data
- **Real-time Updates**: Receive notifications about new sightings in your area

### Preparedness Tools
- **Shelter Locator**: Find private shelters in case of astronomical emergencies
- **Smart Compass**: Use the built-in compass to navigate to the nearest shelter
- **Shelter Management**: Add and maintain your own list of shelters

### Accessibility
- **Dark Mode**: Reduced eye strain and better visibility in low-light conditions
- **High Contrast Option**: Improved readability for visually impaired users
- **Customizable Text**: Adjustable font sizes and styles for better legibility

## Technical Architecture

### Data Sources
- NASA NEO API integration for asteroid data
- Community-reported sightings via MQTT protocol
- Local shelter database with geolocation

### Key Components
- MQTT client for real-time data exchange
- Google Maps API for location services
- Device sensors (accelerometer, magnetometer) for compass functionality
- MPAndroidChart library for data visualization

## Installation

```
git clone https://github.com/yourusername/asteroid-conspiracist.git
cd asteroid-conspiracist
```

Open the project in Android Studio and build with Gradle.

## Usage

1. Launch the app and navigate through the menu to access different features
2. Browse the asteroid list to view detailed information about potential threats
3. Check the impact probability charts for risk assessment
4. Use the compass to locate the nearest shelter in case of emergency
5. Report any unusual sightings through the UFO reporting feature

## Requirements

- Android 8.0 (Oreo) or higher
- Google Play Services
- Location permissions enabled
- Internet connectivity for asteroid data updates

## Future Enhancements

- Cloud-based database for cross-device synchronization
- Augmented reality visualization of asteroid trajectories
- Community collaboration tools
- Real-time alerts for newly detected threats
- Offline functionality for emergency situations
- Voice command integration
- Predictive analytics for risk assessment

## Acknowledgments

- NASA for providing open API access to NEO (Near-Earth Object) data
- HiveMQ for MQTT client libraries
- MPAndroidChart for data visualization components
