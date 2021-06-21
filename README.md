
## Setup

First, checkout this project locally and then follow these steps:

0. Go through the Docker [installation](https://docs.docker.com/installation/) and [getting started guide](https://docs.docker.com/mac/started/) before you start.
1. Install the [Docker Toolbox](https://www.docker.com/docker-toolbox).
2. Start a "Quickstart Terminal" session (see the getting started guide).
3. Build the Docker image: `docker-compose up --build`
4. Open the app running on the docker machine: `open http://$(docker-machine ip default):3000`



## File Structure

Within the download you'll find the following directories and files:

```

back-front/
┣ my-tsx-app3/
┃ ┣ node_modules/
┃ ┣ public/
┃ ┃ ┣ favicon.ico
┃ ┃ ┣ index.html
┃ ┃ ┣ logo192.png
┃ ┃ ┣ logo512.png
┃ ┃ ┣ manifest.json
┃ ┃ ┗ robots.txt
┃ ┣ src/
┃ ┃ ┣ Components/
┃ ┃ ┣ Enums/
┃ ┃ ┣ Pages/
┃ ┃ ┣ App.css
┃ ┃ ┣ App.test.tsx
┃ ┃ ┣ App.tsx
┃ ┃ ┣ index.css
┃ ┃ ┣ index.tsx
┃ ┃ ┣ logo.svg
┃ ┃ ┣ react-app-env.d.ts
┃ ┃ ┣ reportWebVitals.ts
┃ ┃ ┗ setupTests.ts
┃ ┣ .dockerignore
┃ ┣ .gitignore
┃ ┣ Dockerfile
┃ ┣ package-lock.json
┃ ┣ package.json
┃ ┣ README.md
┃ ┗ tsconfig.json
┣ nodeapp/
┃ ┣ handlers/
┃ ┃ ┗ company.js
┃ ┣ .dockerignore
┃ ┣ app.js
┃ ┣ Dockerfile
┃ ┣ package.json
┃ ┣ partners.json
┃ ┗ README.md
┗ docker-compose.yml

```
