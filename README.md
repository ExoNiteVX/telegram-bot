# 🍔 Telegram Food Ordering Bot

A Telegram-based food ordering bot built with **Python**, **python-telegram-bot**, and **SQLite**. Users can register, browse food categories, add products to a cart, and place orders. Admins can manage categories and products and receive orders directly in a Telegram group.

---

## ✨ Features

### 👤 User Features
- User registration with:
  - Full name
  - Phone number
  - Live location
- Browse food categories and products
- Add products to cart with quantity selection
- View and manage cart
- Confirm orders and send them to admin group
- Edit profile (name & phone)

### 🛠️ Admin Features
- Secure admin login via password
- Add new food categories (with emoji)
- Add new products (name, price, image, description)
- Bind a Telegram group to receive orders

### 🗄️ Database
- SQLite database (`users.db`)
- Tables:
  - `users`
  - `categories`
  - `product`

---

## 📁 Project Structure

project/
│
├── bot.py # Main Telegram bot logic
├── db.py # Database functions (SQLite)
└── users.db # Auto-created database



---

## ⚙️ Requirements

- Python 3.8+
- `python-telegram-bot` (v13.x)

Install dependencies:
```bash
pip install python-telegram-bot==13.15



🛒 How Ordering Works

User starts the bot with /start

Registers with name, phone, and location

Browses food categories and products

Adds items to cart with quantity selector

Confirms order

Order is sent to admin group with:

User name

Phone number

Location link

Ordered items and total price



🧠 Technologies Used

Python

python-telegram-bot

SQLite

Telegram Bot API



📌 Notes

Make sure the bot has permission to send messages and photos in the group.

You can improve security by:

Hashing admin passwords

Using environment variables for tokens

Suitable for:

Food delivery

Restaurant ordering

Cafe or shop automation
