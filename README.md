# Tech Gadget E-Commerce App

This repository contains an E-Commerce Application built on Next.js 14, TypeScript, Sass, Stripe for payment processing, and Payload CMS for content management.

E-Commerce App is a robust online platform designed to facilitate services over the internet. It provides users with a seamless shopping experience, offering a wide range of products categorized for easy navigation. 

The web app includes features such as a user-friendly interface for browsing, searching, and filtering items, a secure payment gateway for transactions, account management for users to track orders and manage their profiles, and often an admin dashboard for store owners to manage inventory, orders, and content.


## Features

- #### Next.js 14

    Utilizing the latest version of Next.js for optimal performance, server-side rendering, and lightning-fast page loads.

- #### TypeScript

    Leverages TypeScript for improved code quality, better scalability, and enhanced developer productivity.

- #### SASS

    Utilizing SASS (Syntactically Awesome Stylesheets) for a more organized and maintainable approach to styling.

- #### Stripe

    Leverages TypeScript for improved code quality, better scalability, and enhanced developer productivity.

- #### Payload CMS

    Harnessing the power of Payload CMS for dynamic content management, allowing easy updates and modifications.

- #### User Authentication

    Secure user authentication and authorization functionalities to safeguard user data and access.

- #### Responsive Design

    Ensuring the application is responsive across various devices and screen sizes for an optimal user experience.

- #### Admin Dashboard

    A comprehensive and intuitive dashboard for managing products, orders, and content effortlessly.


## Setup Instructions

#### 1. Clone the repository

    git clone https://github.com/Stephenice/e-commerce.git

#### 2. Install Dependencies

     cd e-commerce-app
     npm install

#### 3. Set up Stripe

Create a Stripe account at [stripe.com](https://stripe.com/).
Obtain API keys from Stripe and configure them in the application.

#### 4. Set up Payload CMS

Create a Payload CMS account or set up a local instance.
Configure Payload CMS settings in the application to connect to your instance.

#### 5. Environment Variables

Create a .env file at the root of the project and add necessary environment variables:

```bash
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key

STRIPE_SECRET_KEY=your_stripe_secret_key

PAYLOAD_API_URL=your_payload_api_url

PAYLOAD_PUBLIC_KEY=your_payload_public_key
```

#### 6. Start the Application

    npm run dev

#### 7. Access the App

Open your browser and visit http://localhost:3000.

## Live Demo

`Url:`  https://e-commerce-pismap.payloadcms.app/

`Username:` test@test.com

`Password:` Usertest
