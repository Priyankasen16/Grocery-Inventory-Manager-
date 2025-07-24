🛍️ FreshMart Inventory Tracker
A simple desktop app to help small grocery shops manage stock effortlessly.
Built with Python, Tkinter, and JSON for local, offline storage.

✨ What this project does
📦 Add items with expiry dates
📋 View and search your entire inventory
🔄 Update stock quantities anytime
🗑 Remove items you no longer need
⚠️ Get notified automatically when stock is low (below 10)
All inventory data is saved locally in a JSON file (inventory.json), so you don’t need any internet connection.

🚀 Quick Start
Make sure you have Python 3 installed.
Install dependencies:
pip install tkcalendar
Run the app:
python inventory_app.py
✅ The application window should open — ready to use!

🛠 Tech Stack & Tools
GUI	Tkinter & ttk
Date picker	tkcalendar
Data storage	Local JSON file
Alerts	tkinter.messagebox
🏗 How it works
Displays all items in a Treeview table
Lets you add items with categories, quantity, price, and expiry date
Updates quantity via a pop-up dialog
Shows warnings if items have low stock when the app starts
All changes automatically save to inventory.json
📂 File Overview
inventory_app.py   # Main application code
inventory.json     # Stores the inventory data
README.md          # Project documentation
✏️ Want to contribute?
Fork this repository
Make your changes
Open a pull request
👤 Author
Created by PRIYANKA SEN to help local businesses track inventory simply and reliably.

⭐ If you find this useful, give it a star or share it with others!

Together, we simplify inventory management 🧡
