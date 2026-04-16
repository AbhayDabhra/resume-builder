# ✨ AI Resume Builder

A sleek, performant, and fully functional full-stack platform that allows users to create, preview, and download professional resumes in minutes, powered natively by the **Google Generative AI** SDK.

## 🚀 Features

- **AI-Powered Generation**: Integrates the Gemini API to intelligently generate professional summaries and role descriptions based on user input.
- **Beautiful & Responsive UI**: Hand-crafted layouts with Tailwind CSS, delivering a premium and intuitive editing experience.
- **Multiple Templates**: Choose from elegant templates like Classic, Modern, and Minimal to perfectly match your professional profile.
- **Live Preview & Export**: See your changes in real-time as you type, and instantly export the final resume to PDF.
- **Robust Full-Stack Backend**: Securely saves resumes and user data using Node.js, Express, and MongoDB, with fast image uploads powered by ImageKit.

## 🛠️ Tech Stack

- **Frontend**: [React](https://react.dev/) + [Vite](https://vitejs.dev/) + Tailwind CSS
- **Backend**: Node.js + Express + MongoDB
- **AI & Storage**: [@google/generative-ai](https://www.npmjs.com/package/@google/generative-ai) for smart text generation, ImageKit for image storage.

## 💻 Running Locally

To run this project on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AbhayDabhra/resume-builder.git
   cd resume-builder
   ```

2. **Configure your Environment Variables:**
   - Create a `.env` file inside the `server/` folder and paste the required keys:
     ```env
     JWT_SECRET="your_jwt_secret"
     MONGODB_URI="your_mongodb_connection_string"
     IMAGEKIT_PRIVATE_KEY="your_imagekit_key"
     OPENAI_API_KEY="your_gemini_api_key"
     OPENAI_BASE_URL="https://generativelanguage.googleapis.com/v1beta/openai/"
     OPENAI_MODEL="gemini-2.5-flash"
     ```

3. **Start the Backend (Server):**
   ```bash
   cd server
   npm install
   npm run server
   ```

4. **Start the Frontend (Client):**
   Open a new terminal window starting from the root directory:
   ```bash
   cd client
   npm install
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser to start building resumes with AI!

---

*Authored by Abhay*
