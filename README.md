# React Library Component

This is a basic configuration project to get started on publishing a library of a react component on npm.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Install the package from npm

```
npm install react-test-library-component
```

### Get started on your new library

Fork or clone the repository https://github.com/andreeasimona/react-test-library-component

Install the dependencies
```
npm install
```

Follow the instructions in src/index.js to add your first changes.

Follow the instructions in package.json to personalise the name/repository/version etc. of your package.
In package.jsonchange the following lines

```
{
....
  "name": "Change this for your library name for example your-component-name",
  "version": "Change this for your version number",
....
  "author": "Add yourself as the author",
....
  "repository": {
    "url": "Change this for your github repository"
  },
....
  "bugs": {
    "url": "Change this for your github repository"
  },
  "homepage": "Change this for your github repository"
}
....
```


## Publish on npm

Login into your account

```
npm login
```

Publish

```
npm run build
npm publish
```

## Usage in local enviroment

In the current project
```
npm run build
npm link
```

Use this in the project where you want to use/test your new library
```
npm link your-component-name
```

Import the component in the target project
```
....
import YourComponentName from 'your-component-name';
....
<YourComponentName />
....
```

## License

This project is licensed under the MIT License