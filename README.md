My Portfolio Project

Welcome to the Portfolio Project! 🚀 This project is a modern, feature-rich portfolio website designed to showcase my skills, projects, and professional experience. It features a dynamic frontend built with the latest web technologies and a robust backend powered by Spring Boot.

🌟 Live Demo

👉 Check out the live site: khenrab.io
(Hosted on my own VPS with a custom domain for full-stack control and performance.)

🖼️ Project Features

	•	Responsive Design: Fully responsive layout for seamless user experience across all devices.
	•	Modern UI/UX: Clean, professional, and interactive user interface with smooth animations.
	•	Dynamic Data: Backend APIs provide data dynamically, enabling easy content updates.
	•	JWT Authentication: Secure user authentication for accessing admin functionalities.
	•	Admin Control Panel: Manage projects, experience, and profile data directly via the admin interface.
	•	Secure API Endpoints: Leveraging Spring Boot and JWT for secure communication between the frontend and backend.
	•	Optimized Hosting: Deployed with Apache and SSL for secure and fast performance.

🛠️ Tech Stack

Frontend 🖌️

	•	Vite: Lightning-fast development environment.
	•	React: Component-based library for building the UI.
	•	JavaScript: ES6+ for dynamic functionality.
	•	Axios: Simplified HTTP requests to communicate with the backend.
	•	SCSS: Modular and reusable styles with advanced CSS features.
	•	AOS (Animate on Scroll): Smooth animations on scroll-based interactions.

Backend ⚙️

	•	Spring Boot: Backend framework for building RESTful APIs.
	•	JWT (JSON Web Token): Secure authentication and authorization.
	•	Hibernate: ORM framework for database operations.
	•	MySQL: Robust and scalable relational database.
	•	Maven: Dependency and build management.
	•	Apache (Reverse Proxy): Optimized backend communication and hosting.

Deployment 🚀

	•	VPS Hosting: Self-hosted on a private VPS for complete control over hosting and scalability.
	•	Certbot SSL: Ensures secure HTTPS communication with free and automated SSL certificates.
	•	GitHub Actions: Automates build processes and triggers deployment workflows directly from GitHub.
	•	Jenkins: Orchestrates complex CI/CD pipelines, enabling advanced automation for testing, building, and deployment.

💡 Key Features Breakdown

Frontend

	•	Interactive Animations: Elegant hover effects and scroll-based animations for an engaging user experience.
	•	Sidebar Navigation: Static left and right sidebars for quick access to socials and email links.
	•	Responsive Navbar: Burger menu for mobile devices with smooth transitions.
	•	Dynamic Content Rendering: Data fetched from backend APIs for seamless updates.

Backend

	•	Admin Dashboard: Easily update profile, manage projects, and more through secure API endpoints.
	•	Role-Based Authentication: Only authenticated users can access admin features.
	•	Error Handling: Comprehensive exception management for a reliable user experience.

Database

	•	Normalized Data Model: Efficient database design to handle user, project, and portfolio data.
	•	Secure Queries: Prepared statements to prevent SQL injection.

📂 Project Structure

Frontend

	•       public/
	•	 │   └── assets/        # Static assets like images and icons.
	•	src/
	•	 ├── api/               # API service files for backend communication.
	•	 ├── components/        # Reusable React components.
 	•	 ├── context/           # Manages global state using React Context API.
	•	 ├── styles/            # SCSS files for styling the application.
	•	 ├── utils/             # Helper and utility functions.
	•	 ├── App.jsx            # Main application layout and routing.
	•	 └── main.jsx           # Entry point rendering the React app.

Backend

	•	src/main/java/io/khenrab/
	•	 ├── controller/    # Handles HTTP requests and maps them to services.
	•	 ├── dto/           # Transfers data between application layers.
	•	 ├── entity/        # Maps database tables to Java objects.
	•	 ├── exception/     # Manages custom exceptions and error responses.
	•	 ├── mapper/        # Converts entities to DTOs and vice versa.
	•	 ├── repository/    # Interfaces for CRUD operations.
	•	 ├── security/      # Implements JWT and app security.
	•	 ├── service/       # Contains business logic.
	•	 │   └── impl/      # Implements service interfaces.
	•	 └── config/        # Configures Spring Boot and security.

🗂️ Future Enhancements

	•	Implement dark mode toggle for user preference.
	•	Add analytics to track portfolio views and interactions.
	•	Integrate email notifications for admin updates.
	•	Optimize database queries for large-scale data.
