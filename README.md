🌱 KrushiMitra AI – Intelligent Farming Assistant
📌 About the Project
KrushiMitra AI is a software-only smart farming platform designed to support Indian farmers with data-driven farming decisions.
The platform aims to recommend suitable crops, detect crop diseases from leaf images, and predict crop yield using machine learning. It is designed to help farmers make informed decisions and improve farm productivity without requiring IoT devices or additional hardware.
✨ Key Features
- 🌾 Crop Recommendation – Suggest suitable crops using inputs such as soil nutrients, pH, temperature, humidity, and rainfall.
- 🍃 Crop Disease Detection – Analyze uploaded crop leaf images to identify possible diseases and provide relevant guidance.
- 📈 Yield Prediction – Estimate expected crop yield using available farming and environmental data.
- 💧 Smart Irrigation Advice – Provide irrigation recommendations based on available crop and weather information.
- 🛒 Market Guidance – Help farmers review market-related information when the relevant data source is configured.
- 💰 Profit Analysis – Support basic farming cost and potential-return analysis.
- 🐛 Pest Risk Information – Provide information to help farmers assess potential pest risks.
🛠️ Technologies Used
Technology	Purpose
React.js	Frontend user interface
Python	Machine learning and backend logic
FastAPI / Spring Boot	Backend API framework, depending on the implemented configuration
MySQL	Database management
Machine Learning	Crop recommendation, disease detection, and yield prediction


Use only the backend framework that is actually implemented in your project. If your current backend uses FastAPI, remove Spring Boot from this list.

🎯 Project Objectives
- Help Indian farmers make informed crop-selection decisions.
- Support early identification of possible crop diseases.
- Provide data-driven crop-yield estimates.
- Make farming guidance accessible through a web application.
- Build a software-only solution that does not require IoT devices or special hardware.
🏗️ How It Works
1. The user opens the web application.
2. The user enters farming details or uploads a crop leaf image.
3. The backend processes the submitted information.
4. The machine-learning component generates a prediction or recommendation, where implemented.
5. The application displays the result and relevant farming guidance.
🚀 Getting Started
Prerequisites
Install the tools required by your implementation:
- Node.js and npm
- Python
- MySQL
- Git
- A code editor such as Visual Studio Code
Installation
Step 1: Clone the repository
git clone YOUR_GITHUB_REPOSITORY_URL
cd KrushiMitra-AI
Step 2: Set up the backend
Open a terminal in your backend folder and create a virtual environment:
python -m venv venv
Activate it on Windows:
venv\Scripts\activate
Install the dependencies listed in your project’s requirements.txt file:
pip install -r requirements.txt
Configure the MySQL database connection using your local settings. Do not publish database passwords, API keys, or other secrets.
Step 3: Start the backend
If your backend uses FastAPI and the entry-point file is main.py, run:
uvicorn main:app --reload
If your entry-point file or framework is different, use the command that matches your project structure.
Step 4: Set up the frontend
Open another terminal in your frontend folder and run:
npm install
npm run dev
Open the local URL shown in the terminal.
Note: These commands are a general setup guide. Check your actual folder names, configuration files, and entry-point files before running them.

🔐 Security Notes
- Do not commit database passwords, secret keys, or private email credentials.
- Store sensitive configuration in environment variables or a local .env file.
- Add .env and virtual-environment folders to .gitignore.
- Treat machine-learning outputs as decision-support guidance, not a guarantee of crop health or yield.

🔮 Future Enhancements
- Support for more regional languages.
- More crop and disease categories.
- Weather-based farming recommendations.
- Improved model evaluation using validated datasets.
- Farmer-friendly reports and recommendations.
  
👨‍💻 Project Type
Final-year IT engineering project — software-only web platform using machine learning.
