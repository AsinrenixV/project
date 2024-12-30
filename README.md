# Project Responsive Web Design using Bootstrap
# Date:29/12/2024
# AIM:
To create a simplified clone of Dribble (https://dribbble.com/) landing page.

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
    <title>Dribble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
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
            <h1 class="display-4">Welcome to Classic Curves</h1>
            <p class="lead">Your one-stop shop for all your needs</p>
            <a href="#products" class="btn btn-primary btn-lg">View</a>
        </div>
    </div>

    <!-- Products Section -->
    <div id="products" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">OUR CLASSICS</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="heels.jpg" class="card-img-top" alt="Product 1">
                        <div class="card-body">
                            <h5 class="card-title">Trends</h5>
                            <p class="card-text">Heels</p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="shoe.jpeg" class="card-img-top" alt="Product 2">
                        <div class="card-body">
                            <h5 class="card-title">Trends</h5>
                            <p class="card-text">Sneakers</p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="crop1.jpeg" class="card-img-top" alt="Product 3">
                        <div class="card-body">
                            <h5 class="card-title">Trends</h5>
                            <p class="card-text">Top</p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- About Section -->
    <div id="about" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p class="text-center">Classic Curves is dedicated to providing top-quality products at affordable prices. Our mission is to make shopping simple, convenient, and enjoyable for everyone. With a wide range of products to choose from, we strive to meet all your needs in one place.</p>
        </div>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <p class="text-center">Reach out to us!</p>
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <form>
                        <div class="mb-3">
                            <label for="name" class="form-label">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Your Name">
                        </div>
                        <div class="mb-3">
                            <label for="email" class="form-label">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Your Email">
                        </div>
                        <div class="mb-3">
                            <label for="message" class="form-label">Message</label>
                            <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">Send Feedback</button>
                    </form>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 Asin Renix V(24900126)</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
# OUTPUT:

![alt text](<renix/dribbleapp/static/Screenshot (103).png>)
![alt text](<renix/dribbleapp/static/Screenshot (104).png>)
![alt text](<renix/dribbleapp/static/Screenshot (105).png>)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
