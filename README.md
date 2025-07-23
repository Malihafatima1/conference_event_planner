# 🏢 BudgetEase Conference Expense Planner

BudgetEase is a business conference expense planner application built for Alejandre, who manages a venue for corporate events. The platform allows customers to easily plan and price their conferences, selecting everything from rooms to meals and add-ons — all in real time.

## 🚀 Project Overview

This web application is designed to help BudgetEase customers:

- Select and price **conference rooms**
- Choose **add-ons** such as microphones and projectors
- Configure **meals** based on the number of guests
- View **real-time cost estimates** and selections

## ✨ Features

- 🎯 **Dynamic UI**: Live updates as users make selections
- 🏢 **Venue Selection**: Choose from various room options
- 🎤 **Add-ons**: Include equipment like projectors, microphones, etc.
- 🍽️ **Meal Options**: Select food packages based on guest count
- 📊 **Cost Summary Popup**: View all selected items and pricing in a clear table
- 🧮 **Live Cost Calculations**: Automatic subtotal and total cost generation

## 🧰 Tech Stack

- **React** – Frontend framework for building UI components
- **Redux Toolkit** – Simplified state management
- **Redux Slices** – Divided state handling for modular components

## 🗂️ Project Structure

conference_event_planner/
├── components/
│ ├── VenueSelector.jsx
│ ├── AddOnsSelector.jsx
│ ├── MealSelector.jsx
│ └── CostSummaryModal.jsx
├── redux/
│ ├── venueSlice.js
│ ├── addonsSlice.js
│ └── mealsSlice.js
├── App.jsx
└── index.js


## 📦 Installation & Running

```bash
# Clone the repo
git clone https://github.com/Malihafatima1/conference_event_planner.git

# Navigate into the project
cd conference_event_planner

# Install dependencies
npm install

# Start the development server
npm run dev
```
## 📸 Screenshots

![conference1](https://github.com/user-attachments/assets/a7e6e883-5135-4cab-bf55-d174c7cbd1f1)
![con2](https://github.com/user-attachments/assets/58428709-bc3f-4d89-a668-b6a90a0833fa)
![con3](https://github.com/user-attachments/assets/6cacab00-e59d-443f-95ed-b799fb0d569e)
![con4](https://github.com/user-attachments/assets/d514daa2-5d78-48c3-8c38-1075d8cf4136)

Made with ❤️ by Maliha Fatima for BudgetEase.





