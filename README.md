# SQL Test

Here are some tables tables:


### order_items

column | type | key
--- | --- | ---
created_at | datetime |
order_id | int | foreign key
line_item_id | int | primary key
product_id | int | foreign key
position | int |
quantity | int |
unit_price_before_discount_sgd | float |
unit_price_after_discount_sgd | float |
client_id | int | foreign key


### products

column | type | key
--- | --- | ---
product_id | int | primary key
brand_id | int | foreign key
name | string | |
sale_price | float |
purchase_cost | float |


### brands

column | type | key
--- | --- | ---
brand_id | int | primary key
name | string |

### users

column | type | key
--- | --- | ---
user_id | int | primary key
email | string |

### orders

column | type | key
--- | --- | ---
order_id | int | primary key
country | string |

## Questions

1. What was the daily revenues of May 2016?
2. How would you update your query to display the daily revenues of the last 10 days?
3. What are the brand margins
  1. based on 2016 orders
  2. based on the products' sale and purchase prices
4. We started to sell the brand "Kat Von D" on May 1st.
  1. what is the performance of the Kat Von D brand: sales, average order value, margin?
  2. for returning clients, which other brands were they buying before buying a Kat Von D product?

**You have 25 minutes**
