# bootlaterus

Equilaterus base boostrap theme

## Builds

| **Branch** | Build status | Version |
| ------------- |:-------------:| -----:|
| **Master**        | [![Build Status](https://travis-ci.org/equilaterus/bootlaterus.svg?branch=master)](https://travis-ci.org/equilaterus/Vortex) | Unavailable  |
| **Dev-unstable**        | [![Build Status](https://travis-ci.org/equilaterus/bootlaterus.svg?branch=dev)](https://travis-ci.org/equilaterus/Vortex) | WIP  |

## How to start

* [Clone the repo and open it on VS Code](https://github.com/equilaterus/wikilaterus/wiki/Cloning-a-repo-on-Github).

* Install npm by downloading [nodejs](https://nodejs.org/en/).

## Windows

* **Option A**: Use the **bat** files that are inside *utils* folder:

  * Run **win-install.bat** to automatically setup the enviroment.

  * Run **win-run.bat** to build bootlaterus. It will open automatically a browser with hot reload so when you update one of the template or scss files it will show you an updated version of **bootlaterus**.

  * **win-build.bat** will just generate the output css files into *dist* folder to distribute your own version of **bootlaterus**.

* **Option B**: Execute the commands like on any other OS.

## Any OS

* Using VS Code terminal run the following commands to setup the enviroment:

    ```
    npm install -g grunt-cli
    npm install
    ```

* To build and run the project in a synchronized browser with hot-reload, run this command:

    ```
    grunt
    ```

* If you want to generate only the output files (*dist/* folder) without running the server run this command:

    ```
    grunt build
    ```

## Important

Always be sure to modify the files located at **src/** and not at **dist/**, when building files located at **dist/** will be overwritten.