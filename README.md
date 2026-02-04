# Ex01 Portfolio
## Date: 04.02.2026

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
## HTML
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kishore M | Portfolio</title>
    <link rel="stylesheet" href="xz.css">
</head>
<body>

    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>I'm a Passionate Software Developer</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>
            I am <strong>Kishore M</strong>, a 3rd-year B.E Computer Science Engineering student
            with a strong passion for software development. I have experience in Python,
            Java, and web development. I enjoy building efficient, scalable, and
            user-friendly applications, including web solutions, backend systems,
            and automation scripts.
            <br><br>
            With a solid foundation in object-oriented programming and full-stack
            development, I love creating innovative solutions to real-world problems.
            I am always eager to learn new technologies and continuously improve my skills.
        </p>

        <img class="profile-img" src="pp .JPG" alt="KISHORE M" height="250px">


        <h3 class="name">KISHORE M</h3>
    </section>

    <section id="skills">
        <h2>Skills</h2>

        <h3>Technical Skills</h3>
        <ul>
            <li>Programming Languages: Python, Java, JavaScript</li>
            <li>Web Development: HTML, CSS, React.js</li>
            <li>Data Science: Machine Learning, Deep Learning</li>
        </ul>

        <h3>Soft Skills</h3>
        <ul>
            <li>Communication</li>
            <li>Teamwork</li>
            <li>Problem Solving</li>
            <li>Leadership</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>
            Currently, I am learning new concepts and actively developing my skills.
            I am working on academic and personal projects to strengthen my practical knowledge.
        </p>
    </section>

    <footer>
        <p>Contact Me</p>
        <p>Email: <a href="mailto:nazkishore18@gmail.com">nazkishore18@gmail.com</a></p>
    </footer>

</body>
</html>
```

### CSS
```

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f6f8;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 30px 20px;
}

header h1 {
    margin-bottom: 10px;
}

section {
    background-color: white;
    margin: 20px auto;
    padding: 25px;
    width: 80%;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.profile-img {
    display: block;
    margin: 10px auto;
    border-radius: 10%;
    border: 1px solid #2c3e50;
    object-fit:scale-down;
}

.name {
    text-align: center;
    color: #2c3e50;
    margin-top: 10px;
}

h2 {
    color: #2c3e50;
    margin-bottom: 15px;
}

h3 {
    margin-top: 20px;
    margin-bottom: 10px;
}

ul {
    margin-left: 20px;
}

ul li {
    margin-bottom: 8px;
}

#projects p {
    text-align: center;
}

footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}

footer a {
    color: #1abc9c;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
```
## OUTPUT

<img width="1862" height="916" alt="Screenshot 2026-02-04 214415" src="https://github.com/user-attachments/assets/100a5313-1a3e-4398-abb4-173fb1df3207" />

<img width="1683" height="916" alt="Screenshot 2026-02-04 214513" src="https://github.com/user-attachments/assets/de71c405-ff74-441b-ac95-7db1e3f7082f" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
