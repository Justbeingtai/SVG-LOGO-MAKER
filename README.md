# SVG Logo Generator

## VIDEO OF THE PROCESS: 

![Video Exmaple](./images/Untitled%20Video%20August%2019,%202024%201_26%20AM.gif)

## Description

The SVG Logo Generator is a command-line application designed to help freelance web developers quickly generate simple and customizable logos for their projects. As a developer, I often needed a quick and easy way to create logos without the hassle of hiring a graphic designer. This project was built to solve that problem by providing a tool that generates SVG logos based on user input, allowing developers to create personalized logos efficiently.

This project enhances my understanding of JavaScript, object-oriented programming, and SVG file generation. Through this project, I learned how to structure a command-line application, manage user input, and create dynamic SVG files programmatically.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation

Follow these steps to install and set up the project on your local machine:

1. Clone the repository to your local machine:
   \`\`\`bash
   git clone https://github.com/Justbeingtai/SVG-LOGO-MAKER.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd svg-logo-generator
   \`\`\`
3. Install the necessary dependencies:
   \`\`\`bash
   npm install
   \`\`\`

## Usage

To generate an SVG logo, follow these steps:

1. Run the application from the command line:
   \`\`\`bash
   node index.js
   \`\`\`
2. Follow the prompts to enter:
   - Up to three characters for the logo text.
   - The text color (either a color keyword or hexadecimal number).
   - A shape (choose between Circle, Triangle, and Square).
   - The shape color (either a color keyword or hexadecimal number).
3. The application will generate a \`logo.svg\` file in the root directory with the specified parameters.

Example of the generated SVG file displayed in a browser:

![Generated SVG Example](./images/SVGgenerated.svg)

## Credits

This project was developed by [Tai Ho](https://github.com/Justbeingtai). 

- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) was used to handle user prompts in the command-line interface.
- The application was inspired by the need for quick and easy logo generation in web development projects.

## License

This project is licensed under the MIT License. For more information, see the [LICENSE](LICENSE) file.

---

## Badges

![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)
![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green)

## Features

- Generate customizable SVG logos with text and shape elements.
- Supports color customization via keywords or hexadecimal values.
- Offers three shape options: Circle, Triangle, and Square.

## How to Contribute

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create your feature branch (\`git checkout -b feature/NewFeature\`).
3. Commit your changes (\`git commit -m 'Add some feature'\`).
4. Push to the branch (\`git push origin feature/NewFeature\`).
5. Create a new Pull Request.

## Tests

To run tests on the shape classes, use the following command:

\`\`\`bash
npm test
\`\`\`

The tests ensure that the shape classes correctly render SVG elements based on the given parameters.
`;