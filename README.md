# MDAP-EX_01-Portfolio
## Date: 09.08.2025

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
# html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Reshma's Portfolio</title>
    <link rel="stylesheet" href="style.css" />
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="logo">Reshma</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#learning">Learning</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <section class="hero">
            <h1>Hello, I'm <span>Reshma</span></h1>
            <p>A Web Developer & Designer</p>
            <a href="#learning" class="btn">What I'm Learning</a>
        </section>
    </header>

    <main>
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>
                I'm Reshma, a passionate developer who enjoys building beautiful, functional websites. I'm currently focusing on front-end development and love learning new web technologies every day.
            </p>
        </section>

        <section id="learning" class="projects">
            <h2>What I'm Learning</h2>
            <div class="project-list">
                <div class="project">
                    <h3>HTML & CSS</h3>
                    <p>Learning how to structure web pages and style them to create visually appealing designs.</p>
                </div>
                <div class="project">
                    <h3>Responsive Design</h3>
                    <p>Practicing how to make websites look great on mobile, tablet, and desktop screens.</p>
                </div>
                <div class="project">
                    <h3>JavaScript (Coming Soon)</h3>
                    <p>Planning to learn JavaScript to build interactive features like sliders, forms, and animations.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>You can reach me via:</p>
    <ul class="contact-list">
        <li>Email: <a href="mailto:reshmachellapandi@gmail.com">reshmachellapandi@gmail.com</a></li>
        <li>Github: <a href="RESHMA22C" target="_blank">RESHMA22C</a></li>
    </ul>
</section>

    </main>

    <footer>
        <p>&copy; 2025 Reshma. All rights reserved.</p>
    </footer>
</body>
</html>
~~~

# CSS 
~~~
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f5f5f5;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #111;
    padding: 1rem 2rem;
    color: white;
}

.navbar .logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.navbar .nav-links {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

.navbar .nav-links a {
    color: white;
    text-decoration: none;
    font-weight: 500;
}

.navbar .nav-links a:hover {
    color: #00bcd4;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 5rem 2rem;
    background: linear-gradient(to right, #00bcd4, #2196f3);
    color: white;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero span {
    color: #ffe082;
}

.hero .btn {
    display: inline-block;
    margin-top: 1.5rem;
    padding: 0.75rem 1.5rem;
    background: white;
    color: #2196f3;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
}

.hero .btn:hover {
    background: #f0f0f0;
}

/* Sections */
section {
    padding: 4rem 2rem;
    max-width: 1000px;
    margin: auto;
}

h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    text-align: center;
    color: #2196f3;
}

.project-list {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
}

.project {
    background: white;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

/* Contact */
.contact a {
    color: #2196f3;
    text-decoration: none;
    font-weight: bold;
}

.contact a:hover {
    text-decoration: underline;
}

.contact-list {
    list-style: none;
    padding: 1rem 0;
    line-height: 2;
    font-size: 1.1rem;
}

/* Footer */
footer {
    text-align: center;
    padding: 2rem;
    background: #111;
    color: white;
    margin-top: 2rem;
}

/* Responsive */
@media (max-width: 768px) {
    .project-list {
        grid-template-columns: 1fr;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .navbar .nav-links {
        flex-direction: column;
        gap: 1rem;
    }
}
~~~


## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/724861b3-de7f-41f5-8487-af973e118370" />

<img width="1277" height="518" alt="image" src="https://github.com/user-attachments/assets/e606f0fb-dd2a-48cd-a47b-08b16d3a7260" />


<img width="1186" height="266" alt="image" src="https://github.com/user-attachments/assets/a4fa7a72-b839-41e4-b5c3-490edf4269ac" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
