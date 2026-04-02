# Personal-Portfolio-website
This project is a personal portfolio website developed as part of the Coursera Final Project submission.  It demonstrates frontend development skills using HTML, CSS, and JavaScript.

# 🌐 Personal Portfolio Website

## 📌 Overview
This project is a **Personal Portfolio Website** developed using **HTML, CSS, and JavaScript**. It serves as a digital platform to showcase my skills, projects, achievements, and contact details in a structured and visually appealing manner.

The website is fully responsive and interactive, designed to provide a smooth user experience while demonstrating strong front-end development skills.

## 🎯 Purpose of the Project
The main objectives of this project are:

- To create a professional online presence
- To demonstrate front-end web development skills
- To showcase technical projects and achievements
- To practice responsive design and UI/UX concepts
- To implement dynamic functionality using JavaScript

## 🚀 Key Features

### 🔹 1. Responsive Navigation Bar
- Sticky navigation bar for easy access
- Smooth scrolling between sections
- Clean and modern UI design

### 🔹 2. About Me Section
- Displays profile image (embedded using Base64)
- Includes introduction, contact details, and career focus
- Highlights interest in Web Development and AI

### 🔹 3. Skills Section
- Visual representation of technical skills
- Uses icons for better user experience
- Displays experience level for each skill

### 🔹 4. Projects Section
- Showcases multiple projects with descriptions
- Structured in card format for clarity
- Easy to extend with additional projects

### 🔹 5. Recommendations & Reviews
- Includes predefined testimonials
- Displays star-based reviews
- Enhances credibility and presentation

### 🔹 6. Dynamic Recommendation System
- Users can submit recommendations
- Implemented using JavaScript DOM manipulation
- New recommendations are added instantly to the UI

### 🔹 7. Scroll-to-Top Button
- Improves navigation experience
- Smooth scrolling functionality


## 🛠️ Technologies Used

| Technology   | Purpose |
|-------------|--------|
| HTML5       | Structure of the website |
| CSS3        | Styling and layout design |
| JavaScript  | Interactivity and dynamic features |
| Google Colab| Development and execution environment |
| Base64 Encoding | Embedding images directly into HTML |


## 🧠 Concepts Applied

- Semantic HTML structure
- CSS Flexbox and responsive design
- DOM manipulation in JavaScript
- Event handling
- UI/UX design principles
- Base64 image embedding


portfolio-website/
│
├── index.html # Main file containing structure, styling, and script
├── assets/ # (Optional) Images and icons
└── README.md # Project documentation


---

## ⚙️ How to Run the Project

### 🔹 Method 1: Run Locally
1. Download or clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio.git

   function addRecommendation() {
    var text = document.getElementById("newRecommendation").value.trim();
    if(text !== "") {
        var div = document.createElement("div");
        div.className = "recommendation-box new-recommendation";
        div.textContent = text;
        document.querySelector(".recommendation-table").appendChild(div);
        document.getElementById("newRecommendation").value = "";
        alert("Recommendation submitted successfully!");
    }
}

Advantages
Simple and clean user interface
Fully responsive design
Interactive elements using JavaScript
No external dependencies required
Easy to customize and extend

 Limitations
No backend integration
Data is not stored permanently
No authentication system
Limited scalability for large applications

🔮 Future Enhancements
🔐 Add authentication system (Login/Signup)
🗄️ Integrate database (MySQL/MongoDB)
🌐 Deploy using GitHub Pages / Netlify
⚡ Add animations using advanced CSS/JS
🤖 Integrate AI chatbot (based on your ongoing project)
📊 Add analytics dashboard
🌍 Deployment 

👩‍💻 Author
Kristi Roy
🎓 B.Tech CSE (Health Informatics Engineering), VIT Bhopal
💻 Web Developer & AI Enthusiast
📧 Email: kristi.24bhi10113@vitbhopal.ac.in
🔗 LinkedIn: www.linkedin.com/in/kristi-roy-889099324

📜 License
This project is created for educational and personal portfolio purposes.

⭐ Acknowledgment
This project was developed as part of learning Web Development (HTML, CSS, JavaScript) and demonstrates practical implementation of front-end concepts.


## 📂 Project Structure

