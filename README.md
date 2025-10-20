<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swapneil Basutkar - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: #fff;
        min-height: 100vh;
        padding: 20px;
    }

    .container {
        max-width: 1000px;
        margin: 0 auto;
        background: rgba(255, 255, 255, 0.1);
        backdrop-filter: blur(10px);
        border-radius: 20px;
        padding: 40px;
        box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
    }

    .header {
        text-align: center;
        margin-bottom: 40px;
    }

    .header h1 {
        font-size: 3em;
        margin-bottom: 10px;
        animation: fadeInDown 1s ease;
    }

    .header .wave {
        display: inline-block;
        animation: wave 2s infinite;
    }

    @keyframes wave {
        0%, 100% { transform: rotate(0deg); }
        25% { transform: rotate(20deg); }
        75% { transform: rotate(-20deg); }
    }

    .header h2 {
        font-size: 1.5em;
        font-weight: 300;
        color: #e0e0e0;
        animation: fadeInUp 1s ease 0.3s both;
    }

    .typing-text {
        font-size: 1.2em;
        color: #ffd700;
        margin-top: 20px;
        min-height: 30px;
        animation: fadeInUp 1s ease 0.6s both;
    }

    @keyframes fadeInDown {
        from {
            opacity: 0;
            transform: translateY(-20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    .divider {
        height: 2px;
        background: linear-gradient(90deg, transparent, #fff, transparent);
        margin: 30px 0;
    }

    .section {
        margin-bottom: 40px;
    }

    .section h3 {
        font-size: 2em;
        margin-bottom: 20px;
        text-align: center;
    }

    .about-content {
        background: rgba(255, 255, 255, 0.05);
        padding: 20px;
        border-radius: 10px;
        line-height: 1.8;
    }

    .about-content p {
        margin-bottom: 10px;
        font-size: 1.1em;
    }

    .tech-stack {
        margin-top: 30px;
    }

    .tech-category {
        margin-bottom: 30px;
    }

    .tech-category h4 {
        font-size: 1.3em;
        margin-bottom: 15px;
        text-align: center;
        color: #ffd700;
    }

    .badges {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        justify-content: center;
        align-items: center;
    }

    .badges img {
        height: 32px;
        transition: transform 0.3s ease;
    }

    .badges img:hover {
        transform: scale(1.1);
    }

    .contact {
        text-align: center;
        margin-top: 40px;
    }

    .contact-buttons {
        display: flex;
        gap: 20px;
        justify-content: center;
        flex-wrap: wrap;
        margin-top: 20px;
    }

    .contact-btn {
        display: inline-flex;
        align-items: center;
        gap: 10px;
        padding: 12px 30px;
        background: rgba(255, 255, 255, 0.2);
        border: 2px solid #fff;
        border-radius: 25px;
        color: #fff;
        text-decoration: none;
        font-weight: 600;
        transition: all 0.3s ease;
    }

    .contact-btn:hover {
        background: #fff;
        color: #667eea;
        transform: translateY(-3px);
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    }

    .quote {
        text-align: center;
        font-style: italic;
        font-size: 1.2em;
        margin-top: 40px;
        color: #ffd700;
    }

    @media (max-width: 768px) {
        .header h1 {
            font-size: 2em;
        }

        .header h2 {
            font-size: 1.2em;
        }

        .container {
            padding: 20px;
        }
    }
</style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1><span class="wave">👋</span> Hi, I'm Swapneil Basutkar</h1>
            <h2>Machine Learning Enthusiast & Backend Developer</h2>
            <div class="typing-text" id="typingText"></div>
        </div>
    <div class="divider"></div>

    <div class="section">
        <h3>🚀 About Me</h3>
        <div class="about-content">
            <p>🔭 Currently working with <strong>Robot Framework</strong>, <strong>LLMs</strong>, and <strong>AWS</strong></p>
            <p>💡 Passionate about building intelligent systems and scalable backend solutions</p>
            <p>📫 Let's connect: <strong>swapneilbasutkar02@gmail.com</strong></p>
        </div>
    </div>

    <div class="divider"></div>

    <div class="section tech-stack">
        <h3>🛠️ Tech Stack</h3>
        
        <div class="tech-category">
            <h4>Languages</h4>
            <div class="badges">
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
                <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
                <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
                <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
                <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
            </div>
        </div>

        <div class="tech-category">
            <h4>Frameworks & Libraries</h4>
            <div class="badges">
                <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
                <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
                <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
                <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn"/>
            </div>
        </div>

        <div class="tech-category">
            <h4>Cloud & Tools</h4>
            <div class="badges">
                <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
                <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
                <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
            </div>
        </div>
    </div>

    <div class="divider"></div>

    <div class="quote">
        "Building the future, one commit at a time" 💻
    </div>

    <div class="contact">
        <div class="contact-buttons">
            <a href="mailto:swapneilbasutkar02@gmail.com" class="contact-btn">
                📧 Email Me
            </a>
            <a href="https://linkedin.com/in/yourprofile" class="contact-btn" target="_blank">
                💼 LinkedIn
            </a>
            <a href="https://github.com/yourusername" class="contact-btn" target="_blank">
                💻 GitHub
            </a>
        </div>
    </div>
</div>

<script>
    const texts = [
        "Building with LLMs & AWS",
        "Robot Framework Developer",
        "Full Stack Engineer"
    ];
    let textIndex = 0;
    let charIndex = 0;
    let isDeleting = false;
    const typingElement = document.getElementById('typingText');

    function type() {
        const currentText = texts[textIndex];
        
        if (isDeleting) {
            typingElement.textContent = currentText.substring(0, charIndex - 1);
            charIndex--;
        } else {
            typingElement.textContent = currentText.substring(0, charIndex + 1);
            charIndex++;
        }

        if (!isDeleting && charIndex === currentText.length) {
            setTimeout(() => isDeleting = true, 2000);
        } else if (isDeleting && charIndex === 0) {
            isDeleting = false;
            textIndex = (textIndex + 1) % texts.length;
        }

        const typingSpeed = isDeleting ? 50 : 100;
        setTimeout(type, typingSpeed);
    }

    type();
</script>
</body>
</html>
