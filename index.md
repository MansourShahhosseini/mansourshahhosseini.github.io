---
layout: default
title: "Mansour Shahhosseini"
description: "PhD Student in Quantitative Marketing at UTD"
---

<style>
:root {
    --primary-color: #1a365d;
    --secondary-color: #2c5282;
    --accent-color: #3182ce;
    --light-gray: #f7fafc;
    --dark-text: #1a202c;
    --medium-gray: #718096;
    --light-border: #e2e8f0;
    --border-radius: 8px;
    --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
    --transition: all 0.3s ease;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    line-height: 1.6;
    color: var(--dark-text);
    background-color: #ffffff;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
}

.profile-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 2rem 0 3rem;
    text-align: center;
}

.my-profile-pic {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid var(--accent-color);
    margin-bottom: 1.5rem;
    transition: var(--transition);
    box-shadow: var(--box-shadow);
}

.my-profile-pic:hover {
    transform: scale(1.03);
    box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
}

h1 {
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    color: var(--primary-color);
}

.subtitle {
    font-size: 1.1rem;
    color: var(--medium-gray);
    margin-bottom: 1.5rem;
}

.nav-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 1rem;
    margin: 1.5rem 0;
}

.nav-link {
    text-decoration: none;
    color: var(--dark-text);
    font-weight: 500;
    padding: 0.5rem 1rem;
    border-radius: var(--border-radius);
    transition: var(--transition);
    position: relative;
}

.nav-link:hover, .nav-link:focus {
    color: var(--accent-color);
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 0;
    height: 2px;
    background-color: var(--accent-color);
    transition: var(--transition);
    transform: translateX(-50%);
}

.nav-link:hover::after {
    width: 70%;
}

.section {
    padding: 2.5rem 1.5rem;
    margin-bottom: 2rem;
    background-color: #ffffff;
    border-radius: var(--border-radius);
    box-shadow: var(--box-shadow);
    transition: var(--transition);
}

.section:hover {
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
}

h2 {
    font-size: 1.8rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid var(--light-border);
    color: var(--primary-color);
}

h3 {
    font-size: 1.4rem;
    font-weight: 600;
    margin: 1.5rem 0 0.75rem;
    color: var(--secondary-color);
}

p {
    margin-bottom: 1rem;
    color: #4a5568;
}

a {
    color: var(--accent-color);
    text-decoration: none;
    transition: var(--transition);
}

a:hover {
    text-decoration: underline;
    color: var(--secondary-color);
}

.timeline {
    position: relative;
    margin-left: 16px;
    padding-left: 10px;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 4px;
    top: 10px;
    bottom: -20px;
    width: 3px;
    background: var(--light-border);
}

.timeline-item {
    position: relative;
    padding-left: 30px;
    margin-bottom: 2rem;
}

.timeline-item:last-child {
    margin-bottom: 0;
    padding-bottom: 0;
}

.timeline-item::before {
    content: '';
    position: absolute;
    left: -6px;
    top: 4px;
    width: 15px;
    height: 15px;
    border-radius: 50%;
    background: var(--accent-color);
    border: 3px solid #fff;
    box-shadow: 0 0 0 2px var(--accent-color);
}

.timeline-year {
    display: inline-block;
    font-weight: 600;
    color: var(--accent-color);
    margin-bottom: 0.25rem;
}

.timeline-content h4 {
    font-size: 1.2rem;
    font-weight: 600;
    margin-bottom: 0.25rem;
}

.interests-container {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 1rem 0;
}

.interest-badge {
    background-color: #ebf4ff;
    color: var(--secondary-color);
    padding: 0.4rem 0.8rem;
    border-radius: 20px;
    font-size: 0.9rem;
    font-weight: 500;
}

.code-repo {
    display: block;
    margin-bottom: 1rem;
    padding: 1rem;
    background-color: var(--light-gray);
    border-radius: var(--border-radius);
    transition: var(--transition);
    border-left: 3px solid var(--accent-color);
}

.code-repo:hover {
    background-color: #edf2f7;
    transform: translateX(5px);
}

.contact-links {
    display: flex;
    flex-wrap: wrap;
    gap: 1.25rem;
    justify-content: center;
    margin-top: 1rem;
}

.contact-link {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-weight: 500;
    transition: var(--transition);
    text-decoration: none;
}

footer {
    text-align: center;
    padding: 2rem 0;
    color: var(--medium-gray);
    font-style: italic;
    border-top: 1px solid var(--light-border);
    margin-top: 2rem;
}

@media (max-width: 768px) {
    .my-profile-pic {
        width: 160px;
        height: 160px;
    }
    
    h1 {
        font-size: 1.8rem;
    }
    
    .section {
        padding: 2rem 1rem;
    }
    
    .timeline::before {
        left: 8px;
    }
    
    .timeline-item {
        padding-left: 35px;
    }
}

hr {
    display: none;
}

ul {
    padding-left: 20px;
    margin-bottom: 1rem;
}

li {
    margin-bottom: 0.5rem;
    color: #4a5568;
}
</style>

<div class="container">
    <div class="profile-container">
        <img src="assets/profile.jpg" alt="Profile Photo" class="my-profile-pic">
        <h1>Mansour Shahhosseini</h1>
        <div class="subtitle">PhD Student in Quantitative Marketing at The University of Texas at Dallas</div>
        
        <div class="nav-container">
            <a href="#education" class="nav-link">Education</a>
            <a href="#publications" class="nav-link">Publications</a>
            <a href="#working-papers" class="nav-link">Working Papers</a>
            <a href="#codes" class="nav-link">Code</a>
            <a href="#contact" class="nav-link">Contact</a>
        </div>
    </div>
    
    <div class="section" id="cv">
        <h2>Curriculum Vitae</h2>
        <p>Download my complete CV <a href="https://www.dropbox.com/scl/fi/xesa5zyqnbydtcvs8wkty/MansourShahhosseini_CV.docx?rlkey=qdrngb2cws7po5t5f38hnsdi9&st=gp67fcdc&dl=0">here</a></p>
    </div>
    
    <div class="section" id="research">
        <h2>Research Interests</h2>
        <div class="interests-container">
            <span class="interest-badge">Customer Analytics</span>
            <span class="interest-badge">Social Media</span>
            <span class="interest-badge">Unstructured Data in Marketing</span>
        </div>
        
        <h3>Methods</h3>
        <div class="interests-container">
            <span class="interest-badge">Econometrics</span>
            <span class="interest-badge">Causal Inference</span>
            <span class="interest-badge">Deep Learning</span>
        </div>
    </div>
    
    <div class="section" id="education">
        <h2>Education</h2>
        <ul class="timeline">
            <li class="timeline-item">
                <div class="timeline-year">2025-2029 (Expected)</div>
                <div class="timeline-content">
                    <h4>PhD in Quantitative Marketing</h4>
                    <p>The University of Texas at Dallas</p>
                </div>
            </li>
            <li class="timeline-item">
                <div class="timeline-year">2023-2025</div>
                <div class="timeline-content">
                    <h4>Master of Business Research in Quantitative Marketing</h4>
                    <p>Temple University</p>
                </div>
            </li>
            <li class="timeline-item">
                <div class="timeline-year">2020-2023</div>
                <div class="timeline-content">
                    <h4>Master of Business Administration in Marketing</h4>
                    <p>Sharif University of Technology</p>
                </div>
            </li>
            <li class="timeline-item">
                <div class="timeline-year">2016-2020</div>
                <div class="timeline-content">
                    <h4>Bachelor of Science in Materials Engineering</h4>
                    <p>Iran University of Science and Technology</p>
                </div>
            </li>
        </ul>
    </div>
    
    <div class="section" id="publications">
        <h2>Publications</h2>
        <p>Shahhosseini, M., & Khalili Nasr, A. (2024). <a href="https://www.tandfonline.com/doi/abs/10.1080/10548408.2024.2306358">What attributes affect customer satisfaction in green restaurants? An aspect-based sentiment analysis approach.</a><br>
        <em>Journal of Travel & Tourism Marketing</em>, 41(4), 472–490.</p>
    </div>
    
    <div class="section" id="working-papers">
        <h2>Working Papers</h2>
        <ul>
            <li>"How to Sell in the Secondhand Market"</li>
            <li>"What Makes a Movie Trailer Great?"</li>
        </ul>
        
        <h3 style="margin-top: 1.5rem;">Work in Progress</h3>
        <ul>
            <li>"Customer Guided GenAI"</li>
            <li>"Livestreamers' Hidden Value"</li>
        </ul>
    </div>
    
    <div class="section" id="codes">
        <h2>Code Repositories</h2>
        <a href="https://github.com/MansourShahhosseini/LLM-Tutorial" class="code-repo">
            LLMs Tutorial - Introduction to LLMs for PhD students at Fox School of Business
        </a>
        <a href="https://github.com/MansourShahhosseini/Quantitative-Economics" class="code-repo">
            Quantitative Economics - Repository with economics code examples
        </a>
        <a href="https://github.com/MansourShahhosseini/Face-Photograph-Memorability-Score" class="code-repo">
            Face Memorability Prediction - Machine learning project predicting face memorability scores
        </a>
    </div>
    
    <div class="section" id="contact">
        <h2>Contact</h2>
        <div class="contact-links">
            <a href="mailto:mansour.shahhosseini@utdallas.edu" class="contact-link">
                <img src="https://img.icons8.com/ios-filled/20/3182ce/new-post.png" alt="Email"> Email
            </a>
            <a href="https://github.com/MansourShahhosseini" class="contact-link">
                <img src="https://img.icons8.com/ios-glyphs/20/3182ce/github.png" alt="GitHub"> GitHub
            </a>
            <a href="https://scholar.google.com/citations?user=8iK7T7EAAAAJ&hl=en" class="contact-link">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Google_Scholar_logo.svg/48px-Google_Scholar_logo.svg.png" width="20" height="20" alt="Google Scholar"> Google Scholar
            </a>
            <a href="https://www.linkedin.com/in/mansourshahhosseini/" class="contact-link">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/LinkedIn_icon_circle.svg/48px-LinkedIn_icon_circle.svg.png" width="20" height="20" alt="LinkedIn"> LinkedIn
            </a>
        </div>
    </div>
    
    <footer>
        <p>Life is not fair, nor is it unfair. It is what it is.</p>
    </footer>
</div>
