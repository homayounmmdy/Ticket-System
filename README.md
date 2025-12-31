# 🎫 Ticket System

<img width="1856" height="973" alt="Screenshot 2025-12-31 at 21-33-30 Ticket System" src="https://github.com/user-attachments/assets/92d547b5-6495-467a-9318-a0ef0fba55d4" />


The **Ticket System** is a modern, web-based application designed to manage and track support tickets, feature requests, bugs, or any task that benefits from structured workflows. Built with developer experience and end-user usability in mind! 💻✨

## 🎯 Project Goals

✅ **Completed**  
- Secure **authentication** with **Clerk** 👤  
- Core **ticket CRUD operations** 📝  
- **Responsive UI** using Tailwind CSS + DaisyUI 📱  
- **Serverless API** via Next.js routes ☁️  
- **MongoDB** integration for data persistence 🗃️  

🔜 **Planned / In Progress**  
- 🔐 **Multi-user roles** (Admin, Agent, Customer)  
- 📊 **Data visualization** with **Chart.js** (e.g., ticket volume, status trends)  
- ✅ **Form validation** using **Zod** + React Hook Form  
- 🧠 **Global state management** with **Zustand**  
- 📅 **Dates & reminders** for tickets  
- 🔍 **Advanced filtering & search** (by assignee, tag, date, etc.)  
- 📤 **CSV export** of ticket data  

## 🚀 Features

- **🎫 Ticket Management**: Create, view, edit, and delete tickets  
- **🚦 Status Tracking**: Follow tickets through statuses like *Open*, *In Progress*, and *Closed*  
- **📱 Fully Responsive**: Looks great on mobile, tablet, and desktop  
- **🔐 Secure Auth**: Powered by **Clerk** for seamless sign-in/sign-up  
- **🎨 Clean UI**: Built with **Tailwind CSS** + **DaisyUI** for polished components  


## 🛠️ Tech Stack

### Frontend
- **Next.js** ⚡ – SSR & SSG for React  
- **React** 🧩 – Declarative UI components  
- **Tailwind CSS** 🎨 – Utility-first styling  
- **DaisyUI** 🧵 – Beautiful pre-built components  
- **Zustand** 🧠 – Lightweight global state  
- **Zod** ✅ – Type-safe schema validation  

### Backend
- **Next.js API Routes** ☁️ – Serverless functions  
- **Clerk** 👤 – Authentication & user management  

### Database
- **MongoDB** 🗃️ – Flexible NoSQL storage  

## 📥 Getting Started

### Prerequisites
- Node.js (v14+)  
- npm or yarn  

### Installation
1. **Clone the repo**
   ```bash
   git clone https://github.com/homayunmmdy/Ticket-System.git
   cd Ticket-System
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**  
   Create a `.env.local` file:
   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
   CLERK_SECRET_KEY=your_clerk_secret
   MONGODB_URI=your_mongodb_connection_string
   ```

4. **Run the app**
   ```bash
   npm run dev
   # or
   yarn dev
   ```
   Visit `http://localhost:3000` 🌐

## 🧪 Usage

1. **Sign in** with Clerk (email, Google, etc.)  
2. **Create a Ticket**: Click **+ New Ticket**, fill in title, description, and priority ⚡  
3. **Manage Tickets**: View, update status, add comments, or close from your dashboard 📋  

## 🤝 Contributing

Contributions are **welcome**! 🙌  
Whether it’s a bug fix, new feature, or UX improvement—your help matters.

### How to contribute:
1. Fork the repo 🍴  
2. Create your feature branch (`git checkout -b feat/amazing-feature`)  
3. Commit your changes (`git commit -m 'Add some amazing feature'`)  
4. Push to the branch (`git push origin feat/amazing-feature`)  
5. Open a **Pull Request** 💌  


Made with ❤️ and ☕ | Open to feedback & collaboration!
