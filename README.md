# 🚀 Auto-Internshala  

**Auto-Internshala** is a backend automation project built with **Node.js** and **Puppeteer** to simplify and streamline interactions with the **Internshala platform**.  
From **automated login** to **job/internship searches** and **data extraction**, Auto-Internshala saves time by managing repetitive tasks programmatically.  

---

## 📑 Table of Contents  
- [Overview](#overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [Folder Structure](#folder-structure)  
- [Contributing](#contributing)
  
---

## 📝 Overview  

Internshala is one of the most popular platforms for internships and jobs, but manual searching and applying can become repetitive and time-consuming.  
**Auto-Internshala** automates these interactions with **Puppeteer**, giving you the ability to:  
- Log in seamlessly  
- Search internships/jobs with filters  
- Extract details like title, company, stipend, and location  
- Save results in structured formats  

This project is highly **configurable** and acts as a foundation for building more advanced automation (e.g., automated applications, custom cover letters).  

---

## ✨ Features  

- 🔐 **Automated Login**: Secure login using environment variables.  
- 🔎 **Smart Search**: Programmatic internship/job search with custom filters.  
- 📊 **Data Extraction**: Extracts details like title, company name, location, stipend, and duration.  
- 💾 **Structured Output**: Save results in JSON or CSV for easy use.  
- ⚙️ **Configurable**: Modify `config.js` to customize filters, output, and scraping logic.  
- 🖥️ **Headless Mode**: Runs silently in the background with Puppeteer.  

---

## 🛠️ Tech Stack  

- **Node.js** → Runtime environment  
- **Puppeteer** → Headless browser automation  

---

## ⚡ Setup & Installation  

### ✅ Prerequisites  
- [Node.js](https://nodejs.org/) (v14.x or later)  
- npm (comes with Node.js)  

### 🔧 Installation Steps  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/auto-internshala.git
   cd auto-internshala

Install dependencies

npm install


Configure environment variables
Create a .env file in the root directory:

INTERNSHALA_USERNAME=your_email@example.com
INTERNSHALA_PASSWORD=your_password


Run the project

node index.js

▶️ Usage

Start the script:

node index.js


The script will automatically:

Log in to your Internshala account

Perform searches based on your config

Extract and save data in output.json (or preferred format)

Customization:

Modify config.js to change filters (profile, location, stipend, etc.)

Adjust output format as per your needs

📂 Folder Structure
auto-internshala/
├── cover.js              # Add your customized cover letter here
├── scripts/              # Puppeteer automation scripts
├── .env                  # Environment variables (username/password)
├── index.js              # Main entry point
└── README.md             # Project documentation

🤝 Contributing

Contributions are welcome!
If you'd like to improve Auto-Internshala:

Fork the repo

Create a feature branch (git checkout -b feature-name)

Commit your changes (git commit -m 'Add new feature')

Push the branch (git push origin feature-name)

Open a Pull Request


🚀 Auto-Internshala — Automate, Extract, and Save Time.


---


