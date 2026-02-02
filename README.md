<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>J. Rishikeshwar - Portfolio</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@200..1000&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Nunito Sans", sans-serif;
}

:root {
    --bg-color: #191f36;
    --snd-bg-color: #262B40;
    --text-color: #fff;
    --main-color: #59B2F4;
}

body {
    background: var(--bg-color);
    color: var(--text-color);
}

section {
    min-height: 100vh;
    padding: 10rem 9% 2rem;
}

/* Header */
.header {
    position: fixed;
    top: 0;
    width: 100%;
    padding: 2rem 9%;
    background: var(--bg-color);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}

.logo {
    font-size: 2.5rem;
    color: var(--main-color);
    font-weight: 700;
}

.navbar a {
    font-size: 1.5rem;
    color: var(--text-color);
    margin-left: 2rem;
}

.navbar a.active,
.navbar a:hover {
    color: var(--main-color);
}

/* Home */
.home {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.home-content h1 {
    font-size: 5.6rem;
}

.home-content h3 {
    font-size: 3rem;
}

.home-img img {
    width: 25vw;
    border-radius: 10px;
    border: 3px solid var(--main-color);
}

/* Skills */
.skills-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
}

.skill-card {
    border: 2px solid var(--main-color);
    padding: 2rem;
    border-radius: 10px;
}

/* Footer */
.footer {
    text-align: center;
    padding: 2rem;
}
    </style>
</head>

<body>

<header class="header">
    <a href="#home" class="logo">Portfolio</a>
    <nav class="navbar">
        <a href="#home" class="active">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="home" id="home">
    <div class="home-content">
        <h3>Hi, Myself</h3>
        <h1>J. Rishikeshwar</h1>
        <h3>And I'm a <span class="multiple-text">Software Developer</span></h3>
        <p>MST graduate with strong skills in C, C++, Java, HTML, CSS, JavaScript, and MySQL.</p>
        <a href="#" class="btn">Download CV</a>
    </div>
    <div class="home-img">
        <img src="profile.jpg" alt="Profile Image">
    </div>
</section>

<section class="skills" id="skills">
    <h2>My Skills</h2>
    <div class="skills-container">
        <div class="skill-card">C</div>
        <div class="skill-card">C++</div>
        <div class="skill-card">Java</div>
        <div class="skill-card">HTML</div>
        <div class="skill-card">CSS</div>
        <div class="skill-card">JavaScript</div>
        <div class="skill-card">MySQL</div>
    </div>
</section>

<footer class="footer">
    <p>&copy; 2026 J. Rishikeshwar. All rights reserved.</p>
</footer>

</body>
</html>
