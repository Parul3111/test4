<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="assets/css/styles.css" />
    <title>D2</title>
    <style>
        .cursor {
            position: fixed;
            border-radius: 50%;
            transform: translateX(-50%) translateY(-50%);
            pointer-events: none;
            left: -100px;
            top: 50%;
            mix-blend-mode: difference;
            background-color: transparent;
            z-index: 10000;
            border: 2px solid white;
            height: 30px;
            width: 30px;
            transition: all 300ms ease-out;
        }
    </style>
</head>

<body>
    <main>
        <!-- navbar  -->
        <nav class="navbar" id="scrollTop">
            <div class="container">
                <div class="navbarCont">
                    <div class="logo">
                        <p>Zebronics</p>
                    </div>
                    <div class="displayDesktop">
                        <ul class="navLinks aln-cntr">
                            <li><a href=".">Home</a></li>
                            <li><a href="#About">About</a></li>
                            <li><a href="#services">Services</a></li>
                            <li><a href="#projects">Project</a></li>
                            <li><a href="#testimonials">Testimonial</a></li>
                            <li><a href="#contact">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="nvList">
                        <ul class="navLinks aln-cntr navListMbl">
                            <li><a href=".">Home</a></li>
                            <li><a href="#About">About</a></li>
                            <li><a href="#services">Services</a></li>
                            <li><a href="#projects">Project</a></li>
                            <li><a href="#testimonials">Testimonial</a></li>
                            <li><a href="#contact">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="threebars displayMbl aln-cntr">☰</div>
                    <div class="closenv aln-cntr">✕</div>
                </div>
            </div>
        </nav>

        <!-- header  -->
        <header class="grdaientBg headerBg ptb-5">
            <div class="container">
                <div class="row">
                    <div class="col-6 mainHeading aln-cntr">
                        <h1>Growing Innovation with Cutting-Edge IT Solutions.</h1>
                        <p>
                            We are committed to site design and development as well as efficient operations. Let's work together to solve your IT problems.
                        </p>
                        <div class="ctaBtn">
                            <a href="#contact">Get In Touch &gt;</a>
                        </div>
                    </div>
                    <div class="col-6 headerSideImg">
                        <img src="assets/images/headerImg.webp" alt="" />
                    </div>
                </div>
            </div>
        </header>
        <!-- About -->
        <section class="ptb-5" id="About">
            <div class="container">
                <div class="aboutContainer">
                    <div class="row">
                        <div class="col-6 aln-cntr">
                            <div class="aboutExOff">
                                <div class="sectHeadingBox">
                                    <p>About</p>
                                    <h2>
                                        <span class="pinkClr">Zebronics</span> is Web Design & Development Company
                                    </h2>
                                </div>
                                <div class="abtCont">
                                    <p>
                                        We are your reliable IT company, providing site design and development as well as unique solutions for your digital needs.
                                    </p>
                                    <div class="displayDesktop">
                                        <h5>Let's work Together</h5>
                                        <div class="ctaBtn">
                                            <a href="#contact">Get In Touch &gt;</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-6">
                            <div class="aboutFeactBox">
                                <div class="FeatBox">
                                    <img src="assets/images/quality.png" alt="" />
                                    <h6>7+</h6>
                                    <p>Years Experience</p>
                                </div>
                                <div class="FeatBox">
                                    <img src="assets/images/prjtDone.png" alt="" />
                                    <h6>200+</h6>
                                    <p>Project Completed</p>
                                </div>
                                <div class="FeatBox">
                                    <img src="assets/images/handshake.png" alt="" />
                                    <h6>100%</h6>
                                    <p>Customer satisfaction</p>
                                </div>
                                <div class="FeatBox">
                                    <img src="assets/images/timeMang.png" alt="" />
                                    <h6>100%</h6>
                                    <p>Time Managment</p>
                                </div>
                                <div class="FeatBox">
                                    <img src="assets/images/freeLogo.png" alt="" />
                                    <h6>1</h6>
                                    <p>Free Logo (at 3+ Pages)</p>
                                </div>
                                <div class="FeatBox">
                                    <img src="assets/images/customSprt.png" alt="" />
                                    <h6>24/7</h6>
                                    <p>Customer Support</p>
                                </div>
                            </div>
                        </div>
                        <div class="abtCont displayMbl">
                            <h5>Let's work Together</h5>
                            <div class="ctaBtn"><a href="">Get In Touch &gt;</a></div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- services  -->
        <section class="halfWallPaper ptb-5" id="services">
            <div class="container">
                <div class="sectHeadingBox txt-cntr">
                    <p>Service</p>
                    <h2>Our Agency Services</h2>
                </div>
                <div class="row servicesRow">
                    <div class="col-6">
                        <div class="serBox1 clrBlue">
                            <div class="servBox aln-cntr">
                                <p>Web Designing</p>
                                <h4>Making Creative Web Experiences</h4>
                                <a href="#" class="underLineEffect">Learn more </a>
                            </div>
                            <div class="servImg">
                                <img src="assets/images/webDesign.webp" alt="" />
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="serBox1 clrRed">
                            <div class="servBox aln-cntr">
                                <p>Web Development</p>
                                <h4>Developing Innovative Online Solutions</h4>
                                <a href="#" class="underLineEffect">Learn more </a>
                            </div>
                            <div class="servImg">
                                <img src="assets/images/webDevlopment.webp" alt="" class="img2" />
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="serBox1 clrLightBlue">
                            <div class="servBox aln-cntr">
                                <p>ui & ux</p>
                                <h4>Designing User-Friendly Interfaces</h4>
                                <a href="#" class="underLineEffect">Learn more </a>
                            </div>
                            <div class="servImg">
                                <img src="assets/images/uiuX.webp" alt="" class="img3" />
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="serBox1 clrYllw">
                            <div class="servBox aln-cntr">
                                <p>Web Maintenance</p>
                                <h4>Maintaining Websites Working Comfortably</h4>
                                <a href="#" class="underLineEffect">Learn more </a>
                            </div>
                            <div class="servImg">
                                <img src="assets/images/webMaintence.webp" alt="" class="img4" />
                            </div>
                        </div>
                    </div>
                </div>
                <div class="ctaBtn dFlex">
                    <h5>Let's Start A <strong>New Project Together</strong></h5>
                    <a href="https://calendly.com/gurheesolutions/30min" target="_blank">Book a Call</a
            >
          </div>
        </div>
      </section>
      <!-- project -->
      <section class="ProjectSection ptb-5" id="projects">
        <div class="container">
          <div class="sectHeadingBox txt-cntr">
            <p>Projects</p>
            <h2>our recent work</h2>
          </div>
          <div class="row mb-40">
            <div class="col-6">
              <div class="projectCont clrPink1">
                <div class="projectContent">
                  <h3>Vallera</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Doloribus quam corrupti
                  </p>
                </div>
                <div class="projectImg">
                  <img src="assets/images/Vallera.png" alt="" />
                </div>
              </div>
            </div>
            <div class="col-6">
              <div class="projectCont clrPink2">
                <div class="projectContent">
                  <h3>Vallera</h3>
                  <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                    Doloribus quam corrupti maiores
                  </p>
                </div>
                <div class="projectImg">
                  <img src="assets/images/Vallera.png" alt="" />
                </div>
              </div>
            </div>
          </div>
          <div class="ctaBtn dFlex">
            <h5>Our Recently <strong>Completed Work</strong></h5>
            <a href="https://calendly.com/gurheesolutions/30min" target="_blank"
              >View More</a
            >
          </div>
        </div>
      </section>
      <!-- project -->
      <!-- ourIndustry -->
      <section class="ourIndustry ptb-5">
        <div class="container">
          <div class="sectHeadingBox txt-cntr">
            <p>Our specialization</p>
            <h2>Industries We Serve</h2>
          </div>
          <div class="dFlex mb-30">
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/landingserv.png" alt="" />
                <p>Landing Pages</p>
              </div>
            </div>
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/portfolioserv.png" alt="" />
                <p>Portfolio</p>
              </div>
            </div>
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/tourserv.png" alt="" />
                <p>Tour & Travels</p>
              </div>
            </div>
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/horoscopeserv.png" alt="" />
                <p>Horoscope</p>
              </div>
            </div>
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/restaurantserv.png" alt="" />
                <p>Restaurants</p>
              </div>
            </div>
            <div class="induBox">
              <div class="industryBox">
                <img src="assets/images/Fitness.png" alt="" />
                <p>Fitness</p>
              </div>
            </div>
          </div>
          <div class="ctaBtn dFlex">
            <h5>Let's Start A <strong>New Project Together</strong></h5>
            <a href="#contact">Book a Call</a>
                </div>
            </div>
        </section>
        <!-- ourIndustry -->
        <!-- testimonial -->
        <section class="ptb-5 testiBg" id="testimonials">
            <div class="container">
                <div class="sectHeadingBox txt-cntr">
                    <p>testimonials</p>
                    <h2>Our happy Clients</h2>
                </div>
                <div class="testimonialCont">
                    <div class="row">
                        <div class="col-5 testiRight aln-cntr">
                            <h3>What Our Clients Say About Our Company</h3>
                            <p>
                                Discover our business through the perspective of our customers. Learn how our web design solutions have helped organizations transform and exceed expectations.
                            </p>
                        </div>
                        <div class="col-7">
                            <div class="testiCont">
                                <div class="testiSlide">
                                    <div>
                                        <figure class="testimonial">
                                            <blockquote>
                                                Finding an IT partner who actually cares for a small business was difficult until we discovered Zebronics. Their responsiveness, dependability, and reasonable pricing have made a major difference. They have gained our faith.

                                                <div class="btn"></div>
                                            </blockquote>
                                            <img src="assets/images/testi4.webp" alt="" />
                                            <div class="peopl">
                                                <h3>Neil Patel</h3>
                                                <p class="indentity">Delhi, INDIA</p>
                                            </div>
                                        </figure>
                                    </div>

                                    <div>
                                        <figure class="testimonial">
                                            <blockquote>
                                                Zebronics has been a delight to work with from the initial consultation to the final launch. The procedure was made easier by their team's communication and teamwork. The end result is a website that actually speaks to our intended audience.
                                                <div class="btn"></div>
                                            </blockquote>
                                            <img src="assets/images/testi3.webp" alt="" />
                                            <div class="peopl">
                                                <h3>Tania</h3>
                                                <p class="indentity">Houston, USA</p>
                                            </div>
                                        </figure>
                                    </div>

                                    <div>
                                        <figure class="testimonial">
                                            <blockquote>
                                                I'm astounded by Zebronics's degree of skill and originality. They created a website that stands out in a crowded market. Their dedication to ongoing improvement and response distinguishes them.
                                                <div class="btn"></div>
                                            </blockquote>
                                            <img src="assets/images/testi2.webp" alt="" />
                                            <div class="peopl">
                                                <h3>Lara Shawn</h3>
                                                <p class="indentity">Phuket, THAILAND</p>
                                            </div>
                                        </figure>
                                    </div>

                                    <div>
                                        <figure class="testimonial">
                                            <blockquote>
                                                After working with Zebronics, our website underwent an incredible metamorphosis. They created a seamless user experience by integrating utility and aesthetics effortlessly. It appears as though they have given our brand life online.
                                                <div class="btn"></div>
                                            </blockquote>
                                            <img src="assets/images/testi1.webp" alt="" />
                                            <div class="peopl">
                                                <h3>Stiff Dean</h3>
                                                <p class="indentity">Melbourne, AUSTRALIA</p>
                                            </div>
                                        </figure>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- testimonial -->
        <!-- contact us -->
        <section class="contactBg ptb-5" id="contact">
            <div class="container">
                <div class="sectHeadingBox txt-cntr">
                    <p>Contact us</p>
                    <h2>Get in touch with us</h2>
                </div>
                <div class="row pt-30">
                    <div class="col-6 txt-cntr">
                        <img src="assets/images/webContact.webp" class="contactImg" />
                    </div>
                    <div class="col-6">
                        <div class="contactForm">
                            <form>
                                <input type="text" class="inputStyle" placeholder="Enter Your Name" required="" />
                                <input type="email" class="inputStyle" placeholder="Enter Your Email" required="" />
                                <input type="text" class="inputStyle" placeholder="Enter Your Subject" required="" />
                                <textarea name="" id="" cols="40" rows="4" placeholder="Enter Your Message" class="inputStyle" required=""></textarea>
                                <button class="contactBtn">Send</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- contact us -->
        <!-- faq -->
        <section class="ptb-5">
            <div class="container">
                <div class="sectHeadingBox txt-cntr">
                    <p>faq</p>
                    <h2>Frequently Asked Questions</h2>
                </div>
                <div class="accordion">
                    <div class="accrd active">
                        <div class="label">
                            What services do you offer as a web designing company?
                        </div>
                        <div class="content">
                            Custom website design, responsive design, development solutions, UI/UX design, and website makeover are just a few of the wide range of web design services we provide.
                        </div>
                    </div>
                    <div class="accrd">
                        <div class="label">
                            How long does it take to design and develop a website?
                        </div>
                        <div class="content">
                            Depending on the size and complexity of the project, different timelines apply. Larger projects can take several months, whereas simpler websites may only take a few weeks. During the project consultation, we present projected time frames.
                        </div>
                    </div>
                    <div class="accrd">
                        <div class="label">
                            Do you work with specific programming languages and technologies?
                        </div>
                        <div class="content">
                            Yes, we are knowledgeable in a wide range of computer languages and frameworks, such as HTML, CSS, JavaScript, Jquery, PHP, Wordpress, Figma, Bootstrap, Tallwind CSS, and others. Based on the needs of the project, we select the finest tools.
                        </div>
                    </div>
                    <div class="accrd">
                        <div class="label">
                            What steps are involved in the web development process?
                        </div>
                        <div class="content">
                            Analysis of the requirements, design, programming, testing, deployment, and continuing maintenance are normally included in our web development process. Throughout the process, we make sure there is constant communication and feedback.
                        </div>
                    </div>
                    <div class="accrd">
                        <div class="label">Can you redesign an existing website?</div>
                        <div class="content">
                            Absolutely! We provide website redesign services to update the appearance and functionality of your present website while bringing it into the modern era.
                        </div>
                    </div>
                    <div class="accrd">
                        <div class="label">
                            What is the cost of your web design & development services?
                        </div>
                        <div class="content">
                            The cost is influenced by a number of variables, including the project's complexity, the features needed, and the extent of the work. After evaluating your unique demands during the initial meeting, we offer customized prices.
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- faq -->
        <!-- footer -->
        <footer>
            <div class="container">
                <div class="row footerRow">
                    <div class="col-4 footerAbt footerheading">
                        <h5>Zebronics</h5>
                        <p>
                            We are your reliable IT company, providing site design and development as well as unique solutions for your digital needs.
                        </p>
                    </div>
                    <div class="col-4 footerheading">
                        <h5>Quick Links</h5>
                        <div class="footerFlex">
                            <p>
                                <a href="#About">About</a>
                            </p>
                            <p>
                                <a href="#services">Services</a>
                            </p>
                            <p>
                                <a href="#projects">Projects</a>
                            </p>
                            <p>
                                <a href="#testimonials">Testimonials</a>
                            </p>
                        </div>
                    </div>
                    <div class="col-4 footerheading">
                        <h5>Contact Us</h5>
                        <div class="footerFlex">
                            <p>
                                <a href="tel:9465473151">+91 9465473151</a>
                            </p>
                            <p>
                                <a href="mailtto:gurheesolutions@gmail.com">@gmail.com</a>
                            </p>
                            <p>
                                <a href="#">Punjab, INDIA</a>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="copyryt txt-cntr">
                    <p>Copyright © 2023 All rights reserved.</p>
                </div>
            </div>
        </footer>
        <!-- footer -->
        <a href="#" class="topBar"><img src="assets/images/up-arrow.png" alt="" /></a>
    </main>
    <!-- with cursor code -->
    <!-- <div class="cursor" id="cursor"></div> -->
    <!-- with cursor code -->
</body>
<script src="assets/js/jquery.min.js"></script>
<script src="assets/js/scripts.js"></script>
<script src="assets/js/testimonialjs.js"></script>

</html>
