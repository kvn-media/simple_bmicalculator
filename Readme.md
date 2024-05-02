## Simple BMI Calculator - Kotlin Android App

This is a simple Android application written in Kotlin that calculates Body Mass Index (BMI).

### Features

* User enters weight and height.
* Calculates BMI based on the formula: BMI = weight (kg) / height (m²)
* Displays the calculated BMI value.
* Interprets the BMI value and displays a category (e.g., Underweight, Normal weight, Overweight, etc.)

### Getting Started

1. **Prerequisites:**
    * Android Studio installed with Kotlin plugin enabled.
    * Basic understanding of Kotlin and Android development concepts.

2. **Cloning the Project:**
    * (Replace `<your_github_username>` with your actual username)
    ```bash
    git clone https://github.com/kvn-media/simple_bmicalculator.git
    ```

3. **Opening the Project in Android Studio:**
    * Open Android Studio.
    * Go to **File > Open**.
    * Select the project directory you cloned and click **Open**.

4. **Running the App:**
    * Make sure your device is connected or an emulator is running.
    * Click the **Run** button (green triangle) in the toolbar.
    * Select your device or emulator from the dropdown menu.
    * The app will be installed and launched on your device.

### Using the App

1. Enter your weight (in kilograms) in the weight field.
2. Enter your height (in meters) in the height field.
3. Click the "Calculate BMI" button.
4. The app will display your BMI value and its corresponding category.

### Code Structure

The codebase is expected to be divided into the following main parts:

* **Activity:** This is the main class responsible for the UI and user interaction. It handles user input, calls the calculation functions, and displays the results.
* **Layouts:** These XML files define the visual structure of the app's screens, including elements like input fields, buttons, and text views.
* **Functions:** These functions perform specific tasks like BMI calculation and category interpretation.
