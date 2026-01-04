# apod-web-app 🌌

**apod-web-app** is a simple, modern web application that displays NASA’s *Astronomy Picture of the Day (APOD)* using the official NASA API.  
Users can explore breathtaking space images and read daily astronomy explanations in a clean, responsive interface.

---

## 🚀 Tech Stack
- HTML  
- CSS  
- JavaScript  
- NASA APOD API  

---

## 🔗 Live Demo
You can deploy this project on platforms like **Netlify** or **Vercel** for free.  

---

## 📦 Features
- Displays daily astronomy picture from NASA  
- Responsive and clean UI  
- Image title, description, and date  
- Supports image and video media types  

---

## 🔒 API & Security
- Uses the official [NASA APOD API](https://api.nasa.gov/)  
- **Do not expose your API key in client-side JavaScript**  
- Recommended approach:
  - Use a **backend proxy** (Node.js/Express or serverless function)  
  - Store your API key in **environment variables**  
  - Fetch data securely from the backend to the frontend  

---

## 📝 Installation / Usage

```bash
git clone https://github.com/yourusername/apod-web-app.git
cd apod-web-app
# Open index.html in your browser
