# Frontend Documentation

## Project Setup

```bash
cd frontend
npm install
npm run dev
```

Visit http://localhost:3000 to see the application.

## Features

- 🌐 **Bilingual Support** - Arabic and English
- 🎨 **Modern UI** - Built with Tailwind CSS
- 📱 **Responsive Design**
- 🔐 **Authentication** - Login and Register
- 🛍️ **Services Showcase**
- 📅 **Booking System**
- 📊 **User Dashboard**

## Directory Structure

```
frontend/
├── components/
│   ├── Layout.jsx
│   ├── Navbar.jsx
│   ├── Footer.jsx
│   └── ServiceCard.jsx
├── pages/
│   ├── index.js (Home)
│   ├── services.js (Services)
│   ├── login.js (Login)
│   ├── register.js (Register)
│   └── dashboard.js (Dashboard)
├── store/
│   ├── authStore.js
│   └── servicesStore.js
├── lib/
│   ├── api.js
│   └── i18n.js
├── styles/
│   └── globals.css
└── public/
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Environment Variables

Create a `.env.local` file:

```
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

## Technologies

- Next.js 14
- React 18
- Tailwind CSS
- Zustand (State Management)
- i18next (Internationalization)
- Axios (HTTP Client)
