# Product Catalog

A simple and responsive web application built with **Vanilla JavaScript** and **TailwindCss**.

## Preview

## Features

- Display products from an external API
- Search products
- Filter products by category
- Filter products by rating
- View product details
- Add products to wishlist
- Remove products from wishlist
- View wishlist
- Infinite scrolling for product loading
- Responsive design
- Loading and error states

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API
- Parcel
- TailwindCSS

## API

This project uses the [DummyJSON Products API](https://dummyjson.com/) to fetch product data.

The API is used for:

- Fetching products
- Fetching all categories
- Searching products
- Filtering products
- Sorting products
- Fetching individual product details

> [!NOTE]
> In this project, arrays are used in JavaScript to better understand and practice core concepts.
>
> For now, we only need two APIs: one for fetching products and one for fetching categories.
>
> We will use APIs for these purposes later.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Erfun-H/product-catalog.git
```

### 2. Navigate to the project directory

```bash
cd product-catalog
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run start
```

The application will then be available at the local development URL provided by Vite.

## Project Structure

```text
product-catalog/
├── LICENSE
├── package.json
├── package-lock.json
├── README.md
└── src/
    ├── fonts/
    ├── images/
    ├── index.css
    ├── index.html
    └── js/
```

## What I Practiced

This project was built to practice and improve my JavaScript skills through a real-world use case.

Key concepts practiced:

- DOM manipulation
- Event handling
- Event delegation
- Fetch API
- Async/Await
- Array methods such as `map()`, `filter()`, `find()`, and `reduce()`
- Working with objects and arrays
- State management
- Dynamic UI rendering
- Error handling
- Infinite scrolling implementation
- Responsive UI development

## License

This project is licensed under the MIT License.
