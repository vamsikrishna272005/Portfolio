# Ex01 Portfolio
## Name: Vamsi Krishna G
## Reg No: 212223220120
## Date:27-04-2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

## index.html

'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Vamsi Krishna Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <header>
        <h2 class="logo">Vamsi</h2>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="section home">
        <h1>Hello, I'm Vamsi Krishna</h1>
        <p>B.Tech IT Student | Python | C | UI/UX Learner</p>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
            I am a B.Tech IT student at Saveetha Engineering College.
            I have knowledge in C, Python, and UI/UX design.
            I enjoy building projects and learning new technologies.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="section">
        <h2>Projects</h2>

        <div class="project-card">
            <h3>Gym Website (Figma)</h3>
            <p>Designed a modern gym website UI using Figma.</p>
        </div>

        <div class="project-card">
            <h3>FSM Enemy AI Game</h3>
            <p>Developed a 2D game AI using Unity FSM logic.</p>
        </div>

        <div class="project-card">
            <h3>Data Analytics Internship</h3>
            <p>Worked on real-world data analysis tasks.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact</h2>
        <p>Email: vamsikrishna272005@email.com</p>
        <p>Phone: 9361800247</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Vamsi Krishna</p>
    </footer>

</body>
</html>

'''

## style.css

'''
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}

/* Navbar */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #222;
    color: white;
    padding: 15px 40px;
    position: sticky;
    top: 0;
}

.logo {
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #00adb5;
}

/* Sections */
.section {
    padding: 60px 40px;
    text-align: center;
}

.home {
    background: linear-gradient(to right, #00adb5, #393e46);
    color: white;
    height: 80vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

/* Projects */
.project-card {
    background: #f4f4f4;
    margin: 15px auto;
    padding: 20px;
    width: 60%;
    border-radius: 10px;
    transition: 0.3s;
}

.project-card:hover {
    transform: scale(1.05);
    background: #e0f7fa;
}

/* Footer */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

'''

## OUTPUT
<img width="1919" height="781" alt="Screenshot 2026-04-27 110726" src="https://github.com/user-attachments/assets/78cedade-3fd2-48db-b7df-67ea9c27a85d" />
<img width="1919" height="868" alt="Screenshot 2026-04-27 110740" src="https://github.com/user-attachments/assets/63d6ce77-fdf0-4be5-b0b5-1ef8abc96d96" />
<img width="1919" height="874" alt="Screenshot 2026-04-27 110801" src="https://github.com/user-attachments/assets/2ba71ce0-0f4b-4c2f-b0ce-b6779749f949" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
