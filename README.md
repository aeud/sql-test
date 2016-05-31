# SQL Test

Here are some tables tables:


### order_items

|created_at|datetime||
|order_id|int||
|line_item_id|int|primary key|
|product_id|int||
|position|int||
|quantity|int||
|unit_price_before_discount_sgd|float||
|unit_price_after_discount_sgd|float||
|client_id|int||


### products

|product_id|int|primary key|
|brand_id|int||
|name|string||
|sale_price|float||
|purchase_cost|float||


### brands

|brand_id|int|primary key|
|name|string||

## Questions

1) What was the daily revenues of May 2016?
2) How would you update your query to display the daily revenues of the last 10 days?
3) What are the brand margins
    a) based on 2016 orders
    b) based on the products' sale and purchase prices
4) We started to sell the brand "Kat Von D" on May 1st.
    a) what is the performance of the Kat Von D brand: sales, average order value, margin?
    b) for returning clients, which other brands were they buying before buying a Kat Von D product?

* You have 25 minutes *
