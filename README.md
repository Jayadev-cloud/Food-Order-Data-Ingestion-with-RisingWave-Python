# Food-Order-Data-Ingestion-with-RisingWave-Python

This project demonstrates how to insert food order data into a RisingWave (PostgreSQL-compatible) database using Python.
It supports both manual entry and bulk upload via CSV/Excel files.

🚀 Features

✅ Database Connection – Connects securely to RisingWave using psycopg2.

✅ Manual Data Insertion – Insert order records through interactive input (Order ID, Customer Name, Restaurant, Item, Delivery Status, Rating).

✅ CSV/Excel Upload – Upload datasets and insert them directly into the food_orders table.

✅ Real-time Timestamping – Automatically adds the current timestamp (order_time, delivery_time) during insertion.

✅ Error Handling – Catches and logs issues if any rows fail to insert.


⚙️ How It Works

Connect to RisingWave

The script connects to your RisingWave Cloud instance with secure credentials.

Choose an Option

1️⃣ Insert data manually

2️⃣ Upload CSV/Excel file

Insert Records

For manual entry, the script asks for inputs like Order ID, Customer Name, Item, Delivery Status, and Rating.

For CSV/Excel, it loops through all rows and inserts them into the database.

Commit and Confirm

💡 Use Cases

Testing real-time ingestion pipelines with RisingWave.

Managing food delivery datasets.

Building dashboards and analytics for order trends, delivery performance, and customer ratings.
Data is committed into the food_orders table.

A success ✅ message confirms insertion.
