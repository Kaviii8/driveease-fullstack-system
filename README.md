# DriveEase Full-Stack Software System

## 📌 Project Overview
This project was developed as part of the internship challenge at **Capital Maharaja Group IT**. It aims to digitize the car rental operations of **DriveEase**, replacing manual workflows with a full-stack software system.

DriveEase receives vehicle availability and pricing details from providers via physical documents. The system digitizes these contracts and enables support agents to search, calculate prices, and simulate bookings.

## 🚀 Features
- Upload and manage car rental contracts
- Apply 10% service fee markup to provider prices
- Search interface for support agents with criteria:
  - Pickup date
  - Number of rental days
  - Number of vehicles
  - Vehicle type preference
- Display search results with:
  - Vehicle type
  - Provider name
  - Final price (with markup)
  - Availability status
- Simulate bookings and print results
- Admin features to upload/remove contracts

## 🧮 Price Calculation Formula
```
Price = (base daily rate from provider) × (1 + markup) × (number of rental days) × (number of vehicles)
```

## 🛠️ Tech Stack
- **Frontend**: React
- **Backend**: Spring Boot (Java)
- **Database**: MySQL

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/driveease-fullstack-system.git
   ```

2. **Frontend Setup**
   - Navigate to the frontend directory
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm start
     ```

3. **Backend Setup**
   - Open the Spring Boot project in your IDE
   - Configure database connection in `application.properties`
   - Run the application

4. **Database Setup**
   - Create a MySQL database
   - Import the ER diagram and schema

## 📄 License
This project is developed for educational and internship purposes.
