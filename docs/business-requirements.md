# Green Market – Business Requirements
Overview  
Green Market is a full-stack agricultural e-commerce platform that connects verified sellers (farmers and agricultural suppliers) with buyers. The platform allows sellers to list agricultural products such as fertilizers, seeds, pesticides, and farming tools, while buyers can browse, search, and purchase these products.

The platform has three types of users:

Customer – A customer who browses and purchases products.  
Seller – A verified agricultural supplier who lists and sells products.  
Admin – A single platform administrator who manages the system.  

The Customer must register to use the platform. Each buyer has a unique ID, username, email address, password, phone number, primary address (Governorate, City/Village, Street, and Additional Details), date of birth, registration date, and an active status. A buyer can update their profile information at any time.  

The supplier must apply to join the platform and wait for Admin approval before listing products. Each supplier has a unique ID, username, email address, password, phone number, primary address, date of birth, registration date, a verification status (pending, approved, or rejected), and an active status. A supplier can manage their products and view their orders and sales.  

The platform has one Admin account created directly by the development team. The Admin approves or rejects supplier applications, deactivates customer or supplier accounts, manages product categories, and views all orders and platform statistics.  

Each product is listed by a supplier and belongs to a category. A product has a unique ID, name, description, one or two images, price, available quantity, category, supplier, date added, and an availability status.  

Categories are created and managed by the Admin. Each category has a unique ID, name, and description.  

A customer can add products to their cart before placing an order. Each cart item has a unique ID, the customer, the product, the quantity, and the date added. When the customer places an order, the cart items are converted into order items and the cart is cleared.  

An order is created when a customer checks out their cart. Each order has a unique ID, the customer who placed it, a delivery address, the date placed, a status (Pending, Confirmed, Delivered, or Cancelled), and a total price.  

Each order contains one or more order items. Each order item has a unique ID, the order it belongs to, the product ordered, the quantity, and the price of the product at the time of purchase.  
