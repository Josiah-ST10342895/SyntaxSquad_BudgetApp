# SyntaxSquad_BudgetApp

Budget Buddy
A simple and effective personal budget tracker for Android users

--Overview--
Budget buddy aims on helping it's users save their money. Users can set monthly goals, track money spent, 

--Features--
# Budget Tracker App
-  Create and manage spending categories
-  Record expenses with details
-  View categorized spending
-  Basic budget tracking
-  Tips page to assist users 
-  History page to view past budgets and more
  
--Database Schema--
 Tables

1. **users**
   - `user_id` (Primary Key)
   - `username`
   - `password` (hashed)
   - `email`

2. **Expense**
   - `expense_id` (Primary Key)
   - `expense_title`
   - `expense_amount`
   - `expense_date`
   - `expense_photo` (receipt image path)
   - `expense_filepath` 

3. **Budget**
   - `budget_id` (Primary Key)
   - `mingoal` (minimum spending goal)
   - `maxgoal` (maximum spending limit)

4. **Category**
   - `cat_id` (Primary Key)
   - `catname` (category name)


### Screens Implemented
1. `CreateCategoryActivity` - Add new spending categories
2. `ViewCategoriesActivity` - Browse all categories
3. `ExpenseEntryActivity` - Record new expenses
4. `DashboardActivity` - Main overview screen (WIP)


