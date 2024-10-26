# Expense Tracker - Java & MySQL Application

An intuitive and efficient expense management system built in Java with a MySQL database backend. This application enables users to track, categorize, and analyze their expenses seamlessly with a user-friendly graphical interface. Ideal for individuals who want a reliable way to monitor spending habits over time.

### Key Features

- **Add, View, and Delete Expenses**: Easily add new expenses by specifying details like date, amount, category, and description. The application allows users to view or delete any saved expenses with a few clicks.
  
- **Expense Categorization**: Categorize expenses (e.g., Food, Travel, Utilities, etc.) for better tracking and spending analysis across various areas.
  
- **Monthly and Yearly Reports**: Generate detailed reports that summarize spending over different periods. Gain insights into spending trends with monthly or yearly breakdowns.
  
- **Database Integration with MySQL**: All data is stored securely in a MySQL database, ensuring data persistence and reliability. CRUD operations are optimized to ensure seamless interaction with the database.
  
- **Filter and Search**: Search expenses by category, date range, or keywords to quickly access specific entries. Filters make it easy to find relevant data even in large databases.
  
- **Spending Analytics**: Analyze spending habits with charts or numerical summaries, helping users identify potential savings areas.
  
- **User Authentication (optional)**: Add login functionality to protect personal expense data, enabling multiple users to have individual accounts.

### Technologies Used

- **Java**: Core programming language for building the application logic and GUI.
- **Swing/JavaFX**: Graphical interface to provide a user-friendly experience.
- **MySQL**: Database system for storing expense data persistently.
- **JDBC**: Java Database Connectivity (JDBC) API to establish a connection and interact with the MySQL database.

### Project Structure

- **src/**: Contains all Java source code files, organized into packages like `model`, `view`, and `controller`.
- **resources/**: Holds any necessary resources, such as images for the GUI or configuration files.
- **sql/**: Includes SQL scripts for setting up the MySQL database and tables.
- **README.md**: Detailed documentation and setup instructions.

### How to Set Up

1. **Database Setup**: 
   - Import the provided SQL script in `sql/` to create the necessary tables in a MySQL database.
   - Update `database.properties` with your MySQL credentials and database URL.

2. **Run the Application**:
   - Compile and run the Java application. Ensure MySQL is running and accessible from your application.

3. **Using the Expense Tracker**:
   - Start by adding new expenses through the main window. View expenses or filter them by category or date for quick reference.

### Future Improvements

- **Multi-user support**: Enable multiple users with separate expense tracking.
- **Enhanced Visualizations**: Integrate charting libraries for better spending analysis.
- **Mobile App Version**: Expand functionality to mobile platforms for easier on-the-go expense tracking.

### Contributions

Contributions are welcome! Feel free to submit issues, pull requests, or feature requests.
