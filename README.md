<h1 align="center">🍽️ React Native Recipe App 🍽️</h1>

![Demo App](/mobile/assets/images//screenshot-for-readme.png)

Highlights:

- 🔐 **Secure Login & Signup** with Clerk Authentication
- 📊 **Compare Smartphone Features** Side-by-Side
- 🔍 **Search Phones** with Instant Suggestions
- 📷 View Full-Resolution Images of Smartphones
- 💾 Save Favorite Comparisons
- 🌙 8 **Color Themes** for Better User Experience
- 🧩 Built with **React Native**, **Express**, **PostgreSQL**, and **Expo**
- 🆓 100% Free — No Paid APIs or Services Used

---

## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=5001
DATABASE_URL=your_neon_db_url
NODE_ENV=development
```

### Mobile App (`/mobile`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 📱 Run the Mobile App

```bash
cd mobile
npm install
npx expo start
```
