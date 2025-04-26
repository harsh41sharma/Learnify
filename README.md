# 📚 Learnify - Learning Management System (LMS) Platform

Learnify is a modern, full-stack Learning Management System built with the MERN Stack. It enables students to enroll in courses, track progress, and access learning materials, while instructors can manage courses, students, and content.

---

## 🚀 Features

- 🔐 User Authentication (Student/Instructor/Admin Roles)
- 🎓 Course Enrollment and Tracking
- 📄 Course Creation & Management (Instructor Dashboard)
- 🎥 Video Lectures and Material Upload
- 📝 Assignments and Quiz Management
- 🏆 Certificate Generation (Coming Soon)
- 📊 Student Progress Tracking
- 📱 Fully Responsive UI
- 📈 Admin Analytics and Reports

---

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS, Redux Toolkit, Axios  
**Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT, Bcrypt  
**Video Upload & Management:** Cloudinary / AWS S3 (Optional)  
**Payment Integration:** Stripe / Razorpay (Optional)

---

## 🔧 Setup Instructions

1. Clone the repository and move into the project:

   `git clone https://github.com/yourusername/learnify-lms.git && cd learnify-lms`

2. Set up the backend:

   `cd backend && npm install && npm run dev`

3. Open a new terminal, then set up the frontend:

   `cd frontend && npm install && npm start`

4. Create a `.env` file in the `/backend` directory and add the following:

   `MONGO_URI=your_mongodb_connection_string`  
   `JWT_SECRET=your_jwt_secret`  
   `CLOUDINARY_API_KEY=your_cloudinary_api_key` *(optional)*  
   `STRIPE_SECRET_KEY=your_stripe_secret_key` *(optional)*

---

## 🧠 Folder Structure

learnify-lms/ ├── backend/ # Express.js API + MongoDB + Auth + Course Logic ├── frontend/ # React.js UI + Redux for Courses and Users └── cloud/

## 🌐 Live Demo

🔗 Coming Soon  
➡️ Deploy frontend on [Vercel](https://vercel.com)  
➡️ Deploy backend on [Render](https://render.com) or [Railway](https://railway.app)

---

## 📸 Screenshots

| Home Page | Course Details | Instructor Dashboard |
|-----------|----------------|-----------------------|
| ![Home](./screenshots/home.png) | ![Course](./screenshots/course.png) | ![Instructor](./screenshots/instructor.png) |

---

## 🙌 Contributing

Contributions are welcome!  
Feel free to fork the repo and submit a pull request with improvements.

---

## 📄 License

Licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---

## 👨‍💻 Developed By

**Harsh Sharma**  
Aspiring Full Stack Developer | Entrepreneur in the Making 🚀  
[LinkedIn](https://www.linkedin.com/in/harsh41sharma) • [GitHub](https://github.com/harsh41sharma)
