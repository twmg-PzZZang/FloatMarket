# FloatMarket – CS2 Skin Marketplace

FloatMarket is a full-stack Counter-Strike 2 (CS2) skin marketplace developed as a personal project. The platform allows users to create accounts, browse available CS2 skins, list their own skins for sale and simulate purchases through Stripe's sandbox payment environment.

The project was built to develop my understanding of full-stack web development, backend programming, database management, user authentication and payment integration.

## Features

### User Authentication
- User registration and login functionality.
- Password hashing using bcrypt.
- Account-based access to marketplace features.
- User-specific functionality for buying and selling skins.

### Marketplace
- Browse skins listed for sale by other users.
- Create and manage marketplace listings.
- Store skin listings and associated information in an SQLite database.
- Display available items dynamically through the frontend.

### Buying and Selling
- Users can list their own CS2 skins on the marketplace.
- Users can browse available listings and initiate purchases.
- Integrated Stripe's sandbox environment to simulate the checkout process.
- Product prices are retrieved from marketplace listings rather than relying on a fixed price.

### User Interface
- Dark-themed interface inspired by existing gaming marketplaces.
- Light and dark theme functionality.
- Account navigation and user-focused interface elements.
- Responsive page layouts and interactive components.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and layouts |
| JavaScript | Frontend functionality |
| Node.js | Backend runtime |
| Express.js | Server and API routes |
| SQLite | Database management |
| bcrypt | Password hashing |
| Stripe API | Sandbox payment integration |
| Git & GitHub | Version control |

## Project Structure

```text
FloatMarket/
│
├── backend/
│   ├── server.js
│   ├── database.js
│   └── routes/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── images/
│
├── .env
├── .gitignore
└── README.md
```

*The structure above is an example; adjust it to match the actual repository.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the project

```bash
cd FloatMarket
```

### 3. Install dependencies

Navigate to the backend directory and install the required packages:

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the backend directory and add your Stripe test secret key:

```env
STRIPE_SECRET_KEY=your_stripe_test_secret_key
```

Never share or commit your Stripe secret key to GitHub.

### 5. Start the backend

```bash
node server.js
```

The backend should now be running locally.

### 6. Open the frontend

Open the frontend's main HTML file in your browser to access the marketplace.

## Payment Integration

FloatMarket uses Stripe's sandbox environment to demonstrate the payment process.

This allows users to experience a simulated checkout without processing real financial transactions.

**Note:** This project is intended for development and demonstration purposes. It is not a live trading platform and does not process actual CS2 skin transfers.

## What I Learned

Developing FloatMarket helped me gain practical experience in:

- Building and connecting a frontend to a backend.
- Creating REST API endpoints using Node.js and Express.
- Implementing user registration and authentication.
- Hashing passwords securely using bcrypt.
- Designing and interacting with relational databases using SQLite.
- Integrating third-party APIs, including Stripe.
- Managing application state and user sessions.
- Debugging backend errors and resolving database issues.
- Implementing different website themes and improving user experience.

## Future Improvements

Potential improvements include:

- Further improving the responsive design.
- Expanding user profile and account management features.
- Adding more advanced marketplace filtering and searching.
- Improving listing management and purchase handling.
- Implementing additional security and validation measures.

---

**Developer:** TWMG
**Project:** FloatMarket  
**Year:** 2026  
**Type:** Personal Full-Stack Development Project
