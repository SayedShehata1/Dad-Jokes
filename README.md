# Dad Jokes App

<div id="top"></div>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Font-Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<!-- PROJECT LOGO -->
<div align="center">
  <br>
  <a href="https://dad-jokes-flax.vercel.app/">
      <img src="./public/logo512.png" alt="Logo" height="50" >
    </a>
  <br>
  <br>

  <p align="center">
  <a href="https://dad-jokes-smoky.vercel.app/">View Demo</a>
    ·
    <a href="https://github.com/SayedShehata1/Dad-Jokes/issues">Report Bug</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#ports-and-endpoints">Ports and EndPoints</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

React App that lets people view and vote on cheesy jokes from [icanhazdadjoke](https://icanhazdadjoke.com/) API

![Preview](./src/assets/preview.png)

### Features

- List jokes fetched from [icanhazdadjoke](https://icanhazdadjoke.com/) API, along with:
  - "vot-up" Button
  - "vot-down" Button
  - net score for each joke
- User can vote and net score should update
- Should show loading state when loading jokes
- Should show the jokes sorted by net score, and update this as the scores changes on each fetch
- Should show dynamic vote-border-color and emoji based on joke net vote score
- Should persist the list of jokes in local storage
  - > When user visit the app, it should show saved jokes, rather than fetching new jokes, However the user should still be able to generate new jokes via the "New Jokes" button, and these new jokes should update the ones in local storage.

<p align="right">(<a href="#top">back to top</a>)</p>

---

## Getting Started

This project require some perquisites and dependencies to be installed, you can view it online using this [demo](https://dad-jokes-smoky.vercel.app/). or you can find the instructions below:

> To get a local copy, follow these simple steps :

### Installation

#### installing Locally

1. Clone the repo

   ```sh
   git clone https://github.com/SayedShehata1/Dad-Jokes.git
   ```

2. go to project folder

   ```sh
   cd dad-jokes
   ```

3. install dependencies

   ```bash
   npm install
   ```

4. Run development server

   ```sh
   npm start
   ```

---

### Ports and EndPoints

#### Ports

- FrontEnd Development Server runs on port `3000`

#### API endpoints

- joke: [https://icanhazdadjoke.com/](https://icanhazdadjoke.com/) [GET]
  - headers: `"application/json"`

<p align="right">(<a href="#top">back to top</a>)</p>

<p align="right">(<a href="#top">back to top</a>)</p>
