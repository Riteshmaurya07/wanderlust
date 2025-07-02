
# 🌍 Wanderlust

**Wanderlust** is a full-stack travel and hotel booking web application built using **Node.js**, **Express**, **MongoDB**, and **EJS**. It allows users to explore, list, and book rental properties around the world with a smooth and interactive interface.

🔗 **Live Demo:** [wanderlust-3f61.onrender.com](https://wanderlust-3f61.onrender.com)

---

## 🚀 Features

- 🔐 User authentication (register, login, logout)
- 🏠 List and manage rental properties
- 📸 Upload images for listings using Cloudinary
- 📍 Search properties by location
- ✏️ Edit and delete listings (for listing owners)
- 💬 Leave reviews and ratings on listings
- 🎨 Responsive UI using EJS templating
- 🧾 Form validations and error handling

---

## 🛠️ Tech Stack

- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- EJS (Embedded JavaScript Templates)  
- Passport.js for authentication  
- Cloudinary (Image uploads)  
- Multer (File uploads)  
- Dotenv (Environment variables)

---

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/8ea469b7-af95-4259-a0ff-d8d89918dd69)
![image](https://github.com/user-attachments/assets/4d8f48a2-0853-4a46-b5e8-61780dee319e)
![image](https://github.com/user-attachments/assets/4c16f713-57ea-457c-a55b-b88b66226a76)
![image](https://github.com/user-attachments/assets/607a86a9-6fd9-4cbd-b61a-a0e42052abde)
![image](https://github.com/user-attachments/assets/04aa81ba-edd6-4dc1-8b1b-0190421827e1)

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Riteshmaurya07/wanderlust.git
cd wanderlust
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SESSION_SECRET=your_session_secret
```

### 4. Start the Server

```bash
npm run dev
```

---

## 📁 Folder Structure

```
wanderlust/
│
├── controllers/              # Route handlers (listing, reviews, users)
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── init/                     # App initialization scripts
│   ├── data.js
│   └── index.js
│
├── models/                   # Mongoose models
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── public/                   # Static assets
│   ├── css/
│   └── js/
│
├── routes/                   # Express routes
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── utils/                    # Utility functions (error handling, wrappers)
│
├── views/                    # EJS templates
│   ├── includes/
│   ├── layouts/
│   ├── listings/
│   └── users/
│
├── middleware/               # Custom middleware
├── cloudConfig.js            # Cloudinary setup
├── schema.js                 # Joi schemas
├── app.js                    # Main app file
├── package.json
└── README.md
```

---

## 💡 Future Improvements

- Add payment integration (Stripe, Razorpay)
- Map-based property search with real-time location filter
- Email notifications for bookings and messages
- Improve mobile responsiveness and accessibility

---

## 🙋‍♂️ Author

- **Ritesh Maurya**  
  🔗 [LinkedIn](https://www.linkedin.com/in/riteshmaurya07)  
  🐙 [GitHub](https://github.com/Riteshmaurya07)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## ⭐️ Show Your Support

If you like this project, please consider giving it a ⭐️ on GitHub!
