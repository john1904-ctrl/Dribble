# Project Responsive Web Design using Bootstrap
## Date:31/12/2024

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
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-white">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-basketball-ball"></i> Dribble
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="service.html">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Sorting Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-secondary py-2">
        <div class="container d-flex justify-content-center">
            <ul class="navbar-nav">
                <li class="nav-item"><a class="nav-link" href="#">Popular</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Newest</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Random</a></li>
            </ul>
        </div>
    </nav>

    <!-- Cards Section -->
    <div class="container my-5">
        <div class="row g-4">
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/1.webp" class="card-img-top" alt="Personal Finance">
                    <div class="card-body text-center">
                        <h6 class="card-title">Personal Finance</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/9.webp" class="card-img-top" alt="Highlight Cards">
                    <div class="card-body text-center">
                        <h6 class="card-title">Highlight Cards</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/3.webp" class="card-img-top" alt="Travel History">
                    <div class="card-body text-center">
                        <h6 class="card-title">Travel History</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/4.webp" class="card-img-top" alt="Attio Email Sharing Setting">
                    <div class="card-body text-center">
                        <h6 class="card-title">Attio Email Sharing Setting</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/5.webp" class="card-img-top" alt="Grant Management Software">
                    <div class="card-body text-center">
                        <h6 class="card-title">Grant Management Software</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/6.webp" class="card-img-top" alt="Interviews and Data">
                    <div class="card-body text-center">
                        <h6 class="card-title">Interviews and Data</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/7.webp" class="card-img-top" alt="Cruz: Connect ID">
                    <div class="card-body text-center">
                        <h6 class="card-title">Cruz: Connect ID</h6>
                    </div>
                </div>
            </div>
            <div class="col-6 col-md-3">
                <div class="card">
                    <img src="myapp/static/8.webp" class="card-img-top" alt="Machine Learning Pipeline">
                    <div class="card-body text-center">
                        <h6 class="card-title">Machine Learning Pipeline</h6>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center text-warning mb-4">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Your message" required></textarea>
                </div>
                <button type="submit" class="btn btn-warning">Send</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center bg-dark text-white py-3">
        <p>Designed and Developed by JOHN PALL M (24900131)</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (75).png>) 
![alt text](<Screenshot (76).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
