CareerRise 🚀

CareerRise is a full-stack job portal platform that connects recruiters and job seekers through a modern, scalable, and secure web application. It includes authentication, recruiter dashboard, company management, job posting, and job application features.

Built using React JS, Supabase, Clerk, Tailwind CSS, and Shadcn UI.

✨ Features
👤 Authentication

Secure login & signup using Clerk

Role-based access (Recruiter / Job Seeker)

Protected routes

🏢 Recruiter Features

Create and manage companies

Post new job listings

Edit / delete job postings

View applicants

💼 Job Seeker Features

Browse job listings

View detailed job descriptions

Apply for jobs

Track applications

🎨 UI & UX

Fully responsive design

Modern UI with Tailwind CSS

Clean components using Shadcn UI

🛠 Tech Stack
Technology	Purpose
React JS	Frontend
Supabase	Backend & Database
Clerk	Authentication
Tailwind CSS	Styling
Shadcn UI	UI Components
📂 Project Structure
src/
 ├── components/
 ├── pages/
 ├── hooks/
 ├── lib/
 ├── context/
 └── assets/
⚙️ Environment Variables

Create a .env file in the root directory and add:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

⚠️ Never commit your .env file to GitHub.

🚀 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/vinayrendla6/CareerRise.git
cd CareerRise
2️⃣ Install dependencies
npm install
3️⃣ Start development server
npm run dev
📦 Build for Production
npm run build
🌍 Deployment

You can deploy this project on:

Vercel

Netlify

Render

Make sure to configure environment variables in the deployment platform.

📸 Screenshots

(Add your project screenshots here)

🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

📄 License

This project is open-source and available under the MIT License.