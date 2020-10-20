* original codes are in https://ccoenraets.github.io/es6-tutorial/setup-babel/

1. download and install npm from https://nodejs.org/en/download/

2. open command window change directory to project directory 
> cd C:\Users\A\source\repos\es6-tutorial

3. install all modules in order (module lists in package.json)
> npm install @babel/cli@^7.12.1 --save-dev
> npm install @babel/core@^7.12.3 --save-dev
   ...

4. build project
> npm run webpack

5. start http-server and see in browser
> npm start