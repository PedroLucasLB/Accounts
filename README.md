# Finance App - Expense and Bill Tracker

## Overview

This app is a basic yet effective solution for managing personal finances. It is designed to help users track their **expenses**, **future bills**, and **salary**, ensuring they stay on top of their financial obligations. By focusing on simplicity and clarity, this app aims to provide a straightforward approach to financial management, without unnecessary complexity.

## Purpose

The main goal of this app is to provide an easy-to-use platform for users to:

- **Track Expenses:** Keep a record of all expenditures to better manage daily finances.
- **Manage Future Bills:** Store and track upcoming bills or payments that need to be paid in the future.
- **Salary Tracking:** Optionally input and adjust salary to calculate available balance.

## App Structure

### 1. **Home Page (`home.kv`)**
   - **Purpose:** The Home page is where users can quickly check their current **balance**, see a summary of their financial situation, and access the app's core features.
   - **Features:** 
     - Displays the current balance based on salary and registered expenses.
     - Provides navigation to the **Expenses** and **Future Bills** sections.
     - Allows users to add their **salary** and adjust it as needed.

### 2. **Expenses Page (`expenses.kv`)**
   - **Purpose:** This page allows users to log individual expenses that they incur. By keeping a record of spending, users can maintain better control over their budget.
   - **Features:** 
     - A text input to enter the **expense description** (e.g., "Groceries", "Dining out").
     - A numerical input to record the **amount** of the expense.
     - The app stores each expense, updating the user’s balance accordingly.

### 3. **Future Bills Page (`future_bills.kv`)**
   - **Purpose:** This page lets users keep track of future bills or payments, such as rent, utilities, or subscription services, ensuring they are prepared for upcoming expenses.
   - **Features:**
     - A text input for the **description** of the future bill (e.g., "Electricity Bill", "Car Insurance").
     - A numerical input for the **amount** of the bill.
     - A date input to specify the **due date** for the bill.
     - Helps users see what payments they have coming up and plan accordingly.

### 4. **Settings Page (`settings.kv`)**
   - **Purpose:** The Settings page gives users control over their financial information, including the option to add or update their **salary**. This is essential for calculating and tracking the user's available balance.
   - **Features:**
     - A field for entering the **salary**.
     - Option to update and track salary adjustments over time.

## Why This App?

The purpose of this project is to create a **simple yet effective financial management tool** that is easy to use, even for beginners. Rather than trying to implement a complex set of features that may overwhelm users, this app focuses on the essentials:

- **Expense tracking** to monitor daily spending.
- **Future bill tracking** to prevent late payments and missed obligations.
- **Salary management** to keep track of income and balance.

This app aims to be a minimalist yet powerful tool to help individuals take control of their finances without being bogged down by complicated interfaces or unnecessary features.

## Key Features

- Simple, intuitive interface for tracking daily expenses and future bills.
- Option to input salary and automatically adjust balance.
- Keep a running total of the balance, factoring in salary, expenses, and future bills.
- Secure password management with encryption for privacy.

## Technology Used

- **Kivy** for the graphical user interface (GUI).
- **SQLite** for data storage (expenses, future bills, salary).
- **Cryptography** for secure password storage and authentication.

## Future Improvements

- Adding features like **budget planning** or **expense categories**.
- Implementing **reminders** for upcoming bills.
- **Data visualization** (e.g., charts or graphs) for a better understanding of spending patterns.

## Conclusion

This app is designed to meet the needs of users looking for a **simple, efficient way to manage their personal finances**. It’s a great starting point for anyone looking to track their spending and future bills without being overwhelmed by complex features. 

Feel free to contribute or make suggestions for improvements as the app evolves!

---

I hope this message effectively explains the goals and structure of your finance app. Let me know if you need any more changes or additions!