# 🎨 Online Art Gallery

An online platform to explore, showcase, and purchase artwork.  
This project allows artists to upload their artworks and users to browse, search, and purchase them.

## 📌 Features
- 🖼️ View a collection of artworks with images and descriptions
- 🔍 Search and filter artworks by category
- 📝 Artist registration and artwork upload
- 🛒 Add artworks to cart and checkout
- 🔐 User authentication (Login / Register)
- 📱 Responsive design for mobile and desktop

## 🛠️ Tech Stack
### Frontend
- HTML, CSS, JavaScript
- React.js (or your frontend tech if different)
- Axios for API requests

### Backend
- Node.js & Express.js
- MongoDB / MySQL (whichever you used)
- JWT Authentication
- Multer for image uploads

## 📂 Project Structure
art-gallery/
│── backend/ # Backend code (API, database)
│── frontend/ # Frontend code (UI)
│── README.md # Project documentation
│── package.json

bash
Copy
Edit

## 🚀 Installation & Setup
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/art-gallery.git
cd art-gallery
2️⃣ Install dependencies
For backend:

bash
Copy
Edit
cd backend
npm install
For frontend:

bash
Copy
Edit
cd frontend
npm install
3️⃣ Setup environment variables
Create .env file in both backend and frontend folders:

ini
Copy
Edit
# Backend
PORT=5000
MONGO_URI=your_database_url
JWT_SECRET=your_secret_key

# Frontend
VITE_API_URL=http://localhost:5000
4️⃣ Run the project
Backend:

bash
Copy
Edit
cd backend
npm start
Frontend:

bash
Copy
Edit
cd frontend
npm run dev
Now open http://localhost:5173 in your browser.

📸 Screenshots
Add some screenshots of your project here
