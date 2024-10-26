# Inventory Management API

A simple RESTful API for managing inventory data, suppliers, and handling bulk data operations using Node.js, Express, and MongoDB.

## Features

- CRUD operations for inventory items and suppliers.
- Bulk import and export of inventory items via CSV.
- Low stock alerts based on predefined thresholds.

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- nodemon
- Multer
- dotenv
- CSV-parser
- CSV-Writer

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sujanbutani/Inventory-Management-System-p-12.git

2. Install dependencies:

    ```bash
    npm install

3. .env file

     ```
    MONGODB_URI=your_mongo_db_connection_string
    PORT=5000
    ```

4. Start the development server:

   ```bash
   npm start
   The server should now be running at http://localhost:5000
   ```

## API Endpoints

### Supplier Management
1. Supplier Api (Post) :- localhost:5000/api/suppliers
2. Supplier Api (Get - All) :-  localhost:5000/api/suppliers
3. Supplier Api (Update) :- localhost:5000/api/suppliers/<supplier_Id>
4. Supplier Api (Delete) :- localhost:5000/api/suppliers/<supplier_Id>

### Inventory Management
1. Inventory Api (Post) :- localhost:5000/api/inventory
2. Inventory Api (Get - All) :- localhost:5000/api/inventory
3. Inventory Api (Update) :- localhost:5000/api/inventory/<inventory_Id>
4. Inventory Api (Delete) :- localhost:5000/api/inventory/<inventory_Id>
6. Inventory Api (Put - Mark Payment as Paid) :- localhost:5000/api/payments/<payment_Id>/mark-paid
5. Inventory Api (Post - Import Inventory Items) :-  localhost:5000/api/inventory/import
6. Inventory Api (Get - Export Inventory Items) :-  localhost:5000/api/inventory/export

## Environment Variables
- PORT: The port for the server to listen on.
- MONGODB_URI: Your MongoDB connection string.