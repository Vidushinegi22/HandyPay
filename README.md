# HandyPay
HandyPay is a cutting-edge, safe, and intuitive web-based payment solution that leverages biometric palm recognition for user verification and transactions. It features a token-based system, visually represented by a sleek gold coin icon marked with a ‘W’, ensuring both functionality and a polished user experience.
# Features
Palm-based Registration & Login: Users register and log in using their palm image and credentials.
Biometric Payment: Make payments by verifying your palm.
Token System: All balances and transactions use tokens (1 token = 1 rupee), displayed with a gold coin 'W' icon.
Recharge Wallet: Users can top up their wallet via UPI.
Admin Dashboard: Manage users, view transactions, and edit balances.
Modern UI/UX: Responsive, professional design with modals, icons, and clear flows.
# Tech Stack
Backend: Python, Flask, SQLite
Biometrics: MediaPipe, PyTorch, ResNet50
Frontend: HTML, CSS, JavaScript (vanilla), Bootstrap, SVG icons
# Setup Instructions
# 1. Clone the Repository
git clone <your-repo-url>
cd facepayment (1)/facepayment
# 2. Create and Activate a Virtual Environment
python -m venv venv
#On Windows:
venv\Scripts\activate
#On Mac/Linux:
source venv/bin/activate
# 3. Install Dependencies
pip install -r requirements.txt
# 4. Initialize the Database
The database is initialized automatically when you run the app for the first time. To reset, delete palmpayment.db and restart the app.

# 5. Run the Application
python app_new.py
# Usage
Register: Capture your palm, enter your details, and sign up.
Login: Enter your username and password, or use palm verification for payments.
Make Payment: Add items to your cart, verify your palm, and pay with tokens.
Recharge: Top up your wallet using UPI.
Admin: Log in as admin to manage users and transactions.
# Gold Coin 'W' Icon
All token/currency displays use a custom SVG gold coin with a 'W' in the center for a professional, unified look.

# Credits
UI: Bootstrap, FontAwesome
Project by Vidushi Negi

