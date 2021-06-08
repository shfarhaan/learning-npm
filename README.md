# Learning How to Use Node Package Manager
This repo aims to represent my working knowledge with NPM
<br>
## Installing NodeJS
First we need to install NodeJS. Visit [NodeJS](https://nodejs.org/en/) and install preferred version. 

### Check Version
We open Terminal and write `node -v` to check which version we have installed or had installed. As long as we see any version after this we are good to go.

### Creating the **Package.json** File 
In the Terminal inside VSCode(Or any code Editor according to your preference) write `npm init` which is the base command to initialize a new **Package.json** file. And Done!!

### Adding a new Package
For instance we want to install Express, we open the terminal and write `npm install express`, thus the syntax to install <br> a package is `npm install package-name`

### Installing Dev Dependencies 
For instance we want to install babel-cli, we open the terminal and write `npm install babel-cli babel-preset-stage-0 babel-preset-es2020 --save-dev`, thus the syntax to install a dev dependencies is `npm install dev-package-name --save-dev`

### Installing React
We open the terminal and write `npm install -g react`, thus the syntax to install a package globally is `npm install -g package-name` or `npm install -global package-name` 

### Installing a specific version
We open the terminal and write `npm install eslint@5.2.0 -g`, thus the syntax to install a package globally is `npm install -g package-name@version-number`

### Checking Outdated Version
We open the terminal and write `npm outdated -g`, thus the command helps us to find outdated packages globally.

### To Remove a Package
We open the terminal and write `npm uninstall package-name`, thus the command helps us to remove any package that we have installed in our project.

### Semantic Versioning 
The process of assigning unique version numbers to every release. Within a given version number category, these numbers are generally assigned in increasing order and correspond to new developments in the release.

![semantic versioning](https://user-images.githubusercontent.com/19478310/121196412-48f92500-c892-11eb-811c-6fb1cedbac5d.PNG)
