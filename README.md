<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 10 Study Hub</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
    <style>
        :root {
            --primary-color: #007bff;
            --secondary-color: #f8f9fa;
            --text-color: #333;
            --background-color: #fff;
        }
        body { 
            font-family: 'Arial', sans-serif; 
            margin: 0; padding: 0; 
            background: var(--background-color);
            color: var(--text-color);
            transition: 0.3s;
        }
        header {
            display: flex; justify-content: space-between; align-items: center; 
            padding: 15px; background: var(--primary-color); color: white;
        }
        nav {
            background: var(--secondary-color); padding: 10px;
        }
        nav ul {
            display: flex; list-style: none; padding: 0; justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none; color: var(--text-color); font-weight: bold;
        }
        main {
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        section {
            padding: 20px; background: var(--secondary-color); border-radius: 8px;
            text-align: center; box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            transition: 0.3s;
        }
        section:hover {
            transform: scale(1.02);
        }
        button {
            background: var(--primary-color); color: white; padding: 10px 15px;
            border: none; cursor: pointer; border-radius: 5px;
        }
        footer {
            text-align: center; padding: 15px; background: var(--primary-color); color: white;
        }
        .dark-mode {
            --background-color: #222;
            --text-color: #fff;
            --secondary-color: #333;
        }
        .dark-mode nav ul li a {
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Class 10 Study Hub</h1>
        <input type="text" id="search-bar" placeholder="Search topics...">
        <button id="dark-mode-toggle"><i class="fas fa-moon"></i></button>
    </header>
    <nav>
        <ul>
            <li><a href="#notes">Study Materials</a></li>
            <li><a href="#quizzes">Quizzes</a></li>
            <li><a href="#videos">Video Lessons</a></li>
            <li><a href="#chatbot">AI Chatbot</a></li>
            <li><a href="#forum">Discussion Forum</a></li>
        </ul>
    </nav>
    <main>
        <section id="notes">
            <h2>📚 Study Materials</h2>
            <p>Download PDFs, notes, and explanations for all subjects.</p>
            <button>Download Notes</button>
        </section>
        <section id="quizzes">
            <h2>📝 Interactive Quizzes</h2>
            <p>Test your knowledge with MCQs and practice tests.</p>
            <button>Start Quiz</button>
        </section>
        <section id="videos">
            <h2>🎥 Video Lessons</h2>
            <p>Learn with text-based videos and infographics.</p>
            <button>View Lessons</button>
        </section>
        <section id="chatbot">
            <h2>🤖 AI Chatbot</h2>
            <p>Ask questions and get instant answers.</p>
            <button>Chat Now</button>
        </section>
        <section id="forum">
            <h2>💬 Discussion Forum</h2>
            <p>Engage with peers and ask questions.</p>
            <button>Join Discussion</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Class 10 Study Hub. All rights reserved.</p>
    </footer>
    <script>
        document.getElementById("dark-mode-toggle").addEventListener("click", function() {
            document.body.classList.toggle("dark-mode");
            this.innerHTML = document.body.classList.contains("dark-mode") ? '<i class="fas fa-sun"></i>' : '<i class="fas fa-moon"></i>';
        });document.getElementById("search-bar").addEventListener("input", function() {
        let query = this.value.toLowerCase();
        let sections = document.querySelectorAll("main section");
        sections.forEach(section => {
            section.style.display = section.innerText.toLowerCase().includes(query) ? "block" : "none";
        });
    });
</script>
</body>
</html>
