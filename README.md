# Hack Your Future - webshop exercise:

The task is to build a simple webshop interface.

As a minimum it should allow the user to:
- Browse available products (pictures, descriptions and prices)
- Add items to cart
- View the cart and show the total order amount

- You should not worry about handling multiple users on the site at the same time - no need for login.
- You should not try to implement actual payment.
- You are allowed to store product data in a json file in your application, but see below for a better solution.

The clients has requested some additional features. Try to cover as many of these as you can:
- Assigning categories to products and browsing products "by category"
- The clients wants to offer a 10% discount if you add 5 items of the same type to the cart.
- Fetching the data from a remote server. You can use JSON server to build a quick API from a single JSON file. Try to use promises when communicating with the server.

A sample JSON file is included in the project.