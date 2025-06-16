
# 🪑 Terra Furniture Lab

Welcome to **Terra Furniture Lab**, a modern **e-commerce web application** built with Next.js and TypeScript. This platform is designed for showcasing and selling furniture collections, featuring essential functionalities like a **shopping cart**, **checkout process**, and more, to provide a seamless user experience. It integrates a robust backend using Prisma ORM for efficient data management and includes a dedicated **admin panel** for comprehensive product and order management.

---

## ✨ Features

### 🛍️ For Customers:

- 🛋️ **Extensive Product Catalog**: Browse a wide range of furniture products with detailed descriptions and images.
- 🛒 **Shopping Cart Functionality**: Easily add, view, and manage items in your shopping cart.
- 💳 **Seamless Checkout Process**: A streamlined and secure checkout flow for purchasing products.
- 🔍 **Product Search & Filtering**: Efficiently find desired items using search and various filtering options.
- 📱 **Responsive Design**: A user-friendly interface that adapts to various screen sizes (desktop, tablet, mobile).
- ⚡ **Optimized Performance**: Fast loading times and smooth navigation powered by Next.js and next/font.

### 🧑‍💼 For Administrators (Admin Panel):

- 🪑 **Product Management**: Add, edit, delete, and manage furniture products, including details, pricing, and images.
- 📦 **Order Management**: View, update the status of, and manage customer orders.
- 👥 **User Management**: Oversee registered user accounts (if applicable).
- 🖼️ **Content Management**: Potentially manage website content such as banners, promotions, or categories.

### ⚙️ Technical Features:

- 🚀 **Modern Web Stack**: Built with Next.js for server-side rendering (SSR), static site generation (SSG), and robust API routes.
- 🛡️ **TypeScript**: Ensures type safety, enhances code quality, and improves maintainability across the application.
- 🗃️ **Database Integration with Prisma**: Utilizes Prisma ORM for powerful and intuitive database access and management.
- 🔤 **Optimized Fonts**: Employs `next/font` to optimize and load Geist, a performant font family for Vercel, enhancing overall aesthetics and speed.
- 🧩 **Component-Based Architecture**: Leverages React's component model for modular, reusable, and scalable UI elements.

---

## 🛠️ Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Next-Auth](https://next-auth.js.org/)
- [Vercel](https://vercel.com/) (for deployment)
- [Neon](https://neon.tech/) (for database)
- [Cloudinary](https://cloudinary.com/) (for image hosting)
- [ESLint](https://eslint.org/) (for code linting)

---

## 🧑‍💻 Getting Started

Follow these instructions to set up and run the project locally.

### 📦 Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/alghifrz/terra-furniture-lab.git
    cd terra-furniture-lab
    ```

2. **Install dependencies**:

    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

### 🏃 Running the Development Server

Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### 🧬 Prisma Setup (if applicable)

If your project utilizes Prisma:

1. Configure your database in `prisma/schema.prisma`.
2. Generate the Prisma client:

    ```bash
    npx prisma generate
    ```

3. Apply any migrations:

    ```bash
    npx prisma migrate dev
    ```

---

## 📚 Learn More

- [Next.js Documentation](https://nextjs.org/docs) – Explore Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) – Interactive Next.js tutorial.
- [Next.js GitHub Repository](https://github.com/vercel/next.js) – Feedback and contributions welcome!

---

## 🚀 Deployment

Deploy effortlessly using [Vercel](https://vercel.com/), the creators of Next.js.

See the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for details.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

---

## 📄 License

Consider adding a license file (like MIT or Apache 2.0) to this repository and referencing it here.
