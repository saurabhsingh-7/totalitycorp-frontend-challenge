# Shopping Cart Assignments

## Overview
This project is all about creating a shopping cart where you can put items you want to buy. You'll see the number of items you've added in your cart, and you can even sort and filter products. We're using some special tools and tricks to make this work.

### How It Works
Displaying Products
We've made a way to show you products, but we didn't go shopping! Instead, we used a cool tool called Faker to make up some pretend products. These fake products look real, and we show them on the screen one by one using something we made called "SingleProduct."

### Sorting and Filtering
Want to see the cheapest or most expensive products first? We've got you covered. You can pick either "ascending" (cheapest first) or "descending" (most expensive first) using buttons. We also made a special filter for product ratings so you can find the best-rated items.

### Adding to Cart
When you find something you want to buy, you click the "Add to Cart" button. But if it's sold out, we won't let you add it. We used a clever trick called "conditional rendering" to show either the "Add to Cart" button or an "Out of Stock" message.

### Shopping Cart
We made sure you can keep track of what you want to buy in your cart. When you click "Add to Cart," the product goes into your cart, and you can see the total number of items there.

# Tech Stack
We used some powerful tools to make this project happen:

## React: 
It's like the engine of our project, helping us build everything you see on the screen.
## React Bootstrap: 
This makes our project look nice and work well on different devices.
## Faker.js: 
This tool creates fake product data that looks real, helping us show you lots of items.
## Context API:
 It's like the shopping cart's brain, keeping track of what's in your cart and how you're sorting and filtering products.
Components
### SingleProduct: 
This shows each product on the screen, one at a time.
### Filtering: 
You can sort products and filter them by rating.
### Add to Cart:
 This lets you add products to your cart, but only if they're in stock.
Shopping Cart: It keeps track of what you want to buy.
Behind the Scenes
We used some code to make all of this happen. Here's a sneak peek of what's going on:

In our code, we create an array to store the products and then use it to show them on the screen.
We use "reducers" to manage the shopping cart and how products are sorted and filtered.
The "Context API" helps us share important information between different parts of the project.
That's it! Now you know how our shopping cart project works and what tools we used to build it. Enjoy your virtual shopping experience!
