# fashion
Fashion is the creativity of styles in shapes
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lamodeve Lookbook</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    form {
      margin-top: 30px;
    }
    input, textarea, button {
      display: block;
      width: 100%;
      margin-bottom: 15px;
      padding: 10px;
      font-size: 1rem;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lamodeve Lookbook</h1>
    <p>Models & Fashion Designers Showcase</p>
  </header>
  <nav>
    <a href="#models">Models Lookbook</a>
    <a href="#designers">Fashion Designers Lookbook</a>
    <a href="#register">Register</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="models">
    <h2>Models Lookbook</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x400?text=Model+1" alt="Model 1">
      <img src="https://via.placeholder.com/300x400?text=Model+2" alt="Model 2">
      <img src="https://via.placeholder.com/300x400?text=Model+3" alt="Model 3">
    </div>
  </section>  <section id="designers">
    <h2>Fashion Designers Lookbook</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x400?text=Design+1" alt="Design 1">
      <img src="https://via.placeholder.com/300x400?text=Design+2" alt="Design 2">
      <img src="https://via.placeholder.com/300x400?text=Design+3" alt="Design 3">
    </div>
  </section>  <section id="register">
    <h2>Register to Participate</h2>
    <form>
      <input type="text" placeholder="Full Name" required />
      <input type="email" placeholder="Email Address" required />
      <input type="tel" placeholder="Phone Number" required />
      <textarea placeholder="Tell us about yourself..." rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: mm2zevents@gmail.com</p>
    <p>Phone: +2348161346422</p>
  </section>  <footer>
    &copy; 2025 Lamodeve. All rights reserved.
  </footer>
</body>
</html>