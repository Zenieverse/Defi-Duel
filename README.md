# Defi-Duel
DeFi Duel is a real-time, zero-collateral, competitive platform that allows users to track and compare the performance (PnL) of multiple crypto wallets over a defined period. Challenge your friends or track the top wallets in a defined trading theme!


https://gemini.google.com/share/bc5c654d8f44

![IMG_1329](https://github.com/user-attachments/assets/44a1e778-792d-4b00-8dd4-03a24b89cb40)


<img width="1024" height="1024" alt="IMG_1317" src="https://github.com/user-attachments/assets/e0786c18-6908-43a5-9432-fdbd25fefadd" />



Features

Real-time Leaderboard: Compare PnL (%) and Net Value across all duel participants, powered by simulated Zerion API data.

Multi-Wallet Duels: Create custom duels by specifying competitor wallet addresses and defining a trading theme and duration.

On-Chain Activity Feed: View recent swaps, transfers, and liquidity events for all participants in the active duel.

Detailed Wallet Profiles: Click any wallet on the leaderboard to see a 30-day historical PnL chart, total net worth, and a breakdown of their current token, DeFi, and NFT positions.

Persistence: Duel data is stored using Firebase Firestore for real-time updates and persistence across sessions.

🛠 Tech Stack

Frontend: React (JSX)

Styling: Tailwind CSS (loaded via CDN for single-file deployment)

Database: Google Firebase (Firestore for duel data, Auth for user session tracking)

Charting: Recharts

Data Source: Zerion API (Mocked for performance and demonstration purposes)

📦 Repository Structure

The entire application logic (React, CSS, and component structure) is contained within the single App.jsx file.

/
├── App.jsx           # The complete, runnable React application.
├── README.md         # This guide.
├── .gitignore        # Standard React ignore file.
└── LICENSE.md        # MIT License.


⚙️ Installation and Setup

Since this is a single-file React component, local setup requires a standard Node.js/React environment for packaging and a working Firebase configuration.

Clone the Repository:

git clone [Your Repository URL]
cd defi-duel


Install Dependencies:

npm install react react-dom firebase recharts lucide-react
# or
yarn add react react-dom firebase recharts lucide-react


Run Locally (Requires a local React setup like Vite or CRA):
Copy the contents of App.jsx into your main component file (App.jsx or main.jsx) and run your local development server.
