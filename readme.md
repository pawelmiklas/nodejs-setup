# NodeJS Setup Boilerplate
This repository is a NodeJS setup boilerplate that provides a basic starting point for building a NodeJS application. It includes a package.json file with scripts for building, starting, and developing the application, as well as a set of devDependencies for common development tools.

## Getting Started
To get started with this boilerplate, you'll need to have NodeJS and npm (or yarn) installed on your machine. Once you have those set up, you can clone this repository and install the dependencies by running the following command:
```
npm install
```
## Building the Application
To build the application, you can use the build script in the package.json file. This script uses the tsup tool to transpile the TypeScript source code into JavaScript and output it to the dist directory. You can run the build script by executing the following command:

```
npm run build
```

## Starting the Application
Once the application is built, you can start it using the start script in the package.json file. This script simply runs the main JavaScript file in the dist directory using NodeJS. You can start the application by executing the following command:
```
npm start
```
## Developing the Application
While developing the application, you may want to run the build and start scripts in parallel so that changes to the source code are automatically transpiled and the application is restarted. The dev script in the package.json file uses the concurrently tool to run the build and start scripts simultaneously. You can run the dev script by executing the following command:
```
npm run dev
```
