
## Name: Sethupathi K
## Reg.no: 212223040189

# Ex-01 Portfolio
## Date:13.08.2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Praveen K | Portfolio</title>
    <link rel="stylesheet" href="praveen.css">
</head>
<body>
    <header>
        <h1>Personal Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#internship">Internship</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hero">
            <div class="hero-content">
                <h2>About Me</h2>
                <p>Hi, I'm Praveen K! A 3rd-year B.E ComputerScience and Engineering student with a passion for building Machine Learning and Data Analytics applications. My expertise lies in Data Science and Machine Learning.</p>
            </div>
            <div class="hero-img">
                <img src="./my.png" alt="image">
            </div>
        </div>
    </header>
    

    
    <section id="projects">
        <h2>Projects Ideas</h2>
        <div class="project">
            <div class="project-content">
                <h3>Speech emotion recognition model</h3>
                <p>Create a speech emotion recognition model that classifies emotions from audio recordings.A Speech Emotion Recognition model is a machine learning system designed to analyze audio recordings of human speech and automatically identify the speaker’s emotional state (such as happiness, sadness, anger, fear, or neutrality) based on features extracted from the speech signals like tone, pitch, energy, and rhythm.</p>
            </div>
            <div class="project-image">
                <img src="./ml.png" alt="image" >
            </div>
        </div>
        <div class="project">
            <div class="project-content">
                <h3>AI-driven healthcare diagnosis system</h3>
                <p>Develop an AI-driven healthcare diagnosis system combining genomic, clinical, and imaging data.An AI-driven healthcare diagnosis system is a machine learning or deep learning-based platform that analyzes various types of medical data—such as patient symptoms, clinical records, medical images, lab results, and genomic information—to assist doctors in diagnosing diseases accurately and quickly, often by detecting patterns or anomalies that might be difficult for humans to spot.</p>
            </div>
            <div class="project-image">
                <img src="./DS.png" alt="image">
            </div>
        </div>

        
    </section>
    
    <section id="internship">
         <div class="project intern">
            <div class="project-content">
                <h2>Internship Experience</h2>
                <p><strong> Retech solutions| 2025</strong></p>
                <p>Gained hands-on experience in data science, focusing on predictive modeling, machine learning algorithms, and SAR image colorization using deep learning.My internship experience was an invaluable opportunity to apply theoretical knowledge in a real-world professional environment. During the internship, I was able to work on challenging projects that enhanced my technical skills and problem-solving abilities. I collaborated with experienced team members, which improved my communication and teamwork skills. The hands-on exposure to industry-standard tools and practices deepened my understanding of the field and gave me insights into workplace dynamics. Overall, the internship not only strengthened my professional competence but also boosted my confidence and clarified my career goals.</p>
                
            </div>
            <div class="project-image">
                <img src="./inter.png" alt="image">
            </div>
        </div>
    </section>
    
    
    
    <section id="skills">
        <div class="skills">
            <h2>Skills</h2>
            <h3>Technical Skills</h3>
            <ul >
                <li>Programming: Java, Python, SQL, C Programming </li>
                <li>Web Development: HTML, CSS</li>
                <li>Data Science: Machine Learning, Deep Learning, Data Analysis</li>
                <li>Computer Vision:Image Colorization</li>
            </ul>
            <h3>Soft Skills</h3>
            <ul>
                <li>Communication</li>
                <li>Teamwork</li>
                <li>Problem-Solving</li>
                <li>Leadership</li>
            </ul>
        </div>
        <div class="contact">
            <h2>Contact</h2>
            <p>Email: k.praveenkp2006@gmail.com</p>
            <p>Address: Chennai, India</p>
            <p>Phone: 8015809116</p>
            <p>GitHub: <a href="#">github.com/Praveen</a></p>
            <p>LinkedIn: <a href="#">linkedin.com/in/Praveen</a></p>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Praveen K. All Rights Reserved.</p>
    </footer>
</body>
</html>




```
## praveen.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #3192f4;
    color: white;
    padding: 15px 0;
    text-align: center;
    height: 100vh;
}


nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}
.hero{
    display: flex;
    width: 80%;
    margin: 5rem auto;
    align-items: center;
    border: 1px solid #000;
    border-radius: 10px;
    box-shadow: 0px 0px 20px 5px #0b0b0b74;
}

.hero p{
    margin: 1.5em;
    font-size: 20px;
    font-weight: bold;
}
nav ul li {
    display: inline;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    text-align: center;
}

.project {
    display: flex;
    background-color: #e6f2ff;
    padding: 15px;
    border-radius: 8px;
    margin: 10px auto;
    width:50% ;
    align-items: center;
}

#skills{
    margin: 0 auto;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #0073e6;
    color: white;
    position: relative;
    bottom: 0;
}
.project-image img{
    width:300px;
    height: 300px;
    border-radius: 10px;
}



```
## OUTPUT
<img width="1909" height="1016" alt="Screenshot 2025-08-11 211121" src="https://github.com/user-attachments/assets/812ea784-80e5-4018-a877-08192a7060f0" />
<img width="1919" height="1079" alt="Screenshot 2025-08-11 211210" src="https://github.com/user-attachments/assets/04b56ec2-c16a-4f24-8a35-ca1f72c83efb" />
<img width="1895" height="764" alt="Screenshot 2025-08-11 211222" src="https://github.com/user-attachments/assets/bd9730a4-9c7f-4a72-9433-0da26477140a" />
<img width="1919" height="1079" alt="Screenshot 2025-08-11 211236" src="https://github.com/user-attachments/assets/77ec564a-3554-444e-9924-3c36d7d82f89" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
