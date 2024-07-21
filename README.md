# Webshop

This project is an Angular-based e-commerce application with a variety of features for users to browse and manage products in their shopping cart.
This project was generated with [Angular CLI](https://angular.io/cli) version 14.2.1.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Components Overview](#components-overview)
- [Services Overview](#services-overview)
- [Usage](#usage)

## Features

- **Product Listing**: Users can view products in a three different layouts.
- **Product Categories**: Filter products by categories.
- **Sorting and Pagination**: Sort products by price in ascending or descending order and view a specified number of products per page.
- **Shopping Cart**: Add, remove, and update product quantities in the shopping cart.
- **Cart Management**: View cart items, total price, and clear the cart.
- **Snackbar Notifications**: Real-time feedback for cart operations.

## Technologies Used

- **Angular**: Framework for building the application.
- **Angular Material**: UI component library for Material Design.
- **RxJS**: Library for reactive programming using Observables.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **TypeScript**: Superset of JavaScript for type-safe code.
- **HTTP Client**: For making API calls to the fake store API.

## Installation

1. **Install dependencies**: npm install.
2. **Start the server**: Run `ng serve`.
3. **Access the app**: Open [http://localhost:4200](http://localhost:4200) in your browser.

## Code scaffolding

Run `ng generate component component-name` to generate a new component.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Project Structure

```
webshop/
└── store/
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ ├── cart/
│ │ │ ├── filters/
│ │ │ ├── header/
│ │ │ ├── home/
│ │ │ ├── product-box/
│ │ │ └── products-header/
│ │ ├── models/
│ │ ├── services/
│ │ └── app.module.ts
│ ├── assets/
│ ├── environments/
│ └── index.html
├── angular.json
├── package.json
└── README.md
```


## Usage

- **Viewing Products**: Products can be viewed in three different layouts: small- four product per column, medium - three products per columns, and one-by-one product size. Use the layout buttons in the products header to switch between views.
- **Filtering Products**: Use the category filter to display products from a specific category.
- **Sorting Products**: Sort products by price in ascending or descending order.
- **Managing Cart**: Add products to the cart, adjust quantities, and remove items as needed. View the total price and clear the cart if desired.

