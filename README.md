## Hi there 👋
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jaypph | Game Developer Portfolio</title>

  <style>
    :root {
      --bg: #0b0f1a;
      --card: #121a2a;
      --accent: #6cf0ff;
      --text: #e6f1ff;
      --muted: #9fb3c8;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #14203a, var(--bg));
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      color: var(--accent);
    }

    header p {
      color: var(--muted);
      margin-top: 10px;
      font-size: 1.2rem;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    .section-title {
      margin: 40px 0 20px;
      font-size: 1.5rem;
      color: var(--accent);
    }

    .card {
      background: var(--card);
      padding: 20px;
      border-radius: 14px;
      margin-bottom: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .project-title {
      font-size: 1.3rem;
      color: var(--text);
    }

    .tag {
      display: inline-block;
      margin-top: 8px;
      padding: 4px 10px;
      border-radius: 999px;
      background: rgba(108,240,255,0.15);
      color: var(--accent);
      font-size: 0.8rem;
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      color: var(--muted);
      font-size: 0.9rem;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 16px;
      border: 1px solid var(--accent);
      border-radius: 8px;
      color: var(--accent);
      transition: 0.2s;
    }

    .btn:hover {
      background: var(--accent);
      color: #000;
    }
  </style>
</head>

<body>

  <header>
    <h1>Jaypph</h1>
    <p>Game Developer • Creative Builder • Indie Project Explorer</p>
  </header>

  <div class="container">

    <section>
      <h2 class="section-title">About</h2>
      <div class="card">
        <p>
          Welcome to my developer hub. I build games, experimental projects, and interactive web ideas.
          I focus on creative mechanics, immersive experiences, and fun prototypes that evolve over time.
        </p>
        <p style="margin-top:10px;">
          Hosted and shared via <strong><a href="https://github.com/">GitHub</a></strong>.
        </p>
      </div>
    </section>

    <section>
      <h2 class="section-title">Projects</h2>

      <div class="card">
        <div class="project-title">🚀 SpaceShoot</div>
        <span class="tag">Game</span>
        <p style="margin-top:10px;">
          A fast-paced space shooter built with a focus on arcade mechanics, explosions, and endless replayability.
          Designed to test reaction speed and pattern recognition.
        </p>
        <a class="btn" href="#">View Project</a>
      </div>

      <div class="card">
        <div class="project-title">🌐 VikLin.fun</div>
        <span class="tag">Web Platform</span>
        <p style="margin-top:10px;">
          A creative web experiment combining interactive features, playful UI, and lightweight design.
          Built as a sandbox for ideas and digital storytelling.
        </p>
        <a class="btn" href="#">Visit Site</a>
      </div>

      <div class="card">
        <div class="project-title">🧪 More Experiments</div>
        <span class="tag">Prototype</span>
        <p style="margin-top:10px;">
          Small prototypes, engines, and experimental systems that push mechanics and web interaction forward.
          Always evolving.
        </p>
      </div>

    </section>

    <section>
      <h2 class="section-title">Contact</h2>
      <div class="card">
        <p>
          Want to collaborate or follow development progress?
          Connect via GitHub or project links.
        </p>
        <a class="btn" href="https://github.com/">GitHub Profile</a>
      </div>
    </section>

  </div>

  <footer>
    © 2026 Jaypph — Built with curiosity, iteration, and classic developer craftsmanship.
  </footer>

</body>
</html>
<!--
**Jaypph/Jaypph** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
