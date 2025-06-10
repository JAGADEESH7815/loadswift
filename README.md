"# loadswift" 
🚛 LoadSwift – Logistics Platform Like Delhivery
A logistics platform for shippers and transporters with zero brokerage fees , inspired by Delhivery. Users can book truckloads, view posted loads, and manage shipments easily.

Built using modern web technologies:

Frontend: HTML, CSS, JavaScript
Backend: Node.js + Express
Database: MongoDB Atlas
Authentication: JWT + bcrypt
Deployment-ready (GitHub Pages + Render/Railway)
🎯 Features
✅ Load booking form
✅ User authentication (Shipper & Transporter)
✅ Dashboard to view posted loads
✅ MongoDB backend with Mongoose ODM
✅ RESTful API endpoints
✅ Mobile-responsive design
✅ Deployable frontend (GitHub Pages)
✅ Free backend hosting guide (Render/Railway)

🧰 Tech Stack
Frontend
HTML5, CSS3, JavaScript
Backend
Node.js, Express.js
Database
MongoDB Atlas
Authentication
JWT, bcryptjs
Deployment
GitHub Pages (frontend), Render/Railway (backend)

📦 Folder Structure



loadswift/
│
├── index.html                  # Homepage
├── book-load.html              # Load booking form
├── dashboard.html              # User dashboard
├── style.css                   # Styling
├── backend/
│   ├── server.js               # Main server
│   ├── config/
│   │   └── db.js               # MongoDB connection
│   ├── models/
│   │   ├── Load.js             # Load model
│   │   └── User.js             # User model
│   ├── controllers/
│   │   ├── loadController.js
│   │   └── authController.js
│   ├── routes/
│   │   ├── loadRoutes.js
│   │   └── authRoutes.js
│   └── middleware/
│       └── authMiddleware.js
├── .env                        # Environment variables
├── .gitignore                  # Files to ignore in Git
└── README.md                   # Project description & setup guide
🛠️ How to Run Locally
1. Clone the repo
bash


1
2
git clone https://github.com/JAGADEESH7815/loadswift.git 
cd loadswift
2. Install backend dependencies
bash


1
2
cd backend
npm install
3. Set up .env file
Create a .env file inside backend/:



1
MONGO_URI=mongodb+srv://loadswift:jagadeesh%409177@cluster0.uwly4ui.mongodb.net/loadswift?retryWrites=true&w=majority&appName=Cluster0
Replace with your own MongoDB Atlas URI if needed. 

4. Start the server
bash


1
node server.js
Server will run at:
👉 http://localhost:5000

5. Open frontend
Open index.html in your browser or use a live server extension in VS Code.

🌐 How to Deploy
🟢 Frontend: GitHub Pages
Push code to GitHub
Go to Settings > Pages
Select branch: main, folder: /
Your site will be live at:
👉 https://JAGADEESH7815.github.io/loadswift
🔵 Backend: Render or Railway (Free Hosting)
Push backend code to GitHub
Create a new service on:
Render
Railway
Link to your GitHub repo
Add environment variable:


1
MONGO_URI=your_mongodb_connection_string
Deploy and get your live API URL
✅ Future Enhancements (Optional)
Add transporter bidding system
Enable real-time tracking
Add admin panel
Implement search/filter for loads
Add notifications or chat between users
🧑‍💻 Developed By
Jagadeesh

GitHub: @JAGADEESH7815
Email: jagadeesh@example.com

📜 License
MIT License – see LICENSE for details.
