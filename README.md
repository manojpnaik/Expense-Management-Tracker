Expense Management Tracker

Click on this link- https://expense-tracker-sable-beta.vercel.app

1 Overview:
The expense management tracker will consist of the following components:

Front-end: Built with React.js
Back-end: Built with Node.js and Express.js
Database: MongoDB for data storage

    ┌──────────┐           ┌─────────────┐
    │  Client  │◀──HTTP───▶│  Front-end  │
    └──────────┘           └─────────────┘
          ▲                      │
          │                      │
       Browser             React App
          │                      │
    ┌──────────┐           ┌─────────────┐
    │  MongoDB │◀──HTTP───▶│ Back-end    │
    └──────────┘           └─────────────┘
          ▲                 Node.js/Express
          │
       Data Storage

2 Implementation

Features:
User Authentication: Sign up, login, logout 
Expense Tracking: CRUD operations for expenses
Expense Categories: Ability to categorize expenses
Reporting: Visualize expenses over time 


3  Unit tests for the core functionalities

-> User authentication tests.
-> Expense CRUD operations tests.

4 Project Title: Expense Management Tracker

Description:
A simple expense management tracker built with the MERN stack.

Features:

User authentication 
Expense tracking (CRUD operations)
Expense categories

System Architecture:

Front-end: React.js
Back-end: Node.js, Express.js
Database: MongoDB

------Setup Instructions:---------------

1 Clone the repository
git clone https://github.com/manojpnaik/Expense-Management-Tracker/tree/my-new-branch
cd expense-management

2 Switch to the my-new-branch Branch
git checkout my-new-branch

3 Install Dependencies 
            For the back-end
                    cd server
                    npm install
                    
            For the front-end
                    cd ../client
                    npm install
4 Environment Variables
MONGO_URI=your_mongodb_connection_string
5 Running the Application
        Start the back-end server
            cd server
            npm start
        Start the front-end server
            cd client
            npm start
            

Registration  Page

![Screenshot 2024-07-20 205849](https://github.com/user-attachments/assets/a11d76fd-5342-41f0-ae27-6809e924c198)


Login Page

![Screenshot 2024-07-20 205906](https://github.com/user-attachments/assets/f9899b62-7b89-4ea8-bcbb-274e334bed5c)

Home Page

![Screenshot 2024-07-20 210311](https://github.com/user-attachments/assets/ef0a4da2-06a5-4d17-adc6-dabec2036f4a)

![Screenshot 2024-07-20 210326](https://github.com/user-attachments/assets/33e374dc-6ecf-43da-8e39-7327430a610e)

Creating Expense

![Screenshot 2024-07-20 210411](https://github.com/user-attachments/assets/e6405726-e4a5-464e-a833-8ef4f96f3afa)

Editing and deleting expense

![Screenshot 2024-07-20 210431](https://github.com/user-attachments/assets/0e678b7e-ae0f-4083-8234-1d2469cd90aa)


Logut
![Screenshot 2024-07-20 210452](https://github.com/user-attachments/assets/e0bd7f64-51d8-41a3-984b-10d989cc3ad1)









