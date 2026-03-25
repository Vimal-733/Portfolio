# Ex01 Portfolio
## Date:18.03.2026

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

### index.html

```


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <h2 class="logo">Portfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home" class="home">
        <h1>Hi, I'm <span>vimal a</span></h1>
        <p>212224240183</p>
        <p>java  Developer | Student</p>
    </section>
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>
        Hello! I’m <strong>Eshwer M</strong>, a passionate and motivated student
        with a strong interest in web development. I enjoy designing and
        developing clean, user-friendly websites using modern web technologies.
    </p>

    <p>
        I am currently learning HTML, CSS, and JavaScript, and I focus on
        building responsive and visually appealing web pages. I like exploring
        new tools and improving my problem-solving skills through practical
        projects.
    </p>

    <p>
        My goal is to become a skilled full-stack web developer and contribute
        to real-world applications. I am always eager to learn, adapt, and grow
        in the field of web development.
    </p>
    </section>
    <section id="skills" class="skills">
        <h2>My Skills</h2>
        <ul>
            <li><strong>aiml</strong></li>
            <li><strong>machine leaning</STRONG></li>
            <li><strong>JavaScript</strong></li>
            <li><strong>Python</strong></li>
            <li><strong>C Programming</strong></li>
        </ul>
    </section>
    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-box">Portfolio Website</div>
        <div class="project-box">Student Management System</div>
        <div class="project-box">Simple Calculator</div>
    </section>
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: vimalvimal9386@gmail.com</p>
        <p>Github: vimal.github</p>
        <p>Phone: 7339336032</p>
    </section>

    

</body>
</html>

```

### style.css

```
/* Body */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;   /* Dark blue background */
    color: #ffffff;
}

/* Navigation bar */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
    background: linear-gradient(90deg, #1e3a8a, #7c3aed); /* Blue to Purple */
}

.logo {
    color: #ffffff;
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline-block;
    margin-left: 20px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #38bdf8;  /* Light blue hover */
}

/* Home section */
.home {
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: center;
    background: linear-gradient(135deg, #1e3a8a, #9333ea); /* Blue-Purple gradient */
}

.home h1 {
    font-size: 40px;
    color: #ffffff;
}

.home span {
    color: #38bdf8;  /* Highlight name */
}

/* About */
.about {
    background-color: #1e293b;
    padding: 40px;
}

/* Skills */
.skills {
    background-color: #0f172a;
    padding: 40px;
}

/* Projects */
.projects {
    background-color: #1e293b;
    padding: 40px;
}

.project-box {
    background-color: #334155;
    margin: 10px;
    padding: 15px;
    border-radius: 8px;
    color: #38bdf8;
}

/* Contact */
.contact {
    background-color: #0f172a;
    padding: 40px;
}
```

### output

<img width="1920" height="1200" alt="Screenshot 2026-02-18 143920" src="https://github.com/user-attachments/assets/90055c75-f033-4fc3-9f58-f3542c49b750" />

<img width="1860" height="979" alt="Screenshot 2026-02-18 143642" src="https://github.com/user-attachments/assets/e6dfde29-4228-406c-9536-c366b0141d6e" />

###  RESULT

The program for creating Portfolio using HTML and CSS is executed successfully.
