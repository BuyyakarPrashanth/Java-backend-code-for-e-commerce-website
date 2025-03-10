# Java-backend-code-for-e-commerce-website
I recently developed a comprehensive e-commerce website management system using Java and JDBC for seamless interaction with a MySQL database. This project is designed to empower both sellers and customers, providing a robust platform for managing products, orders, and user accounts effectively.
The provided Project represents a comprehensive e-commerce website management system built using Java and JDBC (Java Database Connectivity) to interact with a MySQL database. The system is designed to facilitate operations for both sellers and customers, allowing them to manage products, orders, and user accounts effectively.

![image](https://github.com/user-attachments/assets/7f4c2b6b-c2f0-4dce-bcd1-9ccc61f1e70f)


For sellers, the system includes functionalities such as logging in, signing up, adding products, updating product details, displaying products, and removing products from their inventory. The seller can perform various operations based on their login credentials, ensuring that only authorized users can manage their products. The product management features allow sellers to maintain their inventory efficiently, providing a seamless experience for both sellers and customers.

On the customer side, the system allows users to sign up, log in, view available products, and place orders. Customers can browse through the products, check their orders, and manage their accounts. The system ensures that customers can only purchase products if they have sufficient balance, and it updates both customer and seller balances accordingly after a successful transaction.

The code is structured into two main packages: SellerCustomerDao, which contains the data access object (DAO) classes for handling database operations, and SellerCustomerController, which serves as the main entry point for the application, managing user interactions and controlling the flow of the program. The use of prepared statements helps prevent SQL injection attacks, enhancing the security of the application. Overall, this e-commerce management system provides a robust framework for managing online sales and customer interactions.
