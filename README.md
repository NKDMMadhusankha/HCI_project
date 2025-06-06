# 🛋️ Styled Spaces

Styled Spaces is a modern web application for interactive room and furniture design, built with **React**, **Three.js**, and **Vite**. It allows users to visualize, customize, and manage room layouts in both 2D and 3D, with features for shopping cart, checkout, and staff management.

---

## 🚀 Features

- **2D & 3D Room Visualization**: Switch between top, front, side, and 3D views of your room.
- **Drag-and-Drop Furniture**: Place, move, and rotate furniture models in real time.
- **Customizable Room Dimensions & Colors**: Edit room size and wall colors with intuitive controls.
- **Shopping Cart & Checkout**: Add furniture to your cart and complete purchases with a modern checkout flow.
- **Template Management**: Save, load, and manage room templates for future use.
- **Staff Management**: Admins can add staff accounts securely.
- **Responsive UI**: Fully responsive and mobile-friendly design.
- **Authentication**: Secure login and role-based access.

---

## 🖥️ Tech Stack

- **Frontend**: [React](https://react.dev/), [Three.js](https://threejs.org/), [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/), [Tailwind CSS](https://tailwindcss.com/), [Vite](https://vitejs.dev/)
- **State Management**: [Zustand](https://zustand-demo.pmnd.rs/)
- **Icons**: [Lucide](https://lucide.dev/), [Heroicons](https://heroicons.com/)
- **Backend**: [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [MongoDB](https://www.mongodb.com/), [Mongoose](https://mongoosejs.com/)
- **Authentication**: JWT, bcrypt
- **Other**: [Axios](https://axios-http.com/), [react-hot-toast](https://react-hot-toast.com/)

---

## 📦 Project Structure

```
client/
  src/
    components/      # Reusable UI components (Navbar, 2D/3D views, etc.)
    Pages/           # Main app pages (Dashboard, Cart, Checkout, Login, etc.)
    3D_Models/       # 3D furniture models
    store/           # Zustand stores
    assets/          # Images and static assets
    lib/             # Utility libraries (e.g., axios instance)
  public/            # Static files
  index.html
  package.json
server/
  controller/        # Express controllers (user, etc.)
  middleware/        # Auth and other middleware
  model/             # Mongoose models
  routes/            # Express routes
  server.js
  package.json
```

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/styled-spaces.git
   cd styled-spaces
   ```

2. **Install client dependencies:**
   ```sh
   cd client
   npm install
   ```

3. **Install server dependencies:**
   ```sh
   cd ../server
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in `server/` with your MongoDB URI and JWT secret:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     NODE_ENV=development
     ```

---

## 🏃‍♂️ Running the App

### Start the backend server

```sh
cd server
npm run dev
```

### Start the frontend (in a new terminal)

```sh
cd client
npm run dev
```

- The frontend will be available at [http://localhost:5173](http://localhost:5173)
- The backend will run at [http://localhost:3000](http://localhost:3000) (or your configured port)

---

## 🧪 Scripts

| Command           | Description                |
|-------------------|---------------------------|
| `npm run dev`     | Start development server  |
| `npm run build`   | Build for production      |
| `npm run preview` | Preview production build  |
| `npm run lint`    | Run ESLint                |

---

## 📸 Screenshots

> _Add screenshots or GIFs here to showcase your app!_

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 🙏 Acknowledgements

- [Vite](https://vitejs.dev/)
- [React Three Fiber](https://docs.pmnd.rs/react-three-fiber/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- [Heroicons](https://heroicons.com/)

---

> _Styled Spaces — Transform rooms with beautiful furniture!_
