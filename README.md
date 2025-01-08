# Chirp - Social Media Platform

Chirp is a mock social media application built with Next.js, showcasing the power of full-stack development with React Server Components and the App Router.

## 🚀 Tech Stack

- **Framework:** Next.js 14 (App Router & Server Components)
- **Authentication:** Clerk
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Styling:** Tailwind CSS
- **Deployment:** Vercel

## ✨ Features

- Modern, responsive UI
- User authentication with Clerk
- Real-time social feed
- Post creation and interaction
- Profile management
- Database persistence with Prisma & PostgreSQL

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/chirp.git
```

2. Install dependencies:

```bash
cd chirp
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:

```plaintext
DATABASE_URL="your_postgresql_url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

4. Set up the database:

```bash
npx prisma generate
npx prisma db push
```

5. Start the development server:

```bash
npm run dev
```

Visit `http://localhost:3000` to see your application running.

## 📝 Learning Goals

This project was built to gain hands-on experience with:

- Next.js App Router and Server Components
- User authentication implementation with Clerk
- Database modeling and management with Prisma
- Full-stack development best practices

## 🚀 Deployment

The application is configured for easy deployment on Vercel. Simply connect your repository to Vercel and it will automatically detect the Next.js configuration.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/chirp/issues).

---

Built with ❤️ using [Next.js](https://nextjs.org/)
