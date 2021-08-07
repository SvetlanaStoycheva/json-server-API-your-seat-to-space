## Mock API with json-server / deployment on Heroku

#### API for my Vanilla JS project Your-Seat-To-Space

- [get started with json-server](https://www.npmjs.com/package/json-server#getting-started)
  - local install: npm i json-server
  - create db.json file with some data
  - npx json-server --watch db.json
- npm init (we create package.json)
- npm i json-server (again to set the dependencies in package.json)
- in package.json => in scripts: "start": "node server.js"; create a file: server.js
- install HEROKU:

  - npm install heroku; create
  - link: heroku create your-seat-to-space-api
    https://your-seat-to-space-api.herokuapp.com/
    https://git.heroku.com/your-seat-to-space-api.git
  - create project: heroku create your-seat-to-space-api-project
    https://your-seat-to-space-api-project.herokuapp.com/

- [tutorial that helped](https://www.youtube.com/watch?v=FLnxgSZ0DG4)
