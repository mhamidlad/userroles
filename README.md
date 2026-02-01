Built a secure role-based admin dashboard using Firebase Authentication and Firestore on the Spark plan. Implemented Google and email login, protected routes, admin-only permissions, user management, real-time updates, and Firestore security rules following real-world SaaS access control patterns.

```md
# Role-Based Admin Dashboard (RBAC)

A secure role-based admin dashboard built using Firebase on the Spark (free) plan. The application demonstrates real-world authentication, authorization, and access control patterns commonly used in SaaS products.

## 🚀 Live Demo
🔗 https://userroles.web.app

## ✨ Features
- Google and Email/Password authentication
- Role-based access control (Admin / User)
- Protected routes for authorized users
- Admin dashboard to manage users and roles
- Real-time data updates with Firestore
- Secure Firestore rules for data protection

## 🛠 Tech Stack
- **Frontend:** React
- **Authentication:** Firebase Authentication
- **Database:** Cloud Firestore
- **Hosting:** Firebase Hosting (Spark plan)

## 🔐 Security Highlights
- Users can only access their own data
- Admin-only permissions enforced using Firestore rules
- Unauthorized access is blocked at both UI and database levels

## 📁 Project Structure
```

src/
├── components/        # Reusable UI & route guards
├── pages/             # App pages (Login, Dashboard, Admin)
├── context/           # Auth context and state
├── firebase/          # Firebase configuration

```

## 📌 What This Project Demonstrates
- Real-world Firebase authentication & authorization
- Secure role-based systems without paid features
- Clean frontend architecture and state management
- Firebase Spark plan best practices

## 📄 License
This project is open source and available for learning and portfolio use.
```

---




