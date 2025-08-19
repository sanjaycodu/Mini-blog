# 📝 Blog-App

Full-stack blog application built with **Spring Boot** (backend) and **React** (frontend). Users can register, log in with JWT authentication, create posts, and view blogs. The app follows RESTful principles and features protected routes, clean UI, and MySQL database integration.

---

## 🚀 Features

### 🔒 Backend (Spring Boot)
- User Registration & Login
- Spring Security with JWT Authentication
- Create and view blog posts
- RESTful API structure
- MySQL + Spring Data JPA

### ⚛️ Frontend (React)
- React with Vite
- JWT token storage in `localStorage`
- Login & Registration forms
- Protected routes for authenticated users
- Post creation and viewing
- Axios for API calls
- Clean and responsive UI

---

## 🛠️ Tech Stack

| Layer     | Technologies Used                                                                 |
|-----------|------------------------------------------------------------------------------------|
| Backend   | Java , Spring Boot , Spring Security, Spring Data JPA, MySQL, Maven               |
| Frontend  | React , Vite, React Router , Axios                                                |

---

## 📦 Getting Started

### 🔧 Backend Setup

1. Clone the repository and navigate to the backend folder:

   ```bash
   git clone https://github.com/sanjaycodu/Mini-blog.git
   cd Mini-blog/blog-backend
   ```
   Make sure your are in the correct folder blog-backend 
3. Configure your application.properties or application.yml file:

```bash
spring.datasource.url=jdbc:mysql://localhost:3306/blogdb
spring.datasource.username=your_username
spring.datasource.password=your_password
```
3. jwt.secret=your_256_bit_secret_key
- Run the backend using Maven:
  ```bash
  ./mvnw spring-boot:run
  ```
  Or u can reinstall the dependencie through your tool(easy)
  After u can run the tomcat server by Run the appliction in the folder
  "BlogAppApplication.java"
  if tomcat run without error move to forntend folder with other tool
⚛️ Frontend Setup- Navigate to the frontend folder:
cd blog-frontend
- Install dependencies:
  ```bash
  npm install
     ```
- Start the development server:
  ```bash
  npm run dev
  ```
📁 Folder StructureMini-blog/
├── blog-frontend/   # React frontend
└── blog-backend/    # Spring Boot backend
💡 Notes- Ensure MySQL is running and the blogdb database is created.
- JWT secret should be a secure 256-bit key.
- CORS is configured to allow frontend-backend communication.
📬 ContactFor questions or suggestions, feel free to reach out via GitHub Issues.
---

Let me know if you want to add deployment instructions, contribution guidelines, or a license section. This README is already looking sharp!
Feel free to ask on instagram,whatsapp,gamil.
