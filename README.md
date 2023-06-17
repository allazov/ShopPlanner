## ShopPlanner
ShopPlanner is a script that helps users to plan their shopping based on their budget and preferred products. The script makes use of a given dataset of products and aids in creating an efficient and economical shopping list.

## Key Features
Budget-based shopping: The user can input their total budget for shopping, and the script will attempt to create a shopping list that stays within this budget.

**Product prioritization**: Users can list their preferred products in order of priority. The script will then consider this order when recommending products to be included in the shopping list.

**Shopping strategies**: Users can choose between an 'ekonom' and 'premium' strategy. The 'ekonom' strategy prioritizes cheaper products, while the 'premium' strategy prioritizes more expensive ones.

**Dynamic budget adjustment**: If the budget is not sufficient for all the preferred items, the script prompts the user to adjust their budget until it fits or to skip the item.

**Local language support**: This code is specifically designed for Azerbaijani users. All commands, input placeholders, and messages to users are provided in Azerbaijani.

## How it works
Data Preparation: The script reads in a dataset of products from a CSV file. Each product in the dataset includes information about the product's name, price, parent category, subcategory, and url.

**User Input**: The user is asked to input their budget, their list of preferred products (with quantity), and their shopping strategy ('ekonom' or 'premium').

**Product Recommendation**: Based on the user's inputs, the script looks for the products in the dataset that match the user's preferences. It prioritizes the products based on their presence in the user's list and the selected strategy.

**Budget Adjustment**: If the total cost of the recommended products exceeds the user's budget, the script asks the user to increase their budget or to skip the item.

**Output**: The script outputs the recommended products along with their quantities, individual prices, total cost, and the remaining budget.

**Please note** that this script doesn't handle scenarios where a product is not available in the dataset. Also, the accuracy of product recommendations is heavily dependent on the quality and completeness of the product dataset.
