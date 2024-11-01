
# Referral System with Google-Based User Authentication

This project combines a referral system with secure user authentication via Google. It enables users to refer others using unique referral IDs, awarding both the referrer and the referred party points: 20 points for the first referral and 10 points for each subsequent referral.

## Features

- **Referral System**: Users receive a unique referral ID to share with others. Both the referrer and the invitee earn 20 points for the initial referral and 10 points for every subsequent referral.
- **User Authentication**: Google API-based login ensures secure, email-verified authentication.
- **Frontend**: Built with Vite and React for a responsive and dynamic interface.
- **Backend**: Developed with Node.js, Express, and MongoDB for robust server-side logic and data handling.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

- **Node.js** and **MongoDB** installed on your machine

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Gagan20-vis/Referral-System-with-User-Authentication-Using-Google-API.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Referral-System-with-User-Authentication-Using-Google-API
   ```
3. Install dependencies for both the client and server:
   ```bash
   # For the client
   cd client && npm install

   # For the server
   cd server && npm install
   ```

### Configuration

1. **Server Configuration**:
   - In the `server` directory, create a `.env` file with the following keys:
     - `DB`, `HOST`, `USER`, `PASS`, `SERVICE`, `BASE_URL` and any necessary Google API keys.
  
2. **Client Configuration**:
   - In the `client` directory, create a `.env` file with:
     ```env
     VITE_BASE_URL=http://localhost:8000/api/user
     ```

### Running the Application

1. Start the server:
   ```bash
   cd server && npm start
   ```
2. Launch the client:
   ```bash
   cd client && npm start
   ```

Access the application at `http://localhost:your_client_port` in your browser.

## Usage

- **User Registration**: New users register and receive a unique referral ID to invite others.
- **Email Verification**: Verification emails are sent via Google API, and users must verify their email to access the platform.
- **Referral Process**: Users can refer others, earning points for both themselves and the invitees.
- **Dashboard**: Authenticated users have access to a personalized dashboard to view points, manage referrals, and track invite progress.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests. For more details, see the `CONTRIBUTING.md` file.

