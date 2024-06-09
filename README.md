SkyCast

SkyCast is a Java-based weather forecasting application designed to provide users with accurate and real-time weather information. The application pulls data from various meteorological sources to deliver current weather conditions, detailed forecasts, and other relevant weather-related information.

Features
Current Weather: Get real-time updates on weather conditions.
Forecast: Access weather forecasts for the upcoming days.
Detailed Information: View detailed meteorological data including temperature, humidity, wind speed, and more.
User-Friendly Interface: Easy-to-navigate interface designed for a seamless user experience.
Installation and Setup
Follow these steps to set up and run SkyCast on your local machine:

Clone the Repository:
sh
Copy code
git clone https://github.com/shahanweerakoon/SkyCast.git
Navigate to the Project Directory:
sh
Copy code
cd SkyCast
Build the Project Using Gradle:
sh
Copy code
./gradlew build
Run the Application:
sh
Copy code
./gradlew run
Dependencies
SkyCast relies on several dependencies to function properly. Ensure you have the following installed:

Java Development Kit (JDK) 8 or higher
Gradle
Project Structure
app/ - Contains the main application code including UI and business logic.
gradle/ - Includes Gradle wrapper files for building the project.
build.gradle.kts - The main Gradle build script for compiling the project.
settings.gradle.kts - Settings script for Gradle configuration.
Usage
Once the application is running, you can:

View Current Weather: See up-to-date weather conditions for your location.
Check Forecasts: Get weather predictions for the next few days.
Detailed Reports: Access in-depth weather reports with metrics such as temperature, wind speed, humidity, and more.
Contributing
We welcome contributions from the community! To contribute to SkyCast, follow these steps:

Fork the Repository:
Click the 'Fork' button at the top right corner of this repository to create a copy under your GitHub account.
Create a New Branch:
sh
Copy code
git checkout -b feature-branch
Make Your Changes:
Implement your feature or bugfix.
Commit Your Changes:
sh
Copy code
git commit -m 'Add new feature'
Push to the Branch:
sh
Copy code
git push origin feature-branch
Open a Pull Request:
Navigate to the original repository and click on 'New Pull Request' to submit your changes for review.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Support
For any issues or questions, please open an issue on the GitHub repository or contact the maintainers directly.
