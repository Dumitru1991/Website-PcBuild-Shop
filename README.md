[README_PcBuild_Shop.md](https://github.com/user-attachments/files/34101404/README_PcBuild_Shop.md)
# PcBuild Shop

A small front-end shop website for PC components, built with **HTML, CSS and vanilla JavaScript**. The project was made to understand and practice the JavaScript behind a **shopping cart**: adding items, removing items and updating the cart.

🛒 **Live demo:** [dumitru1991.github.io/PcBuild_Shop](https://dumitru1991.github.io/PcBuild_Shop/)

## Features

- Product listing loaded from a JSON file (`products.json`)
- Add products to the cart
- Remove products from the cart
- Cart updates dynamically without reloading the page
- Responsive, static front-end (no backend or build tools required)

## Tech Stack

- HTML5
- CSS3
- JavaScript (vanilla, no frameworks)
- JSON as the product data source

## Project Structure

```
Website-PcBuild-Shop/
├── images/         Product and site images
├── index.html      Page structure
├── app.js          Cart logic (add/remove items, product loading)
├── products.json   Product data
├── main.css        Main styles
├── styles.css      Additional styles
└── poza2.jpg       Site image
```

## Getting Started

### Play online

Open the live demo: https://dumitru1991.github.io/PcBuild_Shop/

### Run locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dumitru1991/Website-PcBuild-Shop.git
   ```
2. **Open the project folder**
   ```bash
   cd Website-PcBuild-Shop
   ```
3. **Start a local server.** Because the products are loaded from `products.json`, opening `index.html` directly may be blocked by the browser. Use a local server instead, for example:
   - the VS Code **Live Server** extension, or
   - Python: `python -m http.server 8000`, then open `http://localhost:8000`

## How It Works

`app.js` reads the product data from `products.json`, displays the products on the page, and manages the cart. When a user clicks to add or remove an item, the cart contents and totals are updated in the page. `index.html` provides the layout, and the CSS files style the shop.

## Possible Improvements

- Save the cart in `localStorage` so it survives a page refresh
- Quantity controls for each cart item
- Category filters and search
- Checkout page
- Mobile menu improvements

## Author

**Dumitru** – [@Dumitru1991](https://github.com/Dumitru1991)

## License

*Add a license of your choice (e.g. MIT).*
