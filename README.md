# NutriVision Pro 🥗📸

> AI-powered nutrition analysis platform with food recognition, meal planning, and smart dietary assistance using Google Gemini AI.
> - vercel:https://nutrivison-pro.vercel.app/

---

## 🌟 Overview

NutriVision Pro is an intelligent nutrition and diet management platform that helps users make healthier food decisions through AI-powered analysis.

The application allows users to:
- Analyze food using images
- Get detailed nutritional information
- Generate personalized meal plans
- Search food nutrition instantly
- Chat with an AI nutrition assistant
- Track food analysis history

Built using **Flask**, **MongoDB Atlas**, and **Google Gemini 2.5 Flash**, the project combines AI, nutrition science, and modern web technologies into one smart platform.

---

# 🚀 Features

## 🔐 Authentication System

Secure user authentication system with:
- User Registration
- Login & Logout
- Session Management
- Personalized User Dashboard

---

## 📷 AI Food Analyzer

Upload or capture food images and receive instant nutritional analysis.

### Features
- AI-powered food recognition
- Nutritional breakdown
- Calorie estimation
- Macronutrient analysis
- Nearby food place recommendations

### Nutritional Information Includes
- Calories
- Protein
- Carbohydrates
- Fat
- Fiber
- Vitamins & minerals (if available)

---

## 🍽 Personalized Meal Planner

Generate meal plans tailored to user goals and dietary preferences.

### User Inputs
- Goal
  - Weight Loss
  - Maintenance
  - Muscle Gain

- Diet Type
  - Balanced
  - Vegetarian
  - Vegan
  - High Protein

- Meals Per Day
- Daily Calorie Target
- Allergies / Restrictions
- Preferred Cuisines

### Output
- Breakfast
- Lunch
- Dinner
- Snacks
- Daily calorie distribution
- Personalized recommendations

---

## 🔎 Food Search Feature

Search nutritional information for any food item instantly.

### Inputs
- Food Name
- Serving Size (grams)

### Results
- Calories
- Protein
- Carbohydrates
- Fat
- Fiber

---

## 🤖 Gemini Nutrition Assistant

AI-powered chatbot built using Google Gemini 2.5 Flash.

### Capabilities
- Nutrition guidance
- Healthy meal suggestions
- Macro planning
- Healthier food alternatives
- Dietary education
- Personalized food advice

### Example Questions
- “What should I eat for muscle gain?”
- “Healthy Indian breakfast ideas?”
- “How much protein do I need daily?”
- “Best foods for weight loss?”

---

## 🕘 Analysis History

Store and manage previous food analyses.

### Features
- View previous scans
- Check nutrition breakdowns
- Delete old entries
- User-specific history management

---

# 🛠 Technology Stack

## Backend

| Technology | Purpose |
|---|---|
| Python 3.8+ | Core Language |
| Flask 2.0+ | Backend Framework |
| Google Gemini 2.5 Flash | AI Processing |
| MongoDB Atlas | Cloud Database |
| Pillow (PIL) | Image Processing |
| python-dotenv | Environment Variables |

---

## Frontend

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript (ES6+) | Interactivity |
| Font Awesome 6.4 | Icons |
| Google Fonts (Poppins) | Typography |

---

## Infrastructure

| Service | Purpose |
|---|---|
| Flask Development Server | Backend Hosting |
| MongoDB Atlas | Cloud Storage |
| Google Generative AI API | AI Integration |
| GridFS/Base64 | Image Storage |

---

# 📂 Project Structure

```bash
nutrivision-pro/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── uploads/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   └── ...
│
├── routes/
├── models/
├── utils/
├── app.py
├── requirements.txt
├── .env
└── README.md
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Harshraj0106/nutrivison-pro.git

cd nutrivison-pro
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configure Environment Variables

Create a `.env` file in the root directory.

```env
MONGO_URI=your_mongodb_connection_string

GEMINI_API_KEY=your_google_gemini_api_key

SECRET_KEY=your_secret_key
```

---

## 5️⃣ Run the Application

```bash
python app.py
```

Server will start at:

```bash
http://127.0.0.1:5000
```

---

# 🧠 How It Works

## Food Analysis Workflow

```text
User Uploads Food Image
           ↓
Image Processed with PIL
           ↓
Gemini AI Identifies Food
           ↓
Nutrition Data Generated
           ↓
Results Stored in MongoDB
           ↓
Nearby Food Suggestions Displayed
```

---

# 🔒 Security Features

- Secure authentication system
- Protected environment variables
- MongoDB cloud security
- User-specific data storage
- Session management

---

# 📸 Screenshots

Add screenshots here.

 <img width="1060" height="578" alt="Screenshot 2026-05-16 152409" src="https://github.com/user-attachments/assets/ac0b0b38-4b31-44a3-a66c-be55d78d555d" />


<img width="754" height="812" alt="Screenshot 2026-05-16 152343" src="https://github.com/user-attachments/assets/3911e8d1-e302-4e39-86ad-41b4eedbde3b" />


(screenshots/analyzer.png)<img width="1028" height="896" alt="Screenshot 2026-05-16 151933" src="https://github.com/user-attachments/assets/327c8c1b-16d7-4c7e-81bb-0bbaf965da19" />
<img width="1013" height="905" alt="Screenshot 2026-05-16 151948" src="https://github.com/user-attachments/assets/b7848698-a7bc-4837-be09-bfa135f8ac70" />



<img width="1036" height="892" alt="Screenshot 2026-05-16 152058" src="https://github.com/user-attachments/assets/360fbd0f-d94f-4282-a613-25ffa9e520c7" />


<img width="1027" height="887" alt="Screenshot 2026-05-16 152148" src="https://github.com/user-attachments/assets/ed7f5dbc-12c4-47cc-9d62-7ba4ab2dd83b" />


<img width="1008" height="745" alt="Screenshot 2026-05-16 152253" src="https://github.com/user-attachments/assets/43010e98-0f48-4889-828f-9c0710a2b63a" />


<img width="992" height="514" alt="Screenshot 2026-05-16 152316" src="https://github.com/user-attachments/assets/05cfbfdb-5307-4906-98cd-f5b0fb7119f5" />



---

# 🎯 Future Enhancements

- Real-time camera food detection
- Barcode scanner integration
- Mobile application
- AI workout recommendations
- Fitness tracker integration
- Multi-language support
- Dark mode support

---

# 🧪 Example Use Cases

### Weight Loss
Generate calorie-controlled meal plans with balanced nutrition.

### Muscle Gain
Receive high-protein meal recommendations and macro guidance.

### Nutrition Tracking
Track meals and revisit previous analyses.

### Smart Dietary Guidance
Get AI-powered suggestions for healthier eating.

---

# 🤝 Contributing

Contributions are welcome.

### Steps
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Harshraj

- GitHub: https://github.com/Harshraj0106
- Project Repository: https://github.com/Harshraj0106/nutrivison-pro
- vercel:https://nutrivison-pro.vercel.app/

---

# ⭐ Support

If you like this project:

⭐ Star the repository  
🍴 Fork the project  
🛠 Contribute improvements

---

# 🥗 NutriVision Pro

### *“Transforming food into intelligent nutritional insights with AI.”*
