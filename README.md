# Factored Employees App

This repository contains a web application for visualizating the employees of Factored.

- The frontend was build with `React` using `Typescript`.
  Also, were used:
  - `React routes` for React app routing.
  - `Material UI` for the user interface style system.
  - `chart.js` & `react-chartjs-2` for charting.
- The backend was build with FastAPI and SQLAlchemy.
  - `uvicorn` is used for server deployment.

## Table of Contents

- [Factored Employees App](#factored-employees-app)
  - [Table of Contents](#table-of-contents)
  - [How to run the project](#how-to-run-the-project)
    - [Install WSL](#install-wsl)
    - [Install Docker](#install-docker)
    - [Install Git](#install-git)
    - [Run the project](#run-the-project)
  - [Login credentials](#login-credentials)
  - [Submodules](#submodules)
  - [Author](#author)

---

## How to run the project

This project was built for running on Docker using Docker Compose.

Next, I am going to explain how to run it easily:

### Install WSL

If you are using Windows as you PC operating system, then Install WSL:

1. Open PowerShell or Windows Command Prompt in administrator mode by right-clicking and selecting "Run as administrator"
2. In the opened command line, write the `wsl --install` command and press enter.

   ```bash
   wsl --install
   ```

3. Wait for the installation to finish.
4. Then, restart your PC.
You can find more information on [How to install Linux on Windows with WSL](https://learn.microsoft.com/en-us/windows/wsl/install) official guide from Windows, if needed.

### Install Docker

1. Go to [Get Started with Docker](https://www.docker.com/get-started/)
2. Press the download button for Download Docker for your operating system. For example "Download for Windows" button if you are using Windows as you PC operating system.

   This will download a "Docker Desktop Installer" file into you pc.

3. Open the downloaded "Docker Desktop Installer" and give permission to your PC to execute it if a banner ask this to you.
4. Docker will open an installation window. Left the checked checkboxes as default and proceed to installation.
5. Wait for the installation to finish.
6. If you are asked to log out of your user Windows session, then do it and enter again.
7. Open the Docker Desktop application in you PC.
8. Accept the Docker Suscription Service Agreement.
9. In the login panel select "Continue without sign in".

Go to [Learn How to install Docker](https://docs.docker.com/desktop/) guide if needed.

### Install Git

If you don't have Git installed, download it from [Git SCM](https://git-scm.com/download/).

You can follow the installation instructions for your operating system on [Getting Started - Installing Git](https://www.git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Run the project

1. Open a Terminal or Command Prompt:
   - On Windows, you can use Command Prompt, PowerShell, or Git Bash.
   - On macOS and Linux, open the Terminal application.
2. Clone this repository

   ```bash
   git clone --recurse-submodules https://github.com/sebasnop/factored-assessment.git
   ```

3. Navigate to the Project Directory

   ```bash
   cd factored-assessment
   ```

4. Run docker compose command

   ```bash
   docker-compose up --build
   ```

5. Wait for the process to complete.
6. Access the application on your web brower using the next URL:

   [http://localhost:3000](http://localhost:3000)

## Login credentials

For viewing the employees, use the next credentials on login page ([Login](http://localhost:3000/login/)) form:

- **email**:
  
  `admin@factored.ai`

- **password**:
  
  admin

## Submodules

Frontend and backend were developed in different repositories. Then, were added as "submodules" on this repository.

You can see them and watch the commits history here:

- [Frontend](https://github.com/sebasnop/factored-frontend/)
- [Backend](https://github.com/sebasnop/factored-backend/)

## Author

Sebastian Valencia Zapata
[sevalenciaz@unal.edu.co](mailto:sevalenciaz@unal.edu.co)
