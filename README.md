# Qamar Exchange - Banking & Currency Exchange System

## Overview
Qamar Exchange is a comprehensive banking system designed for mobile, web, and tablet platforms. The system utilizes modern technologies including **React Native** for front-end development, **Node.js** for back-end services, and **MongoDB** for database management.

## Features
- **User Registration & Authentication**: Secure user registration and login system.
- **Account Management**: Users can view and manage their accounts in real-time.
- **Transaction Processing**: Seamless transaction handling including deposits, withdrawals, and money transfers.
- **Currency Exchange**: Real-time currency conversion with live exchange rates.
- **Multi-Platform Support**: Access from mobile devices, tablets, and web browsers.
- **Real-Time Notifications**: Users receive real-time updates on their transactions and account activities.
- **User-Friendly Interface**: Intuitive UI/UX design for an enhanced user experience.

## Technology Stack
- **Frontend**: React Native, Redux, React Navigation, Axios
- **Backend**: Node.js, Express, RESTful API
- **Database**: MongoDB, Mongoose 
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Docker, AWS

## Project Structure
```
Qamar-Exchange/
├── backend/
│   ├── models/
│   │   ├── User.js
│   │   ├── Transaction.js
│   │   └── ExchangeRate.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── transactions.js
│   │   └── exchange.js
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
├── frontend/
│   ├── screens/
│   ├── components/
│   ├── navigation/
│   └── App.js
├── package.json
└── README.md
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MariwanMahammad/Qamar-Exchange.git
   cd Qamar-Exchange
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the database:
   - Create a MongoDB database and update the configuration.
4. Start your application:
   ```bash
   npm start
   ```

## Usage
- Access the mobile application on your iOS/Android device.
- For web access, navigate to the provided link.
- Login with your credentials or create a new account.
- Start making transactions and currency exchanges.

## Contributing
Contributions are welcome! Please follow the standard Git workflow:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
**Mariwan Mahammad** - [GitHub Profile](https://github.com/MariwanMahammad)  
_Date: 2026-04-01_