# Black-Horse (E-Commerce Multi-Vendor)
![لا](https://github.com/Yahya-Tarek/Black-Horse/blob/main/assests/1.png)


## Overview
This project is an e-commerce platform that connects clients, suppliers, and delivery personnel. It allows vendors to sell their products, clients to browse and purchase items, and delivery personnel to manage deliveries. The system is built using **Flutter** for the mobile apps and the **web-based admin panel** for managing the platform.

## Apps Overview

### 1. Client App
The **Client App** provides a user-friendly interface for customers to explore products, place orders, and track their purchases. Key features include:

- **Product Browsing**: Clients can search for products, view details, and add items to their cart.
- **Order Management**: Clients can place orders, view order history, and track delivery status.
- **User Authentication**: Secure login and registration for clients.
- **Notifications**: Real-time notifications for order updates.



![Black_horse_client](https://github.com/Yahya-Tarek/Black-Horse/blob/main/assests/2.png)


### 2. Supplier App
The **Supplier App** empowers vendors to manage their inventory, update product details, and fulfill orders. Features include:

- **Product Management**: Suppliers can add new products, update prices, and manage stock.
- **Order Fulfillment**: Suppliers receive order notifications and mark orders as fulfilled.
- **Grouping**: Suppliers receive group of orders that achieve minimum order price as a one order with details for each order.
- **Group Fulfillment**: Suppliers receive group of orders notifications and mark the group as fulfilled.
- **Reports**: Supplier can observe his orders statistics ,fines and balance sheet.
- **Supplier Authentication**: Secure login for suppliers.


![black_horse_supplier](https://github.com/Yahya-Tarek/Black-Horse/blob/main/assests/3.png)

### 3. Delivery App
The **Delivery App** is designed for delivery personnel to handle order deliveries efficiently. Features include:

- **Delivery Assignments**: Delivery personnel receive order assignments and route details.
- **Delivery Status Updates**: Real-time tracking of delivery progress.
- **Authentication**: Secure login for delivery personnel.

<!-- 
#### Screenshots
!Client App Screenshot 1
!Client App Screenshot 2
-->

## Web Admin Panel
The **Web Admin Panel** serves as the control center for managing the entire platform. Admins can perform the following tasks:

- **User Management**: Add, edit, or deactivate user accounts (clients, suppliers, and delivery personnel).
- **Product Management**: add products description,categories,delivery regions,etc.
- **Order Management**: Monitor orders, handle disputes, and track deliveries.
- **Analytics and Reports**: View sales data, user activity, and performance metrics.

<!-- 
#### Screenshots
!Client App Screenshot 1
!Client App Screenshot 2
-->

#### Used Packages
Here are the essential packages utilized in this project:

- **dio**: A powerful HTTP client for making network requests.
- **get**: A lightweight state management solution for Flutter.
- **hive**: Lightweight and fast NoSQL database for Flutter.
- **hive_flutter**: Hive integration with Flutter.
- **get_it**: A simple service locator for dependency injection.
- **geolocator**: Retrieves location information (latitude, longitude, etc.).
- **google_maps_flutter**: Integrates Google Maps into your app.
- **socket_io_client**: Connects to Socket.IO servers for real-time communication.
- **firebase_core**: Initializes Firebase services.
- **firebase_messaging**: Handles push notifications using Firebase Cloud Messaging.
- **flutter_local_notifications**: Shows local notifications within the app.
- **font_awesome_flutter**: Provides a collection of FontAwesome icons for Flutter.
- **image_picker**: Enables image selection from the device’s gallery or camera.
- **intl**: Offers internationalization and localization support.
- **lottie**: Integrates Lottie animations (JSON-based animations) into your app.
- **flutter_svg**: Renders SVG images in your app.
- **flutter_native_splash**: Customizes the native splash screen for Android and iOS.
- **flutter_rating_bar**: Displays rating bars with customizable styles.
- **cached_network_image**: Efficiently loads and caches network images.



