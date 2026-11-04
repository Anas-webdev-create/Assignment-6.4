<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Positioning Practice</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="hero" id="home">
    <h1>Positioning Practice</h1>
    <p>Scroll the page to see sticky, fixed, and absolute positioning.</p>
  </header>

  <nav class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about" class="section">
      <h2>About</h2>
      <p>This section gives the page enough content to scroll. The navigation bar sticks to the top of the screen while scrolling.</p>
    </section>

    <section id="services" class="section">
      <h2>Featured Service</h2>
      <article class="card">
        <span class="badge">NEW</span>
        <h3>Website Design</h3>
        <p>Our design service helps create a clear and welcoming online presence.</p>
      </article>
    </section>

    <section id="contact" class="section">
      <h2>Contact</h2>
      <p>Use the floating Help button in the bottom-right corner to get in touch.</p>
    </section>
  </main>

  <a class="help-button" href="mailto:help@example.com">Help</a>
</body>
</html>