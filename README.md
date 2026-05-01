<div align="center">

# <span id="typing-text"></span>

</div>

<div align="center">

Hi, I'm **Neel de Souza** 👋

A passionate Full-Stack Developer building modern web applications and exploring the intersection of AI and software development.

</div>

---

## 🚀 About Me

I'm a developer focused on creating clean, efficient solutions to real-world problems. Currently diving deep into vector embeddings and search technologies while building interactive web experiences.

- 🔭 Currently working on a vector-based search engine for Project Gutenberg
- 🌱 Learning and experimenting with AI/ML technologies
- 💡 Always exploring new tools and frameworks
- 🎯 Committed to writing clean, maintainable code

---

## 🛠️ Current Projects

### 📚 Vector Search Engine
Building a small-scale search engine on Project Gutenberg's book database using:
- **Python** scripts for data processing
- **Ollama** for vector embeddings
- **PostgreSQL (Supabase)** for vector storage and similarity search

### 🌐 Interactive Business Website
Developing a responsive, interactive website for a small business using:
- **HTML5** & **CSS3** for modern UI/UX
- Clean, accessible design principles

---

## 💻 Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/neel-desouza)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ThatGuyNeel)

</div>

---

<div align="center">

**⭐ Star this repo if you find my work interesting!**

</div>

<script>
  const text = "Full-Stack Developer";
  const typingElement = document.getElementById('typing-text');
  let index = 0;
  
  function typeText() {
    if (index < text.length) {
      typingElement.textContent += text.charAt(index);
      index++;
      setTimeout(typeText, 100);
    } else {
      setTimeout(() => {
        typingElement.textContent = '';
        index = 0;
        typeText();
      }, 2000);
    }
  }
  
  typeText();
</script>
