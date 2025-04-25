<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Portofolio</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <!--Lightbox2 CSS-->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css" rel="stylesheet">
        <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
        echo "# Vernanda-Yneza" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/Vernanda-Yneza/Vernanda-Yneza.git
        git push -u origin main
    </head>
    <body>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
        <script>
            document.addEventListener("DOMContentLoaded", function () {
                AOS.init({
                    duration: 1000, once: true
                });
            });
        </script>
        <!--Navbar-->
        <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#home">Vernanda Yneza P.M</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class=nav-link href="#home">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#portofolio">Portofolio</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>
        <!--Home Section-->
        <section id="home" class="vh-100 d-flex align-items-center bg-light text-center" data-aos="fade-in">
            <div class="container">
                <h1 class="display-4">Welcome to My Portofolio</h1>
                <p class="lead">My name is Vernanda Yneza putri Mareta, and this is my work showcase.</p>
            </div>
        </section>
        <!--About Section-->
        <section id="about" class="py-5 bg-white" data-aos="fade-right">
            <div class="container py-5">
                <div class="row">
                    <div class="col-lg-6 mx-auto text-center">
                        <h2>About me</h2>
                        <p>Saya adalah salah satu murid dari SMKN 1 Nganjuk, dan jurusan yang saya ambil adalah Pengembangan Gim. I like to learn new things.</p>
                    </div>
                </div>
                <div class="row mt-4">
                    <!--Resume-->
                    <div class="col-lg-6">
                        <h3>Resume</h3>
                        <p><strong>Web Developer</strong></p>
                        <p> - A student from SMKN 1 Nganjuk that was taught how to build a web from scratch.</p>
                        <p><strong>Graphic Designer</strong></p>
                        <p>Designed branding materials, marketing visual, and 3D models.</p>
                    </div>

                    <!--Skills-->
                    <div class="col-lg-6">
                        <h3>Skills</h3>
                        <p>Graphic Designer</p>
                        <div class="progress mb-3">
                            <div class="progress-bar bg-success" style="width: 90%;">80%</div>
                        </div>
                        <p>Web Developer</p>
                        <div class="progress mb-3">
                            <div class="progress-bar bf-danger" style="width: 75%;">75%</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Portofolio Section-->
        <section id="portofolio" class="py-5 bg-light">
            <div class="container">
                <h2 class="text-center" data-aos="fade-in">My portofolio</h2>
                <div class="row">
                    <div class="col-lg-4 col-md-6 mb-4" data-aos="zoom-in">
                        <div class="card">
                            <a href="31. Vernanda yneza p.m.png" data-lightnox="portofolio" data-title="Project 1">
                                <img src="31. Vernanda yneza p.m.png" class="card-img-top img-fluid" alt="Project 1">
                            </a>
                            <div class="card-body">
                                <h5 class="card-title">Project 1</h5>
                                <p class="card-text">Design asbak menggunakan Blender</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 mb-4" data-aos="zoom-in" data-aos-delay="200">
                        <div class="card">
                            <a href="render 4.png" data-lightbox="portofolio" data-little="Project 2">
                                <img src="render 4.png" alt="Project 2" class="card-img-top img-fluid" alt="Project 2">
                            </a>
                            <div class="card-body">
                                <h5 class="card-title">Project 2</h5>
                                <p class="card-text">Design merk, Canva dan CorelDraw</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 mb-4" data-aos="zoom-in"data-aos-delay="400">
                        <div class="card">
                            <a href="rdr v2 bright.jpg" data-lightbox="portofolio" data-little="Project 3">
                                <img src="rdr v2 bright.jpg" alt="Project 3" class="card-img-top img-fluid" alt="Project 3">
                            </a>
                            <div class="card-body">
                                <h5 class="card-title">Project 3</h5>
                                <p class="card-text">Design poster game menggunakan Adobe Photoshop</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!--Contact Section-->
        <section id="contact" class="py-5 bg-white">
            <div class="container" data-aos="fade-up" data-aos="zoom-out">
                <h2 class="text-center">Contact me</h2>
                <div class="row">
                    <div class="col-lg-6 mx-auto text-center" data-aos="fade-up" data-aos-delay="200">
                        <p><i class="fas fa-envelope"></i> ynezaa123@gmail.com</p>
                        <p><i class="fas fa-phone"></i> +62 857855847706</p>
                        <p><i class="fas fa-map-marker-alt"></i> Jl. Merapi, Kec. loceret, Kab. Nganjuk, Jawa timur.</p>
                        
                    </div>
                </div>
            </div>
            <div data-aos="fade up" data-aos-duration="1500" data-aos-delay="300" data-aos-once="false">
            </div>
        </section>
        <!--Footer-->
        <footer class="text-center py-4 bg-light">
            <div class="container">
                <p>&copy; 2025 MyPortofolio. All rights reserved.</p>
            </div>
        </footer>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
        <!--Lightbox2 JS-->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    </body>
</html>
