# 🌐 Bootstrap 5 UI Exploration & Page Design

## 🚀 Project Overview
This project is created as part of the **Internship Task – Bootstrap 5 UI Exploration & Page Design**.  
The goal is to explore and remix **Bootstrap 5 components** (Navbar, Cards, Carousel, Forms, etc.) and build **responsive and modern web pages**.

The project includes **three pages**:
- 🏠 `index.html` – Home Page  
- ℹ️ `about.html` – About Page  
- 📞 `contact.html` – Contact Page  

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **Bootstrap 5 (via CDN)**
- **Formspree** (for form submission)
- **Git & GitHub** (for hosting)

---

## 📁 Folder Structure
```
full
│
├── index.html
├── about.html
├── contact.html
└── README.md
```

---

## ⚙️ Setup Instructions
1. Download or clone this repository  
   ```bash
   git clone https://github.com/yourusername/bootstrap-ui-project.git
   ```
2. Open in **VS Code** and use **Live Server**.
3. Replace Formspree ID in `contact.html`:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```
4. Push to GitHub and enable **GitHub Pages** for deployment.

---

## 💻 Code Files

### 🏠 `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap 5 UI Project - Home</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body { background-color: #f8f9fa; }
    .hero {
      background: linear-gradient(to right, #007bff, #6610f2);
      color: white;
      padding: 100px 0;
      text-align: center;
    }
    .card img {
      height: 200px;
      object-fit: cover;
    }
    footer {
      background: #212529;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">UI Explorer</a>
      <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1 class="display-4 fw-bold">Welcome to Our Bootstrap 5 UI</h1>
      <p class="lead">Beautiful, modern, and fully responsive designs made easy with Bootstrap 5.</p>
      <a href="about.html" class="btn btn-light btn-lg">Learn More</a>
    </div>
  </section>

  <!-- Features Section -->
  <section class="py-5">
    <div class="container text-center">
      <h2 class="mb-4 fw-bold text-primary">Our Features</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card shadow">
            <img src="https://picsum.photos/400/200?1" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">Responsive Design</h5>
              <p class="card-text">Every page looks perfect on any device using Bootstrap grid system.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow">
            <img src="https://picsum.photos/400/200?2" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">Modern UI</h5>
              <p class="card-text">Stylish components with vibrant colors and smooth animations.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow">
            <img src="https://picsum.photos/400/200?3" class="card-img-top" alt="">
            <div class="card-body">
              <h5 class="card-title">Built with Bootstrap 5</h5>
              <p class="card-text">Leverage the latest version of Bootstrap for UI excellence.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 UI Explorer | Designed with ❤️ using Bootstrap 5</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

---

### ℹ️ `about.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - Bootstrap 5 UI Project</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">UI Explorer</a>
      <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <div class="text-center mb-5">
      <h2 class="fw-bold text-primary">About Our Project</h2>
      <p class="text-muted">Exploring Bootstrap 5 UI components and creative design approaches.</p>
    </div>

    <div class="row align-items-center">
      <div class="col-md-6">
        <img src="https://picsum.photos/600/400" class="img-fluid rounded shadow" alt="About">
      </div>
      <div class="col-md-6">
        <h3 class="fw-semibold">Our Mission</h3>
        <p>To build clean, responsive, and appealing web interfaces using Bootstrap 5. This project demonstrates the power of reusable UI components, effective layout design, and creativity in remixing Bootstrap examples.</p>
        <ul>
          <li>Responsive Layouts</li>
          <li>Beautiful Components</li>
          <li>Simple and Effective Design</li>
        </ul>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-light text-center py-3">
    <p>© 2025 UI Explorer | Created by Lavanya</p>
  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

---

### 📞 `contact.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Bootstrap 5 UI Project</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">UI Explorer</a>
      <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <div class="text-center mb-5">
      <h2 class="fw-bold text-success">Contact Us</h2>
      <p class="text-muted">We’d love to hear from you. Please fill the form below.</p>
    </div>

    <div class="row justify-content-center">
      <div class="col-md-6">
        <form action="https://formspree.io/f/your-form-id" method="POST" class="p-4 border rounded shadow bg-light">
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" name="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email address</label>
            <input type="email" class="form-control" id="email" name="_replyto" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
          </div>
          <button type="submit" class="btn btn-success w-100">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-light text-center py-3">
    <p>© 2025 UI Explorer | Designed by Lavanya</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

---

## 🧭 Reflection
- Explored Bootstrap documentation and examples.
- Built and remixed components for creative layouts.
- Focused on responsiveness and visual balance.
- Used GitHub for hosting via GitHub Pages.

---


