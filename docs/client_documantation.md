src/
│
├── app/                 # App bootstrap
│   ├── App.jsx
│   ├── routes.jsx
│
├── shared/              # Reusable UI
│   ├── components/
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   ├── layout/
│   │   ├── AuthLayout.jsx
│   │   └── MainLayout.jsx
│
├── features/
│   ├── auth/            # 🔐 Authentication
│   │   ├── pages/
│   │   │   └── StudentLogin.jsx
│   │   ├── components/
│   │   │   └── LoginForm.jsx
│   │   ├── auth.api.js
│   │   ├── auth.slice.js
│   │   └── auth.routes.jsx
│   │
│   ├── student/
│   ├── courses/
│   ├── instructor/
│   └── admin/
│
├── services/            # Axios, API config
├── hooks/
├── utils/
├── index.css
└── main.jsx
