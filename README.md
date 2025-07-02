
# 🌍 Wanderlust

**Wanderlust** is a full-stack travel and hotel booking web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to explore, list, and book rental properties around the world with a smooth and interactive interface.

🔗 **Live Demo:** [wanderlust-3f61.onrender.com](https://wanderlust-3f61.onrender.com)

---

## 🚀 Features

- 🔐 User authentication (register, login, logout)
- 🏠 List and manage rental properties
- 📸 Upload images for listings using Cloudinary
- 📍 Search properties by location
- ✏️ Edit and delete listings (for listing owners)
- 💬 Leave reviews and ratings on listings
- 🎨 Responsive UI with modern design
- 🧾 Form validations and error handling

---

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- React Router  
- Tailwind CSS  

**Backend**  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- Passport.js for authentication  

**Other Tools**  
- Cloudinary (Image uploads)  
- Mapbox or other geolocation API (if used)  
- Multer (for file uploads)  
- Dotenv (environment variables)

---

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/8ea469b7-af95-4259-a0ff-d8d89918dd69)
![image](https://github.com/user-attachments/assets/4d8f48a2-0853-4a46-b5e8-61780dee319e)
![image](https://github.com/user-attachments/assets/4c16f713-57ea-457c-a55b-b88b66226a76)
![image](https://github.com/user-attachments/assets/22a34ff1-bdd6-4534-99e5-ae71193e333a)
![image](https://github.com/user-attachments/assets/ec550108-d368-40be-836c-ac64eeadf79b)


---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Riteshmaurya07/wanderlust.git
cd wanderlust
```

### 2. Install Backend Dependencies

```bash
cd backend
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the `backend` folder with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SESSION_SECRET=your_session_secret
```

### 4. Start the Backend Server

```bash
npm run dev
```

### 5. Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### 6. Start the Frontend

```bash
npm run dev
```

---

## 📁 Folder Structure

```
wanderlust/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── ...
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   └── ...
```

---

## 💡 Future Improvements

- Add payment integration (Stripe, Razorpay)
- Map-based property search with real-time location filter
- Progressive Web App (PWA) support
- Email notifications for bookings and messages

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
