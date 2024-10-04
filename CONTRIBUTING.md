<-- this is my html code of corsera first module--> 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="stylessss.css">
</head>
<body>
    <header>
        <div class="left-header">
            <h1>Jane Doe</h1>
            <p>Email: jane.doe@email.com</p>
            <p>Contact: +1234567890</p>
        </div>
        <nav class="right-header">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#recommendations">Recommendations</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="https://img.freepik.com/free-vector/blue-circle-with-white-user_78370-4707.jpg" alt="Jane Doe">
        <p>Hi, I'm Jane Doe, a passionate web developer with 4+ years of experience in HTML, CSS, and JavaScript. I love building responsive and dynamic web applications that deliver great user experiences. In addition to web development, I have worked on numerous projects involving JavaScript frameworks such as React and Node.js.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill-box">
                <img src="https://cdn4.iconfinder.com/data/icons/flat-brand-logo-2/512/html5-512.png" alt="HTML">
                <h3>HTML</h3>
                <p>4 years experience</p>
            </div>
            <div class="skill-box">
                <img src="https://banner2.cleanpng.com/20180605/yjb/aa9yal4pp.webp" alt="JavaScript">
                <h3>JavaScript</h3>
                <p>3 years experience</p>
            </div>
            <div class="skill-box">
                <img src="https://cdn.iconscout.com/icon/free/png-256/free-css3-logo-icon-download-in-svg-png-gif-file-formats--css-wordmark-programming-langugae-language-pack-logos-icons-1175200.png?f=webp&w=256" alt="CSS">
                <h3>CSS</h3>
                <p>4 years experience</p>
            </div>
            <div class="skill-box">
                <img src="https://w7.pngwing.com/pngs/235/872/png-transparent-react-computer-icons-redux-javascript-others-logo-symmetry-nodejs-thumbnail.png" alt="React">
                <h3>React</h3>
                <p>2 years experience</p>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1: Chatbot</h3>
            <p>Developed an interactive chatbot for an automation service that helps customers with booking queries.</p>
        </div>
        <div class="project">
            <h3>Project 2: Sentiment Analyzer</h3>
            <p>Worked on a sentiment analysis tool that processes live social media feeds to give real-time feedback.</p>
        </div>
        <div class="project">
            <h3>Project 3: Fashion Website</h3>
            <p>Created a responsive fashion e-commerce website optimized for mobile devices and integrated with a shopping cart system.</p>
        </div>
    </section>

    <!-- Recommendations Section -->
    <section id="recommendations">
        <h2>Recommendations</h2>
        <div class="recommendation">
            <p>Jane is a very detail-oriented and hardworking web developer. She always meets the deadlines and delivers excellent work. - Client A</p>
        </div>
        <div class="recommendation">
            <p>Working with Jane has been an amazing experience. Her ability to solve problems is exceptional. - Client B</p>
        </div>
        <div class="recommendation">
            <p>Jane is highly skilled in JavaScript frameworks and is a fantastic team player. - Client C</p>
        </div>

        <h3>Recent Recommendations</h3>
        <div class="recent-recommendation">
            <p>Jane's latest project has truly exceeded my expectations. She is creative and innovative. - Client D</p>
        </div>
    </section>

    <!-- Submit Recommendation Form -->
    <section id="submit-recommendation">
        <h2>Leave a Recommendation</h2>
        <form id="recommendationForm">
            <textarea name="recommendation" id="recommendation" placeholder="Enter your recommendation here..."></textarea>
            <button type="submit">Submit</button>
        </form>
        <div id="popup" class="popup">
            <p>Thank you for your recommendation!</p>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
