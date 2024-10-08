<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">MEAN Stack Task Manager</h3>

  <p align="center">
    Project built using Angular, NodeJS, Express.js and MongoDB<br>         
  </p>
  
  <br>
  <br>
</div>

### Built With

This section shows what technologies are used in this particular project.

- [Angular](https://angular.io/)
- [NodeJS](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [Angular Material](https://material.angular.io/)
- [Redis](https://redis.io/)
- [Swagger](https://swagger.io/)
- [Chart.js](https://www.chartjs.org/)
- [Yarn](https://www.yarnpkg.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Hosting

This section shows what technologies are used in this particular project.

- <strong>MongoDB</strong> hosted on <a href="https://www.mongodb.com/pricing">MongoDB</a> shared cluster
- <strong>Redis</strong> hosted on <a href="https://render.com/pricing">Redis</a> free tier
- <strong>NodeJS</strong> hosted on <a href="https://render.com/pricing">NodeJS</a> free tier
- <strong>Angular</strong> hosted on <a href="https://pages.github.com/">Github Pages</a>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

After cloning the project, you need to do a few things to be able to run it.

### Prerequisites

You need to have the following requirements:

- mongodb <a target="_blank" href="https://www.mongodb.com/try/download/community/">(download here)</a>
- node 16.20.1 <a target="_blank" href="https://nodejs.org/en/download/">(download here)</a>
- redis <a target="_blank" href="https://redis.io/download/">(download here for Linux)</a> or <a target="_blank" href="https://github.com/tporadowski/redis/releases">(download here for windows)</a>
- yarn

  ```sh
  npm install -g yarn
  ```

- angular cli 14

  ```sh
  npm install -g @angular/cli@14
  ```

### Installation

_Below is an example of how you can run the project._<br>
_More scripts at package.json_

1. Clone the repo
   ```sh
   git clone https://github.com/Bhumi704/task-manager.git
   ```
2. Install NPM packages via yarn
   ```sh
   yarn install
   ```
3. If running for the first time, run the following command to answer angular cli questions
   ```js
   ng serve
   ```
4. Run angular, express and mongoDB as development mode
   ```js
   yarn dev
   ```
5. Deploy to github pages
   ```js
   yarn deploy
   ```
   If needed, you can debug express using `yarn api-debug`. <br>More builds scripts at `./package.json`. <br>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage



```js
-------------------------------
-------- [USER ROUTES] --------
-------------------------------
[GET] localhost:3000/api/users -> 'getAll'
[GET] localhost:3000/api/users/{id} -> 'getOne'
[POST] localhost:3000/api/users -> 'create'
[PUT] localhost:3000/api/users/{id} -> 'update'
[DELETE] localhost:3000/api/users/{id}-> 'remove'
[POST] localhost:3000/api/users/authenticate -> 'authenticate'
[GET] localhost:3000/api/user/exists/{email}/ -> 'checkIfEmailExists'
[PUT] localhost:3000/api/users/changePassword/{id} -> 'changePassword'
[POST] localhost:3000/api/users/refreshToken -> 'refreshToken'
[POST] localhost:3000/api/users/logout -> 'logout'

-------------------------------
-------- [TASK ROUTES] --------
-------------------------------
[GET] localhost:3000/api/tasks?pageSize&searchTerm&pageIndex&sortFilter&sortDirection&startDate&finalDate -> 'getAll'
[GET] localhost:3000/api/tasks/{id} -> 'getOne'
[POST] localhost:3000/api/tasks -> 'create'
[PUT] localhost:3000/api/tasks/{id} -> 'update'
[DELETE] localhost:3000/api/tasks/{id}-> 'remove'




 
 
