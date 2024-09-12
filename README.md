# Logo-Maker

## Description

This command-line application allows users to generate simple logos in SVG format. Users can customize the text, text color, and shape of the logo. The program is built with Node.js and utilizes Inquirer for prompting user input and Jest for testing.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Badges](#badges)
- [Contribute](#contribute)
- [Questions/Contact](#questions)
- [License](#license)

## Installation

1. Clone the project repository to your desired directory.
2. Open a terminal in the project directory.
3. Run `npm install` to install all required dependencies.
4. Once dependencies are installed, run the application using `node index.js`.

## Usage

1. Run `node index.js` to start the command-line interface.
2. Follow the prompts to:
   - Enter up to 3 characters for the logo text.
   - Choose a text color (either by keyword or hex code).
   - Select a shape (circle, triangle, or square).
   - Choose a color for the shape (either by keyword or hex code).
3. The generated SVG logo file will be saved as `logo.svg` in the project directory.

### Example Output:

![Sample LogoMaker Output](examples/sample_logomaker.svg)

This is an example of a logo generated with the program using the input "SVG", a white text color, a circle shape, and a green shape color.

## Badges

[![Static Badge](https://img.shields.io/badge/GitHub-breannacamacho-darkgreen)](https://github.com/breannacamacho) 
[![Static Badge](https://img.shields.io/badge/Inquirer-8.2.4-blue)](https://www.npmjs.com/package/inquirer) 
[![Static Badge](https://img.shields.io/badge/Jest-29.7.0-red)](https://www.npmjs.com/package/jest) 

## Contribute

Contributions are what make the open-source community such a wonderful place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that could improve this project, please fork the repo and create a pull request. You can also open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Questions

[Link to GitHub Profile](https://github.com/breannacamacho)

If you have any additional questions, feel free to reach out via email at breannacamacho1@gmail.com.

## License

N/A

---

### User Story

**AS** a freelance web developer,  
**I WANT** to generate a simple logo for my projects,  
**SO THAT** I don't have to pay a graphic designer.


### Mock-Up

Here is a mock-up of the expected result based on the user input:
![Mockup](./examples/sample_logomaker.png)

Here is a link to a video to show you it in action! ![Click here!](https://www.youtube.com/watch?v=vceO3neAybk)

### Getting Started

This project utilizes **Inquirer** for user input and **Jest** for testing. Follow the installation and usage instructions above to run the application. The application will be invoked using the following command:

```bash
node index.js