# weather-dashboard
![Static Badge](https://img.shields.io/badge/License-MIT-green)

## Description

- **Motivation**: The motivation for building this weather dashboard stemmed from my interest in both web development and providing a real-world application that interacts with an API. I wanted to create a project that would allow me to explore backend development using Node.js and Express, while also working with third-party APIs. The idea of building something useful—like a weather app—was an exciting challenge that would allow me to practice both server-side and client-side skills.
- **Why build This Project**: I decided to build this project to improve my full-stack development skills. I wanted to create a functional app that integrates both frontend and backend technologies, and using the OpenWeather API allowed me to work with real-time data. Weather apps are a common but very practical use case for APIs, and building this gave me a tangible product to showcase while learning how to handle API requests, manage responses, and display data in a user-friendly interface. Additionally, I wanted to experience deploying an app to a platform like Render to understand the deployment process and how to manage both frontend and backend together in a cloud environment.
- **What problem's did it solve**: This weather dashboard solves the problem of easily accessing weather data for any location in real-time. Instead of relying on separate websites or mobile apps, users can quickly check the weather forecast directly from the dashboard. It also highlights how backend and frontend can work together seamlessly. By interacting with the OpenWeather API, users can get updated and accurate weather information without needing to manually check different sources. Moreover, this app also demonstrates how to integrate third-party services into your own app for useful functionality.
- **Lesson's Learned**: API Integration: I gained hands-on experience integrating external APIs (specifically the OpenWeather API) into a web application. This involved handling API requests, parsing responses, and managing error states, which can be tricky when dealing with third-party services.Full-Stack Development: I learned how to develop both the backend and frontend of an app. Using Express for the server-side logic, setting up routes, and creating a simple yet effective frontend to display the weather data gave me a comprehensive understanding of full-stack development.Deployment & CI/CD: I learned how to deploy a full-stack application to Render, which required configuring both the backend and frontend services and managing their dependencies. This experience was invaluable in understanding the deployment process for Node.js apps and how to handle environment variables securely in production.Error Handling & Validation: I learned how to handle errors and display meaningful messages to users if something goes wrong with the API or the network request. This is an important part of ensuring a good user experience.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)


## Installation
- **Clone the repository to your local machine:**
```
git clone git@github.com:HMasese/weather-dashboard.git

cd weather-dashboard
```

- **Run the following command to install all the dependencies for both the frontend and backend:**
```
npm install
```

- **Create a .env file in the root directory and add your OpenWeather API key:**
```
OPENWEATHER_API_KEY=your_api_key_here
```

- **To start both the backend and frontend in development mode, run the following command This will start The backend server on port 3000 (default).The frontend development server on port 3001.**
```
npm run start:dev
```

## Usage
Clone Repository, Install Dependencies, Setup Environment Variables, Run Project locally

## Credits
phil, dylan, aley, sidhaud

## License
A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code. https://choosealicense.com/licenses/mit/

## Features
- **Express Server:** The backend is powered by an Express server.
- **Weather Data Fetching:** Fetches weather data from the OpenWeather API.
- **Frontend:** Simple dashboard for displaying weather information.
- **Responsive UI:** Built with Bootstrap for a clean and responsive design.
- **Real-Time Weather:** Displays the current temperature, weather conditions, and more for a given city.

## How to Contribute
Contributions are welcome! Feel free to fork the repository, submit issues, and create pull requests.

## Tests
```
npm run test
```

## Questions
- For Further Questions and Bug reports Please reach out to me at Github (https://github.com/HMasese) or email me at harrietm616@gmail.com

## Links
- [Deployed App]()
- [Github Repository](https://github.com/HMasese/weather-dashboard)
