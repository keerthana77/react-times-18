# React-Times-18

React-Times-18 is a time picker component for React applications, designed to support **React 18**. This package is a fork of the original [React-Times](https://www.npmjs.com/package/react-times) package, with updates to ensure compatibility with React 18. Additionally, Storybook support has been removed to streamline the library.

## Why React-Times-18?

The original `react-times` package supports React versions up to 16, leaving React 18 users without a compatible solution. To address this limitation, this project was created by forking `react-times` and updating it to work seamlessly with React 18 while removing Storybook support to simplify the setup.

---

## Features

- Fully compatible with React 18.
- Easy-to-use and customizable time picker component.
- Lightweight and dependency-free (no reliance on jQuery).
- Removed Storybook support to streamline usage.

---

## Installation

Install the package via npm:

```bash
npm install react-times-18
```

## Basic Usage

Import and use `react-times-18` in your React project:

```
import TimePicker from 'react-times-18';
import 'react-times-18/css/material/default.css'; // Import required CSS

function App() {
  const handleTimeChange = (options) => {
    console.log(options); // Logs the selected time
  };

  return (
    <TimePicker
      onTimeChange={handleTimeChange}
      theme="material"
      timeMode="12"
    />
  );
}

export default App;
```

---

## Changes from the Original React-Times

1.  **React 18 Compatibility:** Updated dependencies and components to support React 18.
2.  **Removed Storybook Support:** Storybook-related files and configurations were removed to focus solely on the core library functionality.

## Props

`react-times-18` inherits all the original props and functionality from the `react-times` package. For a full list of props, refer to the [original documentation](https://www.npmjs.com/package/react-times).

## License

This project is licensed under the MIT License, as is the original `react-times` package.

## Acknowledgments

This package is based on [React-Times](https://www.npmjs.com/package/react-times) by [ecmadao](https://github.com/ecmadao). All credits for the original implementation go to them.
