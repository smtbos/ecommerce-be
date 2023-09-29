## Users
- id (PK,AI)
- name
- email
- password
- google_id (to login user next time)
- facebook_id (to login user next time)

## Categories
- id (PK, AI)
- name
- product_count

## Sub Categories
- id
- category_id
- name
- product_count

## Varients
- id
- name

## Varient Options
- id
- varient_id
- name

## Products
- id
- name
- description

## Product Varients
- id
- varient_id (Default - NULL)
- varient_option_id (Default - NULL)
- price
- stock
- is_enabled

## Carts
- id
- user_id
- product_id
- product_varient_id
- quantiry
- price
- total

## Orders
- id
- user_id
- total
- payment info.
- dates

## Order Products
- id
- order_id
- product_id
- product_varient_id
- quantiry
- price
- total