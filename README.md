<!doctype html>
<html lang="en">
<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <!-- Custom CSS -->
    <style>
        body {
            padding-top: 50px;
            font-family: Arial, sans-serif;
            background-color: hsl(0, 86%, 59%); /* Chameleon color */
            min-height: 100vh;
        }
        h1 {
            color: #1d201a; /* Change the title color here */
            font-size: 2rem; /* Adjust the font size */
            text-align: left; /* Align the text to the left */
        }
        .jumbotron {
            background-color: rgba(94, 218, 52, 0.8); /* Transparent white background */
            padding: 2rem 1rem;
            border-radius: 30px;
        }
        .container {
            max-width: 960px;
        }
        footer {
            background-color: #343a40;
            color: #ffffff;
            padding: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #dddddd;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        .highlight {
            background-color: yellow;
        }
        .scroll-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: none;
        }
    </style>

    <title>ITP DEN</title>
</head>
<body>

<!-- Navigation -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
        <a class="navbar-brand" href="#">ITP DEN</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <form class="d-flex ms-auto">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-light" type="submit">Search</button>
            </form>
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#services">Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="mailto:info@itpden.com">Email</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://www.facebook.com">Facebook</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Page Content -->
<div class="container">
    <!-- Carousel -->
    <div id="carouselExampleIndicators" class="carousel slide my-4" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="./images/dyno.jpg.jpg" class="d-block w-100" alt="Slide 1">
            </div>
            <div class="carousel-item">
                <img src="./images/elevator.jpg.webp" class="d-block w-100" alt="Slide 2">
            </div>
            <div class="carousel-item">
                <img src="./images/motor.jpg" class="d-block w-100" alt="Slide 2">
            </div>
            <div class="carousel-item">
                <img src="./images/Porsche.jpg.jpg" class="d-block w-100" alt="Slide 3">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>

    <!-- Jumbotron Header -->
    <header class="jumbotron my-4">
        <h1 class="display-5">Bine ati venit!</h1> <!-- Adjusted font size -->
        <p class="lead">Destinatia ta, catre toate solutiile tehnice.</p>
    </header>

    <!-- Services Section -->
    <section id="services">
        <h2>Serviciile noastre!</h2>
        <!-- Embed YouTube video -->
        <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/G80hJ5b0YjY" allowfullscreen></iframe>
        </div>
        <!-- End of embedded video -->
        <p>Explora serviciile noastre, urmarind clipul.</p>
        <ul>
            <li>Testare Frane</li>
            <li>Testare noxe</li>
            <li>Diagnoza</li>
            <li>Reglare faruri</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:info@itpden.com">info@itpden.com</a></p>
        <p>Phone: 0749804097</p>
    </section>

    <!-- Technical Inspections Table -->
    <h2>Inspectie Tehnica Periodica</h2>
    <table>
        <tr>
            <th>Zi</th>
            <th>08:30 - 09:30</th>
            <th>09:30 - 10:30</th>
            <th>10:30 - 11:30</th>
            <th>11:30 - 12:30</th>
            <th>12:30 - 13:30</th>
            <th>13:30 - 14:30</th>
            <th>14:30 - 15:30</th>
            <th>15:30 - 16:30</th>
            <th>16:30 - 17:30</th>
        </tr>
        <tr>
            <td>Luni</td>
            <td class="highlight"></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td class="highlight"></td>
        </tr>
        <tr>
            <td>Marti</td>
            <td></td>
            <td></td>
            <td class="highlight"></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Miercuri</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td class="highlight"></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Joi</td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td class="highlight"></td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>Vineri</td>
            <td class="highlight"></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td></td>
            <td class="highlight"></td>
        </tr>
    </table>

    <!-- Scroll to Top Button -->
    <button class="btn btn-primary scroll-to-top" onclick="scrollToTop()">Scroll to Top</button>
</div>

<!-- Footer -->
<footer class="text-center">
    <div class="container">
        <p>&copy; 2024 ITP DEN. All rights reserved.</p>
    </div>
</footer>

<!-- Bootstrap Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

<!-- Scroll to Top Function -->
<script>
    function scrollToTop() {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }
</script>

</body>
</html>
