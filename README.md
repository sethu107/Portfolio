
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
### Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Sethupathi | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="logo">S<span>.</span></div>
        <nav class="nav">
            <a href="#hero">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#timeline">Journey</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="hero">
    <div class="hero-content">
        <p class="hero-tag">3rd Year Engineering • DSA & CP</p>
        <h1>Hi, I'm <span class="highlight">Sethupathi K</span></h1>
        <p class="hero-subtitle">
            I’m a 3rd-year engineering student who enjoys building web apps,
            experimenting with AI, and sharpening my <strong>C, C++, Java, and JavaScript</strong> skills through
            projects and DSA / CP practice.
        </p>
        <div class="hero-actions">
            <a href="#projects" class="btn primary">View My Projects</a>
            <a href="#contact" class="btn ghost">Contact Me</a>
        </div>
    </div>

    <!-- ADD THIS NEW PHOTO CARD -->
    <div class="hero-photo professional-photo">
        <img src="profile.jpg" alt="Sethupathi Photo">
    </div>
</section>


        <!-- About Section -->
        <section id="about" class="section">
            <h2 class="section-title">About Me</h2>
            <div class="section-content about-grid">
                <div>
                    <p>
                        I’m a <strong>3rd-year student at Saveetha Engineering College, Thandalam</strong>.
                        I like learning by building small, focused projects and solving coding problems.
                    </p>
                    <ul class="bullet-list">
                        <li>Hands-on practice with web apps using HTML, CSS, and JavaScript</li>
                        <li>Exploring AI / ML basics through projects like DocGuard</li>
                        <li>Improving problem-solving with DSA & competitive programming</li>
                    </ul>
                    <p>
                        My goal is to become a solid software engineer who can write clean code,
                        understand system behaviour, and build useful tools.
                    </p>
                </div>
                <div class="about-card">
                    <h3>Current Focus</h3>
                    <ul>
                        <li>Strengthening core DSA concepts topic-wise</li>
                        <li>Building real-world style projects for my portfolio</li>
                        <li>Preparing for tech interviews and coding rounds</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="section section-alt">
            <h2 class="section-title">Skills</h2>
            <div class="chips">
                <span class="chip">C</span>
                <span class="chip">C++</span>
                <span class="chip">Java</span>
                <span class="chip">HTML</span>
                <span class="chip">CSS</span>
                <span class="chip">JavaScript</span>
                <span class="chip">Data Structures</span>
                <span class="chip">Algorithms</span>
                <span class="chip">Competitive Programming</span>
                <span class="chip">Basic Machine Learning</span>
                <span class="chip">AI / NLP (Beginner)</span>
                <span class="chip">Git & GitHub</span>
                <span class="chip">VS Code</span>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="section">
            <h2 class="section-title">Projects</h2>
            <div class="cards-grid">

                <!-- Project 1: DocGuard -->
                <article class="card">
                    <h3>DocGuard – AI PDF Similarity Detector</h3>
                    <p class="card-tag">AI • NLP • PDF Processing</p>
                    <p>
                        DocGuard is a tool that detects similarity between two PDF documents
                        using text extraction and AI-based comparison. It can be used for
                        basic plagiarism detection or checking overlap between reports.
                    </p>
                    <ul class="card-list">
                        <li>Extracts text from PDF files for analysis.</li>
                        <li>Uses NLP-style similarity logic to compare documents.</li>
                        <li>Designed for academic / internal document comparison use cases.</li>
                    </ul>
                    <p class="card-status">Status: <span>Active Development</span></p>
                    <div class="project-links">
                        <a class="btn ghost small" href="https://github.com/sethupathi107" target="_blank">GitHub (Profile)</a>
                    </div>
                </article>

                <!-- Project 2: To-Do List -->
                <article class="card">
                    <h3>Smart To-Do List Web App</h3>
                    <p class="card-tag">HTML • CSS • JavaScript</p>
                    <p>
                        A simple and responsive to-do list app that helps users keep track
                        of tasks directly in the browser using JavaScript and LocalStorage.
                    </p>
                    <ul class="card-list">
                        <li>Add, mark as complete, and remove tasks easily.</li>
                        <li>Tasks are stored in browser storage (no backend).</li>
                        <li>Clean UI suitable for both desktop and mobile.</li>
                    </ul>
                    <p class="card-status">Status: <span>Completed</span></p>
                    <div class="project-links">
                        <a class="btn ghost small" href="https://github.com/sethupathi107" target="_blank">GitHub (Profile)</a>
                    </div>
                </article>

                <!-- Project 3: Calm Script Synth -->
                <article class="card">
                    <h3>Calm Script Synth – Meditation App</h3>
                    <p class="card-tag">Web App • Text to Speech</p>
                    <p>
                        A browser-based meditation tool that converts custom text to audio
                        and adds a time gap between words to create a slow, calm listening
                        experience for focus and relaxation.
                    </p>
                    <ul class="card-list">
                        <li>Text to speech conversion for custom scripts.</li>
                        <li>Configurable delay between words for meditation pacing.</li>
                        <li>Works directly in the browser, no installation needed.</li>
                    </ul>
                    <p class="card-status">Status: <span>Live</span></p>
                    <div class="project-links">
                        <a class="btn primary small" href="https://calm-script-synth.lovable.app" target="_blank">Live Demo</a>
                    </div>
                </article>

                <!-- Project 4: JavaScript Mini Games -->
                <article class="card">
                    <h3>Mini Games – JavaScript Collection</h3>
                    <p class="card-tag">JavaScript • DOM • Logic</p>
                    <p>
                        A set of small browser games built to practice JavaScript logic and
                        DOM manipulation, including Rock–Paper–Scissors and Number Guessing.
                    </p>
                    <ul class="card-list">
                        <li>Rock–Paper–Scissors with basic AI logic.</li>
                        <li>Number Guessing game with feedback on each try.</li>
                        <li>Reinforced event handling and state management in JS.</li>
                    </ul>
                    <p class="card-status">Status: <span>Practice Projects</span></p>
                    <div class="project-links">
                        <a class="btn ghost small" href="https://github.com/sethupathi107" target="_blank">GitHub (Profile)</a>
                    </div>
                </article>

            </div>
        </section>

        <!-- Journey / Timeline Section -->
        <section id="timeline" class="section section-alt">
            <h2 class="section-title">Learning Journey</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h4>Year 1–2: Programming Basics</h4>
                        <p>
                            Learned C, C++, and Java fundamentals. Built small programs and
                            understood basic syntax, loops, arrays, and functions.
                        </p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h4>Year 3: Web & DSA Focus</h4>
                        <p>
                            Started focusing on web projects using JavaScript and practicing
                            DSA / CP for company-wise and topic-wise preparation.
                        </p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-dot"></div>
                    <div class="timeline-content">
                        <h4>Projects & Tools</h4>
                        <p>
                            Built apps like DocGuard, Calm Script Synth, To-Do List, and
                            JS games. Configured VS Code, compilers, and used GitHub to
                            organize code.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="section">
            <h2 class="section-title">Contact</h2>
            <div class="section-content contact-grid">
                <p>
                    I’m open to internships, beginner-level projects, and opportunities
                    to grow as a developer. Feel free to reach out for collaboration,
                    coding discussions, or feedback on my work.
                </p>
                <div class="contact-card">
                    <p><strong>Email   :</strong> <span>sethupathiofficial107@gmail.com</span></p>
                    <p><strong>GitHub  :</strong> <span>github.com/sethupathi107</span></p>
                    <p><strong>LeetCode:</strong> <span>leetcode.com/Sethupathi107</span></p>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>© <span id="year">2025</span> Sethupathi • Built with HTML & CSS</p>
    </footer>

    <script>
        document.getElementById("year").textContent = new Date().getFullYear();
    </script>
</body>
</html>

```
## style.css
```
:root {
    --bg: #050816;
    --bg-alt: #0b1020;
    --card-bg: #111827;
    --accent: #6366f1;
    --accent-soft: rgba(99, 102, 241, 0.15);
    --text: #e5e7eb;
    --text-muted: #9ca3af;
    --border: #1f2937;
    --radius-lg: 18px;
    --radius-xl: 26px;
    --shadow-soft: 0 18px 40px rgba(15, 23, 42, 0.75);
    --shadow-card: 0 16px 30px rgba(15, 23, 42, 0.9);
}

*,
*::before,
*::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html, body {
    scroll-behavior: smooth;
}

body {
    font-family: "Poppins", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
    background: radial-gradient(circle at top, #111827 0, #020617 45%, #000 100%);
    color: var(--text);
    line-height: 1.6;
}

/* Header */
.header {
    position: sticky;
    top: 0;
    z-index: 20;
    backdrop-filter: blur(16px);
    background: linear-gradient(to bottom, rgba(2, 6, 23, 0.95), rgba(2, 6, 23, 0.7));
    border-bottom: 1px solid rgba(15, 23, 42, 0.9);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0.75rem 6vw;
}

.logo {
    font-weight: 700;
    font-size: 1.3rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
}

.logo span {
    color: var(--accent);
}

.nav {
    display: flex;
    gap: 1.2rem;
    flex-wrap: wrap;
}

.nav a {
    text-decoration: none;
    color: var(--text-muted);
    font-size: 0.9rem;
    font-weight: 500;
    position: relative;
    padding-bottom: 0.2rem;
}

.nav a::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0;
    height: 2px;
    background: var(--accent);
    transition: width 0.25s ease;
}

.nav a:hover {
    color: var(--text);
}

.nav a:hover::after {
    width: 100%;
}

/* Layout */
main {
    padding: 1.5rem 6vw 4rem;
}

/* Sections */
.section {
    padding: 3.5rem 0;
}

.section-alt {
    background: radial-gradient(circle at top left, #020617 0, #020617 40%, #000 100%);
    border-radius: var(--radius-xl);
    padding-inline: 1.5rem;
    margin-inline: -1.5rem;
}

.section-title {
    font-size: 1.7rem;
    font-weight: 600;
    margin-bottom: 1.8rem;
    position: relative;
    display: inline-block;
}

.section-title::after {
    content: "";
    position: absolute;
    left: 0;
    bottom: -0.4rem;
    width: 40%;
    height: 3px;
    background: linear-gradient(90deg, var(--accent), transparent);
    border-radius: 999px;
}

/* Hero */
.hero {
    display: grid;
    grid-template-columns: minmax(0, 2.2fr) minmax(0, 1.4fr);
    gap: 2rem;
    align-items: center;
    padding-top: 2.5rem;
}

.hero-tag {
    font-size: 0.85rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 0.8rem;
}

.hero h1 {
    font-size: clamp(2.2rem, 3.2vw + 1.5rem, 3rem);
    font-weight: 700;
    margin-bottom: 0.4rem;
}

.highlight {
    color: var(--accent);
}

.hero-subtitle {
    font-size: 0.98rem;
    color: var(--text-muted);
    max-width: 32rem;
    margin-bottom: 1.4rem;
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.9rem;
}

/* Buttons */
.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 0.65rem 1.4rem;
    border-radius: 999px;
    font-size: 0.9rem;
    font-weight: 500;
    text-decoration: none;
    cursor: pointer;
    border: 1px solid transparent;
    transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease, border-color 0.15s ease;
}

.btn.small {
    padding: 0.45rem 1.1rem;
    font-size: 0.8rem;
}

.btn.primary {
    background: linear-gradient(135deg, var(--accent), #4f46e5);
    color: #f9fafb;
    box-shadow: 0 14px 30px rgba(79, 70, 229, 0.35);
}

.btn.primary:hover {
    transform: translateY(-1px);
    box-shadow: 0 18px 40px rgba(79, 70, 229, 0.55);
}

.btn.ghost {
    background: transparent;
    color: var(--text);
    border-color: rgba(148, 163, 184, 0.8);
}

.btn.ghost:hover {
    background: rgba(15, 23, 42, 0.9);
    transform: translateY(-1px);
}

/* Hero Card */
.hero-card {
    background: radial-gradient(circle at top, var(--accent-soft) 0, #020617 55%);
    border-radius: var(--radius-xl);
    padding: 1.4rem 1.5rem;
    border: 1px solid rgba(55, 65, 81, 0.8);
    box-shadow: var(--shadow-soft);
    font-size: 0.9rem;
}

.hero-card h2 {
    font-size: 1.1rem;
    margin-bottom: 0.8rem;
}

.hero-card ul {
    list-style: none;
}

.hero-card li {
    margin-bottom: 0.45rem;
    color: var(--text-muted);
}

/* Professional Photo Style */
.professional-photo {
    display: flex;
    align-items: center;
    justify-content: center;
}

.professional-photo img {
    width: 260px;
    height: 300px;
    object-fit: cover;
    border-radius: 15px;
    border: 2px solid rgba(255,255,255,0.15);
    background: #0d1117;
    box-shadow: 0px 12px 28px rgba(0, 0, 0, 0.55);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.professional-photo img:hover {
    transform: scale(1.04);
    box-shadow: 0px 20px 40px rgba(0, 0, 0, 0.65);
}

/* About */
.section-content {
    display: grid;
    gap: 1.8rem;
}

.about-grid {
    grid-template-columns: minmax(0, 1.8fr) minmax(0, 1.2fr);
}

.bullet-list {
    margin: 0.7rem 0 0.7rem 1.2rem;
    color: var(--text-muted);
    font-size: 0.95rem;
}

.about-card {
    background: rgba(15, 23, 42, 0.95);
    border-radius: var(--radius-lg);
    padding: 1.2rem 1.3rem;
    border: 1px solid var(--border);
    box-shadow: var(--shadow-card);
    font-size: 0.9rem;
}

.about-card h3 {
    font-size: 1.05rem;
    margin-bottom: 0.7rem;
}

/* Skills */
.chips {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
}

.chip {
    padding: 0.35rem 0.8rem;
    border-radius: 999px;
    background: rgba(15, 23, 42, 0.95);
    border: 1px solid rgba(55, 65, 81, 0.9);
    font-size: 0.8rem;
    color: var(--text-muted);
}

/* Projects */
.cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
    gap: 1.5rem;
}

.card {
    background: radial-gradient(circle at top, rgba(79, 70, 229, 0.08) 0, #020617 60%);
    border-radius: var(--radius-lg);
    padding: 1.2rem 1.3rem 1.3rem;
    border: 1px solid rgba(31, 41, 55, 0.9);
    box-shadow: var(--shadow-card);
    font-size: 0.9rem;
}

.card h3 {
    font-size: 1.05rem;
    margin-bottom: 0.3rem;
}

.card-tag {
    font-size: 0.78rem;
    text-transform: uppercase;
    letter-spacing: 0.14em;
    color: var(--accent);
    margin-bottom: 0.6rem;
}

.card p {
    color: var(--text-muted);
    margin-bottom: 0.5rem;
}

.card-list {
    margin-left: 1rem;
    color: var(--text-muted);
    margin-bottom: 0.6rem;
    padding-left: 0.2rem;
}

.card-list li {
    margin-bottom: 0.25rem;
}

.card-status {
    font-size: 0.82rem;
    color: var(--text-muted);
}

.card-status span {
    color: #bbf7d0;
}

.project-links {
    margin-top: 0.4rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
}

/* Timeline */
.timeline {
    border-left: 2px solid rgba(55, 65, 81, 0.9);
    padding-left: 1.5rem;
    margin-top: 0.3rem;
}

.timeline-item {
    position: relative;
    margin-bottom: 1.4rem;
}

.timeline-dot {
    position: absolute;
    left: -1.12rem;
    top: 0.2rem;
    width: 10px;
    height: 10px;
    border-radius: 999px;
    background: var(--accent);
    box-shadow: 0 0 0 4px rgba(99, 102, 241, 0.25);
}

.timeline-content h4 {
    font-size: 0.98rem;
    margin-bottom: 0.1rem;
}

.timeline-content p {
    font-size: 0.9rem;
    color: var(--text-muted);
}

/* Contact */
.contact-grid {
    grid-template-columns: minmax(0, 1.6fr) minmax(0, 1.2fr);
}

.contact-card {
    background: rgba(15, 23, 42, 0.96);
    border-radius: var(--radius-lg);
    padding: 1.1rem 1.2rem;
    border: 1px solid var(--border);
    box-shadow: var(--shadow-card);
    font-size: 0.9rem;
}

.contact-card p {
    margin-bottom: 0.4rem;
}

.contact-card span {
    color: var(--text-muted);
}

.note {
    font-size: 0.8rem;
    color: var(--text-muted);
    margin-top: 0.4rem;
}

/* Footer */
.footer {
    border-top: 1px solid rgba(15, 23, 42, 0.9);
    padding: 1rem 6vw 1.4rem;
    font-size: 0.8rem;
    color: var(--text-muted);
    text-align: center;
}

```
## OUTPUT
<img width="1901" height="924" alt="Screenshot 2025-12-02 154730" src="https://github.com/user-attachments/assets/8fd0ee37-f788-4b14-82fb-84dce12958c6" />
<img width="1902" height="931" alt="Screenshot 2025-12-02 154815" src="https://github.com/user-attachments/assets/db6d9deb-d263-4432-a8c2-5c8aacb9aefe" />
<img width="1905" height="921" alt="Screenshot 2025-12-02 154835" src="https://github.com/user-attachments/assets/42777eeb-a616-4ce6-a561-be31999f1b8a" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
