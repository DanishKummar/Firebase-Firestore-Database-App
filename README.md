# Firebase Firestore Database App

A Flutter project demonstrating how to seamlessly integrate and interact with Firebase Cloud Firestore. This application provides a foundational structure for performing read and write operations (CRUD) using a cloud-based NoSQL database.

## 📱 Features Included

Based on the project structure, this app includes the following core functionalities:

* **Home View:** (`lib/HomeView/home.dart`) - The main dashboard that fetches and displays data/products in real-time from the Firestore database.
* **Add Product View:** (`lib/AddProduct/adproduct.dart`) - An interface allowing users to input new product details and push them directly to Firestore collections.

## 📂 Project Structure

```text
lib/
├── AddProduct/
│   └── adproduct.dart       # UI and logic for adding items to the database
├── HomeView/
│   └── home.dart            # UI for displaying the list of items from Firestore
├── firebase_options.dart    # Auto-generated Firebase configuration file
└── main.dart                # Application entry point and Firebase initialization
