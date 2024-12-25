# Project Responsive Web Design using Bootstrap
## Date:23.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
drib html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .top-center-info {
      position: absolute;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      z-index: 1030;
    }
  </style>
</head>
<body>
  <!-- Top-Center Info -->
  <div class="top-center-info">
    <span class="badge bg-primary text-white fs-5 px-3 py-2 shadow-sm">
      G.T. Gowtham | Ref No: 24901330
    </span>
  </div>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light border-bottom shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#explore">Explore</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#more-designs">More Designs</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="bg-light text-center py-5">
    <div class="container">
      <h1 class="display-5 fw-bold">Discover the World's Best Designs</h1>
      <p class="lead">Join our creative community and showcase your work to millions of professionals.</p>
      <a href="#" class="btn btn-primary btn-lg">Join Now</a>
    </div>
  </div>

  <!-- Explore Section -->
  <section id="explore" class="py-5">
    <div class="container">
      <h2 class="text-center fw-bold mb-4">Explore Top Designs</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://bce.iafor.org/wp-content/uploads/sites/52/2020/07/The-Relevance-of-the-Humanities-and-Arts-in-Uncertain-Times-1100x550.jpg" class="card-img-top" alt="Design 1">
            <div class="card-body">
              <h5 class="card-title">Design Title 1</h5>
              <p class="card-text">Short description of the design. A creative and unique work by our community.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://i.ibb.co/frYnvW9/pexels-steve-1585325-1.jpg" class="card-img-top" alt="Design 2">
            <div class="card-body">
              <h5 class="card-title">Design Title 2</h5>
              <p class="card-text">Showcase of exceptional talent and creativity from designers.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://5.imimg.com/data5/RE/IH/MY-65027118/paintings-sketch-500x500.jpg" class="card-img-top" alt="Design 3">
            <div class="card-body">
              <h5 class="card-title">Design Title 3</h5>
              <p class="card-text">Innovative and inspiring designs from our vibrant community.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- More Designs Section -->
  <section id="more-designs" class="py-5">
    <div class="container">
      <h2 class="text-center fw-bold mb-4">Explore More Designs</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://static.wixstatic.com/media/11062b_cb11cb4ffe084b37b66633ca51f8592d~mv2.jpg/v1/fill/w_568,h_426,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/11062b_cb11cb4ffe084b37b66633ca51f8592d~mv2.jpg" class="card-img-top" alt="More Design 1">
            <div class="card-body">
              <h5 class="card-title">Design Title 4</h5>
              <p class="card-text">A compelling design reflecting artistic expression.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://innerspacetherapy.in/wp-content/uploads/2014/10/escher-hand-with-reflecting-sphere-medium1.jpg" class="card-img-top" alt="More Design 2">
            <div class="card-body">
              <h5 class="card-title">Design Title 5</h5>
              <p class="card-text">An intricate and thought-provoking artwork.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100 shadow-sm">
            <img src="https://img.freepik.com/premium-photo/dinosaurs-fire-end-world-dinosaurs_366165-77.jpg" class="card-img-top" alt="More Design 3">
            <div class="card-body">
              <h5 class="card-title">Design Title 6</h5>
              <p class="card-text">A bold and dramatic depiction of creativity.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5">
    <div class="container text-center">
      <h2 class="fw-bold mb-4">Get in Touch</h2>
      <p>Email us at <a href="mailto:contact@dribbbleclone.com">contact@dribbbleclone.com</a></p>
      <p>Follow us on <a href="#">Twitter</a> | <a href="#">LinkedIn</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p class="mb-0">© 2024 G.T. Gowtham. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
## OUTPUT:
![Screenshot 2024-12-25 204110](https://github.com/user-attachments/assets/462c4dd4-8aef-463c-8ede-986e90bd5b28)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
