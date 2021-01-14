# Condent Printer App

[![N|Solid](https://camo.githubusercontent.com/2ef2a441f9eaa1aca489796981cfa851d9388e08209b08e57526a06b4e604a57/68747470733a2f2f656c656374726f6e6a732e6f72672f696d616765732f656c656374726f6e2d6c6f676f2e737667)](https://nodesource.com/products/nsolid)

## Dev

To operate the project as a developer:

1. Checkout this Projekt
2. Checkout Develop/Master Branch
3. Run:

```sh
$ npm install
```

4. To compile Typescript and SCSS

```sh
$ npm run dev
```

5. At the same time in a other terminal:

```sh
$ npm start
```

## Log

Just a simple logging module for your Electron or NW.js application. No dependencies. No complicated configuration. Just require and use. Also, it can be used without Electron in any node.js application.

By default, it writes logs to the following locations:

on Linux: ~/.config/{app name}/logs/{process type}.log
on macOS: ~/Library/Logs/{app name}/{process type}.log
on Windows: %USERPROFILE%\AppData\Roaming\{app name}\logs\{process type}.log
