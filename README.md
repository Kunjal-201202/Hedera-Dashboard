# Hedera-Dashboard

# Hedera Live Transaction Dashboard

## Overview
A real-time dashboard application that monitors and displays live Hedera network transactions using the Mirror Node API. The dashboard provides insights into network activity, token transfers, and contract interactions, with HashPack wallet integration for personal transaction tracking.

![Hedera Dashboard Screenshot]
[Add a screenshot of your dashboard here]

## Features

### 1. Real-Time Transaction Monitoring
- Live updates of Hedera network transactions
- Automatic refresh every 10 seconds
- Visual representation of transaction flow
- Detailed transaction information display

### 2. Transaction Filtering
- Filter by account ID
- Filter by transaction type
- View personal transactions through HashPack wallet integration
- Historical transaction lookup

### 3. Data Visualization
- Real-time transaction volume chart
- Transaction type distribution
- Fee statistics
- Network activity trends

### 4. Wallet Integration
- HashPack wallet connection
- Personal account transaction tracking
- Secure wallet connection management
- Account balance display

## Technology Stack

### Frontend
- React.js
- Material-UI (MUI) for styling
- Chart.js for data visualization
- HashConnect for wallet integration

### APIs
- Hedera Mirror Node API
- HashPack Wallet API

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/hedera-dashboard.git
cd hedera-dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure
