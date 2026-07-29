# 🌍 WanderLust

WanderLust is a full-stack Airbnb-inspired web application where users can explore, create, edit, and manage property listings. The application includes secure authentication, image uploads, reviews, and role-based authorization, providing a smooth and user-friendly rental listing experience.

---

# ✨ Features

* 🔐 User Authentication (Register & Login)
* 👤 Authorization for Listings and Reviews
* 🏡 Create, Edit, and Delete Property Listings
* 🖼️ Upload Listing Images with Cloudinary
* ⭐ Add, Edit, and Delete Reviews
* 📱 Fully Responsive User Interface
* 🛡️ Secure Sessions and Flash Messages
* ✅ Server-side Validation using Joi
* 📂 MVC Architecture for Better Code Organization

---

# 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* EJS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Security

* Passport.js
* Passport Local Strategy
* Express Session
* Connect Flash
* Joi Validation

### Image Storage

* Cloudinary
* Multer

---

# 📁 Project Structure

```text
wanderlust/
├── controllers/
├── models/
├── routes/
├── views/
│   ├── listings/
│   ├── users/
│   └── includes/
├── public/
│   ├── css/
│   └── js/
├── utils/
├── middleware.js
├── cloudConfig.js
├── schema.js
├── app.js
├── package.json
└── .env
```

---

# 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
```

### Install dependencies

```bash
npm install
```

### Create a `.env` file

```env
ATLASDB_URL=

SECRET=

CLOUD_NAME=
CLOUD_API_KEY=
CLOUD_API_SECRET=
```

### Run the application

```bash
npm start
```

or

```bash
node app.js
```

For development:

```bash
nodemon app.js
```

---

# 📦 Main Dependencies

* Express.js
* MongoDB
* Mongoose
* Passport.js
* Passport Local
* EJS
* Bootstrap 5
* Cloudinary
* Multer
* Joi
* Method Override
* Connect Flash
* Dotenv

---

# 🎯 Future Improvements

* ❤️ Wishlist/Favorites
* 🔍 Search and Filters
* 📅 Booking System
* 💳 Payment Integration
* 📍 Maps & Location Support
* 📧 Email Notifications
* 🌙 Dark Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Ankit Kumar**

If you found this project helpful, don't forget to ⭐ the repository!
