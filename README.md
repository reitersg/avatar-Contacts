# avatar-Contacts

A Contacts List application for the AVATAR Project.

# Requires
- Node and NPM
- The Avatar Service (jetty-avatar-0.2.5 is the most recent version)
  - Requires Java
# Installation instructions

- Clone the repo: git clone https://github.com/robbawebba/avatar-todo.git.
- Run npm install to get the dependencies. 
  - You may have to install webpack globally: npm install -g webpack.
- Copy .env-example to a new file called .env. This will be your personal dev environment settings.
- Configure the values in your .env file:
  - API_HOST: The base URL for the Avatar Service API. The routes should remain the same, but the port is configurable. The port number should match the port the Avatar Service uses for its Jetty server. To change the port inside the Avatar Service, edit the following files of the Avatar Service: start.bat/start.sh, src/main/resources/avatar/fuseki.properties. (Default 8081)
  - DEV_PORT: The port used by WebpackDevServer when serving this front-end project. (Default 9090)
# Execution instructions
- Start the dev server with npm start.
- Navigate to localhost:9090 (or the value for DEV_PORT you configured in your .env file).
