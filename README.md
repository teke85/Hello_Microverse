![](https://img.shields.io/badge/Microverse-blueviolet)

# Project Name

> **Hello Microverse!**

# Project Requirements

> In this project, you will set up a "Hello world" repository. No complex coding is required for this exercise. Your goal here is to master all of the tools and best practices you learned about in previous steps. You will be using them in all Microverse projects and most likely in your future job as well, so it is important to know them!.

## Built With

- Languages Used: Html, CSS
- Code Editor: Visual Studio Code
- Tools Used: Linters
- Applications Used: GitHub Desktop
- VCS: Git
- Package Manager: Node, NPM

### Prerequisites

To get a local copy up and running follow these simple example steps.

- You need to have a Code Editor Installed.
- Make sure Nodejs and NPM are installed in your system to setup linters

### Setup

- Create a repo name **"Hello-World"** in your github account and add README.MD file
- Create a new branch according to the GitHub flow rules.
  - Remember to switch to the new branch :exclamation:
- git clone your repo into your local repository
- Add a .gitignore file.
- Update the README.MD file in [this template](https://github.com/microverseinc/readme-template) and commit changes
- Remember to _customise_ the template to your project :exclamation:
- Setup Linters by running following commands in your terminal:
  - npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x (Install the StyleHint linters)
  - npx stylelint "\*_/_.{css,scss}" (checks for the CSS related errors in your project)
  - npx stylelint "\*_/_.{css,scss}" --fix (This will fix the linters error, if any)
  - npm install --save-dev hint@7.x (Install the WebHint Linters)
  - npx hint . (You should see Finishing... on your terminal)
  - Commit the Linters changes to your github repo
  - Add 3 files (each one in a separate commit):
    - A .html file that includes a header with the text "Hello Microverse!". Use h1 tag for that.
    - A .css file that includes one class with styles for your header (make it in your favorite color).
    - A test.md file with the text "This file should be ignored by git".
  - Make sure that the last file is actually ignored by git and is not present in your GitHub repository.
  - Commit all changes.
- Open a pull request.

## Authors

👤 **Author**

- GitHub: [@teke85](https://github.com/teke85)
- Twitter: [@muttau](https://twitter.com/muttau)
- LinkedIn: [isiteketo mutau](https://www.linkedin.com/in/isiteketo-mutau-736894241/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- [Youtube Videos](https://www.youtube.com/watch?v=PrIY8sYwe90)
- [Setup Linters](https://questions.microverse.org/t/configure-linters-for-html-and-css/2009)
- [Elie ](https://github.com/X-Elie-X), for always being their to help
- Thanks to everyone who will dedicate time to check this code and suggest any changes to improve the project.

## 📝 License

This project is [MIT](./MIT.md) licensed.
