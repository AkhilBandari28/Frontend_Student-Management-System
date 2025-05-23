# 🎓 Student Management System (Frontend)

This is the **frontend** of the **Student Management System**, built using **React** and powered by **Vite** for a fast development experience. It provides a clean and responsive UI, styled with **Tailwind CSS**, and enhanced user interaction using **React Toastify** for real-time feedback. The frontend communicates with a backend API to manage core student-related functionalities.

---

## 🚀 Tech Stack

- **React** – for building dynamic user interfaces.
- **Vite** – for blazing fast dev server and optimized production build.
- **Tailwind CSS** – for modern, utility-first CSS styling.
- **React Toastify** – for non-blocking, elegant notifications.
- **Fetch API** – for client-side HTTP requests.

---

## ✨ Features

- 🔍 **List Courses** – Fetch and display all available courses from the backend.
- ➕ **Create Course** – Add new course with duration, name, and cost.
- ❌ **Delete Course** – Remove a course with a confirmation toast.
- ⚡ **Toast Notifications** – Real-time success/error messages using Toastify.
- 🧠 **Form Validation** – Client-side checks before submission.
- 🎨 **Fully Responsive** – Optimized for all screen sizes using Tailwind.
- 💻 **Backend Integration** – Seamlessly connects to backend API (`localhost:8080`).

---

## 📂 Folder Structure

```
student-management-frontend/
├── public/
│   └── ...
├── src/
│   ├── ListOfCourses.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
├── index.html
├── tailwind.config.js
├── package.json
└── README.md
```

---

## 🔗 Backend Connection

This frontend interacts with a Java-based backend (Spring Boot or Servlet) hosted locally at:

```
http://localhost:8080
```

Ensure that the backend endpoints like:

- `GET /allcourses`
- `POST /savecourse`
- `DELETE /deletecourse/{cid}`

...are up and running to allow full functionality.

---

## 📷 Screenshots

> Add your UI screenshots here using:

```markdown
![Course List UI](./screenshots/course-list.png)
![Create Course Form](./screenshots/create-form.png)
```

---

## 📦 Getting Started

### Prerequisites

- Node.js
- Backend API running on `localhost:8080`

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/student-management-frontend.git
cd student-management-frontend

# Install dependencies
npm install

# Run the app
npm run dev
```

---

## 🧑‍💻 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request with improvements.

---

## 🙏 Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Toastify](https://fkhadra.github.io/react-toastify/introduction/)
- [Java / Spring Boot / Servlets] – for backend services

---

## 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 📬 Contact

**Akhil Bandari**  
📧 Email: [your.akhilbandari3605@gmail.com](mailto:your.akhilbandari3605@gmail.com)  
🌐 GitHub: [https://github.com/AkhilBandari28](https://github.com/AkhilBandari28)
