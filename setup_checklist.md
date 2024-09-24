📰🚀 Checklist for the express proejct initial setup

- [] Git setup
- [] Node version manager
- [] Nodejs project setup
- [] Typescript setup
- [] Prettier setup
- [] Eslint setup
- [] Git hooks setup
- [] Application config setup
- [] ExpressJs app setup
- [] Logger setup
- [] Error handling setup
- [] Tests setup
- [] Create template

- How to setup typescript:

  1. run the below command in any repository initialized with npm: npm i -D typescript nodemon ts-node @types/node
  2. After installation initialize a tsconfig file with the command: npx tsc --init

- How to setup eslint:

  1. run the following command: npm init @eslint/config

- How to setup prettier

  1. run the following command: npm install -D --save-exact prettier

  2. create a .prettierrc.json file in the repository and write rules inside that file

  3. now use following commands:
    - npx prettier . --check
    - npx prettier . --write
  
  4. Use in script (package.json):
     "format:check":"prettier . --check",
     "format:fix":"prettier . --write"

     npm run format:check
     npm run format:fix
