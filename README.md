# 📱 React & TypeScript Phone Catalog

A **fully responsive, client-side web application** designed to display a catalogue of mobile devices. This project serves as a showcase of modern frontend development practices, focusing on robust state management, efficient component architecture, and type safety.

## 🚀 Live Preview

The application is deployed via GitHub Pages and is publicly accessible here:

[Live Demo Link](https://ElisabethPO.github.io/Phone-catalog-react-ts/)

## 🎨 Design Reference
This project is implemented based on the following design specification:

https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog--V2--Original-Dark?node-id=0-1&p=f&t=nj1T56VpqpPXVnB1-0

## 💻 Technologies Used

## Core
* **React** (v18.2.0) - UI framework
* **TypeScript** (v5.0.2) - Type safety
* **SCSS** (v7.0.3) - Styling

## UI/UX
* **React Router** (v6.14.2) - Navigation
* **Swiper** - Image galleries
* **use-react-router-breadcrumbs** (v4.0.1) - Navigation breadcrumbs
* **React Loading Skeleton** (v3.3.1) - Loading states

## Development & Deployment
* **Vite** (v4.4.5) - Build tool
* **ESLint** (v8.45.0) - Code quality
* **Nestify** - Hosting and deployment

## ✨ Features

* **Responsive Layout:** Optimized for different screen sizes and devices, responses on width 320px, 640px, 1200px and 1440px,
* **Navigation:** react-router-dom library is used in the application to enable navigation between multiple pages, and URL-based search parameters saved when navigating.
* **Favorites & Cart:** adding products to favorites or shopping cart, with total price calculation.
* **Product Filtering:** Filter products by capacity and color inside product card.
* **Sorting:** Sort products based on criteris: year, price, alphabetically.
* **Pagination:** Navigate through large lists of products, opportunity to choose number of items per page, and number of pages depends on this.
* **Sticky header:** Keeps the header visible as you scroll.
* **Scroll to Top Button:** Easily return to the top of the page.
* **Loader:** Indicates loading status for a better user experience.
* **Product Details:** Dedicated pages for detailed information on

## 🏗️ Getting Started

Follow these steps to set up and run the project locally on your machine.

### 1. Clone the repository

Open your terminal and execute the following commands:

```bash

git clone https://github.com/ElisabethPO/Phone-catalog-react-ts.git
cd Phone-catalog-react-ts
```
### 2\. Install dependencies

Install all required packages (Gulp and linters):

```bash
npm install
```

### 3\. Run the project locally

Start the local development server:

```bash
npm start
```
