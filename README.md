# 💊 PharmaQuizPro 🧪

![PharmaQuizPro UI](https://github.com/tharunkumarmekala/Pharmaquizpro/blob/main/Assets/Pharmaquizpro.png?raw=true)

**Master the world of Pharmacy through interactive learning powered by Google Gemini AI!**

## 🚀 Overview

**PharmaQuizPro** is a high-performance educational platform designed for pharmacy students and medical professionals. Learning thousands of drug classifications, dosages, and mechanisms is a monumental task PharmaQuizPro solves this by using **Generative AI** to create dynamic, personalized quiz experiences that adapt to your learning needs. 🎯

## 🛠️ Problems It Solves

* **Static Question Banks:** Traditional apps have limited questions. PharmaQuizPro uses AI to generate fresh scenarios every time. 🤖
* **Complex Data Visualization:** Tracks your performance across different pharmaceutical topics so you know exactly where to study more. 📊
* **Exam Anxiety:** Simulates the pressure of real exams like GPAT or NIPER with a timed Quiz Engine. ⏱️
* **Accessibility:** A modern, mobile-responsive interface for learning on the go. 📱
* **Mobile Learning Gaps:** Most platforms are clunky on small screens; we provide a smooth, app-like experience in the browser. 📱

## ✨ Key Features

* **AI-Powered Questions:** Integration with **Gemini Pro** for generating custom pharmaceutical topics. 🧠
* **📱 Mobile First & Highly Optimized:** Engineered for speed and responsiveness. The UI is specifically tailored for a seamless experience on smartphones, ensuring you can study anywhere from the lab to the commute. ⚡
* **Performance Dashboard:** Visual analytics to track your mastery levels. 📈
* **Custom Topic Generation:** Don't see a topic? Type it in, and the AI builds a custom quiz for you. 🛠️
* **Real-time Feedback:** Instant explanations for every answer to ensure active learning. ✅

## 🏗️ Tech Stack

This project is built using:

- 💻 **Frontend**: HTML5, CSS3, JavaScript (ES6+)  
- ⚙️ **Logic**: Custom JavaScript algorithms for question randomization and scoring  
- 📱💻 **Styles**: Responsive design for mobile and desktop viewing  

## 💻 Local Development

Get your development environment up and running in minutes! ⏱️

1. **Clone & Install:**
```bash
git clone https://github.com/tharunkumarmekala/Pharmaquizpro.git
cd Pharmaquizpro
npm install

```

2. **Environment Setup:**
Create a `.env` file in the project root:
```env
GEMINI_API_KEY=your_api_key_here

```

> 💡 **Note:** Ensure your API key is from [Google AI Studio](https://aistudio.google.com/).


3. **Run Dev Server:**
```bash
npm run dev

```

## 🔐 Cloudflare Secrets

When deploying to the edge, keep your API keys secure. Use Wrangler to add your key as an encrypted secret:

```bash
npx wrangler secret put GEMINI_API_KEY

```

*This ensures your key is securely injected into the production environment without being exposed.* 🛡️



## 🌐 Cloudflare Deployment

PharmaQuizPro is optimized for **Cloudflare**, ensuring global low-latency for students everywhere. 🌎

### Deploy Steps

1. **Build the app:**
```bash
npm run build

```


2. **Deploy with Wrangler:**
```bash
npx wrangler deploy

```

## 📂 Project Structure

A detailed map of the **PharmaQuizPro** architecture: 🗺️

```text
Pharmaquizpro/
├── Assets/
│   └── Pharmaquizpro.png
├── src/
│   ├── components/                 # UI Building Blocks 🧱
│   │   ├── CustomTopicCard.tsx     # AI-generated topic cards
│   │   ├── PerformanceDashboard.tsx# User progress & analytics
│   │   ├── QuizEngine.tsx          # The "Brain" of the quiz logic
│   │   ├── QuizSetupModal.tsx      # Configuration for new sessions
│   │   ├── StatsView.tsx           # Visual data representations
│   │   └── TopicCard.tsx           # Standard curriculum categories
│   ├── services/                   # External Integrations 🌐
│   │   └── geminiService.ts        # AI logic to fetch dynamic questions
│   ├── App.tsx                     # Main Layout & State Management 🏠
│   ├── constants.ts                # App-wide fixed values 📋
│   ├── types.ts                    # TypeScript interfaces/types 🏷️
│   └── index.tsx                   # Application entry point 🚀
├── dist/                           # Optimized production build artifacts 📦
├── vite.config.ts                  # Build and Dev server configuration ⚡
├── wrangler.jsonc                  # Cloudflare deployment settings ☁️
├── .env                            # Local environment variables 🤫
└── README.md                       # Documentation 📖

```

## 🤝 Contributing

1. Fork the Project 🍴
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 🚀

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information. 📜

## 📬 Contact

**Tharun Kumar Mekala** - [@tharunkumarmekala](https://www.google.com/search?q=https://github.com/tharunkumarmekala)

*Made with ❤️ for the Pharmacy Community!* 🏥✨

