# simple-Csharp-dotnet-BMI_Calculator

Welcome to the Health Tracker App! This console application allows you to track health-related information such as your name, age, height, weight, gender, and student status. It also calculates your Body Mass Index (BMI) and provides a classification based on your BMI value.

## Prerequisites
- .NET Framework 4.7.2 or above

## Getting Started
1. Clone the repository or download the source code files.
2. Open the solution in Microsoft Visual Studio.
3. Build the solution to restore NuGet packages and compile the code.
4. Run the application.

## Usage
Upon running the application, you will be prompted to provide the following details:

- Name: Enter your name.
- Age: Enter your age.
- Height in centimeters: Enter your height in centimeters.
- Weight in kg: Enter your weight in kilograms.
- Gender (M/F): Enter your gender as either "M" or "F".
- Are you a student? (Y/N): Enter "Y" if you are a student, or "N" if you are not.

After providing the required information, the application will display the following details:

- Your name.
- Your age.
- Your height in meters.
- Your weight in kilograms.
- Your gender.
- Whether you are a student or not.
- Your height in feet.
- Your BMI (Body Mass Index) value.
- Classification based on your BMI value.

The application also demonstrates the usage of a custom math library:

- It calculates the square of the number 5 using the Square method from the MathLibrary.MathHelper class.
- It calculates the square root of the squared number using the SquareRoot method from the same class.
- The square root result is then displayed on the console.
