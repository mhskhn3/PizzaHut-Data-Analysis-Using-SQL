# PizzaHut Data Analysis Using SQL

## Overview

This project analyzes PizzaHut data using SQL. The dataset consists of four CSV files:

- `Pizzas`
- `Pizza_type`
- `Orders`
- `Order_details`

The `Pizzas` and `Pizza_type` files can be imported directly into SQL Workbench. However, due to their large size, the `Orders` and `Order_details` CSV files require separate table creation before importing.

## Table Creation

### Orders Table


```sql
CREATE TABLE orders (
    order_id INT NOT NULL PRIMARY KEY,
    order_date DATE NOT NULL,
    order_time TIME NOT NULL
);
```

### Order_details Table

```sql
CREATE TABLE order_details (
    order_details_id INT NOT NULL PRIMARY KEY,
    order_id INT NOT NULL,
    pizza_id TEXT NOT NULL,
    quantity INT NOT NULL
);
```





