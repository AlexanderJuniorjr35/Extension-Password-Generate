# Extension Password Generate

## Description

The **Password Generator** is a simple application that creates strong and random passwords to enhance the security of online accounts. It is designed to be user-friendly, allowing users to select the password length and generate it with a single click. Additionally, the generated passwords can be copied to the clipboard for easy use.

## Features

- **Random Password Generation**: Creates strong and random passwords using a combination of uppercase letters, lowercase letters, numbers, and special characters.
- **Password Length Customization**: Allows users to choose the password length between 5 and 25 characters.
- **Quick Copy**: The generated password can be copied to the clipboard with a single click.

## Prerequisites

To run the project locally, you will need a modern browser that supports HTML5, CSS3, and JavaScript.

## Project Structure

- **index.html**: Contains the HTML structure of the password generator.
- **style.css**: Contains the CSS styles for the application.
- **script.js**: Contains the JavaScript code responsible for the password generation logic and interactivity.
- **manifest.json**: Configuration file to transform the project into a browser extension.
- **assets/**: Folder containing image files (logo).

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AlexanderJuniorjr35/Extension-Password-Generate.git
   ```
2. **Open the `index.html` file** in your browser to use the password generator.

### To Use as a Browser Extension

1. **Open Chrome and go to `chrome://extensions/`**.
2. **Enable Developer mode** in the top right corner.
3. **Click on "Load unpacked"** and select the project folder.
4. **The extension will be available for use**.

## How It Works

### HTML (`index.html`)

The HTML defines the basic structure of the password generator, including input elements and action buttons.

### CSS (`style.css`)

The CSS styles the password generator for a user-friendly and modern look. It includes styles for layout, colors, and user interaction.

### JavaScript (`script.js`)

The JavaScript contains the logic for generating random passwords and updating the user interface:

- **Slider Manipulation**: Updates the displayed value as the user adjusts the password length.
- **Password Generation**: Creates a random password based on the user-selected length.
- **Password Copy**: Allows the user to copy the generated password to the clipboard with a click.

## Examples of Use

- **Generate a strong password for a new online account**: Adjust the slider to select the desired length and click "Generate Password". Then click on the generated password to copy it.
- **Customize the password length as needed**: Use the slider to set between 5 and 25 characters.

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Author:** Alexander Junior  
**Contact:** www.linkedin.com/in/alexander-junior-654ab3269
