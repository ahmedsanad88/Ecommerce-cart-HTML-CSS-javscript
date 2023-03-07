# HTML_CSS_JAVASCRIPT_CART_Project💰

![GitHub](https://img.shields.io/github/license/ahmedsanad88/cart-HTML-CSS-javscript)

The project simulates E-commerce cart functionalities using only HTML-CSS-Js.

The Project requirements were the following:

- [x] Create an **array of objects** (containing 6 objects) where each object represents a product with the following properties:-
  - product_name (string, ex: "Gold Coin")
  - product_price (string, ex: "112.55")
  - product_image (string, ex: "gold-coin.png")
  - added_to_cart (boolean, ex: false)
- [x] Create a page where there are 6 product cards displayed with all their details.
- [x] Each product card contains name, price, image, add_to_cart button and quick_view button.
- [x] Create a cart icon in the navbar, which opens a dropdown with added_to_cart products.
- [x] The cart icon should have an **indicator** to the number of **added_to_cart** products.
- [x] Create a quick_view modal which is opened whenever the user clicks on the quick_view button of any product.
- [x] The quick_view modal has the same details displayed in the product card.
- [x] Adding the product to cart or removing it will affect all places where the product is displayed (product card, navbar dropdown quick_view modal)
- [x] If the product is **added_to_cart**, the "add to cart" button should be converted to "remove from cart"
- [x] Use **localStorage** to store the array of products, don't use the default array mentioned in first step if there is an array in the **localStorage**
- [x] You are only allowed to use **HTML**, **CSS** and **JavaScript**, but you can't use jQuery, Bootstrap, Font awesome (you can use icons but you don't need to attach a whole library of icons), Google Fonts (you can just download and use any single font), etc..

<br />
<br />

![Random GIF](https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif)

# Table of contents🗂

- [HTML_CSS_JAVASCRIPT_CART_Project💰](#html_css_javascript_cart_project)
- [Table of contents🗂](#table-of-contents)
- [Project Start🥁](#project-start)
- [Functionality💡](#functionality)
- [disclaimer🔴](#disclaimer)
- [Installation⚙️](#installation️)
- [Development🛠](#development)
- [Contribute🤝](#contribute)
- [License🧾](#license)
- [Footer💐](#footer)
- [Author❤️](#author️)

# Project Start🥁

> Open the project folder on VSCode
> The project entry point is the Index.html
> Simply open the html file on the Live Server.

# Functionality💡

- **Technology Used:**
  - HTML
  - CSS
  - Javascript
- **Techniques used:**
  - DOM manipulation.
  - Javascript Classes.
  - Browser LocalStorage.
- **General Info:**
  - Generate Products Dynamically.
    > looping over all products (_preSaved_) existing in the localStorage and automatically generating the HTML template.
  - Using Classes.
    - > Using classes is one way to do the requirements, and I choose to use classes to keep my code organized and abstracted from others functionalities and enclosed with the inner functions.
    - > The class consists of three stages, the 1st stage is rendering the content _HTML_ then the 2nd stage is to added all required DOM events and the last stage is to handle linking between different part of the app and how to interact together.

# disclaimer🔴

> The main purpose of the project is to handle cart action with pure javascript and there is a better way to handle similar requirements according to the newest technologies that evolved every day.

# Installation⚙️

> No need to install any to run our project.✌🏻

[(Back to top)](#table-of-contents)

# Development🛠

> A project is used a basic structure that can be used as a fundamental structure for an advanced one.

[(Back to top)](#table-of-contents)

# Contribute🤝

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

[(Back to top)](#table-of-contents)

# License🧾

[MIT](https://choosealicense.com/licenses/mit/)

[(Back to top)](#table-of-contents)

# Footer💐

Leave a star on GitHub, give a clap on Medium and share this guide if you found this helpful.

[(Back to top)](#table-of-contents)

# Author❤️

`Ahmed Sanad`

[(Back to top)](#table-of-contents)
