# React Library Component

This is a basic configuration project to get started on publishing a library of a react component on npm.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

Get the package
```
npm install react-test-library-component
```

Get other dependency
```
npm install
```

## Publish on npm

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

Import the component in hte target project
```
....
import ComponentName from 'your-component-name';
....
<ComponentName />
....
```

## License

This project is licensed under the MIT License