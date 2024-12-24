# Rividco Project Repositories

Welcome to the **Rividco** GitHub organization! This organization manages repositories related to the Rividco project, which provides a comprehensive platform for service and project portfolio management, customer administration, and SEO optimization.

## Overview

The Rividco project comprises three key repositories:

### 1. [Rividco Backend](https://github.com/Tharusha-2000/rividco.git)
This repository houses the backend logic for the Rividco platform. It includes:
- **Tech Stack:** Node.js, MongoDB, Express.js
- Features:
  - API endpoints for project and service management.
  - Admin functionality for managing customers and user inquiries.
  - Email campaign support using nodemailer.
  - SEO support, including sitemap and robots.txt generation.
- **Deployment:** Hosted on a Node.js-compatible environment.

### 2. [Rividco Frontend](https://github.com/Rividco-DBM/rividco.git)
This repository contains the user-facing frontend for the Rividco platform. It includes:
- **Tech Stack:** ReactJS
- Features:
  - Dynamic pages for showcasing projects, services, and testimonials.
  - Interactive UI components to manage free quote submissions.
  - SEO enhancements via structured meta-tags.
- **Deployment:** Hosted on Netlify.

### 3. [Rividco Admin Frontend](https://github.com/DilumCA/RividcoAdminFrontend.git)
This repository provides the admin dashboard interface for managing the platform’s data. It includes:
- **Tech Stack:** ReactJS
- Features:
  - Admin panels for CRUD operations on projects, services, employees, and customer requests.
  - Integration with Firebase for media storage.
  - User-friendly management of quotation requests and email campaigns.
- **Deployment:** Hosted on Netlify.

## Organization Structure

### Key Features:
- **Centralized Management:** Separate repositories for frontend, backend, and admin functionalities for easier maintenance and scalability.
- **Seamless Integration:** The frontend and admin panels communicate with the backend through a robust API architecture.
- **Modern Technologies:** Leverages modern web development frameworks and tools like ReactJS, Node.js, MongoDB, and Firebase.
- **SEO Optimization:** Focuses on search engine optimization through automated sitemap generation, robots.txt handling, and OpenAI-driven content strategies.

### Deployment Pipeline:
1. **Frontend and Admin Frontend:** Hosted on Netlify for fast, secure, and scalable delivery.
2. **Backend:** Deployed on a cloud-based Node.js environment for robust API handling.

## Getting Started

### Clone Repositories
1. Clone the backend repository:
   ```bash
   git clone https://github.com/Rividco-DBM/rividco.git
   ```
2. Clone the frontend repository:
   ```bash
   git clone https://github.com/Tharusha-2000/rividco.git
   ```
3. Clone the admin frontend repository:
   ```bash
   git clone https://github.com/DilumCA/RividcoAdminFrontend.git
   ```

### Installation and Setup

#### Backend
1. Navigate to the backend directory and install dependencies:
   ```bash
   cd rividco
   npm install
   ```
2. Set up the environment variables in a `.env` file:
   ```plaintext
   PORT=8000
   MONGO_URI=your_mongodb_connection_string
   EMAIL=your_email@example.com
   PASSWORD=your_email_password
   ```
3. Start the server:
   ```bash
   npm start
   ```

#### Frontend and Admin Frontend
1. Navigate to each repository and install dependencies:
   ```bash
   cd rividco  # For the user-facing frontend
   npm install
   cd ../RividcoAdminFrontend  # For the admin frontend
   npm install
   ```
2. Start the development server:
   ```bash
   npm start
   ```

## Contribution Guidelines

We welcome contributions to improve the Rividco platform. Please follow these steps:
1. Fork the repository you want to contribute to.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them with descriptive messages.
4. Push the changes to your forked repository and create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file in each repository for more details.

## Contact
For any inquiries or support, please contact us at [zionlogy99x@gmail.com](mailto:zionlogy99x@gmail.com).

---

We look forward to building an amazing platform with your contributions and support!

