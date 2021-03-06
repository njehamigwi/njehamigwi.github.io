<!DOCTYPE html>
<html lang="en">
<head>
    <!-- basic metas -->
    <meta charset="utf-8" />
    <meta content="X-UA-Compatible" name="IE-Edge" />

    <!-- mobile meta -->
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />

    <!-- site metas -->
    <title>Njeha Migwi - Personal Portfolio</title>
    <meta content="" name="keywords" />
    <meta content="" name="description" />
    <meta content="Njeha Migwi" name="author" />

    <!-- google fonts -->
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link href="https://fonts.googleapis.com/css2?family=Kiwi+Maru:wght@300;400;500&family=Nunito:wght@200;300;400;600;700&family=Quicksand:wght@300;400;500;600;700&family=Ubuntu:wght@300;400;500;700&display=swap" rel="stylesheet" />

    <!-- main stylesheet file -->
    <link rel="stylesheet" href="css/main.css" />

    <!-- libraries css files -->
    <script type="module" src="https://unpkg.com/ionicons@5.4.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule="" src="https://unpkg.com/ionicons@5.4.0/dist/ionicons/ionicons.js"></script>

    <!-- responsive stylesheet file -->
    <link rel="stylesheet" href="css/responsive.css" />

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->

	<!-- ===================================================================
		Theme Name: Personal Portfolio
		Theme URL: 
		Author: Njeha Migwi
		Author URL: 
	===================================================================== -->
</head>
<body>
    <!-- start navbar section -->
    <nav id="main-nav">
        <div class="padded-side">
            <div class="nav-list">
                <div class="nav-logo">
                    <a href="#header">Njeha Migwi</a>
                </div>

                <div class="nav-menu">
                    <a href="#about" class="smoothScroll">About</a>
                    <a href="#portfolio" class="smoothScroll">Portfolio</a>
                    <a href="#contact" class="smoothScroll">Contact</a>
                </div>
            </div>
        </div>
    </nav> <!-- end navbar section -->

    <!-- start header section -->
    <div id="header">
        <div class="padded-side">
            <div class="header-content">
                <div>
                    <img class="profile_pic" src="images/profile_pic.jpg" alt="njeha migwi" />
                </div>

                <h4>Jambo! I'm Njeha.</h4>
                <p>I'm a Full-Stack Software Developer who has a crush on Django and enjoys creating web application projects while writing about my software development experience.</p>
            </div>
        </div>
    </div> <!-- end header section -->

    <!-- start about section -->
    <section id="about">
        <!-- start about-content-header section -->
        <div class="padded-side m-60">
            <div class="about-content-header">
                <h4>I'm <span class="typed"></span></h4>
                <p>Software Engineer | Writer | Artist</p>
                <h5>As Seen On</h5>

                <ul class="list-social">
                    <li><a href="https://github.com/njehamigwi" target="_blank"><ion-icon name="logo-github"></ion-icon></a></li>
                    <li><a href="https://www.linkedin.com/in/njeha-migwi-1a2315140/" target="_blank"><ion-icon name="logo-linkedin"></ion-icon></a></li>
                    <li><a href="https://twitter.com/NjehaM" target="_blank"><ion-icon name="logo-twitter"></ion-icon></a></li>
                </ul>
            </div>
        </div> <!-- end about service section -->

        <!-- start about me section -->
        <div class="padded-side">
            <div class="section-title">
                <h2>About Me</h2>
            </div>
        
            <div class="about-descr">
                <p class="p-heading">I started this website as a collection of the concepts I have studied and built over time, and everything else I desire to write in future. I have started writing web development tutorial as a documentation of everything I have learnt and will continue learning.</p>

                <p class="p-heading">I want to create a beautiful space on the internet, and inspire others to do so as well. I believe in giving back and learning in public. That is why my site has no ads, affiliates, sponsors, tracking, analytics, or social media. If you would like to support what I do and my content has helped you out in your learning journey, you can buy me a coffee or donate on Patreon.</p>

                <p class="p-heading">You can view my tutorials, read my blogs, learn more about me, or get in touch. To receive an email when I write or create new content, please subscribe to the newsletter.</p>
            </div>
        </div> <!-- end about me section -->
    </section> <!-- end about section -->
    
    <!-- start portfolio section-->
    <section id="portfolio">
        <!-- start portfolio-services section -->
        <div class="m-60">
            <div class="padded-side">
                <div class="section-title">
                    <h2>What I Do</h2>
                </div>
            
                <div class="flex-container">
                    <div class="services-block">
                        <i><ion-icon name="color-wand-outline"></ion-icon></i>
                        <span>Web Design</span>
                    </div>

                    <div class="services-block">
                        <i><ion-icon name="bulb"></ion-icon></i>
                        <span>Brand Identity</span>
                    </div>

                    <div class="services-block">
                        <i><ion-icon name="build"></ion-icon></i>
                        <span>UI / UX Design</span>
                    </div>
                </div>
            </div>
        </div> <!-- end portfolio-services section -->

        <!-- start portfolio section -->
        <div class="padded-side">
            <div>
                <div class="section-title">
                    <h2>My Portfolio</h2>
                </div>
            
                <div >
                    <div>
                        <div class="portfolio-list">
                            <ul class="nav">
                                <li>all</li>
                                <li>web designs</li>
                                <li>mockups</li>
                                <li>branding</li>
                            </ul>
                        </div>

                        <div class="portfolio-container">
                            <div class="portfolio-thumbnail">
                                <a href="#"><img src="#" alt="" /></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div> <!-- end portfolio section -->
    </section> <!-- end portfolio section-->

    <!-- start contact section -->
    <div id="contact" class="m-60">
        <div class="padded-side">
            <div class="section-title">
                <h2>Get In Touch</h2>
            </div>

            <p class="contact-descr">I hope you love the site, and if there is anything you want to talk about with me feel free to drop me a line by email. I am happy to hear your comments, feedback, suggestions, or just say hi!</p>

            <ul class="contact-details">
                <li><ion-icon name="mail-outline"></ion-icon><span>njehamigwi@gmail.com</span></li><br />
                <li><ion-icon name="logo-twitter"></ion-icon><span>@njehamigwi</span></li>
            </ul>
        </div>
    </div> <!-- end contact section -->

    <!-- start footer section -->
    <div id="footer">
        <div class="padded-side">
            <div class="footer-text">
                Copyright &copy; 2020. All rights reserved. <br /> <span>Designed by Njeha Migwi.</span>
            </div>

            <div class="socials-media">
                <ul>
                    <li><a href="https://github.com/njehamigwi" target="_blank"><ion-icon name="logo-github"></ion-icon></a></li>
                    <li><a href="https://www.linkedin.com/in/njeha-migwi-1a2315140/" target="_blank"><ion-icon name="logo-linkedin"></ion-icon></a></li>
                    <li><a href="https://twitter.com/NjehaM" target="_blank"><ion-icon name="logo-twitter"></ion-icon></a></li>
                </ul>
            </div>
        </div>
    </div> <!-- end footer section -->

    <!-- JavaScript libraries -->
    <!-- Add jquery cdn -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <!-- typed.min.js file from typed.js folder -->
    <script src="lib/typed/typed.js"></script>

    <!-- template main javascript file -->
    <script src="js/main.js"></script>

</body>
</html>
