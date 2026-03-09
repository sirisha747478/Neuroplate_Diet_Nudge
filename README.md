# 🧠 NeuroPlate – Diet Nudge AI

NeuroPlate is an **AI-powered diet recommendation system** that provides personalized food suggestions based on user inputs.
The system leverages **Google Gemini AI** to generate intelligent dietary advice and nudges users toward healthier eating habits.

This project demonstrates the integration of **AI, full-stack web development, and modern UI frameworks** to build an interactive health-focused application.

---

## 🚀 Features

* 🥗 **AI Diet Recommendations** – Uses Gemini AI to generate personalized meal suggestions.
* 📊 **Smart Food Nudging** – Encourages healthier food choices using AI insights.
* ⚡ **Fast React Interface** – Built with React + Vite for high performance.
* 🎨 **Modern UI** – Styled using TailwindCSS.
* 🧠 **AI Integration** – Google Gemini API for natural language responses.
* 🗄 **Local Database Support** – Uses SQLite for lightweight data storage.
* 📈 **Data Visualization** – Charts for nutritional insights using Recharts.

---

## 🛠 Tech Stack

**Frontend**

* React
* TypeScript
* Vite
* TailwindCSS

**Backend**

* Node.js
* Express.js

**AI Integration**

* Google Gemini API (`@google/genai`)

**Database**

* SQLite (`better-sqlite3`)

**Visualization**

* Recharts

---

## 📂 Project Structure

```
Neuroplate_Diet_Nudge
│
├── src
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── services
│       └── geminiService.ts
│
├── server.ts
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/sirisha747478/Neuroplate_Diet_Nudge.git
```

Move into the project folder:

```bash
cd Neuroplate_Diet_Nudge
```

Install dependencies:

```bash
npm install
```

---

## 🔑 Environment Setup

Create a `.env` file in the root directory and add your **Gemini API key**:

```
VITE_GEMINI_API_KEY=your_api_key_here
```

You can get the API key from:

https://aistudio.google.com/app/apikey

---

## ▶️ Running the Project

Start the development server:

```bash
npm run dev
```

Then open in browser:

```
http://localhost:3000
```

---

## 📊 Future Improvements

* User authentication
* Personalized nutrition tracking
* Meal planning dashboard
* Integration with wearable health devices
* Advanced AI nutrition analysis

---

## 🤝 Contributing

Contributions are welcome!
If you'd like to improve the project, feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

Developed as part of an AI-based health recommendation system project to explore **Human-AI interaction and intelligent dietary nudging**.
