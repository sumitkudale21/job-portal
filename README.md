# Job Portal – Full Stack React Application 🚀

A modern **full-stack Job Portal web application** built using React and a scalable backend ecosystem. The platform enables recruiters to post jobs, manage applications, and allows job seekers to explore, save, and apply for jobs through an intuitive and responsive interface.

---

## ✨ Features

### 👤 Authentication & Authorization

* Secure authentication using **Clerk**
* Role-based access control for **Recruiters** and **Job Seekers**
* Protected routes and onboarding flow

### 💼 Job Management

* Recruiter can post, update, and manage job listings
* Job seekers can browse and view detailed job descriptions
* Save jobs for later and track applied jobs

### 📊 Application Tracking

* Real-time job application status updates
* Personalized dashboard for recruiters and candidates

### 🎨 UI & UX

* Fully responsive and mobile-friendly design
* Dark mode support
* Modern UI built with **ShadCN UI** and **Tailwind CSS**
* Custom grid-based background layout

---

## 🛠️ Tech Stack

**Frontend:**

* React.js
* React Router DOM
* Tailwind CSS (v4)
* ShadCN UI

**Backend / Services:**

* Supabase (Database & APIs)
* Clerk (Authentication)

**Tools & Platforms:**

* Git & GitHub
* Vite
* Postman

---

## 📂 Project Structure

```
JobPortal/
├── src/
│   ├── components/      # Reusable UI components
│   ├── layouts/         # App layout & shared UI
│   ├── pages/           # Route-based pages
│   ├── hooks/           # Custom React hooks
│   ├── utils/           # Helper functions
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_key
```

### 4️⃣ Run the application

```bash
npm run dev
```

Open 👉 `http://localhost:5173`

---

## 🔐 Authentication Flow

* Users sign up / log in via Clerk
* Onboarding determines user role (Recruiter / Job Seeker)
* Access to routes is controlled based on role

---

## 📈 Future Enhancements

* Resume upload & parsing
* Advanced job filters & search
* Email notifications
* Admin dashboard
* Deployment with custom domain

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Open a Pull Request

---

## 👨‍💻 Author

**Sumit Kumar**
Made with ❤️ while building real-world full-stack projects.

* GitHub: [https://github.com/your-username](https://github.com/sumitkudale21)
* LinkedIn: [https://linkedin.com/in/your-profile](https://linkedin.com/in/sumitkudale)

---

⭐ If you like this project, don’t forget to star the repository!
