# Shopping Cart Application

This is a Shopping Cart application built using React, Redux, Tailwind CSS, JavaScript, and CSS. The app allows users to browse products, add items to the cart, view the total price, and more.

## Features

- Browse products with detailed information.
- Add and remove items from the shopping cart.
- View total price and adjust quantities.
- Responsive design using Tailwind CSS for seamless user experience on different devices.
- Loading spinners for a better user experience while data is being fetched.

## Installation

Follow the steps below to set up and run the project on your local machine:

### Installment

1. Create a new React app:

   ```bash
   npx create-react-app shopping-cart
   ```

2. Change into the project directory:

   ```bash
   cd shopping-cart
   ```

3. Install the necessary dependencies:

   ```bash
   npm i
   ```

4. Install Tailwind CSS as a development dependency:

   ```bash
   npm install -D tailwindcss
   ```

5. Initialize the Tailwind CSS configuration file:

   ```bash
   npx tailwindcss init
   ```

6. Install `react-redux` for state management:

   ```bash
   npm i react-redux
   ```

7. Install Redux Toolkit for easier state management:

   ```bash
   npm i @reduxjs/toolkit
   ```

8. Install `react-loader-spinner` for loading animations:

   ```bash
   npm i react-loader-spinner
   ```

## Configuration

After initializing Tailwind CSS, ensure that you include the following in your CSS files:

# Index.CSS

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

# Tailwind.CSS

```
tailwind.config.js

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

# License

This project is licensed under the MIT License.
