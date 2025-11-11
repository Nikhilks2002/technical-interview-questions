# 💼 Technical Interview Questions

> A Next.js-based web app that organizes and presents technical interview questions to help users prepare effectively.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

---

## 📖 Overview

This project is a modern web application built with **Next.js**, featuring **TypeScript**, **App Router**, and optimized **font loading** via [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts).  
It’s a great starting point for building scalable and performant web applications.

---

## 🚀 Getting Started

Follow these steps to get up and running with your local development environment.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Nikhilks2002/technical-interview-questions.git
````

### 2️⃣ Install dependencies

You can use any package manager:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

### 3️⃣ Run the development server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Once started, open your browser and visit:
👉 [http://localhost:3000](http://localhost:3000)

You should see your Next.js app running locally!

---

## 🧑‍💻 Development Notes

You can start editing the homepage by modifying the following file:

```
app/page.tsx
```

The app supports **Hot Module Replacement (HMR)**, so changes are reflected automatically without refreshing the page.

This project also uses [**Geist Font**](https://vercel.com/font) via the `next/font` integration for automatic optimization and fast loading.

---

## 🧱 Project Structure

Below is the updated structure of this project:

```
├── app/
│   ├── favicon.ico         # App favicon
│   ├── globals.css         # Global styles
│   ├── layout.tsx          # Root layout (shared across pages)
│   └── page.tsx            # Main homepage
│
├── public/                 # Static assets (images, SVGs, etc.)
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
│
├── .gitignore
├── README.md
├── eslint.config.mjs       # ESLint configuration
├── next.config.ts          # Next.js configuration
├── package-lock.json
├── package.json
├── postcss.config.mjs      # PostCSS configuration
└── tsconfig.json           # TypeScript configuration
```

---

## ⚙️ Environment Variables

To configure environment-specific settings, create a `.env.local` file in the project root.

Example:

```
NEXT_PUBLIC_API_URL=https://api.example.com
NEXT_PUBLIC_ENV=development
```

> ⚠️ Never commit your `.env.local` file to version control.
> For sensitive keys, use environment management systems (like Vercel’s Environment Variables).

---

## 🧰 Tech Stack

* **Framework:** [Next.js](https://nextjs.org)
* **Language:** [TypeScript](https://www.typescriptlang.org)
* **Styling:** CSS Modules / Tailwind CSS (optional)
* **Font Optimization:** [next/font](https://nextjs.org/docs/app/building-your-application/optimizing/fonts)
* **Deployment:** [Vercel](https://vercel.com)
* **Package Manager:** npm / yarn / pnpm / bun

---

## 📘 Learn More

To learn more about Next.js, explore the following resources:

* 📚 [Next.js Documentation](https://nextjs.org/docs) — Learn about Next.js features and API.
* 🧑‍💻 [Learn Next.js](https://nextjs.org/learn) — An interactive tutorial for beginners.
* 💬 [Next.js GitHub Repository](https://github.com/vercel/next.js) — Feedback and contributions are always welcome!

---

## 🚀 Deployment

The easiest way to deploy your Next.js app is with **Vercel**, the creators of Next.js.

1. Push your project to GitHub, GitLab, or Bitbucket.
2. Visit the Vercel dashboard:
   👉 [Deploy with Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme)
3. Import your project and deploy — that’s it!

For advanced options, check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

---

## 🧑‍🤝‍🧑 Contributing

Contributions are always welcome!
If you’d like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request 🚀

Maintained by [@Nikhilks2002](https://github.com/Nikhilks2002)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Made with ❤️ using [Next.js](https://nextjs.org)
