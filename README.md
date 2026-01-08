# Power BI Sales & Customer Analysis Dashboard

## 📊 Project Overview
This project is an interactive Power BI report designed to analyze sales, customer behavior, and order performance. The Report enables user-driven insights through dynamic filtering, matrix visuals, and drill-through analysis.

---

## 🧩 Data Model Overview
The data model is structured to support efficient analysis and reporting using best practices.

### Tables Used
- *Orders*  
  Contains order-level and customer-related information such as Order ID, Order Date, Customer Name, City, and State.

- *Details*  
  Stores transactional details including Category, Subcategory, Quantity, Amount, and Profit.

- *Measure Table*  
  A dedicated table created to organize all DAX measures, improving model readability and performance.

### Relationships
- One-to-many relationship between *Orders* and *Details*
- Enables accurate aggregation, filtering, and cross-visual interaction

---

## 📈 Report Pages

### 1️⃣ Sales Analysis Page
- Displays *sales and profit by state* using multiple visuals
- Implements a *Top-N model* to highlight the *top three performing states*
- Helps identify high-performing regions quickly

### 2️⃣ Customer Details Page
- Provides *customer-level analysis*
- Selecting a customer dynamically displays:
  - Customer name and state
  - Purchased categories and subcategories
  - Payment mode details
- Uses matrix visuals and cards for clear insights

### 3️⃣ Order Details Page
- Shows a detailed *order-level table*
- Includes *state-wise order analysis using map visuals*
- Orders are *categorized* for deeper analysis

---

## 🛠 Key Features
- Interactive filtering using customer selection
- Matrix visuals with category and subcategory hierarchy
- Dedicated measure table for organized DAX calculations
- Cross-filtering enabled through optimized relationships
- Clear replacement of pie/donut charts with tables and matrix visuals

---

## 🧮 DAX & Measures
Key measures include:
- Total Sales
- Total Orders
- Payment-related metrics

All measures are maintained in a separate *Measure Table* following Power BI best practices.

---

## 🧠 Skills & Tools Used
- Power BI Desktop
- Data Modeling
- DAX
- Matrix & Map Visuals
- Customer and Sales Analysis
- Business Intelligence Reporting

---

## 🚀 How to Use
1. Download the .pbix file from this repository
2. Open it in Power BI Desktop
3. Interact with visuals by selecting customers, states, or categories

---

## 👤 Author
*Nira Singh*

