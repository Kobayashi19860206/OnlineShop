# Online shop
This is a sample online shop that offers features such as product catalog, shopping cart, checkout and payments

# Features
- User Sign up and authentication
- Password Reset
- Product Catalog \w pagination
- Shopping Cart and Checkout
- Email Notifications
- Image Uploads
- Stripe Payment Integration

## Getting Started

Follow instructions below to have a copy of this project up and running on your local machine for development and testing purposes. 


### Prerequisites

You will need to have the following software installed on your system

- [Nodejs](https://nodejs.org/en/download/), a JavaScript runtime that lets you run applications outside the browser
- NPM, a package manager for Nodejs software packages (Comes with Node)

### Installing

Clone the repository to your local machine

```
git clone https://github.com/JaymesKat/online-shop.git
```

Navigate into root of repository

```
cd online-shop
```

Install application dependencies

```
npm install
```

Create a `.env` file based on the `.env.example` file and populate following variables

```
SENDGRID_API_KEY=
MONGO_DB_URL=
STRIPE_SECRET=
STRIPE_KEY=
```

*NB:* The `MONGO_DB_URL` should be populated to configure the app with a database. I recommend setting up one on [Mongo Atlas](https://www.mongodb.com/cloud/atlas) which is easy to setup and provides a free tier.

## Running the application

Run the command below in the project's root folder
```
npm start
```

## Built With

* [Expressjs](https://expressjs.com/) - Web framework used
* [EJS](https://ejs.co) - Templating engine
* [MongoDB](https://www.mongodb.com) - Database

## License

This project is licensed under the MIT License

## Acknowledgments

* Built through a course instructed by [Maximilian Schwarzmüller](https://www.udemy.com/user/maximilian-schwarzmuller/)
