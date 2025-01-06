# WeatherAppAngular18
A simple weather app, build with the new version of Angular (18). Used also the API: https://www.weatherapi.com/

## Table of Contents

- [Prerequisites](#prerequisites)
- [Install Dependencies](#install-dependencies)
- [Development Server](#development-server)
- [Build](#build)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Further Help](#further-help)

## Prerequisites

- Ensure Node.js is installed on the system. You can download it from [nodejs.org](https://nodejs.org).
- Install Angular CLI: Open a terminal or command prompt and run:

  ```sh
  npm install -g @angular/cli
  ```

## Install Dependencies
Navigate to the project directory and run:
 ```sh
  npm install
  ```
This command will read the package.json file and install all the dependencies listed there into a newly created node_modules folder.

## Development server
In command prompt or Git Bash, run:

 ```sh
  ng serve
  ```
Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files.


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Usage
- Enter a city name in the search bar and click Enter.
- View the current weather information and the forecast for the upcoming days.
- Use the toggle switch to change the temperature unit between Celsius and Fahrenheit.
- Click on location tab to see information about the searched location.


## Technologies Used

- Angular v18
- Angular Material
- Weather API (https://www.weatherapi.com/)
- TypeScript
- SCSS

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
