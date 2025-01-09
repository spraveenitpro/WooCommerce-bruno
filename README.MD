# WooCommerce API Collection

This repository contains a collection of `.bru` files for interacting with the WooCommerce API. Each file represents a specific API request.

## Files

### `Create a product.bru`
Creates a new product in the WooCommerce store.

- **Method**: POST
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/products`
- **Body**: JSON
- **Authentication**: Basic

### `Retrieve Order.bru`
Retrieves details of a specific order from the WooCommerce store.

- **Method**: GET
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/orders/3559`
- **Body**: None
- **Authentication**: Basic

### `Add Note to order.bru`
Adds a note to a specific order in the WooCommerce store.

- **Method**: POST
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v2/orders/3490/notes`
- **Body**: JSON
- **Authentication**: Basic

### `Insert product 2.bru`
Inserts a new product with detailed attributes in the WooCommerce store.

- **Method**: POST
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/products`
- **Body**: JSON
- **Authentication**: Basic

### `Retrieve Product.bru`
Retrieves details of a specific product from the WooCommerce store.

- **Method**: GET
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/products/3561`
- **Body**: None
- **Authentication**: Basic

### `Update Product.bru`
Updates the categories of a specific product in the WooCommerce store.

- **Method**: POST
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/products/`
- **Body**: JSON
- **Authentication**: Basic

### `Update Stock.bru`
Updates the stock quantity of a specific product in the WooCommerce store.

- **Method**: PUT
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/products/3159`
- **Body**: JSON
- **Authentication**: Basic

### `Get list of orders.bru`
Retrieves a list of orders from the WooCommerce store.

- **Method**: GET
- **URL**: `https://woocommerce.mystagingwebsite.com/wp-json/wc/v3/orders`
- **Body**: JSON
- **Authentication**: Basic
