# LipaCheki
# LipaCheki

**LipaCheki** is a simple payment confirmation system designed for public transport conductors to verify e-cash transactions using phone numbers, amounts, and reference codes. It provides a basic form for input and a dashboard to display submitted confirmations.

## 💡 Project Overview

This project was built as part of a hackathon challenge to address the growing need for secure, trackable cashless payments in public transit. LipaCheki allows conductors or agents to:

- Input payment details (phone number, amount, reference code)
- Automatically log the transaction with a timestamp
- View all submissions in a dashboard

## ⚙️ Tech Stack

- Node.js + Express
- EJS templating engine
- HTML + CSS (Basic styling)
- Hosted on Glitch (currently facing preview timeout issues)

## 🖥️ How It Works

1. User fills in the form on the home page (`index.html`)
2. Payment details are sent via POST to the `/submit` route
3. The server stores the details temporarily in memory
4. `/dashboard` displays all submitted payments with timestamps
## 🚧 Known Issues

- Glitch project preview may timeout or take long to load.
- Payments are stored in memory (not persistent on refresh).

## 📌 Future Improvements

- Store data in a real database (e.g., MongoDB or Firebase)
- Add login/authentication for conductors
- Improve styling and responsiveness
- Optimize Glitch hosting or migrate to a more stable deployment platform


