## The Aim

A comprehensive experience when using [Facebook's Jest](https://github.com/facebook/jest) within a project. 

* Useful IDE based Feedback
* Session based test watching

![Screenshot](https://github.com/orta/vscode-jest/raw/master/images/vscode-jest.gif)

## Features

* Starts Jest automatically when you're in a project with Jest installed.
* Show individual fail / passes inline.
* Show fails inside the problem inspector.
* Highlights the errors next to the `expect` functions 

## How to get it?

Open up VS Code, go search for the extension "Jest"

## How to get it set up?

This project has the expectation that you would run something like `npm run test` which _just_ looks like `jest` in the `package.json`. So, please keep your configuration inside the `package.json` as opposed to using command line arguments.

## Future Ideas

* Offer feedback if you are using an old Jest?
* Only run parser on files that match the Jest `testRegex`.
