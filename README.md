penttv-ticketing/
│
├── README.md
│
├── frontend/                         # React App (Vercel)
│   ├── public/
│   ├── src/
│   │   ├── App.js                   # Main app (your UI)
│   │   ├── index.js
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── Payment.js
│   │   │   ├── Confirm.js
│   │   │   ├── Admin.js
│   │   │   └── Scanner.js
│   │   ├── components/
│   │   │   ├── TicketCard.js
│   │   │   ├── PaymentQR.js
│   │   │   ├── AdminTable.js
│   │   │   └── ScannerBox.js
│   │   └── utils/
│   │       └── api.js                # Axios backend calls
│   │
│   ├── package.json
│   └── vercel.json
│
│
├── backend/                          # Node API (Render)
│   ├── server.js                     # Main backend (your API)
│   ├── models/
│   │   ├── Payment.js
│   │   └── Ticket.js
│   │
│   ├── routes/
│   │   ├── paymentRoutes.js
│   │   ├── ticketRoutes.js
│   │   └── adminRoutes.js
│   │
│   ├── controllers/
│   │   ├── paymentController.js
│   │   ├── ticketController.js
│   │   └── adminController.js
│   │
│   ├── config/
│   │   └── db.js                    # MongoDB connection
│   │
│   ├── .env
│   ├── package.json
│   └── render.yaml
│
│
└── docs/
    ├── API.md
    ├── DEPLOYMENT.md
    └── FLOW.md
