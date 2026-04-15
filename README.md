<!DOCTYPE html>

<head>

<title>Practical 13 - College Introduction</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
<link rel="stylesheet" href="style.css">
</head>

<body>

<nav class="navbar navbar-expand-lg navbar-dark sticky-top">
<div class="container">
<a class="navbar-brand fw-bold" href="#">College Portal</a>

<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="menu">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
<li class="nav-item"><a class="nav-link" href="#facilities">Facilities</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
</ul>
</div>
</div>
</nav>

<div id="carouselExample" class="carousel slide" data-bs-ride="false">
<div class="carousel-inner">

<div class="carousel-item active">
<img src="https://images.unsplash.com/photo-1562774053-701939374585" class="d-block w-100">
<div class="carousel-caption">
<h3>College Campus</h3>
</div>
</div>

<div class="carousel-item">
<img src="https://images.unsplash.com/photo-1521587760476-6c12a4b040da" class="d-block w-100">
<div class="carousel-caption">
<h3>Library</h3>
</div>
</div>

</div>

<button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
<span class="carousel-control-prev-icon"></span>
</button>

<button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
<span class="carousel-control-next-icon"></span>
</button>
</div>

<div class="container mt-5" id="facilities">
<h2 class="text-center mb-4">Our Facilities</h2>

<div class="row g-4">

<div class="col-md-3">
<div class="card text-center p-3">
<i class="bi bi-book fs-1 text-primary"></i>
<h5 class="mt-2">Library</h5>
<p>Books & Resources</p>
<button class="btn btn-custom">View</button>
</div>
</div>

<div class="col-md-3">
<div class="card text-center p-3">
<i class="bi bi-laptop fs-1 text-primary"></i>
<h5 class="mt-2">Computer Lab</h5>
<p>Modern Systems</p>
<button class="btn btn-custom">View</button>
</div>
</div>

<div class="col-md-3">
<div class="card text-center p-3">
<i class="bi bi-trophy fs-1 text-primary"></i>
<h5 class="mt-2">Sports</h5>
<p>Indoor & Outdoor</p>
<button class="btn btn-custom">View</button>
</div>
</div>

<div class="col-md-3">
<div class="card text-center p-3">
<i class="bi bi-cup-hot fs-1 text-primary"></i>
<h5 class="mt-2">Cafeteria</h5>
<p>Healthy Food</p>
<button class="btn btn-custom">View</button>
</div>
</div>

</div>
</div>

<div class="container mt-5" id="contact">
<h2 class="text-center mb-4">Contact Us</h2>

<div class="row g-4 justify-content-center">

<div class="col-md-5">
<div class="card text-center p-3">
<i class="bi bi-telephone-fill fs-1 text-primary"></i>
<h5 class="mt-3">Phone Number</h5>
<p>9876543839</p>
</div>
</div>

<div class="col-md-5">
<div class="card text-center p-3">
<i class="bi bi-envelope-fill fs-1 text-primary"></i>
<h5 class="mt-3">Email</h5>
<p>cse25@sbjain.edu.in</p>
</div>
</div>

</div>
</div>

<footer class="text-center mt-5">
<p>© Practical 13 - Webpage using bootstrap <br>
USN : CS25062</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
