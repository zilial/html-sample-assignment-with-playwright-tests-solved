# Exercise: Sample HTML Assignment

In this exercise you will learn to operate with assignments of the HTML&CSS curriculum.

If you are not using VSCode you can install and run the "live-server" npm package following the list of commands:

- [ ] Use `npm i live-server` to install the live-server package
- [ ] Use `npm run live-server` or `npx live-server --port=5551` to run the live-server. The port number should be 5551 strictly.

The live-server NPM package page: [Link](https://www.npmjs.com/package/live-server)

## Learning objectives

This assignment should prove that a student is able to:

- Download the assignment zipped file from Github
- Extract assignment files and open the assignment project folder in VSCode
- Install dependencies
- Run tests
- Read and understand test results
- Submit assignments

## Standard requirements

- [ ] Fork the project to your github account
- [ ] Clone the project to your computer
- [ ] Windows (WSL) setup instructions
  - [ ] Open the project in VSCode with `code <cloned_repo_folder_name>`
  - [ ] If you open the project in WSL the first time you need to follow some additional steps:
    - [ ] If you are prompted to install the WSL extension, please install it, otherwise find the "WSL" in the extensions and install it
    - [ ] Close VSCode
    - [ ] Open the project in VSCode with `code <cloned_repo_folder_name>`. Before the project opens it will install the VSCode server in your Ubuntu distribution.
    - [ ] Install the Live Server extension
  - [ ] Initialize playwright and install project packages
    - [ ] Use `npm i` to install packages
    - [ ] Use `npm run browser-install` to install the browser environment for testing (131mb will be downloaded)
    - [ ] Use `npm run deps-install` to install playwright additional dependencies (160mb will be downloaded)
- [ ] MacOS setup Instructions (skip if you are on Windows)
  - [ ] Open the project in VSCode
  - [ ] Initialize playwright and install project packages
    - [ ] Use `npm i` to install packages
    - [ ] Use `npm run browser-install` to install the browser environment for testing
- [ ] All the tasks of the "Specific requirements" section MUST be solved
- [ ] All the tests MUST pass. Fix the errors in case any tests don't pass BEFORE you submit (acceptance criteria)
  - [ ] Use `npm run test` to run all tests in the terminal
  - [ ] (Optional) Use `npm run test-ui` to run all the tests with GUI
  - [ ] (Optional) Use `npm run show-report` to see the latest report in the browser
- [ ] VSCode IDE MUST have 0 code problems listed (spelling problems are fine)
- [ ] The code MUST be formatted with Prettier
- [ ] Push the changes to the Github repo, when finished.
- [ ] Submit a txt file with the Github repo url.

## Specific requirements

- [ ] Create an html file with the name of "index" in the root of the project
- [ ] Add HTML Boilerplate to the document
- [ ] Set the document title to be "Sample project"
- [ ] Set the page heading to be "Sample project"
- [ ] Add a paragraph of text (20 words at least). You can use random text for the paragraph content.
