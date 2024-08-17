
# Gym Management System

## Overview

The Gym Management System is a comprehensive software solution developed as part of an advanced programming course in C language for a computer science degree. The system is designed to provide a holistic view of the gym's operations, offering various management tools to handle day-to-day activities and make informed decisions.

## Features

### 1. **Management Department**
   - **Add/Delete/Update Components**: 
     - Manage key components of the gym such as employees, trainees, workouts, and equipment.
     - Add new components, update existing ones, or delete them as needed.
   
### 2. **Finances and Data Department**
   - **Financial Overview**: 
     - View detailed financial information including revenues, expenses, and profits.
     - Track the financial health of the gym in real-time.
   - **Real-time Data**:
     - Access the gym's address, the number of trainees, and the number of employees at any time.

### 3. **Gym Store**
   - **Product Management**:
     - Manage the store's inventory by adding, removing, or updating products.
     - Track the number of purchases for each product and manage stock levels.
     - Adjust product prices based on demand or other factors.
   - **Financial Insights**:
     - View the store's income, expenses, and overall profit.
     - Identify the most popular products and make data-driven decisions for restocking and pricing.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/gym-management-system.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd gym-management-system
   ```
3. **Compile the project:**
   - Use a C compiler to compile the project files. For example:
     ```bash
     gcc -o gym_management main.c *.c
     ```

4. **Run the program:**
   ```bash
   ./gym_management
   ```

## Usage

Upon running the program, you will be presented with a menu allowing you to navigate through different departments of the gym management system:

- **Management**: Add, delete, or update employees, trainees, workouts, and equipment.
- **Finances and Data**: View financial data, including revenues, expenses, and profits, as well as real-time gym details.
- **Store**: Manage store products, view sales data, and adjust inventory or prices.

### Example Workflow
1. **Add a New Trainee**: Navigate to the Management Department and select the option to add a trainee. Input the required information, and the system will store it.
2. **View Financial Information**: Go to the Finances and Data Department to get a detailed report on the gym's current financial status.
3. **Manage Store Inventory**: Access the Gym Store to add new products, delete obsolete ones, or update product prices based on recent sales data.

## File Structure

- **main.c**: The entry point of the program.
- **Management Files**: Handles operations related to employees, trainees, workouts, and equipment.
- **Financial Files**: Manages the financial aspects of the gym.
- **Store Files**: Contains logic related to the gym's store operations.
- **Utilities**: Includes helper functions for various common tasks.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## Contact

For any questions or suggestions, please feel free to contact me at [nirb1998@example.com].
