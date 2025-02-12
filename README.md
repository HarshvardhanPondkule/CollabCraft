# 🚀 CollabCraft - Real-Time Document Collaboration Platform

CollabCraft is a **real-time collaborative document editor** that enables seamless teamwork. With live editing, cursor synchronization, comments, and notifications, users can work together effortlessly. Built on a modern tech stack, CollabCraft ensures **high performance, security, and scalability**.  

---

## ✨ Key Features

- **📝 Real-Time Collaboration** – Multiple users can edit simultaneously with **live cursor updates, comments, and notifications**.
- **🔐 User Authentication & Role Management** – Secure access with **role-based permissions** (viewer, editor) using **Clerk**.
- **📱 Mobile-Friendly Interface** – Responsive **Tailwind CSS** design ensures a **smooth experience across all devices**.
- **⚡ Optimized Performance** – **Next.js server-side rendering** for **faster load times** and **SEO-friendly routing**.
- **🛠️ Error Monitoring** – **Sentry** provides **real-time error tracking** and **performance monitoring**.

---

## 🛠️ Tech Stack

- **⚛️ Next.js** – A powerful **React framework** enabling **server-side rendering** and **SEO optimization**.
- **📌 TypeScript** – Enhances development with **static type checking**, reducing runtime errors.
- **🎨 Tailwind CSS** – A **utility-first CSS framework** for rapid styling and **responsive designs**.
- **🔗 Live Blocks** – Powers **real-time collaboration** features, including **live editing, cursors, and comments**.
- **🔑 Clerk** – Handles **user authentication, role-based access control, and session management**.
- **🐞 Sentry** – Monitors **application performance** and logs **errors for debugging and optimization**.

---

## 🚀 Getting Started

### 📦 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/collabcraft.git
```

```bash
cd collabcraft
```

# Install dependencies
```bash
npm install
```

# Start the development server
```bash
npm run dev
```

### 🎯 Environment Variables

Create a `.env.local` file in the root directory and configure your API keys:

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

