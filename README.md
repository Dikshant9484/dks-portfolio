# Personal Portfolio

This repository contains a beautiful, responsive personal portfolio built using **React**, **Vite**, and **TailwindCSS**. The project showcases modern web development techniques including smooth animations, responsive layouts, and interactive UI components.



## Features

- **Modern Design:** Clean, SaaS-inspired design with a glass-effect navbar and sleek animations.
- **Responsive Layout:** Fully responsive across desktop, tablet, and mobile devices.
- **Interactive Components:** Animated sections and a mobile-friendly hamburger menu with smooth transitions.
- **Optimized Performance:** Fast development build using Vite with TailwindCSS for efficient styling.

## Technologies

- **React:** Component-based UI library.
- **Vite:** Fast and lean development build tool.
- **TailwindCSS:** Utility-first CSS framework.
- **JavaScript (ES6+):** Modern JavaScript features and best practices.

✨ Features

Modern Hero Intro Section

About & Skills Section

Featured Projects with Images

Contact Form (EmailJS Integration)

Social Media Footer with Icons

Responsive Design (Mobile + Desktop)

Smooth Scroll & Animations

Dark Themed UI with Glassmorphism Effects

🛠 Tech Stack

Frontend: React, Vite, Tailwind CSS

Icons: React Icons

Email Service: EmailJS

Deployment: Vercel / Netlify (optional)

📁 Folder Structure
src/
 ├─ assets/
 │   └─ projects/
 ├─ components/
 │   ├─ Navbar.jsx
 │   ├─ Footer.jsx
 │   ├─ RevealOnScroll.jsx
 │   └─ sections/
 │       ├─ Home.jsx
 │       ├─ About.jsx
 │       ├─ Projects.jsx
 │       └─ Contact.jsx
 ├─ App.jsx
 └─ main.jsx

⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/yourusername/portfolio.git
cd portfolio

2. Install Dependencies
npm install

3. Start Development Server
npm run dev

📧 EmailJS Setup (Contact Form)

Create account at https://emailjs.com

Add Email Service (Gmail recommended)

Create Email Template with variables:

{{name}}
{{email}}
{{message}}


Copy:

Service ID

Template ID

Public Key

Create .env in project root:

VITE_SERVICE_ID=your_service_id
VITE_TEMPLATE_ID=your_template_id
VITE_PUBLIC_KEY=your_public_key


Restart server.

🧩 Customization
Change Profile Image
src/assets/profile.png

Add Projects

Edit:

src/components/sections/Projects.jsx

Social Links

Edit:

src/components/Footer.jsx
Happy coding and enjoy building your professional portfolio!
