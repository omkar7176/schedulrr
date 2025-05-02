# 📅 Schedulrr

**Schedulrr** is a modern web-based scheduling platform designed to simplify and automate appointment booking for individuals and organizations. It replaces inefficient traditional scheduling methods like emails and phone calls with real-time availability, secure authentication, and a seamless user experience.

## 🚀 Features

- 📆 Set and manage your availability with ease
- 🔗 Share booking links with automatic time slot handling
- 🔒 Secure user authentication using Clerk
- ⚡ Real-time database syncing with Neon DB and Prisma
- 💡 Responsive, accessible UI built with Tailwind CSS and Shadcn UI
- 🔧 Customizable booking durations and settings
- 📱 Mobile-friendly design for all devices

## 🛠️ Tech Stack

- **Frontend**: ReactJS, Next.js
- **Styling**: Tailwind CSS, Shadcn UI
- **Backend**: Prisma ORM, Neon DB
- **Authentication**: Clerk
- **Deployment**: Vercel (recommended)

## 📦 Installation

1. **Clone the repository**  
```bash
git clone https://github.com/your-username/schedulrr.git
cd scheduler
```
2. **Install dependencies**
```bash
npm install
# or
yarn install
```
3. **Set up environment variables**
--Create a .env file and add the following:
```bash
DATABASE_URL=your_neon_db_url
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```
4. **Run the development server**
```bash
npm run dev
# or
yarn dev
```
Open http://localhost:3000 to view it in your browser.

## 🤝Acknowledgements
- Thanks to the open-source community and the developers behind ReactJS, Next.js, Tailwind CSS, Prisma, Neon DB, Clerk, and Shadcn UI.
- Special appreciation to faculty, peers, and family for their guidance, feedback, and support during development.

## 📄License
- This project is licensed under the MIT License.

---

Let me know if you'd like me to generate a `LICENSE` file, add shields/badges, or customize the setup instructions for Docker or CI/CD.
