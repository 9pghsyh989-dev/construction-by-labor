construction-by-labor/
│
├── .github/                  # GitHub workflows & issue templates
├── docs/                     # Database diagrams, API docs, wireframes
│   ├── database-schema.png
│   └── api-endpoints.md
│
├── backend/                  # Server / Database API layer
│   ├── src/
│   │   ├── config/           # Database configuration & environment setups
│   │   ├── controllers/      # Route logic (Labor, Sites, Payroll, Materials)
│   │   ├── models/           # Database models / schemas
│   │   ├── routes/           # API routes
│   │   └── utils/            # Helper functions
│   ├── .env.example
│   ├── package.json
│   └── server.js
│
├── frontend/                 # App UI (Flutter / Web / Mobile)
│   ├── assets/               # Images, icons, fonts
│   ├── lib/                  # Application code
│   └── package.json
│
├── .gitignore                # Files to exclude from Git tracking
├── LICENSE                   # Open-source license (e.g., MIT)
└── README.md                 # Main project documentation
