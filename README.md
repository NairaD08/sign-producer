# Sign Producer

Sign Producer is a simple command-line application that enables users to create custom SVG logos through intuitive command-line inputs. This application leverages the Inquirer library for user interaction and Jest for unit testing, ensuring a smooth and reliable experience. Users can personalize their logos by customizing the text, text color, shape, and shape color, resulting in a unique logo saved as `icon.svg`.

## Features

- **Custom Text Input**: Accepts user input for text (up to three characters) to be displayed on the logo.
- **Text Color Selection**: Allows users to choose the text color using color keywords or hexadecimal values.
- **Shape Selection**: Presents a list of shapes to choose from, including:
  - Circle
  - Triangle
  - Square
  - Ellipse
- **Shape Color Selection**: Users can select the shape color using color keywords or hexadecimal values.
- **SVG File Generation**: Generates an SVG file named `icon.svg` containing the customized logo.
- **Confirmation Message**: Outputs a confirmation message in the command line upon successful creation of the SVG file.

## How It Works

1. **User Input**: Launch the application in the command line and follow the prompts to enter your desired text, text color, shape, and shape color.
2. **Data Processing**: The application processes the input and generates the SVG logo based on the user's specifications.
3. **File Creation**: The logo is saved as `icon.svg` in the current directory, and a confirmation message is displayed.

## Technologies Used

- **Node.js**: The runtime environment for executing the application.
- **Inquirer**: A library for creating interactive command-line user interfaces.
- **Jest**: A testing framework for unit testing the application.

## Getting Started

To get started with Sign Producer, follow these steps:

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/sign-producer.git
   ```
2. Navigate to the project directory.
   ```bash
   cd sign-producer
   ```
3. Install the required dependencies.
   ```bash
   npm install
   ```
4. Run the application.
   ```bash
   node index.js
   ```

## Future Enhancements

- **Shape Customization**: Allow users to adjust the size and position of the shapes.
- **Additional Shapes**: Introduce more shape options for greater customization.
- **User Interface**: Develop a graphical user interface (GUI) for users who prefer a visual approach.

Thank you for using Sign Producer! We hope it helps you create unique and personalized logos with ease. Happy designing!
