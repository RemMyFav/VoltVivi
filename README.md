# VoltVivi

## Project Overview

VoltVivi is an innovative application designed to help users manage and monitor their energy levels through a fun and engaging interface. At the heart of the app is a small robot named Vivi, who consumes batteries to represent different activities in daily life. Each type of battery corresponds to various actions, such as eating, sleeping, and studying, with different energy values. The more batteries Vivi consumes, the better its condition. Conversely, activities that require energy, like working or cooking, deplete Vivi's energy levels.

An interesting feature of VoltVivi is its dynamic assessment system. Users are asked to assign energy values to activities, reflecting their personal perception of energy expenditure. Additionally, users provide feedback on Vivi's status, mirroring their own energy levels. The app also uses data from its database to recommend approximate energy values for different activities, though this is tailored individually.

The main challenge of this project lies in developing a reliable recommendation system and an effective scale for various activities. Inspired by psychological scales used to assess patients' conditions, VoltVivi aims to educate users on the finite nature of human energy and empower them to prioritize activities that matter most. By visualizing energy consumption through animations, users learn to recognize and manage the activities that drain their energy, ultimately taking control of their well-being and becoming masters of their own lives.

## Features

1. **Energy Meter**:
   - Vivi has an energy meter on its chest that displays its current energy level.

2. **Battery Feeding**:
   - Users can feed batteries to Vivi, specifying the activity source (e.g., eating, sleeping, studying) for each battery.

3. **Energy Consumption**:
   - Users can perform activities that consume energy, also specifying the activity source (e.g., working, cooking).

4. **Personalized Database**:
   - All energy inputs and outputs are stored in a personal database for each user, allowing for unique interactions and energy measurements.

5. **Customizable Energy Values**:
   - Users can define the energy value for each activity, reflecting their personal perception of energy expenditure.

6. **Interactive Feedback**:
   - Vivi provides different feedback based on user interactions, helping users understand their energy levels better.

7. **Dynamic Recommendations**:
   - The app uses data from the database to recommend approximate energy values for various activities, personalized to each user.

## Development Tools

We will using following tool to build Vivi:

- **Operating System**: Windows, macOS, or Linux
- **Development Environment**: Flutter SDK, Dart SDK
- **Backend Services**: AWS Amplify
- **Version Control**: Git

## Development Workflow

Below is the workflow for developing the VoltVivi project:

![Development Workflow]()

### Plan
- **Tool**: Figma
- Design the user interface and plan the application features.

### Code
- **Frontend**: Flutter
  - Develop the user interface and user interactions.
- **Backend**: AWS Amplify Data Storage
  - Manage data storage and backend services.

### Build
- **Frontend**: AWS CodeBuild
  - Build the frontend application for iOS and Android.

### Test
- **Frontend**: Flutter Test
  - Conduct unit and integration tests for the frontend.
- **Backend**: Pytest
  - Perform tests for backend functionalities.

### Release
- **iOS and Android**: Fastlane
  - Prepare and submit the application for release to App Store Connect and Google Play Console.

### Deploy
- **iOS and Android**: Fastlane
  - Deploy the application to production environments.

### Operate
- **Tool**: AWS CloudWatch
  - Monitor application performance and backend services.

### Monitor
- **Tool**: AWS QuickSight
  - Analyze and visualize application data and user interactions.


