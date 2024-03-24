# FìNT₹AX - MERN Stack Expense Tracker 📊💰

FìNT₹AX is a powerful expense tracker built using the MERN (MongoDB, Express.js, React.js, Node.js) stack with JWT authentication. It sends email reminders when expense limits are approaching or crossed, enhancing financial awareness. It enables users to effortlessly manage their expenses and income for specific date ranges, providing insightful graphs and analysis using Chart.js.

## About the Project 📊💡

FìNT₹AX stands as a dynamic MERN Stack expense tracker, tailored to empower users in managing their finances effectively. With a seamless user experience and comprehensive features, FìNT₹AX offers a holistic approach to expense tracking.

Users can effortlessly log, edit, and delete expenses and income entries, all meticulously organized based on specific date and time ranges. The intuitive interface boasts a sortable table, allowing users to easily navigate through their financial data. Additionally, filtering options enable users to focus on specific categories, while the search functionality simplifies the process of locating transactions. With intuitive email reminders, users stay informed about approaching or exceeded expense limits, promoting financial mindfulness and accountability.

Harnessing the power of Chart.js, FìNT₹AX presents users with interactive graphs and analyses, offering insights into spending patterns and financial trends. The ability to define custom date ranges for analysis further enhances the utility of the platform, empowering users to make informed financial decisions.

With secure JWT authentication ensuring user privacy and data integrity, FìNT₹AX represents a comprehensive solution for individuals seeking to take control of their finances and achieve their financial goals. 💰🚀

## Features
- ✅**Authentication**: Secure JWT authentication for user accounts.
- ✅**Expense and Income Management**: Add, edit, and delete expenses and income entries for specific date and time.
- ✅**Sortable Table**: Users can sort data based on various parameters for better organization.
- ✅**Filtering**: Easily filter data to view specific categories of expenses and income.
- ✅**Search Functionality**: Search for transactions by title, amount, or description.
- ✅**Graphical Analysis**: Visualize transactions using dynamic graphs and charts generated with Chart.js.
- ✅**Custom Date Range Analysis**: Users can define date ranges to analyze their financial data effectively.
- ✅**Email Reminders**: Sends email reminders when expense limits are approaching or crossed, enhancing financial awareness.

## Technologies Used
- MongoDB
- Express.js
- React.js
- Node.js
- JWT Authentication
- Chart.js
- Primereact 
- Nodemailer

### Starting Backend:

1. **Setup Environment Variables**:
   - Create a `.env` file with the following parameters:
     - `MONGO_URI`: URL for MongoDB
     - `JWT_SECRET`: Any string for JWT secret
     - `GOOGLE_ID`: Email-id from where reminder mail comes from.
     - `GOOGLE_PASS`: Password string for that id.
    - Here I have used :-
        ```
        MONGO_URI=mongodb://127.0.0.1:27017/notesapp
        JWT_SECRET=secretcode
        ```
2. **Navigate to Backend Directory**:
   - Open the main folder in the command prompt.
   - Type `cd backend` to navigate to the backend directory.

3. **Install Dependencies**:
   - Run `npm install` to install all required node_modules.

4. **Start the Server**:
   - Run `node ./server.mjs` to start the server-side application.

### Starting Frontend:

1. **Navigate to Frontend Directory**:
   - Open the main folder in the command prompt.
   - Type `cd frontend` to navigate to the frontend directory.

2. **Install Dependencies**:
   - Run `npm install` to install all required node_modules.

3. **Start the Client**:
   - Run `npm start` to start the client-side application.

4. **Access the Application**:
   - Visit `http://localhost:3000` in your web browser to access the application.
