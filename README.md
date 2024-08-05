# VoltVivi
_Current Version: v0.0.0_
## Project Overview 🚀

VoltVivi is an innovative application designed to help users effectively manage and monitor their energy levels and emotional well-being. Central to the app is a small cute robot named Vivi, who represents the user's inner self. Most activities require energy expenditure, while only a few essential activities, such as sleeping and eating, can replenish energy. Each activity also has the potential to bring positive or negative emotional feedback.

VoltVivi features two main indicators: the Energy Bar and the Mood Bar. 

### Energy Bar 🔌
The Energy Bar shows Vivi's current energy level:
- Most activities consume energy.
- Essential activities like sleeping and eating replenish energy.
- This helps users understand that energy is a precious resource.

### Mood Bar 😊
The Mood Bar indicates the happiness value derived from activities after energy investment:
- Any activity will bring effect on Vivi's mood.
- This helps users understand the trade off between energy expenditure and emotional satisfaction.

Over time, Vivi will prompt users to reflect on whether their recent activities were a reasonable investment of their energy. This encourages users to think critically about how they spend their energy and the impact on their overall well-being.

By visualizing energy consumption and mood through engaging animations, VoltVivi educates users on the finite nature of human energy and the importance of prioritizing activities that contribute positively to their happiness. This empowers users to take control of their well-being, making thoughtful decisions about their energy investments. Vivi’s reactions help illustrate different states:

- **Sufficient energy but low happiness**: Vivi becomes irritable 😠.
- **High energy and high happiness**: Vivi feels satisfied 😄.
- **Low energy and low happiness**: Vivi becomes depressed 😢.
- **Low energy but high happiness**: Vivi feels tired 😴.

![Vivi's Emotions Category](/assets/README/EmotionCategory.jpg)
## Features ✨

1. **Energy Bar**:
   - Displays Vivi's current energy level. Most activities consume energy, while essential activities like sleeping and eating replenish it. Helps users track their energy expenditure.

2. **Mood Bar**:
   - Shows the happiness level resulting from energy investments. Reflects how different activities impact Vivi's mood, helping users balance energy use with emotional satisfaction.

3. **Battery Feeding**:
   - Users can feed batteries to Vivi, specifying the activity source (e.g., eating, sleeping, studying) for each battery. This helps in tracking energy sources and their impact.

4. **Energy Consumption**:
   - Users can perform activities that consume energy, also specifying the activity source (e.g., working, cooking). Helps in understanding how energy is spent throughout the day.

5. **Personalized Database**:
   - All energy inputs and outputs, along with mood feedback, are stored in a personal database for each user. This allows for unique interactions and personalized energy measurements.

6. **Customizable Energy and Mood Values**:
   - Users can define the energy and mood value for each activity, reflecting their personal perception of energy expenditure and happiness. This personalization helps in better managing individual well-being.

7. **Interactive Feedback**:
   - Vivi provides different feedback based on user interactions, helping users understand their energy and mood levels better. This feedback is crucial for making informed decisions about daily activities.

8. **Dynamic Recommendations**:
   - The app uses data from the database to recommend approximate energy and mood values for various activities, personalized to each user. This helps users make better choices for their energy investments.


## Contribution Guidelines 🤝

### Contact 📧

If you are interested in contributing to VoltVivi, please reach out to us first. We want to ensure that all contributors understand the core mission of this project: helping individuals respect their energy, learn to manage themselves, and ultimately love themselves.

If you have any questions or would like to contribute to VoltVivi, please contact us at:

Email: haike.yu@outlook.com

### Understanding the Core Mission 🌟

VoltVivi is more than just an app; it's a tool designed to help users recognize the finite nature of their energy and prioritize activities that matter most. By contributing to this project, you are helping to empower individuals to take control of their well-being and become masters of their own lives.

### How to Contribute 🛠️

1. **Get in Touch**:
   - Contact us to express your interest in contributing. Please include "VoltVivi Collaboration Request" in the subject line of your message. We will provide you with the necessary permissions to contribute directly to the main repository.

2. **Clone the Repository**:
   - Clone the VoltVivi repository to your local machine:
     ```sh
     git clone https://github.com/your-username/voltvivi.git
     ```

3. **Create a New Branch**:
   - Create a new branch for your feature or bugfix:
     ```sh
     git checkout -b feature-or-bugfix-name
     ```

4. **Make Your Changes**:
   - Implement your changes in the new branch. Ensure your code follows the project's coding standards and includes appropriate comments.

5. **Commit Your Changes**:
   - Commit your changes with a clear and concise commit message:
     ```sh
     git commit -m "Description of your changes"
     ```

6. **Push Your Branch**:
   - Push your branch to the main repository:
     ```sh
     git push origin feature-or-bugfix-name
     ```

7. **Open a Pull Request**:
   - Open a pull request from your branch to the main branch. Provide a detailed description of your changes and link to any relevant issues.

### Reporting Issues 🐛

If you encounter any issues while using VoltVivi, please report them in the GitHub issues section. When reporting an issue, please include:

- A clear and descriptive title.
- A detailed description of the problem.
- Steps to reproduce the issue.
- Any relevant screenshots or error messages.

### Licensing 📜

By contributing to VoltVivi, you agree that your contributions will be licensed under the [LICENSE.txt](/LICENSE.txt).

## Development Tools 🛠️

We will be using the following tools to build Vivi:

- **Operating System**: Windows, macOS, or Linux
- **Development Environment**: Flutter SDK, Dart SDK
- **Backend Services**: AWS Amplify
- **Version Control**: Git

## Development Workflow 🔄

Below is the workflow for developing the VoltVivi project:

![Development Workflow](/assets/README/VoltViviWorkFlow.jpg)

### Plan 📋
- **Tool**: Figma
- Design the user interface and plan the application features.

### Code 💻
- **Frontend**: Flutter
  - Develop the user interface and user interactions.
- **Backend**: AWS Amplify Data Storage
  - Manage data storage and backend services.

### Build 🏗️
- **Frontend**: AWS CodeBuild
  - Build the frontend application for iOS and Android.

### Test ✅
- **Frontend**: Flutter Test
  - Conduct unit and integration tests for the frontend.
- **Backend**: Pytest
  - Perform tests for backend functionalities.

### Release 🚀
- **iOS and Android**: Fastlane
  - Prepare and submit the application for release to App Store Connect and Google Play Console.

### Deploy 🌍
- **iOS and Android**: Fastlane
  - Deploy the application to production environments.

### Operate 📈
- **Tool**: AWS CloudWatch
  - Monitor application performance and backend services.

### Monitor 📊
- **Tool**: AWS QuickSight
  - Analyze and visualize application data and user interactions.
