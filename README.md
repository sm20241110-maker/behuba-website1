<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>BeHuBa | We Do It</title>

<style>
:root {
  --bg-dark: #0f172a;
  --bg-card: #1e293b;
  --primary: #2563eb;
  --accent: #60a5fa;
  --muted: #cbd5f5;
}

* { box-sizing: border-box; }

body {
  margin: 0;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  background: var(--bg-dark);
  color: #ffffff;
}

/* NAVBAR */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 40px;
  background: rgba(2,6,23,0.9);
  position: sticky;
  top: 0;
  z-index: 100;
}

nav .logo {
  font-size: 1.4rem;
  font-weight: 600;
  letter-spacing: 1px;
}

nav a {
  color: var(--muted);
  margin-left: 25px;
  text-decoration: none;
  font-size: 0.95rem;
}

nav a:hover { color: #fff; }

/* HERO */
header {
  padding: 110px 20px;
  text-align: center;
  background: linear-gradient(135deg, #2563eb, #1e40af);
}

header h1 {
  font-size: 3.2rem;
  margin-bottom: 15px;
  letter-spacing: 2px;
}

header p {
  font-size: 1.3rem;
  max-width: 720px;
  margin: auto;
  opacity: 0.95;
}

/* SECTIONS */
section {
  padding: 80px 20px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  text-align: center;
  font-size: 2.2rem;
  margin-bottom: 20px;
  color: var(--accent);
}

/* ABOUT */
.about p {
  text-align: center;
  max-width: 820px;
  margin: auto;
  font-size: 1.1rem;
  color: #e5e7eb;
  line-height: 1.7;
}

/* FOUNDERS */
.founders {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin-top: 40px;
  flex-wrap: wrap;
}

.founder-card {
  background: var(--bg-card);
  padding: 25px 30px;
  border-radius: 14px;
  min-width: 260px;
  text-align: center;
  box-shadow: 0 12px 30px rgba(0,0,0,0.35);
}

.founder-card h3 {
  margin-bottom: 8px;
  color: #93c5fd;
  font-size: 1.2rem;
}

.founder-card p {
  color: #d1d5db;
  font-size: 0.95rem;
}

/* SERVICES */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
  margin-top: 50px;
}

.card {
  background: var(--bg-card);
  padding: 30px;
  border-radius: 14px;
  box-shadow: 0 15px 35px rgba(0,0,0,0.35);
  transition: transform 0.3s ease;
}

.card:hover { transform: translateY(-8px); }

.card h3 {
  margin-bottom: 12px;
  color: #93c5fd;
  font-size: 1.25rem;
}

.card p {
  color: #d1d5db;
  line-height: 1.6;
}

/* CONTACT */
.contact {
  text-align: center;
}

.contact p {
  margin: 10px 0;
  font-size: 1.05rem;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: #020617;
  font-size: 0.9rem;
  color: #9ca3af;
}

/* CHATBOT */
#chatbot-btn {
  position: fixed;
  bottom: 25px;
  right: 25px;
  background: var(--primary);
  color: white;
  border: none;
  padding: 15px 18px;
  border-radius: 50%;
  font-size: 20px;
  cursor: pointer;
  box-shadow: 0 10px 25px rgba(0,0,0,0.4);
}

#chatbot {
  position: fixed;
  bottom: 90px;
  right: 25px;
  width: 300px;
  height: 380px;
  background: #020617;
  border-radius: 12px;
  display: none;
  flex-direction: column;
  overflow: hidden;
  box-shadow: 0 15px 40px rgba(0,0,0,0.6);
}

#chatbot header {
  padding: 12px;
  background: var(--primary);
  font-size: 0.95rem;
}

#chatbot iframe {
  flex: 1;
  border: none;
}
</style>
</head>

<body>

<nav>
  <div class="logo">BeHuBa</div>
  <div>
    <a href="#about">About</a>
    <a href="#founders">Founders</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<header>
  <h1>BeHuBa</h1>
  <p>We Do It — execution-focused technology, security, and automation solutions.</p>
</header>

<section id="about" class="about">
  <h2>About Us</h2>
  <p>
    BeHuBa is built on a simple principle: execution matters.
    We focus on delivering real-world technology, cybersecurity,
    automation, and AI solutions that work beyond theory.
  </p>
</section>

<section id="founders">
  <h2>Founders</h2>
  <div class="founders">
    <div class="founder-card">
      <h3>Sahana C Y</h3>
      <p>Co-Founder</p>
    </div>
    <div class="founder-card">
      <h3>Manasa B M</h3>
      <p>Co-Founder</p>
    </div>
  </div>
</section>

<section id="services">
  <h2>What We Do</h2>
  <div class="services">
    <div class="card">
      <h3>Technology Engineering</h3>
      <p>Design and development of scalable, secure, production-ready systems.</p>
    </div>
    <div class="card">
      <h3>Cybersecurity & DFIR</h3>
      <p>Detection engineering, incident response, SOC automation, and investigations.</p>
    </div>
    <div class="card">
      <h3>Automation & AI</h3>
      <p>Workflow automation and AI-assisted solutions to reduce operational load.</p>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact</h2>
  <p>Email: contact@behuba.in</p>
  <p>Website: https://behuba.in</p>
</section>

<footer>
  © 2026 BeHuBa.in | We Do It
</footer>

<button id="chatbot-btn">💬</button>

<div id="chatbot">
  <header>BeHuBa Assistant</header>
  <iframe src="https://example.com"></iframe>
</div>

<script>
const btn = document.getElementById("chatbot-btn");
const bot = document.getElementById("chatbot");
btn.onclick = () => {
  bot.style.display = bot.style.display === "flex" ? "none" : "flex";
};
</script>

</body>
</html>
