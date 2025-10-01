# Fiona-Art-Portfolio

This is the portfolio website for **Fiona Nkatha Kimathi**, showcasing her work in theatre and film production, including roles as Costume Manager, Props Manager, Production Manager, Assistant Stage Manager, and Stage Manager.

## 🚀 Live Demo

You can deploy this project easily on [Vercel](https://vercel.com/) for fast, serverless hosting.

## 📁 Project Structure

- `public/index.html` — Main portfolio page
- `Images/` — Portfolio images
- `style.css` — Custom styles
- `api/` — (Optional) Backend API functions for contact form (see below)

## ✨ Features

- Responsive design using Tailwind CSS
- Hero, About, Productions, Skills, Education, and Contact sections
- Contact form ready for backend integration

## 📬 Contact Form API (Vercel Serverless Example)

To enable backend handling for the contact form, add this file:

````javascript
// filepath: api/contact.js
export default function handler(req, res) {
  if (req.method === 'POST') {
    const { name, email, message } = req.body;
    // Handle form submission (e.g., send email, save to DB)
    res.status(200).json({ success: true });
  } else {
    res.status(405).json({ error: 'Method not allowed' });
  }
}
🛠️ Local Development
Clone the repo:
git clone https://github.com/imutwiri/Fiona-Art-Portfolio.git
Open in VS Code and use Live Server or Vercel CLI:
vercel dev
🌐 Deployment
Connect your GitHub repo to Vercel.
Vercel auto-builds and deploys your site on every push.
📄 License
© 2025 Fiona Nkatha Kimathi. All rights reserved.

For collaborations, productions, or costume work, reach out via the contact form! ``````
