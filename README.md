🧠 EXAM DUDE – AI Exam Mentor
AI-powered Important Question Generator for Anna University Students

url of the web- https://varunraj03676.github.io/Exam_dude/ 

EXAM DUDE is a simple demo AI exam assistant that helps students quickly get important questions based on the Anna University syllabus.
The demo version supports 100 predictions only.

This project uses:

Flowise AI (backend logic & AI responses)

HTML + CSS (frontend design)

Flowise API URL for backend integration

🚀 Features

✔️ AI-powered exam mentor

✔️ Generates important questions for Anna University

✔️ First 100 predictions are free (demo limit)

✔️ Lightweight, fast frontend

✔️ Easy integration using Flowise API

✔️ Clean and modern UI

✔️ Mobile-friendly interface

✔️ Beginner-friendly project structure

🏗️ Tech Stack
Layer	Technology
AI Backend	Flowise AI
Frontend	HTML, CSS, JavaScript
API Communication	Flowise REST API

Deployment	GitHub Pages / Static Hosting
📁 Project Structure
/exam-dude
│
├── one.html        # Main UI
└── README.md         # Project documentation

🔌 How It Works

User types a question/topic.

Frontend sends the user message to Flowise backend using the API URL.

Flowise AI generates important questions based on the Anna University syllabus.

The response appears inside the chat interface.

🧪 Demo Limitations

This demo allows only 100 total predictions (Flowise default).

For unlimited usage, deploy your own Flowise instance or upgrade your plan.

⚙️ Setup Instructions
1. Clone this repository
git clone https://github.com/Varunraj03676/Exam-dude.git

2. Configure Flowise API URL

Inside script.js, update:

const API_URL = "https://cdn.jsdelivr.net/npm/flowise-embed@<version>/dist/web.js";

🛠️ Future Improvements

Add user login

Save chat history

Add PDF export for questions

Better animations and UI

Support for more universities

Dark & light theme switch

🤝 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request to improve the project.

📜 License

Released under the MIT License.
You are free to modify and use it.
