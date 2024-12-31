# Project Responsive Web Design using Bootstrap
## Date:23/12/2024

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light border-bottom">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#">Explore</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Hire a Designer</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Find Jobs</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Blog</a>
          </li>
        </ul>
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="btn btn-outline-dark me-2" href="#">Sign up</a>
          </li>
          <li class="nav-item">
            <a class="btn btn-dark" href="#">Log in</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="py-5 text-center">
    <div class="container">
      <h1 class="display-4">Discover the world’s top designers</h1>
      <p class="lead">Explore work from the most talented and accomplished designers ready to take on your next project</p>
      <div class="input-group mt-4">
        <input type="text" class="form-control" placeholder="What are you looking for?">
        <button class="btn btn-primary" type="button">Search</button>
      </div>
      <div class="mt-3">
        <span class="badge bg-light text-dark me-2">Trending searches</span>
        <span class="badge bg-light text-dark">landing page</span>
        <span class="badge bg-light text-dark">e-commerce</span>
        <span class="badge bg-light text-dark">mobile app</span>
        <span class="badge bg-light text-dark">logo design</span>
        <span class="badge bg-light text-dark">dashboard</span>
        <span class="badge bg-light text-dark">icons</span>
      </div>
    </div>
  </header>

  <!-- Filter Section -->
  <section class="bg-light py-3 border-bottom">
    <div class="container d-flex justify-content-between align-items-center">
      <div class="btn-group" role="group">
        <button type="button" class="btn btn-light">Popular</button>
        <button type="button" class="btn btn-light">Discover</button>
        <button type="button" class="btn btn-light">Animation</button>
        <button type="button" class="btn btn-light">Branding</button>
        <button type="button" class="btn btn-light">Illustration</button>
        <button type="button" class="btn btn-light">Web Design</button>
      </div>
      <button class="btn btn-outline-secondary">Filters</button>
    </div>
  </section>

  <!-- Shots Section -->
  <section class="py-5">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card">
            <img src="1.webp" class="card-img-top" alt="Shot Image">
            <div class="card-body">
              <h5 class="card-title">Vaneltia</h5>
              <p class="card-text">Alfrey Davilla</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="2.webp" class="card-img-top" alt="Shot Image">
            <div class="card-body">
              <h5 class="card-title">The Burrow - Critter Series</h5>
              <p class="card-text">Val Waters</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="3.webp" class="card-img-top" alt="Shot Image">
            <div class="card-body">
              <h5 class="card-title">S logo exploration</h5>
              <p class="card-text">Mark Smith</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-light py-4">
    <div class="container text-center">
      <p class="mb-0">&copy; 2024 Dribbble Clone. All rights reserved.</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](<indhu/dapp/static/Screenshot 2024-12-31 224025.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
