# 🛒 Instacart – Exploratory Data Analysis and Customer Behavior Insights

## 🔍 Project Functionality  
Instacart is a grocery delivery platform similar to Uber Eats and DoorDash. The company wants to understand customer behavior through exploratory data analysis (EDA). This project focuses on examining **order timing**, **shopping habits**, **reorder patterns**, and **most frequently purchased items** using transaction data across multiple tables.

The analysis is structured into three steps:  
1. **Data Import and Setup**  
2. **Data Preprocessing and Cleaning**  
3. **Exploratory Data Analysis** (customer behavior and item trends)

## 🛠️ Technologies and Methods  
- **Python** (Pandas, Matplotlib)
- **Data Sources**:  
  - `instacart_orders.csv`: Order metadata (time, user, frequency)  
  - `products.csv`: Product names and categories  
  - `order_products.csv`: Items per order and reorder status  
  - `aisles.csv`: Grocery aisle info  
  - `departments.csv`: Department names
- **Data Cleaning**:
  - Removed duplicates
  - Verified missing values
- **EDA Questions Addressed**:
  - What time of day do customers order?
  - What day of the week sees the most activity?
  - How long do people wait before placing a new order?
  - What percentage of items per customer are reorders?
  - What are the top 20 products added first to the cart?

## 📈 Key Findings and Conclusion  
- **Ordering Time**: Most orders are placed between **midday and early afternoon**, peaking around 10–15h.
- **Day of Week**: Orders are evenly distributed, with a slight increase on weekends.
- **Reordering Behavior**:  
  - The **average reorder rate is relatively low**, indicating opportunities for personalized marketing to encourage repeat purchases.
- **Most Popular First Items**:  
  - The top 20 items first added to carts are mainly **natural products**, particularly **fruits and vegetables**, reflecting a customer base focused on fresh produce.
- **Customer Loyalty Insight**:  
  - For most users, only a small proportion of their cart consists of previously ordered products.

✅ **Conclusion**:  
The data required exhaustive cleaning and enabled clear insights into Instacart’s customer behavior. Reorder behavior, order timing, and frequently purchased items offer valuable directions for improving retention strategies and enhancing product recommendations.
