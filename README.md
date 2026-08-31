# ⚖️ BMI Calculator

A simple and responsive **BMI (Body Mass Index) Calculator** built with **React.js and Vite**. The application allows users to enter their height and weight and instantly calculates their BMI with the corresponding BMI category.

## 📌 Project Overview

The **BMI Calculator** is a frontend web application developed using React.js.

The application accepts the user's height and weight, performs the BMI calculation, and dynamically displays the calculated result and its corresponding category.

This project was developed to practice **React components, state management, user input handling, conditional rendering, and responsive UI development**.

---

## ✨ Features

* ⚖️ Calculate Body Mass Index (BMI)
* 📏 Accept height input
* 🏋️ Accept weight input
* ⚡ Instant BMI calculation
* 📊 Display BMI result
* 📋 Display corresponding BMI category
* 🔄 Dynamic UI updates
* 📱 Responsive user interface
* ✅ Simple and user-friendly design

---

## 🧮 BMI Formula

The BMI is calculated using:

```text
BMI = Weight (kg) / Height² (m)
```

For example:

```text
Weight = 70 kg
Height = 1.75 m

BMI = 70 / (1.75 × 1.75)
    = 22.86
```

### BMI Categories

| BMI Range      | Category      |
| -------------- | ------------- |
| Below 18.5     | Underweight   |
| 18.5 – 24.9    | Normal Weight |
| 25.0 – 29.9    | Overweight    |
| 30.0 and above | Obese         |

> BMI is a general screening measure and should not be treated as a medical diagnosis.

---

## 🔄 Application Workflow

```text
        Enter Height
             │
             ▼
        Enter Weight
             │
             ▼
       Validate Input
             │
             ▼
       Calculate BMI
             │
             ▼
      Display BMI Value
             │
             ▼
      Display Category
```

---

## 🛠️ Technology Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Build Tool

* Vite

### Development Tools

* Git
* GitHub
* VS Code
* ESLint

---

## 🏗️ Project Structure

```text
BMI-calculator/
│
├── public/
│
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/gowtham250211-png/BMI-calculator.git
```

### 2. Navigate to the Project

```bash
cd BMI-calculator
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

Open the local URL provided by Vite in your browser.

---

## 📦 Production Build

Create a production-ready build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Building React components
* Managing user input with React
* Using state to store and update values
* Performing calculations based on user input
* Conditional rendering
* Handling form interactions
* Creating responsive frontend interfaces
* Using Vite for React development
* Managing source code with Git and GitHub

---

## 🔮 Future Enhancements

* 📊 BMI history tracking
* 📈 BMI progress visualization
* 🌙 Dark/light mode
* 📱 Improved mobile interface
* 💾 Local storage for previous calculations
* 🎨 Improved BMI range visualization
* 🔄 Reset calculation option

---

## 👨‍💻 Author

### Gowtham G

**B.Tech – Artificial Intelligence and Data Science**

**Full Stack Java Developer**

* GitHub: https://github.com/gowtham250211-png
* LinkedIn: https://linkedin.com/in/gowtham-g299132308

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐.

**Repository:**
https://github.com/gowtham250211-png/BMI-calculator
