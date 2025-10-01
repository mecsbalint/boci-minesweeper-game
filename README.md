# BMG - Boci's Minesweeper Game

## About the Project

![BMG screenshot][screenshot01]

The Boci's Minesweeper Game project is a full-stack web application where the users can play minesweeper. It currently supports single-player and two-player versus modes. The backend is powered by Flask, while the frontend is built with React, offering a modern and dynamic user experience. This project serves as the groundwork for a more ambitious multiplayer versions, which will introduce real-time competitive and cooperative features in future iterations.


### Core Features

* **User Authentication:** The application includes user registration and login functionalities to personalize the experience.
* **Single Player and Multiplayer Modes** The application has single player mode as well as a two-player versus mode
* **Game State Caching** Redis-based game state caching for fast, efficient retrieval ad gameplay performance
* **Responsove UI** The UI relies React's responsiveness and performance optimisation
* **Dockerization:** The application is fully containerized using Docker.
* **Backend Tests:** Unit tests cover the business logic of the Backend side of the application.


### Built with

* [![Node.js][Node-ico]][Node-url]
* [![TypeScript][TS-ico]][TS-url]
* [![React][React-ico]][React-url]
* [![Tailwind css][Tailwind-ico]][Tailwind-url]
* [![DaisyUI][DaisyUI-ico]][DaisyUI-url]
* [![PostgreSQL][PostgreSQL-ico]][PostgreSQL-url]
* [![Python][Python-ico]][Python-url]
* [![Pytest][Pytest-ico]][Pytest-url]
* [![Flask][Flask-ico]][Flask-url]
* [![Redis][Redis-ico]][Redis-url]
* [![Socketio][Socketio-ico]][Socketio-url]




## Getting Started

#### Download app

You can download the application here: [BMG GitHub page](https://github.com/mecsbalint/boci-minesweeper-game). Click on the Code button and choose the Download ZIP option. After downloading unzip it.
Or alternatively clone the repository: ```git clone https://github.com/mecsbalint/boci-minesweeper-game```

### With Docker

#### Prerequisites

* **Docker Desktop:** You can download from here: [Docker Desktop][Docker-Desktop]. You have to sign up to use the Docker Desktop app.

#### Set Up and Run
1. **Install and Run Docker Desktop:** Download and run the installation file and follow the steps. After installation run the Docker Desktop application.
2. **Set up .env file**
    1. Rename the `.env.example` file to `.env` in the app's root folder
    3. Optionally you can change the JWT secret key or the port number (for more details see [.env.example](https://github.com/mecsbalint/boci-minesweeper-game/blob/main/.env.example))
3. **Start the Application:** Run the `docker_start.bat` batch file from the application's root folder.
4. **Access the Application:** Open a web browser and go to `http://localhost:` + `PORT_NUMBER` to access the frontend (by default it's `http://localhost:5173`). The port number can be changed in the `.env.example` file.
5. **Stop the application:** Run the `docker_stop.bat` batch file from the application's root folder.

### Manual Setup (Without Docker)

For run the project manually check the readmes of the [Frontend (React)](frontend-react/readme.md#set-up-manually) and [Backend (Flask)](backend-python/readme.md#set-up-manually) subprojects.

## Roadmap

- [x] Single player game mode
- [x] User authentication
- [x] Unit tests
- [x] Dockerization
- [x] Multiplayer modes (competitive and cooperative)
- [ ] Different maps
- [ ] Desktop frontend built on PyQt
- [ ] Integration tests
- [ ] Game replays


## Contact

mecsbalint@gmail.com - https://github.com/mecsbalint


<!-- Links -->

[Docker-Desktop]: https://www.docker.com/products/docker-desktop/

[screenshot01]: readme_resources/bmg_screenshot_01.png

[Node-ico]: https://img.shields.io/badge/Node.js-35422E?style=for-the-badge&logo=node.js
[Node-url]: https://nodejs.org/

[TS-ico]: https://img.shields.io/badge/TypeScript-687959?style=for-the-badge&logo=typescript
[TS-url]: https://www.typescriptlang.org/

[React-ico]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react
[React-url]: https://reactjs.org/

[Tailwind-ico]: https://img.shields.io/badge/Tailwind-35495E?style=for-the-badge&logo=tailwindcss
[Tailwind-url]: https://tailwindcss.com/

[DaisyUI-ico]: https://img.shields.io/badge/DaisyUI-DD0031?style=for-the-badge&logo=daisyui
[DaisyUI-url]: https://daisyui.com/

[PostgreSQL-ico]: https://img.shields.io/badge/PostgreSQL-4A4A55?style=for-the-badge&logo=postgresql
[PostgreSQL-url]: https://www.postgresql.org/

[Python-ico]: https://img.shields.io/badge/Python-ADD8E6?style=for-the-badge&logo=python
[Python-url]: https://www.python.org/

[Pytest-ico]: https://img.shields.io/badge/Pytest-c7d302?style=for-the-badge&logo=pytest
[Pytest-url]: https://flask.palletsprojects.com/en/stable/

[Flask-ico]: https://img.shields.io/badge/Flask-0d7560?style=for-the-badge&logo=flask
[Flask-url]: https://docs.pytest.org/en/stable/

[Redis-ico]: https://img.shields.io/badge/Redis-4A4A55?style=for-the-badge&logo=redis
[Redis-url]: https://redis.io/

[Socketio-ico]: https://img.shields.io/badge/Socketio-25c2a0?style=for-the-badge&logo=socket.io
[Socketio-url]: https://socket.io/
