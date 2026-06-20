# Product Management System

## Project Overview
The Product Management System is a web-based application developed to manage product information efficiently. It allows users to add, update, delete, and view product details through a user-friendly interface. The application helps maintain product records in a centralized database.

## Features
- Add new products
- View product details
- Update existing product information
- Delete products
- Search products by ID or name
- Store product data in a MySQL database

## Technologies Used
- Java
- Servlets
- JDBC
- MySQL
- HTML
- CSS
- Apache Tomcat

## Project Structure
```
ProductManagementSystem/
│
├── src/
│   ├── com.productmanagement.servlet
│   ├── com.productmanagement.dao
│   └── com.productmanagement.model
│
├── WebContent/
│   ├── index.html
│   ├── addProduct.html
│   ├── updateProduct.html
│   └── viewProducts.html
│
└── README.md
```

## Database Schema

### Product Table

| Column Name | Data Type |
|------------|-----------|
| product_id | INT |
| product_name | VARCHAR(100) |
| category | VARCHAR(50) |
| price | DOUBLE |
| quantity | INT |

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Import the project into Eclipse IDE.

3. Create a MySQL database.

4. Create the Product table.

5. Update database credentials in the JDBC connection file.

6. Configure Apache Tomcat Server.

7. Run the application on the server.

8. Open your browser and access:
   ```
   http://localhost:8080/ProductManagementSystem
   ```

## Future Enhancements
- User Authentication and Authorization
- Product Image Upload
- Product Category Management
- Inventory Tracking
- Sales Reporting Dashboard

## Author
**Keerthana Ramakuri**

GitHub: https://github.com/ramakurikeerthana

## License
This project is developed for learning and educational purposes.
