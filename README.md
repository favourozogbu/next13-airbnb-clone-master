# Next.js 13 Airbnb Clone

A full-featured Airbnb-style property rental platform built with **Next.js 13 App Router**, showcasing modern web development practices including server-side data fetching, OAuth authentication, file uploads, advanced search filtering, and a fully responsive UI.

> Developed by **Favour Ozogbu** as a showcase of advanced full-stack development using Next.js, Tailwind CSS, Prisma, and Cloudinary.

![Copy of Fullstack Twitter Clone (8)](https://user-images.githubusercontent.com/23248726/229031522-64a49ad0-66f7-4ea8-94a8-f64a0bb56736.png)

---

## Features

### UI & Design
- Tailwind CSS styling with animations and transitions
- Fully responsive across mobile, tablet, and desktop
- Page-level loading and empty states via `loading.tsx` and `error.tsx`

### Authentication
- Credential-based authentication
- OAuth login with **Google** and **GitHub**
- Secure session management

### Property Management
- Property creation, editing, and deletion
- Image uploads using **Cloudinary CDN**
- Client-side validation with `react-hook-form`
- Server-side error handling with `react-toast`

### Booking & Reservations
- Booking calendar powered by `react-date-range`
- Dynamic pricing calculation
- Booking conflict detection (no double-bookings)
- Guest and host reservation cancellation

### Advanced Filtering & Search
- Filter listings by:
  - Category
  - Date range
  - Location (map-based)
  - Number of guests, rooms, and bathrooms
- Smart filtering excludes unavailable listings in chosen date range
- Shareable URL filters — keep state across sessions/devices

### Favorites System
- Users can favorite/unfavorite listings
- Data persists across sessions

### Technical Highlights
- App directory structure using **Next.js 13 App Router**
- Server components fetch data directly from the database (no API layer needed)
- `POST` and `DELETE` route handlers in `/app/api`
- Relational database modeling with **Prisma**
- Modular, scalable project architecture

---

## Tech Stack

- **Frontend:** Next.js 13 (App Router), Tailwind CSS
- **Backend:** Next.js API routes (Server Components)
- **Authentication:** NextAuth.js
- **Database:** Prisma + PostgreSQL / MongoDB
- **Cloud Storage:** Cloudinary
- **Forms & UX:** react-hook-form, react-toast, react-date-range

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/favourozogbu/next13-airbnb-clone-master.git
cd next13-airbnb-clone-master


### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-airbnb-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

## 👨‍💻 Author's Contact   
**For collaboration or freelance work:**

**Favour S. Ozogbu**   
📧 favoursozogbu@gmail.com  
🔗 [GitHub](https://github.com/favourozogbu)
🔗 [LinkedIn](https://www.linkedin.com/in/favourozogbu)


