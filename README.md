# verdurecena
Vegetarian Italian Menu
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Verdure Cena </title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Verdure Cena</h1>
    <nav>
      <ul>
        <li><a href="#mains">Mains</a></li>
        <li><a href="#desserts">Desserts</a></li>
        <li><a href="#drinks">Drinks</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>"The flavor of food is not in meat, but in care."</h2>
    <p>- Chef Giovanni</p>
  </section>

  <section id="mains">
    <h3>Main Dishes</h3>
    <ul>
      <li>Gnocchi al Pesto</li>
      <li>Lasagna Verdure</li>
      <li>Eggplant Parmigiana</li>
    </ul>
  </section>

  <section id="desserts">
    <h3>Desserts</h3>
    <ul>
      <li>Tiramisu</li>
      <li>Chocolate Hazelnut Tart</li>
      <li>Lemon Sorbetto</li>
    </ul>
  </section>

  <section id="drinks">

    <h3>Drinks</h3>
    <ul>
      <li>Limoncello Spritz</li>
      <li>Bellini</li>
      <li>Herbal Tea Selection</li>
    </ul>
  </section>

  <section id="contact">
    <h3>Contact Us</h3>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>

    rdure Cena - my custom Sage Green colour and Style */

body {
  margin: 0;
  font-family: 'Georgia', serif;
  background-color: #f9f9f6;
  color: #333;
}

header {
  background-color: #a3b18a; /* Sage green */
  color: white;
  padding: 2rem;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2.5rem;
  letter-spacing: 1px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
  margin-top: 1rem;
  gap: 2rem;
}

nav a {
  text-decoration: none;
  color: white;
  font-weight: bold;
  font-size: 1.1rem;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background-color: #dde5d0;
  text-align: center;
  padding: 4rem 2rem;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

.hero p {
  font-size: 1.2rem;
}

section {
  padding: 3rem 2rem;
  max-width: 800px;
  margin: auto;
}

section h3 {
  font-size: 1.8rem;
  color: #4a6741;
  border-bottom: 2px solid #a3b18a;
  padding-bottom: 0.5rem;
}

ul li {
  margin: 0.5rem 0;
  font-size: 1.1rem;
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

input, textarea, button {
  font-family: inherit;
  font-size: 1rem;
  padding: 0.75rem;
  border: 1px solid #ccc;
  border-radius: 6px;
}

button {
  background-color: #a3b18a;
  color: white;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #87986a;
}

footer {
  background-color: #4a6741;
  color: white;
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
}

@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
    gap: 1rem;
  }

  header h1 {
    font-size: 2rem;
  }

  section {
    padding: 2rem 1rem;
  }
}
    <p>&copy; 2025 Verdure Cena. All rights reserved.</p>
  </footer>
</body>
</html>
