Multi_Vendor_Ecommerce_Platform/
│
├── README.md
├── LICENSE
├── .gitignore
├── docker-compose.yml          # optional (future-ready)
│
├── backend/
│   ├── package.json
│   ├── package-lock.json
│   ├── .env.example
│   ├── src/
│   │   ├── app.js               # express app setup
│   │   ├── server.js            # server entry point
│   │   │
│   │   ├── config/
│   │   │   ├── db.js             # DB connection
│   │   │   └── auth.js           # JWT / auth config
│   │   │
│   │   ├── models/               # DB models / schemas
│   │   │   ├── User.js
│   │   │   ├── Vendor.js
│   │   │   ├── Product.js
│   │   │   ├── Order.js
│   │   │   ├── Address.js
│   │   │   └── Review.js
│   │   │
│   │   ├── routes/
│   │   │   ├── auth.routes.js
│   │   │   ├── user.routes.js
│   │   │   ├── vendor.routes.js
│   │   │   ├── product.routes.js
│   │   │   ├── order.routes.js
│   │   │   └── admin.routes.js
│   │   │
│   │   ├── controllers/
│   │   │   ├── auth.controller.js
│   │   │   ├── product.controller.js
│   │   │   ├── order.controller.js
│   │   │   └── vendor.controller.js
│   │   │
│   │   ├── middlewares/
│   │   │   ├── auth.middleware.js
│   │   │   └── role.middleware.js
│   │   │
│   │   ├── services/
│   │   │   ├── recommendation.service.js   # rule-based (Phase 1)
│   │   │   └── payment.service.js
│   │   │
│   │   ├── utils/
│   │   │   ├── logger.js
│   │   │   └── validators.js
│   │   │
│   │   └── database/
│   │       ├── migrations/
│   │       └── seed.js
│   │
│   └── tests/
│
├── frontend/
│   ├── package.json
│   ├── package-lock.json
│   ├── .env.example
│   ├── public/
│   │   └── index.html
│   │
│   └── src/
│       ├── assets/
│       ├── components/
│       │   ├── Navbar.jsx
│       │   ├── ProductCard.jsx
│       │   └── Footer.jsx
│       │
│       ├── pages/
│       │   ├── Home.jsx
│       │   ├── Product.jsx
│       │   ├── Cart.jsx
│       │   ├── Login.jsx
│       │   ├── VendorDashboard.jsx
│       │   └── AdminDashboard.jsx
│       │
│       ├── services/
│       │   ├── api.js
│       │   └── auth.js
│       │
│       ├── context/
│       │   └── AuthContext.jsx
│       │
│       ├── styles/
│       ├── App.jsx
│       └── main.jsx
│
├── ai/
│   ├── README.md
│   ├── recommendation/
│   │   ├── data_preprocessing.py
│   │   ├── recommender.py
│   │   └── model.pkl
│   │
│   └── chatbot/                 # future phase
│       └── chatbot_service.py
│
├── docs/
│   ├── PRD.md
│   ├── ERD.png
│   ├── API_SPEC.md
│   └── WIREFRAMES/
│
└── scripts/
    └── setup.sh
