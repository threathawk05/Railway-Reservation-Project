# 🚆 Railway Reservation System

## 📌 Project Overview
The **Railway Reservation System** is a Java-based application that facilitates the booking, cancellation, and management of railway tickets. It enables passengers to log in, check train availability, book tickets, process payments, and view PNR status. The system ensures seamless train schedule tracking, fare calculations, and data management, all controlled by an administrator.

## 📖 Table of Contents
- [🚀 Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [💾 Database Design](#-database-design)
- [📑 System Architecture](#-system-architecture)
- [📷 Screenshots](#-screenshots)
- [⚙️ How to Run the Project](#-how-to-run-the-project)
- [🎯 Conclusion](#-conclusion)
- [📚 References](#-references)

## 🚀 Features
- 🔐 **User Authentication**: Secure login and signup system.
- 🚆 **Train Search & Booking**: Users can search for trains based on source, destination, and journey date.
- 🔍 **PNR Status Check**: Allows users to check ticket confirmation status.
- 💳 **Payment Processing**: Supports online/offline payment options.
- ❌ **Ticket Cancellation**: Passengers can cancel tickets and receive applicable refunds.
- 🛠️ **Admin Control**: Manages train details, seat availability, fare structure, and user data.

## 🛠️ Technologies Used
- 💻 **Programming Language**: Java (NetBeans IDE)
- 🗄️ **Database**: MySQL
- 🎨 **Frontend**: Swing (Java GUI)
- 🔗 **Backend**: JDBC for database connectivity
- 🏠 **Operating System**: Windows / Mac

## 💾 Database Design
📂 **Database Name**: `BCAPROJECT`

### 📑 Tables:
1. 📝 **signup**: Stores user registration details.
2. 🚉 **traindetails**: Maintains train schedules, routes, seat availability, and fare structure.
3. 🎟️ **pnrdetails**: Stores passenger booking details along with PNR numbers.

## 📑 System Architecture
- 🎭 **Use Case Diagram**: Depicts system interactions between users and functions.
- 🏗️ **Class Diagram**: Shows object relationships in the system.
- 🔄 **Sequence Diagram**: Defines the sequence of operations for booking and cancellation.
- 🏃 **Activity Diagram**: Displays the workflow of the reservation system.
- 🔘 **State Diagram**: Represents various states a ticket can be in (booked, waiting, canceled, etc.).

## 📷 Screenshots
- 🔐 **Login Screen**

  <img src="https://github.com/user-attachments/assets/97eb9f74-30a6-41ec-90e0-8c4e6580b3f3" alt="Login Screen" width="500" height="300">


- 📝 **Signup Screen**
  
  <img src="https://github.com/user-attachments/assets/3a098650-47e5-4533-ae65-b8b0cc22d481" alt="Railway Reservation System" width="500" height="300">

- 🏠 **Main Dashboard**

  <img src="https://github.com/user-attachments/assets/3ee7705f-b069-4759-a61f-ec8baa193c27" alt="Railway Reservation System" width="500" height="300">

- 🎟️ **Ticket Booking Interface**

  <img src="https://github.com/user-attachments/assets/f534ee03-382a-4963-827a-794cab5db3c1" alt="Railway Reservation System" width="500" height="300">

- 🔍 **PNR Status Checker**

  <img src="https://github.com/user-attachments/assets/07785267-24de-45b0-8534-2a6aac7dc926" alt="Railway Reservation System" width="500" height="300">

- 📅 **CheckAvailability**

  <img src="https://github.com/user-attachments/assets/7e8efe14-2f4b-4b01-8f75-0bd55ef849ef" width="500" height="300">


## ⚙️ How to Run the Project
1. 🛠️ Install **NetBeans IDE** and **MySQL Server**.
2. 📂 Import the database from `BCAPROJECT.sql` into MySQL.
3. 🖥️ Open the project in **NetBeans**.
4. 🔧 Configure database connection in the Java code (`JDBC` settings).
5. ▶️ Run the application and log in using valid credentials.

## 🎯 Conclusion
This **Railway Reservation System** provides a platform for users to easily book and manage train tickets. It automates the reservation process and improves user experience by offering real-time ticket availability, fare calculation, and secure transaction processing.

## 📚 References
- 🌐 [RailYatri - Train Timetable](https://www.railyatri.in/time-table)
- 📖 [GeeksforGeeks - Java & MySQL](https://www.geeksforgeeks.org/)

---
💡 **Contributors**: 👨‍💻 Amaan Khojani, 👩‍💻 Sanjana Nandania  
📅 **Academic Year**: 2022-2023  
👨‍🏫 **Guide**: Pankaj Sir  
