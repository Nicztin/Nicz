# Nicz 

Welcome to the **Nicz** repository! This project is dedicated to creating a beautiful, dynamic, and user-friendly website with cutting-edge technology. The website includes features like a **starry glowing background**, **interactive mouse tracking**, and **floating animations**, making the user experience engaging and visually appealing.
<br/>
<p align="center">
  <a href="https://npmjs.com/package/vite"><img src="https://img.shields.io/npm/v/vite.svg" alt="npm package"></a>
  <a href="https://nodejs.org/en/about/previous-releases"><img src="https://img.shields.io/node/v/vite.svg" alt="node compatibility"></a>
  <a href="https://github.com/vitejs/vite/actions/workflows/ci.yml"><img src="https://github.com/vitejs/vite/actions/workflows/ci.yml/badge.svg?branch=main" alt="build status"></a>
  <a href="https://pr.new/vitejs/vite"><img src="https://developer.stackblitz.com/img/start_pr_dark_small.svg" alt="Start new PR in StackBlitz Codeflow"></a>
  <a href="https://chat.vite.dev"><img src="https://img.shields.io/badge/chat-discord-blue?style=flat&logo=discord" alt="discord chat"></a>
</p>
<br/>

## Features

- **Starry Glowing Background**: A dynamic starry effect with glowing stars in the background.
- **Mouse Tracking**: Stars follow the user's mouse movements for an interactive effect.
- **Floating Stars**: Random floating stars animate across the screen, creating a captivating visual design.
- **Responsive Design**: The website is designed to be fully responsive, adapting to various screen sizes.
- **Center Content**: A well-positioned section that holds the main content of the website, ensuring readability and accessibility.

## Technologies Used 

- **HTML**: Structure of the web page and content.
- **CSS**: Styling and animations for the glowing stars, background, and floating effects.
- **JavaScript**: Mouse tracking functionality and dynamic floating stars animation.
- **Bolt Build Tool**: Used for website building and optimization.

<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>
<img align="left" alt="Spring" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
<img align="left" alt="TypeScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" />
<img align="left" alt="Angular" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-plain.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
<img align="left" alt="NodeJS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" />
<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="C++" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-line.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Bash" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
<br />


| Package                                         | Version (click for changelogs)                                                                                                    |
| ----------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| [Nicz](packages/vite)                           | [![vite version](https://img.shields.io/npm/v/vite.svg?label=%20)](packages/vite/CHANGELOG.md)                                    |
| [@vitejs/plugin-legacy](packages/plugin-legacy) | [![plugin-legacy version](https://img.shields.io/npm/v/@vitejs/plugin-legacy.svg?label=%20)](packages/plugin-legacy/CHANGELOG.md) |
| [create-nicz](packages/create-vite)             | [![create-vite version](https://img.shields.io/npm/v/create-vite.svg?label=%20)](packages/create-vite/CHANGELOG.md)               |


## Installation and Setup

### Clone the Repository

1. Clone the repository to your local machine using:

   ```bash
   git clone https://github.com/Nicztin/Nicz

Navigate to the project folder:

   cd nicz-website

## Setting Up Dependencies
Since this project uses Bolt, ensure you have the required dependencies set up:

Install Bolt if you haven't already: 

    npm install -g @bolt/cli

Install the project dependencies:

    npm install
    
## Running the Development Server
To view the website locally, run the following command:

    npm run dev

This will start the development server and open the website in your browser at http://localhost:3000.

## File Structure

/nics-website
  /assets
    /images        # Contains images for the website
  /css
    /styles.css    # Main stylesheet for styling the website
  /js
    /script.js     # JavaScript file for mouse tracking and star animations
  /index.html      # Main HTML file for the website
  README.md        # Documentation for the project

##  Customization
Feel free to modify the design and effects based on your preferences:

1. Star Count: Adjust the number of floating stars by editing the value in the createFloatingStars() function in script.js.
2. Speed & Size of Floating Stars: Modify the @keyframes animations in the styles.css file to adjust speed and size.
3. Mouse Tracking Effect: You can alter the way stars interact with the mouse by modifying the mousemove event in script.js.

## Contributor Covenant Code of Conduct
Our Pledge
In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

Our Standards
Examples of behavior that contributes to creating a positive environment include:

# Improving GitHub Codespace

Your space, your way. Codespaces is a home away from home for your code that feels just like your usual machine.
![17407147747248347010788088850664](https://github.com/user-attachments/assets/ffd3f1a8-5db4-4393-99af-eb3dc8c7120b)

[Learn more](https://github.com/Nicztin/ing/blob/main/improvingGithubCodeSpace.md)

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Nicztin/Nicz/tree/html) file for details.

## Contact
For any questions or [inquiries](https://github.com/Nicztin/ing/blob/main/alldocs.md), feel free to contact us at:

Email: nicztin@gmail.com
GitHub: https://github.com/Nicztin/

[![Gemma3](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)](https://youtu.be/L0f5EaOBfbA?si=Itc9Lj_a1868PWnc)
[![Channel](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)]([https://youtu.be/yGbt7cjc744?si=DmpYjcpL9UxYqDwA](https://www.youtube.com/@Nicztining))


Feel free to copy and paste this **README.md** into your project! You can also update the repository URL and contact details to match your project specifics. Let me know if you need more assistance!



