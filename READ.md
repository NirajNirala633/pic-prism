# PicPrism

PicPrism is a web application built with React and Vite for the client-side and Node.js with Express for the server-side. It allows users to upload, purchase, and manage photos. The application supports user authentication, photo analytics, and payment processing using Razorpay.


## Features

- User Authentication (Signup, Login, Token Refresh)
- Photo Upload and Management
- Photo Purchase and Payment Processing
- Photo Analytics
- Favorites Management
- Responsive Design

## Technologies Used

- React
- Redux Toolkit
- Tailwind CSS
- Vite
- Node.js
- Express
- MongoDB
- Razorpay

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:

```sh
git clone https://github.com/NirajNirala633/pic-prism/
cd pic-prism
```

2. Install dependencies for the client:

```sh
cd client
npm install
```

3. Install dependencies for the server:

```sh
cd ../server
npm install
```

### Environment Variables

Create a `.env` file in the `server` directory and add the following environment variables:

```
MONGO_URI=your_mongodb_uri
ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_SECRET=your_razorpay_secret
CLIENT_URL=http://localhost:5173
```

### Running the Application

1. Start the server:

```sh
cd server
npm start
```

2. Start the client:

```sh
cd ../client
npm run dev
```

The application should now be running at `http://localhost:5173`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License.
