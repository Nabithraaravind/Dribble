# Project Responsive Web Design using Bootstrap
## Date:21-05-2025

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
  <style>
    .shot-card {
      height: 520px;
    }
    .shot-card img {
      height: 370px;
      width: 100%;
      object-fit: cover;
    }
    .shot-card:hover {
      transform: scale(1.02);
      transition: transform 0.2s ease-in-out;
    }
    .card-title {
      font-size: 1.2rem;
      font-weight: 600;
    }
    .card-text {
      font-size: 1rem;
      color: #555;
    }
  </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Dribbble</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
        <li class="nav-item"><a class="nav-link btn btn-primary text-white" href="#">Sign In</a></li>
        <form class="d-flex me-3" role="search">
          <input class="form-control me-2" type="search" placeholder="Search">
          <button class="btn btn-outline-dark" type="submit">Search</button>
        </form>
      </ul>
    </div>
  </div>
</nav>

<!-- Card Grid -->
<div class="container mt-4">
  <div class="row g-4">
    <!-- Repeat for 8 pics only -->
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(1).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">HALLSTATT</h5>
          <p class="card-text">AUSTRIA</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(2).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">SALZBURG</h5>
          <p class="card-text">ALPS</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(3).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">LAGO ANTORNO</h5>
          <p class="card-text">DOLOMITES</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(4).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">MERCED RIVER</h5>
          <p class="card-text">CALIFORNIA</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(5).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">SANTORINI</h5>
          <p class="card-text">AEGEAN SEA</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(6).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">SAN GEORGIO</h5>
          <p class="card-text">ITALY</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(7).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">MARGARET BRIDGE</h5>
          <p class="card-text">HUNGARY</p>
        </div>
      </div>
    </div>
    <div class="col-lg-3 col-md-4 col-sm-6">
      <div class="card shot-card">
        <img src="i1(8).png" class="card-img-top" alt="Destinations">
        <div class="card-body">
          <h5 class="card-title">NEUSCHWANSTEIN CASTLE</h5>
          <p class="card-text">GERMANY</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Footer -->
<footer>
  <h2 style="background-color: rgb(26, 54, 53); color: white; text-align: center; font-size: 18px; font-family: 'Trebuchet MS', sans-serif;">Designed and developed by NABITHRA A</h2>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![alt text](<Nabithra/picapp/static/Screenshot 2025-05-21 231115.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
