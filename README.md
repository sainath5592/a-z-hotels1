
# 🏨 aZ_Hotels

aZ_Hotels is a **full-stack hotel listing and booking web application** built with **Node.js, Express.js, MongoDB, and EJS**.  
It provides users with a platform to browse, book, and review hotels while ensuring secure authentication and role-based access control.

---

## 📖 Project Description

The project follows the **MVC (Model–View–Controller)** architecture to ensure clean separation of concerns, scalability, and maintainability.  

### ✨ Key Features
- **🔐 User Authentication & Authorization**
  - Secure sign-up and login system with encrypted passwords.
  - Role-based access control (regular users vs. admins).
- **🏨 Hotel Listings & Management**
  - Browse hotel listings with images, prices, and descriptions.
  - Authorized users can create, edit, and delete hotel listings.
- **⭐ Review & Rating System**
  - Users can post reviews and ratings for hotels.
  - Integrated with MongoDB for storing real-time feedback.
- **🎨 Templating with EJS**
  - Dynamic rendering of pages with reusable components.
  - Responsive layouts for an improved user experience.
- **⚡ Error Handling & Validation**
  - Custom error pages.
  - Input validation to ensure data integrity.

---

## 🛠️ Technology Stack

- **Backend:** Node.js, Express.js  
- **Frontend:** EJS, CSS  
- **Database:** MongoDB  
- **Architecture:** MVC  

---

## 📂 Project Structure

aZ_Hotels-main/
│── app.js # Main entry point
│── cloudConfig.js # Cloud storage configuration (if using)
│── middelware.js # Custom middleware
│── shema.js # Joi/validation schemas
│── utils/ # Utility functions (Error handling, async wrapper)
│── controllers/ # Controllers for business logic
│── models/ # Mongoose models
│── routes/ # Express routes
│── views/ # EJS templates
│── public/ # Static files (CSS, JS)
│── uploads/ # Uploaded hotel images
│── package.json
│── .gitignore
└── README.md


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone git@github.com:sainath5592/a-z-hotels1.git
   cd a-z-hotels1
Install dependencies

npm install
Configure environment variables
Create a .env file in the project root with the following keys:

PORT=3000
MONGO_URI=mongodb://localhost:27017/hotels
SESSION_SECRET=yourSecretKey
CLOUDINARY_KEY=yourKey        # if using cloud storage
CLOUDINARY_SECRET=yourSecret
Run the application

npm start
Open the app at http://localhost:3000


👨‍💻 Author
Sainath – GitHub
