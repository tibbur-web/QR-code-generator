This is a simple and user-friendly web application that lets users convert text, links, image URLs, and video URLs into QR codes. It also supports uploading images/videos and accessing your device camera.

🔧 Features
✅ Generate QR codes for:

Paragraphs

Hyperlinks

Image URLs or image files (max 20 MB)

Video URLs or video files (max 20 MB)

📸 Camera input support (demo-only: doesn’t capture photos)

🎨 Beautiful UI with colorful category buttons

🧩 Lightweight and runs entirely in the browser

📎 Easy to copy and paste or upload from local storage

🚀 How to Use
Open index.html in any modern web browser.

Choose a content type by clicking the respective button.

Enter or upload your content using the input fields.

Click "Generate QR Code" and your QR code will appear!

🖼 Add Your Logo
Place your logo as logo.png in the same folder as index.html. It will be used as the website favicon (tab icon).

html
Copy
Edit
<link rel="icon" type="image/png" href="logo.png">
🌐 How to Publish
You can publish your site using:

GitHub Pages

Netlify (drag & drop index.html)

Vercel

Any static web host

📁 File Structure
cpp
Copy
Edit
project-folder/
├── index.html
├── logo.png (optional)
└── README.md
⚠️ Notes
Camera support is basic and does not capture or save media.

Files over 20 MB will be rejected.

App works offline after initial load (no server-side processing).
