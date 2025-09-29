# mithil
Independent Project | Launched at age 15
Tech Stack: HTML, CSS (or mention the platform you used — e.g., Google Sites, Wix, GitHub Pages)

Built and published a personal website at age 15 to explore web design and digital creativity. The project focused on experimenting with layout design, visual storytelling, and user-friendly navigation. Though created for fun, the process involved learning foundational web technologies and understanding how websites are structured and deployed online.

Hosted the site using [MITHILTHEdeveloper, e.g., GitHub Pages], and designed all content and visuals independently. This early project sparked a deeper interest in web development and self-driven learning.
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Your Site Title</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial;margin:0;color:#111}
    header{background:#0a84ff;color:white;padding:2rem;text-align:center}
    main{max-width:900px;margin:2rem auto;padding:0 1rem}
    .grid{display:grid;grid-template-columns:1fr;gap:1rem}
    @media(min-width:700px){.grid{grid-template-columns:repeat(2,1fr)}}
    footer{padding:1rem;text-align:center;color:#666}
    a{color:#0a84ff}
    .btn{display:inline-block;background:#0a84ff;color:white;padding:.5rem 1rem;border-radius:6px;text-decoration:none}
  </style>
</head>
<body>
  <header>
    <h1>Your Site Title</h1>
    <p>Short tagline — what this site is about</p>
  </header>
  <main>
    <section class="grid">
      <div>
        <h2>About</h2>
        <p>Write a short intro about you or your project.</p>
      </div>
      <div>
        <h2>Latest</h2>
        <p>Post updates, links, or a call to action.</p>
      </div>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
      <p><a class="btn" href="#contact">Get in touch</a></p>
    </section>
  </main>

  <footer>
    <small>© <span id="year"></span> Your Name — Built with GitHub Pages</small>
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
