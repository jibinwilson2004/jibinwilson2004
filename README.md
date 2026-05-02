# Jibin Wilson · Neo-Brutalism Profile

> **⚠️ NOTE:** GitHub does not allow custom CSS in README.md files.  
> **To use this design:** Save the code below as `index.html` and deploy to GitHub Pages, or use a Markdown-compatible version.

---

## 🚀 Option 1: Deploy as Live Neo-Brutal Portfolio (Recommended)

1. Create a new repository: `jibinwilson2004.github.io`
2. Copy the HTML code below into `index.html`
3. Push to GitHub
4. Your portfolio will be live at: `https://jibinwilson2004.github.io`

---

## 📄 Complete HTML Code

Save this as `index.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jibin Wilson · Neo-Brutalism Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #f5f5f0;
            font-family: 'Space Grotesk', 'Fira Code', 'Courier New', monospace;
            line-height: 1.4;
            color: #111;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: #f5f5f0;
            border-left: 4px solid #ff5e00;
            border-right: 4px solid #0033cc;
            padding: 1.5rem 2rem 2rem 2rem;
            box-shadow: 12px 12px 0 rgba(0,0,0,0.12);
        }

        .brutal-card {
            background: #ffffff;
            border: 3px solid #111;
            box-shadow: 8px 8px 0 #ff5e00;
            padding: 1.5rem;
            margin-bottom: 2rem;
            transition: 0.1s linear;
        }

        .brutal-card:hover {
            transform: translate(-2px, -2px);
            box-shadow: 12px 12px 0 #0033cc;
        }

        .brutal-header {
            background: #111;
            color: #ffdd00;
            padding: 2rem 1.5rem;
            margin-bottom: 2rem;
            border: 4px solid #ff5e00;
            box-shadow: 12px 12px 0 #0033cc;
            text-align: center;
        }

        .brutal-header h1 {
            font-size: 4rem;
            font-weight: 800;
            letter-spacing: -2px;
            text-transform: uppercase;
            word-break: break-word;
            background: linear-gradient(135deg, #ffdd00 30%, #ff5e00 80%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: none;
        }

        .brutal-header p {
            font-size: 1.2rem;
            font-weight: 500;
            color: #ffdd00;
            margin-top: 0.5rem;
            border-top: 2px solid #ff5e00;
            display: inline-block;
            padding-top: 0.5rem;
        }

        .typing-static {
            background: #000;
            color: #00ffcc;
            font-family: 'Fira Code', monospace;
            font-weight: 600;
            font-size: 1.4rem;
            padding: 0.75rem 1.5rem;
            border-left: 8px solid #ff5e00;
            border-bottom: 4px solid #0033cc;
            display: inline-block;
            margin: 1rem 0;
        }

        .badge-row {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            margin: 1.5rem 0;
        }

        .brutal-badge {
            background: #111;
            color: #f5f5f0;
            padding: 0.4rem 1rem;
            border: 2px solid #ffdd00;
            font-weight: 600;
            font-size: 0.8rem;
            letter-spacing: 0.5px;
            text-transform: uppercase;
            box-shadow: 3px 3px 0 #ff5e00;
        }

        .brutal-title {
            font-size: 2rem;
            font-weight: 800;
            text-transform: uppercase;
            border-left: 14px solid #ff5e00;
            padding-left: 0.8rem;
            margin: 1.5rem 0 1.2rem 0;
            letter-spacing: -1px;
        }

        .skill-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 0.7rem;
            margin-top: 1rem;
        }

        .skill-tag {
            background: #111;
            color: #ffdd00;
            font-family: monospace;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border: 2px solid #ff5e00;
            box-shadow: 3px 3px 0 #0033cc;
            font-size: 0.85rem;
            text-transform: uppercase;
            transition: 0.05s linear;
        }

        .skill-tag:hover {
            background: #ff5e00;
            color: #000;
            border-color: #000;
            box-shadow: 2px 2px 0 #000;
        }

        .project-table {
            width: 100%;
            border-collapse: collapse;
            background: #fff;
            border: 3px solid #111;
        }

        .project-table th, .project-table td {
            border: 2px solid #111;
            padding: 1rem;
            vertical-align: top;
            font-size: 0.9rem;
        }

        .project-table th {
            background: #ffdd00;
            color: #000;
            font-weight: 800;
            text-transform: uppercase;
        }

        .project-table td:first-child {
            font-weight: 700;
            background: #f0f0e8;
        }

        .xp-list {
            list-style: none;
            padding-left: 0;
        }

        .xp-list li {
            margin-bottom: 1rem;
            padding-left: 1rem;
            border-left: 6px solid #ff5e00;
            font-weight: 500;
        }

        .xp-list strong {
            color: #0033cc;
            font-weight: 800;
        }

        .trophy-container {
            background: #fff;
            border: 3px solid #000;
            padding: 1rem;
            text-align: center;
            margin: 2rem 0;
        }

        .heatmap-img {
            background: #ffffff;
            border: 3px solid #111;
            padding: 0.8rem;
            text-align: center;
            margin: 1rem 0;
            box-shadow: 6px 6px 0 #ff5e00;
        }

        .connect-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            flex-wrap: wrap;
            margin: 1.5rem 0;
        }

        .brutal-link {
            background: #111;
            color: #ffdd00;
            padding: 0.7rem 1.5rem;
            font-weight: bold;
            text-decoration: none;
            border: 2px solid #ff5e00;
            box-shadow: 4px 4px 0 #0033cc;
            text-transform: uppercase;
            font-size: 0.9rem;
            transition: 0.05s linear;
        }

        .brutal-link:hover {
            background: #ff5e00;
            color: #000;
            box-shadow: 2px 2px 0 #000;
            border-color: #000;
        }

        footer {
            text-align: center;
            margin-top: 2rem;
            border-top: 4px dashed #111;
            padding-top: 1.5rem;
            font-weight: 500;
        }

        hr {
            border: none;
            height: 4px;
            background: #111;
            margin: 1rem 0;
        }

        @media (max-width: 700px) {
            .container {
                padding: 1rem;
            }
            .brutal-header h1 {
                font-size: 2.5rem;
            }
            .project-table th, .project-table td {
                padding: 0.6rem;
                display: table-cell;
            }
        }
    </style>
</head>
<body>
<div class="container">
    
    <div class="brutal-header">
        <h1>JIBIN WILSON</h1>
        <p>B.Tech CSE | Full-Stack Developer | Tech Leader</p>
    </div>

    <div style="text-align: center; margin: 1rem 0 2rem 0;">
        <div class="typing-static">
            ◉ Computer Science Engineer ◉ Full-Stack Web Developer ◉ Workflow Automation Expert ◉ Community Leader & Mentor
        </div>
    </div>

    <div class="badge-row">
        <span class="brutal-badge">🔍 PROFILE VIEWS: 1.2K+</span>
        <span class="brutal-badge">⚡ STATUS: ACTIVE</span>
    </div>

    <hr />

    <div class="brutal-card">
        <div class="brutal-title" style="margin-top: 0;">👨‍💻 ABOUT ME</div>
        <p style="font-size: 1.05rem; margin-bottom: 1rem; font-weight: 500;">Computer Science Engineering student with a passion for building efficient, scalable software and leading technical communities. I combine strong full-stack development skills with workflow automation to deliver impactful solutions.</p>
        <ul style="list-style: none; padding-left: 0;">
            <li style="margin-bottom: 8px;">🎓 <strong>Education:</strong> B.Tech in Computer Science & Engineering (CGPA: 8.7/10) — MBITS Kothamangalam</li>
            <li style="margin-bottom: 8px;">💼 <strong>Experience:</strong> Web Development Intern @ High Court of Kerala | IoT Intern @ IIIT Kottayam</li>
            <li style="margin-bottom: 8px;">🚀 <strong>Core Competencies:</strong> Full-Stack Development, Database Design, Process Automation, Algorithmic Problem-Solving</li>
            <li style="margin-bottom: 8px;">👑 <strong>Leadership:</strong> Chair/IEEE SB MBITS | Vice Chair/IEEE PES | Operations Lead/IEDC</li>
            <li style="margin-bottom: 8px;">🌱 <strong>Current Focus:</strong> Advanced DSA, System Design, Cloud Architecture</li>
        </ul>
    </div>

    <div class="brutal-card">
        <div class="brutal-title">🛠️ TECHNICAL PROFICIENCY</div>
        
        <div style="margin: 1rem 0 1.2rem 0; font-weight: 800; font-size: 1.2rem;">Languages</div>
        <div class="skill-grid">
            <span class="skill-tag">Python</span><span class="skill-tag">Java</span><span class="skill-tag">JavaScript</span>
            <span class="skill-tag">C</span><span class="skill-tag">PHP</span>
        </div>

        <div style="margin: 1.5rem 0 1.2rem 0; font-weight: 800; font-size: 1.2rem;">Frontend & Frameworks</div>
        <div class="skill-grid">
            <span class="skill-tag">React</span><span class="skill-tag">Django</span><span class="skill-tag">HTML5</span>
            <span class="skill-tag">CSS3</span><span class="skill-tag">WordPress</span>
        </div>

        <div style="margin: 1.5rem 0 1.2rem 0; font-weight: 800; font-size: 1.2rem;">Databases & Tools</div>
        <div class="skill-grid">
            <span class="skill-tag">MySQL</span><span class="skill-tag">MongoDB</span><span class="skill-tag">Git</span>
            <span class="skill-tag">Postman</span><span class="skill-tag">n8n</span><span class="skill-tag">Power BI</span>
        </div>
    </div>

    <div class="brutal-card">
        <div class="brutal-title">📌 KEY PROJECTS</div>
        <table class="project-table">
            <thead>
                <tr><th>Project</th><th>Description</th><th>Tech Stack</th></tr>
            </thead>
            <tbody>
                <tr><td><strong>Chit Fund Management System</strong></td><td>Automated financial operations and bidding for secure fund management with real-time tracking.</td><td>`PHP`, `MySQL`, `Bootstrap`</td></tr>
                <tr><td><strong>IEEE SB MBITS Website</strong></td><td>Official institutional website digitizing operations, event showcases, and member management.</td><td>`React.js`, `Node.js`, `MongoDB`</td></tr>
                <tr><td><strong>ResQLink</strong></td><td>Low-cost IoT-based landslide early warning system with LoRaWAN communication and SMS alerts.</td><td>`Embedded C`, `LoRaWAN`, `Python`</td></tr>
                <tr><td><strong>IrisNet50</strong></td><td>Deep learning model (ResNet50) for alcohol detection via iris images achieving 92% accuracy.</td><td>`Python`, `TensorFlow`, `OpenCV`</td></tr>
            </tbody>
        </table>
    </div>

    <div class="brutal-card">
        <div class="brutal-title">💼 EXPERIENCE & LEADERSHIP</div>
        <ul class="xp-list">
            <li><strong>IoT & Web Development Intern</strong> @ IIIT Kottayam (GYAAN Innovation Lab) | Jun 2025 – Jul 2025 <br> ✦ Built a real-time cloud dashboard for temperature monitoring in cold storage facilities.</li>
            <li><strong>Web Development Intern</strong> @ High Court of Kerala | Jun 2024 – Jul 2024 <br> ✦ Automated judges' booking and travel workflows, reducing administrative overhead by 40%.</li>
            <li><strong>Technical Speaker & Mentor</strong> <br> ✦ Conducted 5+ sessions on Python, Java, and C at NIT Calicut, IEDC MBITS, and RSET.</li>
            <li><strong>Active Volunteer</strong> @ NSS (2023-2025) | <strong>Student Coordinator</strong> for 3+ major hackathons.</li>
        </ul>
    </div>

    <div class="trophy-container">
        <div style="font-weight: 800; margin-bottom: 1rem; text-transform: uppercase; font-size: 1.2rem;">🏆 GitHub Trophies</div>
        <img src="https://github-profile-trophy.vercel.app/?username=jibinwilson2004&theme=tokyonight&no-frame=true&row=2&column=4&margin-w=15&margin-h=15" alt="GitHub Trophies" style="max-width: 100%; border: 2px solid #000;" />
    </div>

    <div class="heatmap-img">
        <div style="font-weight: 800; margin-bottom: 0.8rem;">📅 GITHUB ACTIVITY CALENDAR</div>
        <img src="https://ghchart.rshah.org/jibinwilson2004" alt="GitHub Heatmap Calendar" style="width: 100%; border: 2px solid #111; background: #fff;" />
    </div>

    <div class="brutal-card" style="text-align: center;">
        <div class="brutal-title">🤝 CONNECT WITH ME</div>
        <div class="connect-links">
            <a href="https://linkedin.com/in/jibin-wilson" class="brutal-link">LINKEDIN</a>
            <a href="mailto:jibinwilson@ieee.org" class="brutal-link">EMAIL</a>
            <a href="#" class="brutal-link">PORTFOLIO</a>
            <a href="https://github.com/jibinwilson2004" class="brutal-link">GITHUB</a>
        </div>
    </div>

    <footer>
        <div style="display: flex; justify-content: center; gap: 1rem; font-weight: 700;">
            <span>✦ NEO BRUTALISM EDGE ✦</span>
            <span>HIGH CONTRAST // RAW SHADOWS</span>
        </div>
        <div style="margin-top: 1rem; font-size: 0.8rem;">&copy; Jibin Wilson — Full-Stack Engineer & Tech Leader</div>
    </footer>
</div>
</body>
</html>
