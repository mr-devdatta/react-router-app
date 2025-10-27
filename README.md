# React Router App

A modern React application built with React Router v7, featuring a feature-driven architecture and multiple layout systems. This project demonstrates advanced React routing patterns with nested layouts, authentication flows, and employee management functionality.

## 🚀 Technology Stack

- **React 19.1.1** - Latest React with modern features and hooks
- **React Router DOM v7.9.4** - Advanced routing with nested layouts and data loading
- **Material-UI (MUI) v7.3.4** - Beautiful React components
- **Tailwind CSS v4.1.14** - Utility-first CSS framework
- **Emotion** - CSS-in-JS styling library
- **Axios** - HTTP client for API requests
- **Vite** - Fast build tool and development server
- **ESLint** - Code linting and quality assurance

## 📁 Project Structure

```
src/
├── assets/           # Static assets (styles, images, icons)
│   └── styles/      # Global CSS and Tailwind configuration
├── components/       # Reusable UI components
│   ├── form/        # Form-related components
│   └── layout/      # Layout components (Header, Footer, Sidebar, etc.)
├── config/          # Configuration files
│   └── router.jsx   # React Router configuration
├── features/        # Feature modules (business logic)
│   ├── aboutus/     # About Us page
│   ├── authentication/ # Login and password reset
│   ├── employee/    # Employee management (CRUD operations)
│   ├── home/        # Home page
│   └── student/     # Student management (planned)
├── lib/             # Utility functions and shared code
├── pages/           # Page components
└── services/        # API services (for future implementation)
```

## ✨ Features

### 🏗️ Advanced Layout System
- **Nested Routing** - Multi-level layout hierarchy
- **MainLayout** - Root layout with navigation and footer
- **PublicLayout** - For public pages (Home, About Us)
- **Layout1** - Authentication pages (Login, Forgot Password)
- **Layout2** - Protected pages (Employee management)

### 📱 Available Pages
- **Home** (`/`) - Landing page
- **About Us** (`/aboutus`) - Company information
- **Authentication** (`/login`, `/forgetpassword`) - User login system
- **Employee Management** (`/employee`, `/employee/add`) - CRUD operations

### 🎨 Styling & UI
- **Tailwind CSS** for responsive design
- **Material-UI** components for rich interactions
- **Custom CSS classes** for consistent theming
- **Emotion** for styled components

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd react-router-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to see the application

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🏛️ Architecture Overview

This project follows a **feature-driven architecture** with clear separation of concerns:

### Key Architectural Patterns
- **Feature-based organization** - Each feature is self-contained
- **Component composition** - Reusable components across features
- **Layout nesting** - React Router v7 nested layouts
- **Separation of concerns** - Business logic separate from UI

### Routing Strategy
The application uses React Router v7's advanced features:
- Nested routes with layout inheritance
- Multiple layout systems for different user states
- Index routes for default pages
- Path-based route organization

## 🔧 Development

### Adding New Features
1. Create a new folder in `src/features/`
2. Add your components in `src/features/your-feature/components/`
3. Create page components in `src/features/your-feature/pages/`
4. Update the router configuration in `src/config/router.jsx`
5. Add new routes to the appropriate layout

### Styling Guidelines
- Use **Tailwind CSS** for layout and spacing
- Leverage **Material-UI** for complex components
- Add custom styles in `src/assets/styles/index.css`
- Follow the existing naming conventions (e.g., `my-border`, `form-input-field`)

## 📝 Future Enhancements

- [ ] API integration with backend services
- [ ] Authentication middleware implementation
- [ ] State management (Redux Toolkit or Zustand)
- [ ] Form validation and error handling
- [ ] Unit and integration testing
- [ ] TypeScript migration
- [ ] PWA capabilities

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is private and all rights reserved.

---

Built with ❤️ using React, React Router, and modern web technologies.
