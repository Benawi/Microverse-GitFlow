<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)

- [📝 License](#license)


# 📖 Conflicts & git Project <a name="about-project"></a>


The repository also contains files for setting up linters and validators.

### Key Features <a name="key-features"></a>
## Conflicts & git: [Requirements](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/conflicts_git.md)
### Features Added:
# Git flow 
-  Create a new repo. Initialize it with an empty README file.

- Clone the newly created repository to your local machine.
- Add a new branch named dev(alternative names: development, develop).
- Make sure that the dev branch is pushed to GitHub.
```
       - git push --set-upstream origin dev
````
 -  Make the dev branch [the default branch](https://docs.github.com/en/github/administering-a-repository/managing-branches-in-your-repository/changing-the-default-branch#changing-the-default-branch).
 - Create a feature branch called add-quotes
 - Add a programmer.txt file with the following sentence (typo is needed there):
```  
"A good programmer is someone who always looks both ways before crosing a one-way street."
```
- Add a solve.txt file with the following sentence:
 ```
''First, solve the problem. Then, write the code." – John Johnson
```
- Add another test.txt file. It should be empty.
- Commit all files to your feature branch.
- Push your changes to GitHub.
- Open a new pull request from add-quotes into dev.
- Make sure that you want to merge your commits into dev branch. You should add a comment in your opened pull request that is similar to this one:


 - Make sure that you start from the add-quotes branch:
```
 git checkout add-quotes
```
- Create a new branch fix-quotes and switch to it:
``` 
git checkout -b fix-quotes
```
- Make changes in your files:
        -  Fix the typo in the quote about a good programmer (crosing should be crossing).
        -  Remove the empty test.txt file.
        -  Add a new simplicity.txt file with the following sentence:
        ```
        "Simplicity is the soul of efficiency." - Austin Freeman
        ```
- Commit your changes.
- Push fix-quotes to GitHub:
```
git push --set-upstream origin fix-quotes.
``` 
- Open a new pull request (from fix-quotes to dev branch):


<p align="right">(<a href="#readme-top">back to top</a>)</p>




## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Setup

Clone this repository to your desired folder:

> cd my-folder
> git clone git@github.com:myaccount/my-project.git

### Prerequisites

In order to run this project you need:

- gitHub account;
- git installed on your OS.

### Install
>[Linters]( https://github.com/microverseinc/linters-config/tree/master/html-css-js)
- Installations required to run this project:
### Install the node module 
- Run the following command:
```
npm install 
```
### Install the webpack-cli. 
- Run the following command:
```
npm install webpack webpack-cli --save-dev
```
### Install the plugin and adjust the webpack.config.js file
- Run the following command:
```
npm install --save-dev html-webpack-plugin
```
### In order to import a CSS file  add the style-loader and css-loader to your module configuration
- Run the following command:
```
npm install --save-dev style-loader css-loader
```
### webpack-dev-server
- Run the following command:
```
npm install --save-dev webpack-dev-server
```
### Webhint installation. 
- Run the following command:
```
npm install --save-dev hint@7.x
```
### Stylelint installation.
- Run the following command:
```
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
### ESLint
- Run
```
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x
```
### Usage

You can use this project by cloning it to your folder and changing index.html and styles.css files.

### Run tests

To run tests, run the following commands:

To track linter errors locally follow these steps:  

Download all the dependencies run:
```
npm install
```
Track HTML linter errors run:
```
npx hint .
```
Track CSS linter errors run:
```
npx stylelint "**/*.{css,scss}"
```
Track JavaScript linter errors run:
```
npx eslint .
```

### Deployment

You can redeploy this project by adding new lines of code to source files.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

### 👤 Habtamu Alemayehu 
- GitHub: [Benawi](https://github.com/Benawi)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🔭 Future Features <a name="future-features"></a>

- Leaderboard: Hit the API [this](https://github.com/microverseinc/curriculum-javascript/blob/main/leaderboard/m2_send_receive_data.md) will be added.
- Leaderboard: final touches [this](https://github.com/microverseinc/curriculum-javascript/blob/main/leaderboard/m3_final_touches.md)  will be added.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give me ⭐️ If you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- I would like to thank Microverse program for providing me this great chance.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
