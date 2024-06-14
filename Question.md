# Pizza Sales Analysis

## Overview

This project provides a comprehensive analysis of pizza sales data. The analysis is divided into three levels of complexity: Basic, Intermediate, and Advanced. Each level includes various tasks aimed at extracting meaningful insights from the data.

## Basic Analysis

1. **Retrieve the total number of orders placed.**
2. **Calculate the total revenue generated from pizza sales.**
3. **Identify the highest-priced pizza.**
4. **Identify the most common pizza size ordered.**
5. **List the top 5 most ordered pizza types along with their quantities.**

## Intermediate Analysis

1. **Join the necessary tables to find the total quantity of each pizza category ordered.**
2. **Determine the distribution of orders by hour of the day.**
3. **Join relevant tables to find the category-wise distribution of pizzas.**
4. **Group the orders by date and calculate the average number of pizzas ordered per day.**
5. **Determine the top 3 most ordered pizza types based on revenue.**

## Advanced Analysis

1. **Calculate the percentage contribution of each pizza type to total revenue.**
2. **Analyze the cumulative revenue generated over time.**
3. **Determine the top 3 most ordered pizza types based on revenue for each pizza category.**

## Getting Started

To get started with the analysis, ensure you have the necessary data and tools set up. The following sections provide guidance on setting up the environment and running the analysis.

### Prerequisites

- Python 3.x
- Pandas library
- SQLAlchemy or any database connector if using a database

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/pizza-sales-analysis.git
    cd pizza-sales-analysis
    ```
2. Install the required Python packages:
    ```sh
    pip install pandas sqlalchemy
    ```

### Running the Analysis

1. Ensure your data is in the correct format and place it in the `data/` directory.
2. Run the analysis scripts for each level:

    - **Basic Analysis:**
        ```sh
        python basic_analysis.py
        ```

    - **Intermediate Analysis:**
        ```sh
        python intermediate_analysis.py
        ```

    - **Advanced Analysis:**
        ```sh
        python advanced_analysis.py
        ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
