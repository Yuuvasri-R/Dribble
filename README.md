# Project Responsive Web Design using Bootstrap
# Date:11.10.2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dream Worlds</title>


  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #faf8ff;
    }
    .hero {
      background: linear-gradient(135deg, #a18cd1, #fbc2eb);
      color: white;
      text-align: center;
      padding: 25px 20px;
    }
    .hero h1 {
      font-weight: 700;
      font-size: 3rem;
    }
    .gallery img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 15px;
      transition: transform 0.4s ease;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #2e2e2e;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold text-primary" href="#">Dream Worlds</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item mx-2"><a class="nav-link" href="#">Home</a></li>
          <li class="nav-item mx-2"><a class="nav-link" href="#">Gallery</a></li>
          <li class="nav-item mx-2"><a class="nav-link" href="#">About</a></li>
        </ul>
      </div>
    </div>
  </nav>

  
  <section class="hero">
    <h1>Step Into The Dream Worlds</h1>
    <p><h3>Explore the magical places beyond imagination — glowing skies, floating islands, and surreal beauty.</h3></p>
  </section>

 
  <section class="gallery py-5">
    <div class="container">
      <h1 class="text-center mb-4">Explore Dreamscapes</h1>
      <div class="row g-4">
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">FLOATING ISLAND</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\floating island.jpg" alt="Floating Island">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">GLOWING FOREST</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\glowing forest.jpg" alt="Glowing Forest">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">FANTASY CASTLE </h3>
          <img src="c:\Users\B.NAVASRI\Downloads\dream castle.jpg" alt="Fantasy Castle">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">DREAM SKY</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\dream sky.jpg" alt="Dream Sky">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">DREAM OCEAN</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\dream ocean.jpg" alt="Dream Ocean">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">COSMIC DREAMS</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\cosmic dreams.jpg" alt="Cosmic Dream">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">WHIMSICAL GARDEN</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\garden.webp" alt="Whimsical Garden">
        </div>
        <div class="col-lg-3 col-md-6 col-sm-12">
          <h3 align="center">MAGICAL CREATURE</h3>
          <img src="c:\Users\B.NAVASRI\Downloads\magical creation.jpg" alt="Magical Creature">
      </div>
    </div>
  </section>


  <section class="py-5 bg-light text-center">
    <div class="container">
      <h2>About Dream Worlds</h2>
      <p class="text-muted"><h3>Dream Worlds is a visual journey into the imagination — where art, fantasy, and technology combine to create surreal landscapes that exist only in dreams.<h3></p>
    </div>
  </section>


  <footer>
    <p>Designed by <strong>Navasri.B</strong> | © 2025 Dream Worlds</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
# OUTPUT:
<img width="1920" height="966" alt="Screenshot 2025-10-09 135857" src="https://github.com/user-attachments/assets/396fb3d0-f016-4bd6-8957-2ac86abae926" />


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
