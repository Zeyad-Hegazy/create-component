# react-templator

react-templator is a command-line tool that streamlines the process of cleaning up preset code generated by Create React App (CRA) and Vite, and it also assists in creating React component folders.

## Features

- Remove unnecessary boilerplate code generated by CRA and Vite.
- Create React component folders with a consistent structure.
- Save time and reduce repetitive manual tasks when starting new React projects.

## Installation

You can install react-templator globally using npm or yarn:

```bash
npm install -g react-templator
```

Or

```bash
yarn global add react-templator
```

## Usage

To clean up a Create React App (CRA) project, navigate to your project directory and

```bash
react-templator temp
```

This will remove unnecessary boilerplate code and files generated by CRA.
and give you src folder with the following structure

```bash
src/
├── api
├── assets
├── components
├── constants
├── hoc
├── hooks
├── pages
├── ui
├── util
├── App.jsx
├── App.module.css
├── index.css
├── index.js
```

## Creating React Component Folders

To create a React component folder with a consistent structure, run the following command:

```bash
react-templator fc MyComponent
```

Replace 'MyComponent' with the name of your component. This will create a folder for your component with the following structure:

```bash
MyComponent/
├── MyComponent.jsx
├── MyComponent.module.css
├── MyComponent.test.js
└── index.js
```

it well automaticlly create it in src/components folder

**_NOTE:_** you must sure that you have components folder inside src folder to generate component successfully
