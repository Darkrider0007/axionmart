# Axionmart

<img src="./public/landing.jpg" alt="Landing Page" width="100%">

AxionMart is an e-commerce web application where users can sign in and sign up securely, with plans for enhanced security in the future. It allows users to buy and sell products, featuring cart and checkout functionalities.

Built with Next.js, Tailwind CSS, Shadcn UI, MongoDB, and various third-party libraries, AxionMart offers a seamless and modern shopping experience.

## Features

- User authentication
- Product listing
- Cart and checkout
- User profile
- Search functionality
- Product categories

## Technologies Used

- Next.js
- Tailwind CSS
- Shadcn UI
- MongoDB
- Mongoose
- JWT
- bcrypt
- Axios
- React Hook Form

## Installation

1. Clone the repository
2. Install dependencies

```bash
bun install
```

3. Create a `.env.local` file in the root directory and add the following environment variables:

```bash
MONGODB_URI=
ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=p
STRIPE_SECRET_KEY=
```

4. Run the development server

```bash
bun run dev
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE)
