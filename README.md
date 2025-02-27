## Usage

### Env Variables

Create or modify the .env file in then root and add the following

```
NODE_ENV = 'development'
PORT = '5000'
MONGO_URI = "YOUR_MONGODB_URI_HERE"
JWT_SECRET = 'random_secret_key'
PAYPAL_CLIENT_ID = 'your paypal client id'
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend Application (:3000) & Microservices (:5000)
npm run dev

# Run backend only
npm run server
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import General data
npm run data:general

# Import Automotive data
npm run data:automotive

# Import Retail data
npm run data:retail

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

john@example.com (Customer)
123456

jane@example.com (Customer)
123456
```