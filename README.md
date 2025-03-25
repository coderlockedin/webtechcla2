# webtechcla2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Studio Portfolio</title>
    
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    
    
</head>

<body>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <header class="bg-dark text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Creative Studio</h1>
            <p class="lead">Bringing ideas to life with design, development, and creativity. Let’s create something amazing together!</p>
            <a href="#portfolio" class="btn btn-primary btn-lg">Explore my work</a>
        </div>
    </header>
    
    <section id="about" class="py-5">
        <div class="container text-center">
            <h2>Hey, I'm Nandini Vengat!</h2>
            <p>I’m a freelance designer and developer who loves turning ideas into digital experiences. Whether you need a stunning website, a rebrand, or just a little creative touch, I’m here to help bring your vision to life!</p>
        </div>
    </section>
    <section id="portfolio" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">What I've Been Working On</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="project1.jpg" class="card-img-top" alt="Project 1">
                        <div class="card-body">
                            <h5 class="card-title">Project 1</h5>
                            <p class="card-text">A beautiful website I designed for a local bakery. The goal was to blend the warmth of their brand with an easy-to-use online store for ordering custom cakes.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="project2.jpg" class="card-img-top" alt="Project 2">
                        <div class="card-body">
                            <h5 class="card-title">Project 2</h5>
                            <p class="card-text">I helped a non-profit rebrand their online presence. The project included designing a new logo and creating a clean, user-focused website that tells their story.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="project3.jpg" class="card-img-top" alt="Project 3">
                        <div class="card-body">
                            <h5 class="card-title">Project 3</h5>
                            <p class="card-text">A sleek, modern design for a tech startup. The challenge was to convey cutting-edge innovation while keeping things user-friendly.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="testimonials" class="py-5">
        <div class="container">
            <h2 class="text-center">Here’s What My Clients Are Saying</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="testimonial">
                        <blockquote class="blockquote">
                            <p class="mb-0">"Fantastic work! The project exceeded our expectations."</p>
                            <footer class="blockquote-footer">Kashyap, <cite title="Source Title">Kash Enterprises</cite></footer>
                        </blockquote>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="testimonial">
                        <blockquote class="blockquote">
                            <p class="mb-0">"Working with Nandini was an absolute pleasure! The design process was smooth, and the final result was better than we could have imagined. Highly recommend!"</p>
                            <footer class="blockquote-footer">Susan, <cite title="Source Title"> Boho Enterprises</cite></footer>
                        </blockquote>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="testimonial">
                        <blockquote class="blockquote">
                            <p class="mb-0">"Great attention to detail and on time delivery!"</p>
                            <footer class="blockquote-footer">Jack, <cite title="Source Title">Jack and Jill Traders</cite></footer>
                        </blockquote>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Let’s Chat!</h2>
            <p class="text-center">Got a project in mind? I’d love to hear from you. Drop me a message below, and let’s get started!</p>
            <form action="submit_form.php" method="POST">
                <div class="form-row">
                    <div class="form-group col-md-6">
                        <label for="name">Your Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Your Name">
                    </div>
                    <div class="form-group col-md-6">
                        <label for="email">Email Address</label>
                        <input type="email" class="form-control" id="email" placeholder="Your Email">
                    </div>
                </div>
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Tell me a little about your project..."></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </section>
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Creative Studio. All rights reserved. Let’s create something incredible together!</p>
        <div>
            <a href="https://twitter.com" class="text-white mx-2">Twitter</a>
            <a href="https://linkedin.com" class="text-white mx-2">LinkedIn</a>
            <a href="https://github.com" class="text-white mx-2">GitHub</a>
        </div>
    </footer>

</body>
</html>
