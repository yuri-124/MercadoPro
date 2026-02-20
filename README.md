Market Management System 

Index

Overview

Key Features

Installation

How to Use

Examples

License

Overview
The Market Management System (MMS) is an integrated digital ecosystem designed for retail chains. It streamlines inventory control, automates expiration-date promotions, and enhances customer loyalty through a dedicated rewards system and a support chatbot. The project aims to reduce waste and ensure data consistency across multiple market branches in real-time.

Key Features
Inventory Engine: Automated stock entry, exit, and discrepancy registration.

Smart Promotions: Automatic price adjustments for products nearing expiration.

Loyalty Club: Points accumulation and rewards redemption system.

Omnichannel Support: Support chatbot for members with points query functionality.

Admin Dashboard: Restricted desktop application for financial and sales management.

Installation
Clone the Repository:

Bash
git clone [https://github.com/your-username/market-management-system.git](https://github.com/yuri-124/MercadoPro
)

Install Dependencies:
Navigate to the project folder and run:

Bash
npm install
Database Setup: Configure your .env file with your database credentials.

Run the Application:

Bash
npm start
How to Use
Staff Access: Log in via the Desktop Application to manage inventory (REQ001) and view sales reports (REQ019).

Inventory Update: Register new stock arrivals (REQ002) to automatically update the real-time database.

Customer Interaction: Customers can browse the Product List (REQ013) on the mobile web app without logging in.

Redeeming Points: Members log in to the chatbot to check their balance (REQ011) and claim rewards.

Examples
Promotion Trigger: If a yogurt brand is 2 days from expiring, the system automatically flags it in the REQ007 module and updates the price on the mobile app.

Stock Audit: A manager generates a "Stock History Report" (REQ005) to track all movements from the last 7 days.

License
This project is licensed under the MIT License - see the LICENSE file for details.
