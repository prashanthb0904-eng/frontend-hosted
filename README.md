Product Inventory Management System – Frontend

A modern and responsive frontend application for managing product inventory efficiently. This project provides an intuitive user interface for creating, viewing, updating, and deleting products while interacting seamlessly with the backend API.

🚀 Live Demo

Frontend Hosted URL:
Add your deployed frontend URL here after deployment.

Example:

https://your-frontend-app.vercel.app
📌 Features
View all products in a clean dashboard
Add new products to inventory
Edit existing product details
Delete products from inventory
Search and filter products
Responsive design for desktop and mobile devices
Real-time integration with FastAPI backend
User-friendly interface with modern UI components
🛠️ Tech Stack
React.js
JavaScript
HTML5
CSS3
Axios
React Router
Vite
📂 Project Structure
frontend/
│
├── public/

├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── assets/
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
├── vite.config.js
└── README.md
⚙️ Installation
1. Clone the Repository
git clone https://github.com/prashanthb0904-eng/frontend-hosted.git
cd frontend-hosted
2. Install Dependencies
npm install
3. Configure Environment Variables

Create a .env file in the root directory:

VITE_API_URL=http://localhost:8000

Replace the URL with your deployed backend API URL when deploying.

4. Start Development Server
npm run dev

Application will run on:

http://localhost:5173
🔗 Backend Integration

The frontend communicates with the FastAPI backend through REST APIs.

Example API Endpoint:

GET /products
POST /products
PUT /products/{id}
DELETE /products/{id}

Make sure the backend server is running before accessing the frontend application.

📱 Screens Included
Dashboard
Product Listing
Add Product Form
Edit Product Form
Product Details
Search & Filter Interface
🚀 Deployment
Build Production Version
npm run build
Preview Production Build
npm run preview
Deploy Using
Vercel
Netlify
GitHub Pages
🧪 Testing

Run tests using:

npm test
📈 Future Enhancements
User Authentication
Role-Based Access Control
Product Categories
Inventory Analytics Dashboard
Export Reports (PDF/Excel)
Dark Mode Support
Advanced Filtering & Sorting
🤝 Contributing

Contributions are welcome.

Fork the repository
Create a new branch
git checkout -b feature-name
Commit changes
git commit -m "Add feature"
Push to branch
git push origin feature-name
Open a Pull Request
📄 License

This project is developed for educational and learning purposes.

👨‍💻 Author

Prashanth Ganesh
