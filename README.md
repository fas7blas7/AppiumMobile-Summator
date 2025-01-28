# AppiumMobileSummator

## Overview
**AppiumMobileSummator** is a mobile test automation project designed for testing the sum function of numbers in the Android OS app **Summator**. It follows the Page Object Model (POM) approach to enhance test maintainability and reusability.

## Project Structure
The project consists of the following key classes:

### 1. **SummatorPOM.cs**
This class contains methods to interact with the **Summator** mobile application, providing structured and reusable methods for UI elements.

### 2. **SummatorTestsPOM.cs**
This class includes test cases to validate the functionality of the sum feature in the **Summator** Android app.

## Technologies Used
- **C#**
- **Appium**
- **NUnit/xUnit** (or another testing framework if applicable)
- **Android Emulator/Real Device**

## Setup & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AppiumMobileSummator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd AppiumMobileSummator
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Start the Appium server and connect an Android device/emulator.
5. Run the tests:
   ```sh
   dotnet test
   ```
