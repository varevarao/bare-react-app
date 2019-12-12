# Barebones React app
... with the basic setup required for quickly running any small, customizable React based project/proof-of-concept. The project contains a *webpack* based build system, and uses *babel* for transpiling the code. That's all the assumptions made, the rest is up to your imagination, and skill.

# Setup
- Install the dependencies using the regular `npm install` command
- **webpack** based build system, with the following `npm run` commands:
1. `start`: Start a webpack dev server at `http://localhost:3000`/`http://<local-ip>:3000`
1. `build:dev`: Genrates a static *development* build for the project in the folder named `build/`
1. `build:prod`: Genrates a static *production* build, minified using Terser, for the project in the folder named `dist/`