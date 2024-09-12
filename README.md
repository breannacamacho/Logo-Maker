# Logo-Maker

## Description

Built a command-line application that generates simple logos using SVG. The user can input custom text, text color, and shape to create their logo. This application uses Node.js, Inquirer for prompts, and Jest for testing.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Badges](#badges)
- [Contribute](#how-to-contribute)
- [Questions/Contact](#questions)
- [License](#license)

## Installation

1. Clone the project repository down into your desired directory.
2. Open the project terminal and run the command `npm install` to install the packages and dependencies.
3. To invoke the application, run the command `node index.js`. This will start the command-line interface for generating a logo.
4. To run the tests, use the command `npm run test` (ensure Jest is installed).

## Usage

1. Clone the repo from GitHub (link in the contact section).
2. Run `node index.js` in the terminal.
3. Follow the prompts to input text, text color, shape, and shape color for the logo.
4. The application will generate an SVG file based on your inputs and save it as `logo.svg`.

## Badges

[![Static Badge](https://img.shields.io/badge/GitHub-breannacamacho-darkgreen)](https://github.com/breannacamacho) 
[![Static Badge](https://img.shields.io/badge/Inquirer-8.2.4-blue)](https://www.npmjs.com/package/inquirer) 
[![Static Badge](https://img.shields.io/badge/Jest-29.7.0-red)](https://www.npmjs.com/package/jest) 

## Contribute

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Questions

[Link to GitHub Profile](https://github.com/breannacamacho)

If you have additional questions, please email me at breannacamacho1@gmail.com.

## License

N/A but for this project: The application prompts the user to select a color and shape, provide text for the logo, and save the generated SVG to a .svg file.

---

## User Story

**AS** a freelance web developer,  
**I WANT** to generate a simple logo for my projects  
**SO THAT** I don't have to pay a graphic designer.

## Acceptance Criteria

- GIVEN a command-line application that accepts user input.
- WHEN I am prompted for text, THEN I can enter up to three characters.
- WHEN I am prompted for the text color, THEN I can enter a color keyword (or a hexadecimal number).
- WHEN I am prompted for a shape, THEN I am presented with a list of shapes to choose from: circle, triangle, and square.
- WHEN I am prompted for the shape's color, THEN I can enter a color keyword (or a hexadecimal number).
- WHEN I have entered input for all the prompts, THEN an SVG file is created named `logo.svg`.
- WHEN I open the `logo.svg` file in a browser, THEN I am shown a 300x200 pixel image that matches the criteria I entered.


## Getting Started

This challenge combines many skills covered so far. In addition to the User Story and Acceptance Criteria, some guidelines are provided to help you get started.

Your application should use Jest for running the unit tests and Inquirer for collecting input from the user. The application will be invoked by using the following command:

```bash
node index.js