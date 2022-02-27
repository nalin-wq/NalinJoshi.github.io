<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta http-equiv="expires" content="Fri,31 Dec 2010 11:59:59 GMT" />
        <meta http-equiv="cache-control" content="no-cache">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!--=============== FAVICON ===============-->
        <link rel="shortcut icon" href="" type="image/x-icon">

        <!--=============== BOXICONS ===============-->
        <link href='https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css' rel='stylesheet'>
        <!--=============== SWIPER CSS ===============-->
        <link rel="stylesheet" href="nalin.css">

        <!--=============== CSS ===============-->
        <link rel="stylesheet" href="">

        <title> yhalla habibi!!</title>
    </head>
    <body>
        <!--=============== HEADER ===============-->
        <header class="header" id="header">
            <nav class="nav container">
                <a href="#" class="nav__logo">Nalin</a>

                
                    <div class="nav__menu">
                        <ul class="nav__list">
                            <li class="nav__item">
                                <a href="#home" class="nav__link">
                                    <i class='bx bx-home'></i>
                                </a>
                            </li>
                            <li class="nav__item">
                                <a href="#about" class="nav__link">
                                    <i class='bx bx-user' ></i>
                                </a>
                            </li>
                            <li class="nav__item">
                                <a href="#skills" class="nav__link">
                                    <i class='bx bx-file-find' ></i>
                                </a>
                            </li>
                            <li class="nav__item">
                                <a href="#work" class="nav__link">
                                    <i class='bx bx-briefcase' ></i>
                                </a>
                            </li>
                            <li class="nav__item">
                                <a href="#contact" class="nav__link">
                                    <i class='bx bx-chat' ></i>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <i class='bx bx-moon change-theme' id="theme-button" ></i>
            </nav>
        </header>

        <!--=============== MAIN ===============-->
        <main class="main">
            <!--=============== HOME ===============-->
            <section class="home section" id="home">
                <div class="home__container container grid">
                    <div class="home__data">
                        <span class="home__greeting">Hello, I'm </span>
                        <h1 class="home__name">Nalin Joshi</h1>
                        <h3 class="p">web developer</h3>                              
                    </div>
                    <div class="home__handle">
                      <a href="#about" class="home__scroll">
                        <i class='bx bx-mouse home__scroll-icon' ></i>
                        <span class="home__scroll-name">Scroll Down</span>
                      </a>
                    </div> 
                </div> 
            </section>
            
            <!--=============== ABOUT ===============-->
            <section class="about section" id="about">
               <span class="section__subtitle">Who Am I</span>
               <h2 class="section__title">The Best</h2>

               <div class="about__container container grid">
                   <img src="nalin4.jpg" style="width: 240px;" alt="" class="about__img">

                   <div class="about__data">
                       <div class="about__info">
                           <div class="about__box">
                            <i class='bx bx-award about__icon' ></i>
                               <h3 class="about__title">Experience</h3>
                                   <span class="about__subtitle">+2 months</span>
                           </div>

                           <div class="about__box">
                            <i class='bx bx-book-content about__icon' ></i>
                            <h3 class="about__title">Projects</h3>
                                <span class="about__subtitle">+5</span>
                        </div>

                        <div class="about__box">
                            <i class='bx bx-support about__icon' ></i>
                            <h3 class="about__title">Available</h3>
                                <span class="about__subtitle">24/7</span>
                        </div>
                       </div>
                       <p class="about__description">
                           Frontend dev, I create design animation for user...
                       </p>

                   </div>
               </div>
            </section>

            <!--=============== SKILLS ===============-->
            <section class="skills section" id="skills">
                <span class="section__subtitle">what i can do</span>
                <h2 class="section__title">My skills</h2>

                <div class="skills__container container grid">

                    <div class="skills__content">
                        <h3 class="skills__title">Frontend dev</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">HTML</h3>
                                        <span class="skills__level">Basic</span>
                                    </div>
                                </div>
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">CSS3</h3>
                                        <span class="skills__level">Advanced</span>
                                    </div>
                                </div>
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">JavaScript</h3>
                                        <span class="skills__level">Intermediate</span>
                                    </div>
                                </div>
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">Bootstrap</h3>
                                        <span class="skills__level">Advanced</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                        <div class="skills__content">
                        <h3 class="skills__title">Backend dev</h3>

                        <div class="skills_box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">PHP</h3>
                                        <span class="skills__level">Intermediate</span>
                                    </div>
                                </div>
                                <div class="skills__data">
                                    <i class='bx bx-badge-check' ></i>
                                    
                                    <div>
                                        <h3 class="skills__name">MySql</h3>
                                        <span class="skills__level">Basic</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
            </section>


            <!--=============== WORK ===============-->
            <section class="work section" id="work">
                
            </section>

            <!--=============== CONTACT ===============-->
            <section class="contact section" id="contact">
                <span class="section__subtitle">Project in Mind?</span>
                <h2 class="section__title">Contact Me</h2>

            <div class="contact__container container grid">
                <div class="contact__content">
                      
                    <form action="" class="contact__form">
                        <div class="contact__form-div">
                            <label for="" class="contact__form-tag">Name</label>
                            <input type="text" placeholder="Name" class="contact__form-input">
                        </div>
                        <div class="contact__form-div">
                            <label for="" class="contact__form-tag">Mail</label>
                            <input type="text" placeholder="Email" class="contact__form-input">
                        </div>
                        <div class="contact__form-div">
                            <label for="" class="contact__form-tag">Phone</label>
                            <input type="text" Placeholder="Phone no." class="contact__form-input">
                        </div>
                        <div class="contact__form-div contact__form-area">
                            <label for="" class="contact__form-tag"></label>
                            <textarea name="" id="" cols="30" rows="10" placeholder="Project idea?" class="contact__form-input"></textarea>
                        </div> 

                        <button class="button button--ghost">Send</button>
                    </form>
                </div>
            </div>
            </section>
        </main>

        <!--=============== FOOTER ===============-->
        <footer class="footer">
            <div class="footer__container container">
                <h1 class="footer__title">Nalin</h1>

                <ul class="footer__list">
                    <li>
                        <a href="#about" class="footer__link">About</a>
                    </li>
                    <li>
                        <a href="#work" class="footer__link">About</a>
                    </li>
                    <li>
                        <a href="#" class="footer__link">About</a>
                    </li>
                </ul>

                <ul class="footer__social">
                    <a href="" target="_blank" class="footer__social-link">
                        <i class='bx bxl-facebook' ></i>
                    </a>
                    <a href="" target="_blank" class="footer__social-link">
                        <i class='bx bxl-instagram' ></i>
                    </a>
                    <a href="" target="_blank" class="footer__social-link">
                        
                    </a>
                </ul>
            </div>
        </footer>

        <!--=============== SCROLLREVEAL ===============-->
        <script src="https://unpkg.com/scrollreveal"></script>
        <!--=============== SWIPER JS ===============-->
        <script src=""></script>

        <!--=============== MIXITUP FILTER ===============-->
        <script src=""></script>

        <!--=============== MAIN JS ===============-->
        <script src="nalin.js"></script>
    </body>
</html>
