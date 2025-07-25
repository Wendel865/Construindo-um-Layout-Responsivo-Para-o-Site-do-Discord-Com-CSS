# Construindo-um-Layout-Responsivo-Para-o-Site-do-Discord-Com-CSS
/* style.css */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #5865F2;
  color: #fff;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

header {
  background-color: #404EED;
  padding: 20px 0;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 80px 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.btn {
  background-color: #ffffff;
  color: #5865F2;
  padding: 12px 30px;
  border-radius: 5px;
  font-weight: bold;
  text-decoration: none;
}

/* Responsivo */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
    align-items: center;
  }

  .hero h2 {
    font-size: 2rem;
  }

  .hero p {
    font-size: 1rem;
  }
}
