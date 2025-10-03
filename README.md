# GARZON-INTERIORISMO-REFORMAS
Página web de Garzón Interiorismo &amp; Reformas
/* ===== Estilos Generales ===== */
body {
  margin: 0;
  font-family: "Segoe UI", Tahoma, sans-serif;
  color: #333;
}

header {
  background: #1a1a1a;
  color: white;
  padding: 15px 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header h1 {
  margin: 0;
  font-size: 1.5rem;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: 500;
}

nav a:hover {
  color: #f0a500;
}

/* ===== Hero ===== */
.hero {
  background: url("images/hero.jpg") center/cover no-repeat;
  height: 90vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  padding: 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 15px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 25px;
}

.btn {
  background: #f0a500;
  color: white;
  padding: 12px 25px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  font-size: 1rem;
  font-weight: bold;
  margin: 5px;
  display: inline-block;
}

.btn:hover {
  background: #cc8500;
}

/* ===== Servicios ===== */
.services {
  padding: 60px 20px;
  text-align: center;
}

.services h3 {
  font-size: 2rem;
  margin-bottom: 30px;
}

.service-boxes {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.service {
  width: 300px;
  margin: 15px;
  padding: 20px;
  border-radius: 10px;
  background: #f8f8f8;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

/* ===== Proyectos ===== */
.projects {
  background: #f0f0f0;
  padding: 60px 20px;
  text-align: center;
}

.projects img {
  width: 280px;
  margin: 10px;
  border-radius: 10px;
  transition: 0.3s;
}

.projects img:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

/* ===== CTA ===== */
.cta {
  background: #f0a500;
  color: white;
  text-align: center;
  padding: 50px 20px;
}

.cta h3 {
  margin-bottom: 20px;
  font-size: 2rem;
}

/* ===== Footer ===== */
footer {
  background: #1a1a1a;
  color: white;
  padding: 30px 20px;
  text-align: center;
}

footer a {
  color: #f0a500;
  margin: 0 10px;
  text-decoration: none;
}

footer a:hover {
  text-decoration: underline;
}

/* ===== Responsive ===== */
@media (max-width: 768px) {
  .service-boxes {
    flex-direction: column;
    align-items: center;
  }

  header {
    flex-direction: column;
    gap: 10px;
  }

  .hero h2 {
    font-size: 2rem;
  }

  .hero p {
    font-size: 1rem;
  }
}
