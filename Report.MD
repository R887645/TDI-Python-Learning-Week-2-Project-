# Week 2 – Python Control Flow & Supply Chain Dataset Exploration

In Week 2, I moved beyond basic Python syntax and started building logic-driven programs using real data. This project focused on control flow, reusable functions, and my first hands-on exploration of a supply chain dataset using Python.

While I’ve encountered supply chain data conceptually before, this was my first time loading a CSV file into Python and answering practical questions with code. That experience made the learning feel much more realistic and applicable to real-world analytics work.

---

## 🧠 Key Skills Practiced

During this project, I strengthened my understanding of:

- Conditional logic using `if` and `else`
- Comparison operators for evaluating numeric and text-based conditions
- Iteration with `for` loops to process multiple records efficiently
- Writing reusable functions with inputs and return values
- Reading and working with CSV files in Python
- Performing basic exploratory analysis on real-world data

---

## 🖥️ What I Implemented

### Order & Supplier Logic
- Built decision logic to approve or flag orders based on value thresholds
- Applied the same approval rules across multiple orders using loops
- Created a reusable function to evaluate supplier status based on reliability metrics
- Tested the function using multiple supplier scenarios

### Dataset Loading & Inspection
- Loaded the supply chain CSV dataset into Python
- Printed column headers to understand the dataset structure
- Counted total records in the dataset
- Previewed the first few rows to validate data integrity

### Exploratory Data Analysis
Using loops and conditional logic, I explored the dataset to:
- Identify the number of unique suppliers
- Determine the highest and lowest order costs
- Count how many orders fall under a specific delivery status
- Filter orders by supplier and calculate aggregate values
- Detect rows with missing or incomplete data

I also extended the analysis by combining supplier reliability with order value to determine more nuanced approval levels.

---

## 📊 Dataset Overview

The dataset contains several thousand rows with fields including:

- `order_id`
- `product_name`
- `quantity`
- `supplier_name`
- `cost`
- `delivery_date`
- `status`

From my initial exploration:
- A small number of suppliers account for a large share of orders
- Order costs vary significantly, with clear extremes
- Some records contain missing values, particularly in product and quantity fields

---

## 🔍 Questions for Further Analysis

As the dataset will be used throughout the program, I’m interested in exploring:
- Which suppliers are consistently the most reliable?
- How order costs are distributed across suppliers
- Whether delivery outcomes differ significantly by supplier
- How supplier performance impacts overall supply chain efficiency

---

## ✨ Reflection

This project marked a turning point in my Python learning. While writing conditionals and loops was straightforward, handling real data—especially missing values and file validation—required more deliberate problem-solving.

The most impactful part was seeing raw data inside Python and extracting insights directly from it. Counting suppliers, identifying cost extremes, and filtering records gave me a clearer picture of how analysts interact with real datasets. This was the first time Python felt like a genuine analysis tool rather than just a practice language.

---

## 📝 Notes

- All data used in this project is for learning and demonstration purposes only
- Responsible and ethical data handling remains a core principle in analytics

Next, I’ll be expanding this analysis in **Week 3** by using data structures like lists, dictionaries, and sets to model and analyze the supply chain network more deeply.
