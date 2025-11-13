<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Meaghan Ince, a science communicator specializing in oncology, AI research storytelling, and strategic communication.">
    <title>Meaghan Ince - Science Communication Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Montserrat', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #2c3e50;
            background: #ffffff;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            overflow: hidden;
        }
        
        header {
            background: #0b5394;
            color: white;
            padding: 60px 40px;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 900;
        }
        
        header p {
            font-size: 1.2em;
            opacity: 0.95;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .contact-links {
            margin-top: 25px;
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .contact-links a {
            flex: 1;
            text-align: center;
            color: white;
            text-decoration: none;
            padding: 10px;
            background: rgba(255,255,255,0.2);
            border-radius: 8px;
            transition: all 0.3s;
            backdrop-filter: blur(5px);
        }
        
        .contact-links a:hover {
            background: rgba(255,255,255,0.3);
            transform: translateY(-2px);
        }
        
        main {
            padding: 60px 40px;
        }
        
        .section {
            margin-bottom: 60px;
        }
        
        .section h2 {
            font-size: 2em;
            margin-bottom: 30px;
            color: #0b5394;
            position: relative;
            padding-bottom: 10px;
        }
        
        .section h2:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 60px;
            height: 4px;
            background: #0b5394;
            border-radius: 2px;
        }
        
        .about {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #667eea;
        }
        
        .about p {
            margin-bottom: 15px;
            font-size: 1.05em;
        }
        
        .work-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .work-item {
            background: white;
            border: 2px solid #e9ecef;
            border-radius: 15px;
            padding: 30px;
            transition: all 0.3s;
            cursor: pointer;
        }
        
        .work-item:hover {
            border-color: #667eea;
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.2);
        }
        
        .work-item h3 {
            color: #667eea;
            margin-bottom: 10px;
            font-size: 1.4em;
        }
        
        .work-type {
            display: inline-block;
            padding: 5px 15px;
            background: #031b31;
            color: white;
            border-radius: 20px;
            font-size: 0.85em;
            margin-bottom: 15px;
        }
        
        .work-item p {
            color: #5a5a5a;
            margin-bottom: 15px;
        }
        
        .work-item .metrics {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            margin-top: 15px;
            font-size: 0.95em;
        }
        
        .work-item .link {
            display: inline-block;
            margin-top: 15px;
            color: #667eea;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
        }
        
        .work-item .link:hover {
            color: #764ba2;
            transform: translateX(5px);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .skill-category {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 15px;
            border-top: 4px solid #667eea;
        }
        
        .skill-category h3 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 1.2em;
        }
        
        .skill-category ul {
            list-style: none;
        }
        
        .skill-category li {
            padding: 8px 0;
            color: #5a5a5a;
            position: relative;
            padding-left: 20px;
        }
        
        .skill-category li:before {
            content: '→';
            position: absolute;
            left: 0;
            color: #667eea;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 30px;
        }

        footer p {
            margin-top: 10px;
            font-size: 0.9em;
            opacity: 0.8;
        }
        
        @media (max-width: 768px) {
            header {
                padding: 40px 20px;
            }
            
            header h1 {
                font-size: 2em;
            }
            
            main {
                padding: 40px 20px;
            }
            
            .work-grid, .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Meaghan Ince</h1>
            <p>Science Communicator | Content Strategist | Research Storyteller</p>
            <div class="contact-links">
                <a href="mailto:meaghan.ince@gmail.com">Email</a>
                <a href="https://www.linkedin.com/in/meaghanince" target="_blank" rel="noopener noreferrer">LinkedIn</a>
                <a href="tel:+14167378126">416-737-8126</a>
            </div>
<p><strong>My work lives at the intersection of science, storytelling, and strategic communication.</strong>
            <p><strong>Current Focus:</strong> Exploring the transformative potential of AI in scientific discovery and how to communicate responsibly about emerging technologies that will reshape research.</p>
                </div>
        </header>
        
        <main>
            <section class="section">
                <h2>About Me</h2>
                <div class="about">
                    I am a science communicator dedicated to bridging the gap between science and the community I serve. Over the past four years, I have honed my expertise in translating cutting-edge oncology research, including immunotherapy advancements and emerging AI applications in cancer care, into meaningful content that informs, inspires, and drives engagement among patients, donors, researchers, and policymakers.
                    I am committed to elevating research by helping communities understand the "why" behind science. <em>The future is exciting</em> and when people understand that message, it builds trust, inspires action, and helps accelerate innovation.</p>
            </section>

            <section class="section">
                <h2>Selected Work</h2>
                <div class="work-grid">
                    <div class="work-item">
                        <span class="work-type">Science Communication</span>
                        <h3>AI in Ovarian Cancer Research Coalition</h3>
                        <p>Profiled global coalition of research organizations funding AI applications in ovarian cancer research.</p>
                        <div class="metrics">
                            <strong>Impact:</strong> Positioned organization as thought leader in AI-driven cancer research innovation; engaged diverse stakeholder groups including researchers, patients, and funders.
                        </div>
                        <a href="https://ovariancanada.org/news-stories/global-ovarian-cancer-research-consortium-ai-accelerator-grant" target="_blank" rel="noopener noreferrer" class="link">Read Article →</a>
                    </div>
                    
                    <div class="work-item">
                        <span class="work-type">Video Series</span>
                        <h3>Researcher Spotlight</h3>
                        <p>Directed and produced video featuring leading ovarian cancer researchers explaining their work in pioneering the first ever early detection test for ovarian cancer.</p>
                        <div class="metrics">
                            <strong>Impact:</strong> 600% YoY growth in social media engagement; strengthened donor relationships through transparent research communication.
                        </div>
                        <a href="(https://youtu.be/XdSiDfdl4Nw" target="_blank" rel="noopener noreferrer)" class="link">Watch Sample Video →</a>
                    </div>
                    
                    <div class="work-item">
                        <span class="work-type">Campaign Strategy</span>
                        <h3>Walk of Hope Campaign</h3>
                        <p>Led integrated marketing strategy for flagship fundraising initiative, developing data-informed content across email, social, web, and print channels to drive engagement and donations.</p>
                        <div class="metrics">
                            <strong>Impact:</strong> Generated ~$1.5M in revenue with 3% YoY growth; managed cross-functional team across marketing, events, and development.
                        </div>
                        <a href="https://drive.google.com/file/d/1Z7SoypfukbXznklw2lctwlmhRVx7Met3/view?usp=sharing" target="_blank" rel="noopener noreferrer" class="link">View Case Study →</a>
                    </div>
                    
                    <div class="work-item">
                        <span class="work-type">Brand Development</span>
                        <h3>Organizational Rebrand</h3>
                        <p>Played a key role in strategic discussions on visual identity, voice, and tone for organizational rebrand, ensuring science communication aligned with refreshed brand while maintaining credibility with research community.</p>
                        <div class="metrics">
                            <strong>Impact:</strong> Seamless rebranding process with overwhelmingly positive stakeholder sentiment; stronger brand recognition and consistency.
                        </div>
                        <a href="https://drive.google.com/file/d/1QHQktuxVHwww4H7TXIyg4S_n6eY66g_p/view?usp=sharing" target="_blank" rel="noopener noreferrer" class="link">View Brand Guide →</a>
                    </div>
                    
                    <div class="work-item">
                        <span class="work-type">Stakeholder Engagement</span>
                        <h3>Highlighting Government Advocacy Efforts</h3>
                        <p>Profiled organization advocacy initiatives aimed at securing increased funding for prevention initiatives related to ovarian cancer.</p>
                        <div class="metrics">
                            <strong>Impact:</strong> Strengthened relationships with key government stakeholders; contributed to increased advocacy impact.
                        </div>
                        <a href="https://ovariancanada.org/news-stories/ontario-mpps-hear-ovarian-cancer-canadas-call-for-action" target="_blank" rel="noopener noreferrer" class="link">Learn More →</a>
                    </div>
                </div>
            </section>
            
            <section class="section">
                <h2>Skills & Expertise</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <h3>Science Communication</h3>
                        <ul>
                            <li>Biomedical research translation</li>
                            <li>Cancer biology & oncology</li>
                            <li>Clinical trial methodologies</li>
                            <li>AI in scientific research</li>
                            <li>Multi-audience engagement</li>
                        </ul>
                    </div>
                    
                    <div class="skill-category">
                        <h3>Content Creation</h3>
                        <ul>
                            <li>Long & short-form writing</li>
                            <li>Video production & editing</li>
                            <li>Graphic design</li>
                            <li>Social media content</li>
                            <li>Campaign strategy</li>
                        </ul>
                    </div>
                    
                    <div class="skill-category">
                        <h3>Strategic Skills</h3>
                        <ul>
                            <li>Data-driven content strategy</li>
                            <li>Audience research & insights</li>
                            <li>Cross-functional collaboration</li>
                            <li>Brand development</li>
                            <li>Stakeholder engagement</li>
                        </ul>
                    </div>
                    
                    <div class="skill-category">
                        <h3>Technical Tools</h3>
                        <ul>
                            <li>Adobe Creative Suite</li>
                            <li>Premiere Pro (video editing)</li>
                            <li>Canva Pro</li>
                            <li>Google Analytics</li>
                            <li>Project management tools</li>
                        </ul>
                    </div>
                </div>
            </section>
        </main>
        
        <footer>
            <p>© 2024 Meaghan Ince | Science Communication Portfolio</p>
            <p>Translating complex science into compelling stories</p>
        </footer>
    </div>
</body>
</html>
