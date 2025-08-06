# Rohit Banerjee – Personal Portfolio

This is a responsive personal portfolio website built using HTML, CSS, and JavaScript. It showcases professional experience, education, skills, certifications, and accomplishments. The site features a modern layout with smooth navigation and an interactive contact form. It is mobile-friendly and ideal for presenting a clean personal profile to recruiters, collaborators, or clients.

## Sections Included

- About
- Experience
- Education
- Skills
- Accomplishments
- Certifications
- Contact Form

## Author

**Pritam Baidya**  # portfolio-interactive-
This is a responsive portfolio website built with HTML, CSS, and JavaScript. It highlights skills, experience, and certifications with a clean design and contact form—ideal for showcasing a professional profile.

**code here-**

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <nav>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#accomplishments">Accomplishments</a></li>
        <li><a href="#certifications">Certifications</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <h1>Rohit Banerjee</h1>
  </header>

  <main>
    <section id="about" class="section about-section">
      <div class="profile-image-container">
        <img src="profile.jpg" alt="Rohit Banerjee" class="profile-image" />
      </div>
      <div class="about-text">
        <h2>About Me</h2>
        <p>
          Dynamic and results-driven professional with experience at Deloitte, where I developed impactful dashboards using Tableau and optimized database structures. Proficient in Python programming and full stack development, excelling in effective communication and user experience design. Enthusiastic student with strong work ethic and excellent organizational skills.
        </p>
        <ul class="contact-info">
          <li>Email: <a href="mailto:rohitbanerjeeerick@gmail.com">rohitbanerjeeerick@gmail.com</a></li>
          <li>Phone: +917478043023</li>
          <li>Location: Memari, India 713146</li>
          <li>LinkedIn: <a href="https://linkedin.com/in/rohit-banerjee-b833021b6" target="_blank" rel="noopener">linkedin.com/in/rohit-banerjee-b833021b6</a></li>
        </ul>
      </div>
    </section>

    <section id="skills" class="section">
      <h2>Skills</h2>
      <p>
        Full stack development • Python programming • Data analysis • Django framework • User interface design • User experience design • Effective communication
      </p>
    </section>

    <section id="experience" class="section">
      <h2>Experience</h2>
      <div class="experience-item">
        <h3>DELOITTE, Intern</h3>
        <span class="date-location">05/2025 – 05/2025, Kalyani, IN</span>
        <ul>
          <li>Developed dashboards with Tableau to monitor key performance indicators.</li>
          <li>Optimized existing database structures for better performance on analytics tasks.</li>
        </ul>
      </div>
      <div class="experience-item">
        <h3>Amazon Web Service, Intern</h3>
        <span class="date-location">01/2025 – 04/2025, Kalyani, IN</span>
        <ul>
          <li>Involved in troubleshooting issues related to serverless architectures running on AWS Lambda functions or API Gateway endpoints.</li>
          <li>Ensured compliance with security policies through periodic audits and reviews of all resources hosted on AWS platform.</li>
        </ul>
      </div>
    </section>

    <section id="education" class="section">
      <h2>Education and Training</h2>
      <div class="education-item">
        <h3>Bachelor of Science, B.TECH (CSE)</h3>
        <span class="date-location">06/2027, Kalyani, West Bengal</span>
        <p>JIS College of Engineering</p>
      </div>
      <div class="education-item">
        <h3>Associate of Science</h3>
        <span class="date-location">04/2022, Memari, West Bengal</span>
        <p>Physics, Chemistry, Math, Biology, Memari VM Institution (Unit-1)</p>
      </div>
    </section>

    <section id="accomplishments" class="section">
      <h2>Accomplishments</h2>
      <ul>
        <li>5th IEMHacks Hackathon</li>
        <li>7th in AEC hardware based competition</li>
      </ul>
    </section>

    <section id="certifications" class="section">
      <h2>Certifications</h2>
      <div class="certification-item">
        <h3>Accenture UK - Introduction to Technology Apprenticeship Job Simulation</h3>
        <p>(May 2025) - Gained insights into technology apprenticeships.</p>
      </div>
      <div class="certification-item">
        <h3>Deloitte Australia - Data Analytics Job Simulation</h3>
        <p>(May 2025 - Dec 2035) Developed analytical skills and experience with complex datasets.</p>
      </div>
      <div class="certification-item">
        <h3>Fundamentals of Digital Marketing</h3>
        <p>(Google, May 2025) - Certified in core digital marketing principles.</p>
      </div>
      <div class="certification-item">
        <h3>Introduction to Generative AI</h3>
        <p>(Google, May 2025) - Learned key concepts in generative AI.</p>
      </div>
      <div class="certification-item">
        <h3>AWS Academy Cloud Foundations</h3>
        <p>(AWS, Feb 2025) - Built a strong foundation in AWS services, cloud architecture, and security.</p>
      </div>
      <div class="certification-item">
        <h3>AWS Academy Machine Learning Foundations</h3>
        <p>(AWS, Mar 2025) - Hands-on training in supervised/unsupervised learning, data prep, and ML model evaluation.</p>
      </div>
      <div class="certification-item">
        <h3>AWS AI-ML Virtual Internship</h3>
        <p>(Jan 2025 - Mar 2025) - Gained hands-on experience in AI and ML applications through EduSkills & AICTE.</p>
      </div>
    </section>

    <section id="contact" class="section">
      <h2>Contact</h2>
      <form id="contact-form">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>© 2024 My Portfolio. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>


