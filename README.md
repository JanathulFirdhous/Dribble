# Project Responsive Web Design using Bootstrap
## Date:24.12.2024

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
  <title>Dribbble</title>
  
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

 
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Dribbble Showcase</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#shots">Shots</a>
          </li>
        </ul>

        
        <form class="d-flex ms-3" action="#" method="GET">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>


  <div class="container-fluid bg-warning text-white py-5" id="home">
    <div class="container text-center">
      <h1 class="display-4">Discover the Best Creative Works</h1>
      <p class="lead">Showcase your designs, get inspired, and connect with other creatives.</p>
      <a href="#shots" class="btn btn-dark mt-3">Explore Shots</a>
    </div>
  </div>

  
  <div id="shots" class="container my-5">
    <h2 class="text-center mb-4">Featured Design Shots</h2>
    <div class="row row-cols-1 row-cols-md-3 g-4">
      
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="mlo.png" class="card-img-top" alt="Shot 1">
          <div class="card-body">
            <h5 class="card-title">Modern Logo Design</h5>
            <p class="card-text">A sleek and minimalistic logo design for a modern tech company.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
      
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="blo.png" class="card-img-top" alt="Shot 2">
          <div class="card-body">
            <h5 class="card-title">Creative Branding</h5>
            <p class="card-text">An innovative branding project to elevate a startup's image.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
     
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="wlo.png" class="card-img-top" alt="Shot 3">
          <div class="card-body">
            <h5 class="card-title">Web Design Interface</h5>
            <p class="card-text">A modern and user-friendly interface for a new website.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
      
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="ulo.png" class="card-img-top" alt="Shot 4">
          <div class="card-body">
            <h5 class="card-title">App UI Design</h5>
            <p class="card-text">A seamless and intuitive user interface for a mobile application.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
      
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="ilo.png" class="card-img-top" alt="Shot 5">
          <div class="card-body">
            <h5 class="card-title">Minimalistic Poster</h5>
            <p class="card-text">A modern and clean poster design perfect for advertising.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
      
      <div class="col">
        <div class="card shadow-sm border-0">
          <img src="palo.png" class="card-img-top" alt="Shot 6">
          <div class="card-body">
            <h5 class="card-title">Packaging Design</h5>
            <p class="card-text">A creative and innovative design for product packaging.</p>
            <a href="#" class="btn btn-outline-secondary">View More</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  
  <footer class="bg-dark text-white text-center py-3">
    <p>&copy; 2024 Creative Showcase. Designed with passion by Janathul Firdhous.</p>
  </footer>

  
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

## OUTPUT:

![alt text](jannath/bootapp/static/578.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
