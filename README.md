<div align="center">
  <img src="https://raw.githubusercontent.com/umair-rahman/garage-inference/main/manifest.json" onerror="this.style.display='none'" alt="TaxPlain Logo" width="120" />
  <h1>⚡ TaxPlain</h1>
  <p><strong>Making Tax Digital (MTD) — Explained in 10 Seconds.</strong></p>
  <p>
    <a href="https://garage-inference.vercel.app" target="_blank">View Live Demo</a> ·
    <a href="#features">Features</a> ·
    <a href="#how-it-works">How It Works</a>
  </p>
</div>

---

## 🚀 The Problem
**864,000 UK sole traders and landlords** are being mandated by HMRC to comply with *Making Tax Digital (MTD)* starting April 2026. The official guidance is dense, confusing, and scattered across dozens of government pages. People are anxious about deadlines, software requirements, and potential £200 fines.

## 💡 The Solution
**TaxPlain** cuts through the bureaucratic noise. It is an ultra-fast, visually stunning, and privacy-first web application that tells you exactly when you need to comply, what software you need, and generates a professional letter for your accountant—all in under 10 seconds.

---

## ✨ Standout Features

### 🔒 100% Local & Private (Zero Data Sent)
Tax returns are highly sensitive. TaxPlain processes **all** user input entirely on the client side. No databases, no tracking, no server calls. Your data never leaves your device.

### 🧠 Local AI Edge-Case Handler (Phi-4 Mini)
What happens if a user has a highly complex, edge-case tax situation? Instead of sending data to an OpenAI server, TaxPlain leverages **WebLLM** to run the `Phi-4-mini` language model *locally within the browser*. You get enterprise-grade AI tax analysis without compromising a single byte of privacy.

### 📱 Progressive Web App (PWA) Ready
Install TaxPlain directly to your iOS or Android home screen. It comes equipped with a Service Worker and caching strategy, meaning it **works entirely offline**.

### 🖨️ Automated Accountant Letter Generator
Once a user's MTD phase is determined, the app dynamically generates a beautifully formatted, print-ready letter to hand off to their accountant or tax advisor, detailing their exact software and deadline requirements.

### 🎨 Stunning, High-Performance UI
Built entirely without heavy frameworks, utilizing raw CSS for maximum performance. Features a mesmerizing, animated 3D wireframe globe background, custom dropdowns, micro-animations, and dynamic countdown timers.

---

## 🛠️ Technology Stack

TaxPlain is an exercise in brutal minimalism and high-efficiency engineering:
* **HTML5 & Vanilla CSS3**: No Tailwind, no React. Pure, unadulterated web standards for lightning-fast load times.
* **Vanilla JavaScript**: Zero dependencies for the core logic and UI state management.
* **WebLLM**: Bringing the power of local AI inference (Phi-4 Mini) directly to the browser via WebGPU.
* **Service Workers & Manifest**: For full PWA and offline capabilities.

---

## 🏃‍♂️ Running Locally

Getting the app running locally takes less than a minute.

1. **Clone the repository**
   ```bash
   git clone https://github.com/umair-rahman/garage-inference.git
   cd garage-inference
   ```

2. **Serve the project**
   Because the project uses standard web technologies, you can serve it with any local server.
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # OR using Node's http-server
   npx http-server
   ```

3. **Open in Browser**
   Navigate to `http://localhost:8000`

---

## 📄 License
This project is open-source and available under the MIT License. 

*Disclaimer: TaxPlain is an educational tool based on HMRC guidance as of May 2026. It does not constitute formal legal or financial advice.*
