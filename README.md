# Imagify

## Features

- **Real-Time Image Generation**: Image generation using CLIPDROP API.
- **Secure Authentication**: User authentication using JWT and bcrypt for secure login and data protection.
- **RESTful APIs**: Efficiently handles user management, messaging, and file uploads with Express.
- **Responsive Design**: Built with TailwindCSS to ensure the application is fully responsive across all devices.

## Technologies Used

### Frontend

- **React**: Library for building user interfaces.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **Axios**: For making HTTP requests.
- **Motion UI**: For accessible UI components.
- **Vite**: For fast development and build processes.

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for data storage.
- **Mongoose**: ODM for MongoDB.
- **JWT**: For secure authentication.
- **Bcrypt**: For password hashing.
- **Razorpay**: For payment gateway.
- **Clipdrop**: For image generation.
- **Nodemon**: For automatic server restarts during development.


### Clone the Repository

```bash
git clone https://github.com/gurunath-pujar-dev/text-to-image-gen.git
```

### Setup .env file in server folder

```bash
MONGODB_URI = <your_mongodb_uri>

JWT_SECRET = <your_secret_key>

CLIPDROP_API = <clipdrop_api_key>

RAZORPAY_KEY_ID =  <rzpay_key_id>
RAZORPAY_KEY_SECRET = <rzpay_ket_secret>
CURRENCY = <your_currency>

```

### Setup .env file in client folder

```bash
VITE_BACKEND_URL = <server_url>

VITE_RAZORPAY_KEY_ID = <rzpay_key_id>

```


### Setup Backend

- Navigate to the server directory:

```bash
cd server
```

- Install dependencies:

```bash
npm install
```

- Start the server:

```bash
npm run server
```

### Setup Frontend

- Navigate to the client directory:

```bash
cd client
```

- Install dependencies:

```bash
npm install
```

- Start the development server:

```bash
npm run dev
```

## Usage

- Visit http://localhost:5173 to access the application locally. 
