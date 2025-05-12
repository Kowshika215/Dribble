# Project Responsive Web Design using Bootstrap
## Date: 12/05/2025

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
    <title>Design Gallery</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Limit the width of the page content */
        .container {
            max-width: 1200px;
        }

        /* Adjust card images to maintain aspect ratio and fit */
        .card-img-top {
            height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">Design Gallery</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Shots</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Designers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Teams</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Community</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Jobs</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Gallery Section -->
<section class="container my-4">
    <div class="d-flex justify-content-between align-items-center mb-4">
        <h2>Popular Shots</h2>
        <div>
            <button class="btn btn-primary btn-sm">Learn More</button>
            <button class="btn btn-secondary btn-sm">Sign Up</button>
        </div>
    </div>
    <div class="row g-4">
        <!-- Gallery Items -->
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="jacobs.jpg" class="card-img-top img-fluid" alt="Design 1">
                <div class="card-body">
                    <h5 class="card-title">Marc jacobs</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="bro.png" class="card-img-top img-fluid" alt="Design 2">
                <div class="card-body">
                    <h5 class="card-title">Balkan Brothers</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="jan.png" class="card-img-top img-fluid" alt="Design 3">
                <div class="card-body">
                    <h5 class="card-title">Jan Losert</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="mattias.jpg" class="card-img-top img-fluid" alt="Design 4">
                <div class="card-body">
                    <h5 class="card-title">Mattias Johansson</h5>
                </div>
            </div>
        </div>
    </div>
    <div class="row g-4 mt-3">
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="doodle.jpg" class="card-img-top img-fluid" alt="Design 5">
                <div class="card-body">
                    <h5 class="card-title">Doodle</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="jep.png" class="card-img-top img-fluid" alt="Design 6">
                <div class="card-body">
                    <h5 class="card-title">Paperpillar</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="alfrey.webp" class="card-img-top img-fluid" alt="Design 7">
                <div class="card-body">
                    <h5 class="card-title">Alfrey Davilla</h5>
                </div>
            </div>
        </div>
        <div class="col-lg-3 col-md-4 col-sm-6 col-12">
            <div class="card">
                <img src="JQ.jpeg" class="card-img-top img-fluid" alt="Design 8">
                <div class="card-body">
                    <h5 class="card-title">Studio-JQ</h5>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-dark text-white text-center py-3">
    <p>&copy; KOWSHIKA R (212224220049)</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-12 101957](https://github.com/user-attachments/assets/f1eea22e-b316-42b9-b01b-974fbc5b263c)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
