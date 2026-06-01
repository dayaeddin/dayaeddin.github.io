<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Dhaya Eddine Messaoudi, Ph.D. - Artificial Intelligence & Natural Language Processing Researcher specializing in Neural Machine Translation and Arabic NLP">
    <meta name="keywords" content="AI, NLP, Neural Machine Translation, Arabic NLP, Deep Learning, Researcher">
    <meta name="author" content="Dhaya Eddine Messaoudi">
    <title>Dhaya Eddine Messaoudi, Ph.D. | AI & NLP Researcher</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset & Base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background-color: #ffffff;
            color: #1a1a2e;
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 40px;
        }

        /* Typography */
        h1, h2, h3 {
            font-family: 'Merriweather', serif;
            font-weight: 600;
            letter-spacing: -0.02em;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            color: #0A2F6C;
        }

        h2 {
            font-size: 1.75rem;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #0A2F6C;
            display: inline-block;
        }

        h3 {
            font-size: 1.25rem;
            margin-bottom: 0.75rem;
            color: #0A2F6C;
        }

        /* Header */
        .header {
            padding: 60px 0 30px 0;
            text-align: center;
            border-bottom: 1px solid #e0e0e0;
        }

        .title {
            font-size: 1.2rem;
            color: #555;
            margin-bottom: 0.5rem;
            font-weight: 400;
        }

        .affiliation {
            font-size: 0.95rem;
            color: #777;
            margin-bottom: 1.5rem;
        }

        /* Navigation */
        .nav {
            text-align: center;
            padding: 20px 0;
            background: #fafafa;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid #e0e0e0;
        }

        .nav a {
            margin: 0 20px;
            text-decoration: none;
            color: #1a1a2e;
            font-weight: 500;
            font-size: 0.9rem;
            transition: color 0.2s;
        }

        .nav a:hover {
            color: #0A2F6C;
        }

        /* Social Links */
        .social-links {
            text-align: center;
            margin: 20px 0;
        }

        .social-links a {
            margin: 0 10px;
            display: inline-block;
        }

        /* Sections */
        .section {
            margin: 50px 0;
        }

        /* Research Grid */
        .research-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
            margin: 30px 0;
        }

        .research-card {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .research-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }

        .research-card h4 {
            color: #0A2F6C;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .research-card p {
            font-size: 0.85rem;
            color: #555;
        }

        /* Tables */
        .publication-table, .education-table, .appointment-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }

        .publication-table th, .education-table th, .appointment-table th {
            text-align: left;
            padding: 12px 8px;
            background: #f0f0f0;
            font-weight: 600;
            color: #0A2F6C;
            border-bottom: 2px solid #0A2F6C;
        }

        .publication-table td, .education-table td, .appointment-table td {
            padding: 12px 8px;
            border-bottom: 1px solid #e0e0e0;
            vertical-align: top;
        }

        .publication-table tr:hover, .education-table tr:hover, .appointment-table tr:hover {
            background: #fafafa;
        }

        /* Publication Links */
        .doi {
            font-family: monospace;
            font-size: 0.8rem;
            color: #0A2F6C;
            text-decoration: none;
        }

        .doi:hover {
            text-decoration: underline;
        }

        /* Badges Container */
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin: 20px 0;
        }

        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 25px;
            margin: 25px 0;
        }

        .skill-category h3 {
            margin-bottom: 15px;
            font-size: 1rem;
            color: #0A2F6C;
            border-left: 3px solid #0A2F6C;
            padding-left: 10px;
        }

        .skill-list {
            list-style: none;
            padding-left: 0;
        }

        .skill-list li {
            padding: 6px 0;
            font-size: 0.9rem;
            color: #444;
        }

        /* Stats Container */
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
            margin: 30px 0;
        }

        .stats-container img {
            width: 48%;
            border-radius: 8px;
            border: 1px solid #e0e0e0;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 50px 0 30px;
            border-top: 1px solid #e0e0e0;
            margin-top: 50px;
            color: #777;
            font-size: 0.85rem;
        }

        .footer-quote {
            font-style: italic;
            color: #0A2F6C;
            margin-bottom: 20px;
        }

        .footer-divider {
            width: 60px;
            height: 2px;
            background: #0A2F6C;
            margin: 20px auto;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .container {
                padding: 0 20px;
            }
            h1 {
                font-size: 2rem;
            }
            .research-grid {
                grid-template-columns: 1fr;
            }
            .stats-container img {
                width: 100%;
            }
            .nav a {
                margin: 0 10px;
                font-size: 0.8rem;
            }
        }

        /* List Styles */
        ul {
            margin-left: 20px;
            color: #444;
        }

        li {
            margin: 8px 0;
        }

        a {
            color: #0A2F6C;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .publication-title {
            font-weight: 500;
        }

        .journal {
            font-style: italic;
        }

        hr {
            border: none;
            border-top: 1px solid #e0e0e0;
            margin: 30px 0;
        }
    </style>
</head>
<body>

<div class="nav">
    <a href="#bio">Biography</a>
    <a href="#research">Research</a>
    <a href="#publications">Publications</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
</div>

<div class="container">

    <!-- Header -->
    <div class="header">
        <h1>Dhaya Eddine Messaoudi, Ph.D.</h1>
        <div class="title">Artificial Intelligence & Natural Language Processing Researcher</div>
        <div class="affiliation">University Abbas Laghrour, Khenchela, Algeria</div>
        
        <div class="social-links">
            <a href="https://scholar.google.com/citations?user=QMrfV9oAAAAJ&hl=fr"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=Google-Scholar&logoColor=white" alt="Google Scholar"></a>
            <a href="https://www.linkedin.com/in/dhaya-eddine-messaoudi-658205232"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=LinkedIn&logoColor=white" alt="LinkedIn"></a>
            <a href="https://github.com/dayaeddin"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white" alt="GitHub"></a>
            <a href="mailto:messaoudi.dhayaeddine@univ-khenchela.dz"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=Gmail&logoColor=white" alt="Email"></a>
        </div>
    </div>

    <!-- Biography -->
    <div class="section" id="bio">
        <h2>Biography</h2>
        <p style="margin-top: 20px;">I am a <strong>Ph.D. graduate in Artificial Intelligence and Natural Language Processing</strong> (February 2025) from the University of Abbas Laghrour, Algeria. My research focuses on <strong>Neural Machine Translation</strong>, <strong>Arabic NLP</strong>, and <strong>low-resource language processing</strong>. My doctoral dissertation, <em>"Conception of a Neural Model for Natural Language Translation,"</em> introduced novel hybrid attention mechanisms combining character-level CNN-BiLSTM architectures for enhanced Arabic translation quality.</p>
        <p style="margin-top: 15px;">My research spans <strong>multimodal learning</strong>, <strong>stochastic neural networks</strong>, and <strong>Arabic computational linguistics</strong>, with applications in sentiment analysis, part-of-speech tagging, and cross-lingual translation systems. I maintain active collaborations with international institutions, including a research internship at the <strong>University of Malta</strong> (2023).</p>
    </div>

    <!-- Education -->
    <div class="section">
        <h2>Education</h2>
        <table class="education-table">
            <thead>
                <tr><th>Degree</th><th>Field</th><th>Institution</th><th>Year</th></tr>
            </thead>
            <tbody>
                <tr><td><strong>Ph.D.</strong></td><td>Artificial Intelligence – NLP</td><td>University Abbas Laghrour, Algeria</td><td>Feb 2025</td></tr>
                <tr><td><strong>M.Sc.</strong></td><td>Fundamental & Applied Computer Science</td><td>University Abbas Laghrour, Algeria</td><td>2015</td></tr>
                <tr><td><strong>B.Sc.</strong></td><td>Computer Networks</td><td>University Abbas Laghrour, Algeria</td><td>2012</td></tr>
            </tbody>
        </table>
    </div>

    <!-- Research Focus -->
    <div class="section" id="research">
        <h2>Research Focus</h2>
        <div class="research-grid">
            <div class="research-card">
                <h4>Neural Machine Translation</h4>
                <p>Hybrid attention mechanisms, character-level models, low-resource languages</p>
            </div>
            <div class="research-card">
                <h4>Arabic NLP</h4>
                <p>POS tagging, sentiment analysis, multimodal translation</p>
            </div>
            <div class="research-card">
                <h4>Deep Learning</h4>
                <p>CNN-BiLSTM, Neural SDEs, multimodal architectures</p>
            </div>
        </div>
    </div>

    <!-- Academic Appointments -->
    <div class="section">
        <h2>Academic & Professional Appointments</h2>
        <table class="appointment-table">
            <thead><tr><th>Period</th><th>Position</th><th>Affiliation</th></tr></thead>
            <tbody>
                <tr><td>2019–2022</td><td>Volunteer Lecturer</td><td>University of Khenchela, Algeria</td></tr>
                <tr><td>2017–2021</td><td>State Engineer in Computer Science</td><td>Agricultural Chamber of Khenchela, Algeria</td></tr>
                <tr><td>2016–2017</td><td>Reserve IT Officer</td><td>National People's Army, Algeria</td></tr>
                <tr><td>May–Jun 2023</td><td>Visiting Research Intern</td><td>University of Malta — AI & NLP Group</td></tr>
            </tbody>
        </table>
    </div>

    <!-- Publications -->
    <div class="section" id="publications">
        <h2>Peer-Reviewed Publications</h2>
        
        <h3 style="margin: 20px 0 10px 0;">Journal Articles</h3>
        <p><strong>Messaoudi, D.E.</strong> (2023). Enhancing Neural Arabic Machine Translation using Character-Level CNN-BiLSTM and Hybrid Attention. <em>Engineering, Technology & Applied Science Research (ETASR)</em>. <a href="https://doi.org/10.48084/etasr.8383" class="doi">DOI: 10.48084/etasr.8383</a></p>
        
        <h3 style="margin: 25px 0 10px 0;">Conference Proceedings</h3>
        <table class="publication-table">
            <thead><tr><th>Year</th><th>Title</th><th>Conference</th><th>Location</th></tr></thead>
            <tbody>
                <tr><td>2021</td><td>Intelligent System for POS Tagging Using CNN on Arabic</td><td>ICDSIS</td><td>Hefei, China</td></tr>
                <tr><td>2025</td><td>Character-Level Arabic Sentiment Classification via Neural SDE-Based Feature Dynamics</td><td>MIDI Conference</td><td>—</td></tr>
                <tr><td>2026</td><td>Hybrid Approach for Enhancing Multimodal Arabic Neural Machine Translation through Visuals</td><td>ICAIAS</td><td>Algeria</td></tr>
                <tr><td>2026</td><td>Stochastic CNN-SDE Model for Robust Character-Level Arabic POS Tagging</td><td>ICASA</td><td>Djillali Liabes University, Algeria</td></tr>
            </tbody>
        </table>
    </div>

    <!-- Technical Skills -->
    <div class="section" id="skills">
        <h2>Technical Skills</h2>
        <div class="skills-grid">
            <div class="skill-category">
                <h3>Programming Languages</h3>
                <ul class="skill-list">
                    <li>Python</li><li>Java</li><li>C++</li><li>PHP</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Deep Learning</h3>
                <ul class="skill-list">
                    <li>TensorFlow</li><li>PyTorch</li><li>Keras</li><li>Hugging Face</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>NLP & Data Science</h3>
                <ul class="skill-list">
                    <li>NLTK</li><li>SpaCy</li><li>NumPy/Pandas</li><li>Scikit-learn</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Tools & Infrastructure</h3>
                <ul class="skill-list">
                    <li>MySQL</li><li>OpenCV</li><li>Git</li><li>Linux</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Languages -->
    <div class="section">
        <h2>Languages</h2>
        <table class="appointment-table">
            <thead><tr><th>Language</th><th>Proficiency</th></tr></thead>
            <tbody>
                <tr><td>Arabic</td><td>Native (C2)</td></tr>
                <tr><td>French</td><td>Fluent (C1)</td></tr>
                <tr><td>English</td><td>Fluent (C1)</td></tr>
            </tbody>
        </table>
    </div>

    <!-- Current Research -->
    <div class="section">
        <h2>Current Research Directions</h2>
        <ul>
            <li><strong>Multimodal Neural Machine Translation:</strong> Integrating visual information to enhance Arabic translation quality</li>
            <li><strong>Character-Level Arabic Processing:</strong> Neural SDE-based models for POS tagging and sentiment classification</li>
            <li><strong>Low-Resource Language Adaptation:</strong> Transfer learning and hybrid attention mechanisms for under-represented Arabic dialects</li>
        </ul>
    </div>

    <!-- GitHub Stats -->
    <div class="section">
        <h2>Research Metrics</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=dayaeddin&show_icons=true&theme=default&hide_border=true&title_color=0A2F6C&icon_color=0A2F6C" alt="GitHub Stats">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dayaeddin&layout=compact&theme=default&hide_border=true&title_color=0A2F6C" alt="Top Languages">
        </div>
    </div>

    <!-- Contact -->
    <div class="section" id="contact">
        <h2>Collaboration & Contact</h2>
        <p>I welcome research collaboration inquiries, particularly in:</p>
        <ul>
            <li>Neural Machine Translation for low-resource languages</li>
            <li>Arabic computational linguistics</li>
            <li>Multimodal learning architectures</li>
            <li>Stochastic neural networks for NLP</li>
        </ul>
        <p style="margin-top: 20px;"><strong>Office:</strong> University Abbas Laghrour, Khenchela, Algeria<br>
        <strong>Email:</strong> <a href="mailto:messaoudi.dhayaeddine@univ-khenchela.dz">messaoudi.dhayaeddine@univ-khenchela.dz</a><br>
        <strong>Google Scholar:</strong> <a href="https://scholar.google.com/citations?user=QMrfV9oAAAAJ&hl=fr">View Profile</a></p>
    </div>

    <!-- Footer -->
    <div class="footer">
        <div class="footer-divider"></div>
        <div class="footer-quote">"Advancing Arabic Natural Language Processing through Neural Innovation"</div>
        <p>Last updated: February 2026</p>
        <p><img src="https://komarev.com/ghpvc/?username=dayaeddin&color=0A2F6C&style=flat-square" alt="Profile Views"></p>
    </div>

</div>
</body>
</html>
