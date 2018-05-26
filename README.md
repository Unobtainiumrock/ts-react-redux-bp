# React + Redux and TypeScript Boiler Plate

## Description
This is just a simple setup to jump right into developing projects with the previously mentioned tech.
Check out the package.json for additional information on packages that are used.

## Prerequisites
Have node and npm installed https://nodejs.org/en/download/


### Getting Started
1.) cd into `ts-react-redux-bp`.

2.) Run `npm install -g typescript`, and then `npm link typescript`.
    alternatively, you can install typescript as a non-global and skip
    the `npm link typescript`.

3.) Run `npm install` to install all of the other included dependencies.

4.) To ts-compile and webpack bundle all of your files, type `npm run build` into your terminal.
    You can alternatively run `npm start`. This will run the build script, followed by setting
    up a webpack-dev-server to serve the files for viewing at your localhost:8080.

note: This assumes that you have knowledge of module patterns and loading various dependencies into a project.

#### Useful info on declaration files for third party modules
https://blogs.msdn.microsoft.com/typescript/2016/06/15/the-future-of-declaration-files/

I've already added the declaration files to keep TypeScript from annoying you about no declaration files.
You will need to repeat the same process for any further added third party modules.
