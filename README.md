# AI-Summarizer

ai-summarizer/
├── backend/
│   ├── app.js                 # Express server setup
│   ├── routes/
│   │   ├── auth.js            # Routes for user authentication
│   │   ├── chat.js            # Routes for AI chatbox
│   │   ├── summarize.js       # Routes for summarization
│   ├── models/
│   │   ├── userModel.js       # User schema for MongoDB
│   │   ├── summaryModel.js    # Summary schema
│   ├── middlewares/
│   │   ├── authMiddleware.js  # Middleware for authentication
│   ├── config/
│   │   ├── db.js              # Database connection
│   │   ├── openai.js          # OpenAI API integration
│   └── package.json           # Backend dependencies
├── frontend/
│   ├── public/                # Static assets (images, fonts, etc.)
│   ├── src/
│   │   ├── components/        # Reusable React components
│   │   ├── pages/             # Pages (Login, Home, Dashboard)
│   │   ├── App.js             # Main React App
│   │   ├── index.js           # React entry point
│   └── package.json           # Frontend dependencies
├── docs/
│   ├── README.md              # Documentation for GitHub
│   ├── API_REFERENCE.md       # API details and usage
│   ├── FEATURES.md            # Features list
│   ├── SETUP.md               # Local setup instructions
├── .env                       # Environment variables
├── .gitignore                 # Files and folders to ignore in Git
└── README.md                  # Main project README
