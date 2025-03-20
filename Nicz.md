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

1. Install Bolt if you haven't already: 

    npm install -g @bolt/cli

2. Install the project dependencies:

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


Improving GitHub Codespaces can involve optimizing performance, customizing the development environment, and integrating better workflows. Here are some key areas where you can enhance your Codespace experience:![17407143021704149825560717034780](https://github.com/user-attachments/assets/9670e7b1-8a43-4483-878e-03de71fa9e8b)


## 1. Performance Optimization

### Use Lightweight Docker Images
Minimize build times by using lightweight base images in your `devcontainer.json`.

![17407163151471502099556628612551](https://github.com/user-attachments/assets/4e6a6c59-acd3-47a5-aa81-a03266fcd33d)


[Learn more about Docker images](https://docs.docker.com/engine/reference/builder/)
![17407164645514767657305275675575](https://github.com/user-attachments/assets/0b4e6767-00ff-476d-9e25-734415bc9e36)

### Enable Prebuilds
GitHub allows prebuilding environments, which can speed up workspace creation.

![17407159779824452857301128244950](https://github.com/user-attachments/assets/81dec40e-1a17-4c62-8c36-3e1fa10d7d0c)


[Learn more about GitHub Codespaces Prebuilds](https://docs.github.com/en/codespaces/prebuilding-your-codespace)

### Adjust Resource Limits
Choose the appropriate machine type for your workload (e.g., more RAM/CPU for heavy builds).

![174071616594792864237544417317](https://github.com/user-attachments/assets/a8efa839-fb46-4892-b5c6-b2a53740db1c)


[Learn more about configuring machine types](https://docs.github.com/en/codespaces/customizing-your-codespace/configuring-codespaces-for-your-project)

## 2. Customization & Extensions

### Devcontainer Configuration
Customize `.devcontainer/devcontainer.json` to define extensions, scripts, and settings.

![17407165491965715137270132205793](https://github.com/user-attachments/assets/9a97fd29-8138-432e-aa0c-093e10f0258b)


[Learn more about devcontainer.json](https://code.visualstudio.com/docs/remote/containers)

### Install Necessary Extensions
Add VS Code extensions to improve productivity (e.g., ESLint, Prettier, Docker, Python).

![17407166575745501316666916847179](https://github.com/user-attachments/assets/933dcfba-7db8-49f0-ae1a-bd8536daeadc)


[Learn more about VS Code extensions](https://marketplace.visualstudio.com/VSCode)

### Dotfiles for Personalization
Use dotfiles to personalize your shell, Git settings, and aliases.

<img width="1237" alt="1740716752947430419653306265699" src="https://github.com/user-attachments/assets/10fbc147-7f57-4fc2-aa31-7f74c25b1455" />


[Learn more about using dotfiles](https://dotfiles.github.io/)

## 3. Collaboration & Workflow Improvements

![17407146287092240783483458753564](https://github.com/user-attachments/assets/804ba95d-7d31-436a-a5e6-65cb6a36d2d4)


### Use GitHub Actions
Automate build, test, and deployment processes directly from your Codespace.

![17407146707127808855630142639560](https://github.com/user-attachments/assets/70d3681a-4c79-4425-bde1-87f8f2ed7a6f)


[Learn more about GitHub Actions](https://docs.github.com/en/actions)

### Enable Live Share
Collaborate in real-time by using VS Code’s Live Share extension.

![17407168850977765961244992671814](https://github.com/user-attachments/assets/e8a77c37-7193-4cee-a325-4b709bddee31)


[Learn more about VS Code Live Share](https://visualstudio.microsoft.com/services/live-share/)

### Integrate with GitHub CLI
Use `gh` CLI to manage repositories and issues efficiently from the terminal.

![17407170813208656013917642140983](https://github.com/user-attachments/assets/bccddcd8-f839-4512-a2df-5fbd4ed308bd)


[Learn more about GitHub CLI](https://cli.github.com/)

## 4. Security Enhancements

![17407145178258082811593498134258](https://github.com/user-attachments/assets/8ac8bbe1-8ff2-4de9-af6d-eded4d5261d0)


### Use Secrets Properly
Store sensitive credentials securely using GitHub secrets.

![GitHub Secrets](https://github.com/trufflesecurity/trufflehog)

[Learn more about GitHub secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets)

### Enable Dependabot
Keep dependencies updated and secure.

![17407155681058385455954990055102](https://github.com/user-attachments/assets/d7f3c9a8-0449-4abb-a7b1-4e7260ccb87b)


![Dependabot](https://docs.github.com/en/code-security/dependabot/working-with-dependabot/dependabot-options-reference)

[Learn more about Dependabot](https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically)

### Define Code Owners
Ensure code reviews by defining ownership in `.github/CODEOWNERS`.

![Code Owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

[Learn more about CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

## 5. Debugging & Monitoring

### Use Built-in Debugger
Take advantage of VS Code's debugging tools in your Codespace.

![VS Code Debugger](https://code.visualstudio.com/docs/remote/codespaces)

[Learn more about VS Code debugging](https://code.visualstudio.com/docs/editor/debugging)

### Monitor Resource Usage
Regularly check memory and CPU usage with `top` or `htop`.

![17407172852174876201250226333101](https://github.com/user-attachments/assets/d18cae44-b2a5-42d5-9b19-069fc14c8bd1)


[Learn more about monitoring resource usage](https://docs.github.com/en/codespaces/troubleshooting/troubleshooting-codespaces)

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or [inquiries](https://github.com/Nicztin/ing/blob/main/alldocs.md), feel free to contact us at:

Email: nicztin@gmail.com
GitHub: https://github.com/Nicztin/Nic

[![Gemma3](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)](https://youtu.be/L0f5EaOBfbA?si=Itc9Lj_a1868PWnc)
[![Channel](https://img.shields.io/badge/Watch%20on-YouTube-red?style=for-the-badge&logo=youtube)]([https://youtu.be/yGbt7cjc744?si=DmpYjcpL9UxYqDwA](https://www.youtube.com/@Nicztining))


Feel free to copy and paste this **README.md** into your project! You can also update the repository URL and contact details to match your project specifics. Let me know if you need more assistance!



