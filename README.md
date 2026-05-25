## Hi ther 👋
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Flow State Environmental</title>
  <meta name="description" content="Environmental services, consulting, and sustainable solutions." />

  <style>
    :root {
      --bg: #0b1220;
      --card: #111b2e;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #22c55e;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      min-height: 70vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(135deg, #0b1220, #0f2a1f);
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
    }

    header p {
      color: var(--muted);
      font-size: 1.2rem;
      max-width: 600px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 20px;
      background: var(--accent);
      color: black;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
      background: #0f172a;
      position: sticky;
      top: 0;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }

    h2 {
      margin-bottom: 20px;
      font-size: 2rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: var(--card);
      padding: 20px;
      border-radius: 12px;
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    footer {
      text-align: center;
      padding: 30px;
      color: var(--muted);
      background: #050a14;
    }
  </style>
</head>
<body>

  <header>
    <h1>Flow State Environmental</h1>
    <p>Sustainable environmental solutions, consulting, and field services built for a cleaner future.</p>
    <a class="btn" href="#contact">Get in Touch</a>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <div class="card">
      We provide environmental consulting and field services focused on sustainability, compliance, and restoration projects. Our goal is to help organizations reduce environmental impact while improving operational efficiency.
    </div>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="grid">
      <div class="card">
        <h3>Environmental Consulting</h3>
        <p>Regulatory guidance, impact assessments, and compliance strategy.</p>
      </div>
      <div class="card">
        <h3>Field Services</h3>
        <p>On-site inspections, sampling, and environmental monitoring.</p>
      </div>
      <div class="card">
        <h3>Restoration Planning</h3>
        <p>Ecosystem recovery and sustainable land-use strategies.</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="grid">
      <div class="card">
        <h3>Wetland Restoration</h3>
        <p>Rehabilitation of degraded wetland ecosystems to improve biodiversity.</p>
      </div>
      <div class="card">
        <h3>Site Assessment Program</h3>
        <p>Comprehensive environmental site evaluations for development projects.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Email: contact@flowstateenvironmental.com</p>
      <p>Phone: (your number here)</p>
    </div>
  </section>

  <footer>
    © 2026 Flow State Environmental. All rights reserved.
  </footer>

</body>
</html>
<!--
**FlowStateEnv/FlowStateEnv** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
