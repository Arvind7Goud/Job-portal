<h1 align="center" style="font-size: 48px;">🌟 Job Portal Application 🌟</h1>

<p align="center">
  <img src="https://img.shields.io/badge/MERN-Stack-brightgreen" alt="MERN Stack">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/github/stars/Arvind7Goud/Job-portal?style=social" alt="Stars">
</p>

<p align="center" style="font-size: 18px;">
  A comprehensive job portal application built using the <strong>MERN Stack</strong>. It allows job seekers to browse listings, apply for jobs, and manage their applications seamlessly. Employers can post jobs, view applications, and manage their listings—all in one platform.
</p>

---

<h2 style="font-size: 36px;">✨ Features</h2>
<ul style="font-size: 18px;">
  <li><strong>User Authentication:</strong> Secure role-based authentication using <strong>JWT</strong> for both job seekers and employers.</li>
  <li><strong>Job Listings:</strong> Browse through a wide range of job listings fetched from <strong>MongoDB</strong>.</li>
  <li><strong>Application Management:</strong> 
    <ul>
      <li>Job seekers can manage their applications.</li>
      <li>Employers can view and manage received applications.</li>
    </ul>
  </li>
  <li><strong>Responsive Design:</strong> Optimized for seamless usage across all devices.</li>
  <li><strong>Image Upload:</strong> Integrated with <strong>Cloudinary</strong> for managing uploaded images.</li>
</ul>

---

<h2 style="font-size: 36px;">🛠️ Technologies Used</h2>

<h3 style="font-size: 24px;">Frontend</h3>
<ul style="font-size: 18px;">
  <li>React.js</li>
  <li>React Router</li>
  <li>Bootstrap</li>
</ul>

<h3 style="font-size: 24px;">Backend</h3>
<ul style="font-size: 18px;">
  <li>Node.js</li>
  <li>Express.js</li>
  <li>MongoDB</li>
</ul>

<h3 style="font-size: 24px;">Authentication</h3>
<ul style="font-size: 18px;">
  <li>JWT (JSON Web Tokens)</li>
  <li>Bcrypt for password hashing</li>
</ul>

<h3 style="font-size: 24px;">Image Upload</h3>
<ul style="font-size: 18px;">
  <li>Cloudinary</li>
</ul>

<h3 style="font-size: 24px;">Deployment</h3>
<ul style="font-size: 18px;">
  <li>Frontend: Vercel</li>
  <li>Backend: Render</li>
  <li>Database: MongoDB Atlas</li>
</ul>

---

<h2 style="font-size: 36px;">🚀 Getting Started</h2>
<p style="font-size: 18px;">Follow these steps to set up the project locally:</p>

<h3 style="font-size: 24px;">Prerequisites</h3>
<ul style="font-size: 18px;">
  <li>Node.js (v22.2.0 or above) installed</li>
  <li>MongoDB Atlas account or a local MongoDB server</li>
  <li>Cloudinary account for image storage</li>
</ul>

<h3 style="font-size: 24px;">Installation</h3>

<ol style="font-size: 18px;">
  <li>
    Clone the repository:
    <pre><code>git clone https://github.com/Arvind7Goud/Job-portal.git</code></pre>
  </li>
  <li>
    Navigate to the project directory:
    <pre><code>cd Job-portal</code></pre>
  </li>
  <li>
    Install dependencies for the backend:
    <pre><code>
cd backend
npm install
</code></pre>
  </li>
  <li>
    Install dependencies for the frontend:
    <pre><code>
cd ../frontend
npm install
</code></pre>
  </li>
  <li>
    Set up environment variables:
    <ul>
      <li>Create a <code>config.env</code> file inside a <code>config</code> folder in the <code>backend</code> directory.</li>
      <li>Add the following variables (replace placeholders with your details):</li>
    </ul>
    <pre><code>
PORT=5000
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
FRONTEND_URL=http://localhost:3000
DB_URL=your_mongodb_connection_string
JWT_SECRET_KEY=your_jwt_secret
JWT_EXPIRE=7d
COOKIE_EXPIRE=7
</code></pre>
  </li>
  <li>
    Run the application:
    <ul>
      <li>Start the backend:
        <pre><code>
cd ../backend
npm run dev
</code></pre>
      </li>
      <li>Start the frontend:
        <pre><code>
cd ../frontend
npm start
</code></pre>
      </li>
    </ul>
  </li>
  <li>
    Open your browser and navigate to <code>http://localhost:3000</code>.
  </li>
</ol>

---

<h2 style="font-size: 36px;">🤝 Contributing</h2>
<p style="font-size: 18px;">
  Contributions are welcome! Follow these steps to contribute:
</p>

<ol style="font-size: 18px;">
  <li>Fork the repository.</li>
  <li>Create a branch for your feature:
    <pre><code>git checkout -b feature/YourFeatureName</code></pre>
  </li>
  <li>Commit your changes:
    <pre><code>git commit -m "Add your message here"</code></pre>
  </li>
  <li>Push your branch:
    <pre><code>git push origin feature/YourFeatureName</code></pre>
  </li>
  <li>Open a pull request.</li>
</ol>

---

<h2 style="font-size: 36px;">📞 Contact</h2>
<p style="font-size: 18px;">
  <strong>Arvind Goud</strong> <br>
  <a href="https://github.com/Arvind7Goud">GitHub: Arvind7Goud</a> <br>
  <a href="https://github.com/Arvind7Goud/Job-portal.git">Project Link: Job Portal Repository</a>
</p>
