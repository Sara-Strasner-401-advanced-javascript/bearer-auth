# LAB 7

## Project: BEARER AUTH

### Author: Sara Strasner

### Links and Resources

- [Latest PR](https://github.com/sarastrasner/basic-auth/pull/4)
- [ci/cd](https://github.com/sarastrasner/basic-auth/actions)
- [front-end application](https://sarastrasner-basic-auth.herokuapp.com/) 

### Setup

#### `.env` requirements (where applicable)

- `PORT` - 3000
- `MONGODB_URI=mongodb://localhost:27017/auth`

#### How to initialize/run your application (where applicable)

- e.g. `npm start`


#### Tests

- The tests all run via jest in the terminal.
- All tests are passing.
- I spent a lot of time looking at the Jest documentation specifically around matchers to prooerly anticipate returned data from two of my routes and couldn't figure out which matcher/parameter to uses. The closes I could get on those was `toBeDefined`.


#### UML
![UML](./assets/UML.JPG)