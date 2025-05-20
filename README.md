<!-- README.md -->

<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }
  header {
    background-color: #003366;
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 2em;
    font-weight: bold;
  }
  .container {
    display: flex;
    height: 90vh;
  }
  nav {
    width: 200px;
    background-color: #f4f4f4;
    padding: 15px;
    box-shadow: 2px 0 5px rgba(0,0,0,0.1);
  }
  nav a {
    display: block;
    margin: 10px 0;
    text-decoration: none;
    color: #003366;
    font-weight: bold;
  }
  nav a:hover {
    text-decoration: underline;
  }
  main {
    flex: 1;
    padding: 20px;
    overflow-y: auto;
  }
  section {
    display: none;
  }
  section:target {
    display: block;
  }
</style>

<header>DWS</header>

<div class="container">
  <nav>
    <a href="#section1">Home</a>
    <a href="#section2">About</a>
    <a href="#section3">Contact</a>
  </nav>

  <main>
    <section id="section1">
      <h2>Welcome to DWS</h2>
      <p>This is the home section. You can customize this with your own content.</p>
    </section>

    <section id="section2">
      <h2>About DWS</h2>
      <p>DWS stands for Digital Web Solutions. We build beautiful, fast, and accessible websites.</p>
    </section>

    <section id="section3">
      <h2>Contact Us</h2>
      <p>Email us at: <a href="mailto:contact@dws.com">contact@dws.com</a></p>
    </section>
  </main>
</div>
