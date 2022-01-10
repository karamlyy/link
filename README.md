<!DOCTYPE html>
<html lang="en">
<head>
  <title>The LINK</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<!--  HEADER START-->
<header class="header">
  <div class="container">
    <div class="row justify-content-between align-items-center">
      <div class="logo">
        <a href="#">LINK</a>
      </div>
      <input type="checkbox" id="nav-check">
      <label for="nav-check" class="nav-toggler">
        <span></span>
      </label>
      <nav class="nav">
        <ul>
          <li><a href="#home">Main</a> </li>
          <li><a href="#whyus">Why LINK?</a></li>
          <li><a href="#courses">Courses</a></li>
          <li><a href="#reviews">Professors</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </div>
</header>
<!--  HEADER END-->
<!--  HOME SECTION START-->
<section class="home-section" id="home">
  <div class="container">
    <div class="row h-100 align-items-center align-content-center">
      <div class="home-text">
        <h1>The organism that converts coffee to code <br><span>-Programmer</span></h1>
        <h2>Explore the competitive coding world</h2>
        <a href="#courses" class="btn btn-1">Get Started</a>
      </div>
      <div class="home-img">
        <div class="home-img-inner">
          <div class="home-course">
            <div class="home-course-item">Html</div>
            <div class="home-course-item">Css</div>
            <div class="home-course-item">JS</div>
            <div class="home-course-item">React</div>
          </div>
           <img src="img/home-img.png" alt="">
        </div>
      </div>
    </div>
  </div>
</section>
<!--  HOME SECTION START-->
<!--  WHYUS SECTION START-->
<section class="whyus-section sec-padding" id="whyus">
  <div class="container">
    <div class="row">
      <div class="section-title">
        <h2>Why <span>LINK?</span></h2>
      </div>
    </div>
    <div class="row">
      <div class="why-us-item">
        <div class="icon">
          <i class="fa fa-graduation-cap" aria-hidden="true"></i>
        </div>
        <h3>Experience Instructor</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nesciunt cum soluta eveniet blanditiis exercitationem facilis reiciendis, amet eum laboriosam expedita aliquid! Ducimus, quibusdam ex.</p>
      </div>
      <div class="why-us-item">
        <div class="icon">
          <i class="fa fa-laptop" aria-hidden="true"></i>
        </div>
        <h3>Live Projects</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nesciunt cum soluta eveniet blanditiis exercitationem facilis reiciendis, amet eum laboriosam expedita aliquid! Ducimus, quibusdam ex.</p>
      </div>
      <div class="why-us-item">
        <div class="icon">
          <i class="fa fa-certificate" aria-hidden="true"></i>
        </div>
        <h3>Certification</h3>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nesciunt cum soluta eveniet blanditiis exercitationem facilis reiciendis, amet eum laboriosam expedita aliquid! Ducimus, quibusdam ex.</p>
      </div>
    </div>
  </div>
</section>
<!--  WHYUS SECTION END-->
<!--  COURSES SECTION START-->
<section class="courses-section sec-padding" id="courses">
  <div class="container">
    <div class="row">
      <div class="section-title">
        <h2><span>Popular  </span> Courses</h2>
      </div>
    </div>
    <div class="row">
      <div class="course-item">
        <a href="#">
          <div class="course-img">
            <img src="img/courses/1.jpg" alt="">
            <div class="course-price">
              $25
            </div>
          </div>
          <div class="course-info">
            <ul>
              <li>25 Video</li>
              <li>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
              </li>
            </ul>
            <h3>Html,Css,Js</h3>
          </div>
        </a>
      </div>
      <div class="course-item">
        <a href="#">
          <div class="course-img">
            <img src="img/courses/2.jpg" alt="">
            <div class="course-price">
              $50
            </div>
          </div>
          <div class="course-info">
            <ul>
              <li>15 Videos</li>
              <li>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
              </li>
            </ul>
            <h3>React</h3>
          </div>
        </a>
      </div>
      <div class="course-item">
        <a href="#">
          <div class="course-img">
            <img src="img/courses/3.jpg" alt="">
            <div class="course-price">
              $40
            </div>
          </div>
          <div class="course-info">
            <ul>
              <li>45 Videos</li>
              <li>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
              </li>
            </ul>
            <h3>Flutter</h3>
          </div>
        </a>
      </div>
      <div class="course-item">
        <a href="#">
          <div class="course-img">
            <img src="img/courses/4.jpg" alt="">
            <div class="course-price">
              $60
            </div>
          </div>
          <div class="course-info">
            <ul>
              <li>50 Videos</li>
              <li>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
              </li>
            </ul>
            <h3>Javascript</h3>
          </div>
        </a>
      </div>
    </div>
  </div>
</section>
<!--  COURSES SECTION END-->
<!--  FUNCATCS SECTION START-->
<section class="fun-facts-section sec-padding">
  <div class="container">
    <div class="row">
      <div class="section-title">
        <h2>Our <span>Success</span></h2>
      </div>
    </div>
    <div class="row">
      <div class="fun-facts-img">
        <img src="img/fun-facts-img.png" alt="">
      </div>
      <div class="fun-facts-items">
        <div class="row">
          <div class="fun-facts-item">
            <h3>7k</h3>
            <p>Graduation</p>
          </div>
          <div class="fun-facts-item">
            <h3>32k</h3>
            <p>Registered Students</p>
          </div>
          <div class="fun-facts-item">
            <h3>50+</h3>
            <p>All Courses</p>
          </div>
          <div class="fun-facts-item">
            <h3>95%</h3>
            <p>Satisfaction Rate</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!--  FUNCATCS SECTION END-->
<!--  REVIEW SECTION START-->
<section class="reviews-section sec-padding" id="reviews">
  <div class="container">
    <div class="row">
      <div class="section-title">
        <h2>Professors <span>Comments</span></h2>
      </div>
    </div>
    <div class="row">
      <div class="review-item">
        <img src="img/reviews/1.jpg" alt="">
        <p><i class="fa fa-quote-left"></i> Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis totam modi, optio reprehenderit excepturi eum ipsa vero officia tenetur voluptas.
          <i class="fa fa-quote-right"></i></p>
          <h3>Laman Khudadatzade</h3>
          <span>Frontend Developer</span>
      </div>
      <div class="review-item">
        <img src="img/reviews/2.png" alt="">
        <p><i class="fa fa-quote-left"></i> Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis totam modi, optio reprehenderit excepturi eum ipsa vero officia tenetur voluptas.
          <i class="fa fa-quote-right"></i></p>
          <h3>Nuray Gurbanova</h3>
          <span>UI/UX Designer</span>
      </div>
      <div class="review-item">
        <img src="img/reviews/3.jpg" alt="">
        <p><i class="fa fa-quote-left"></i> Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis totam modi, optio reprehenderit excepturi eum ipsa vero officia tenetur voluptas.
          <i class="fa fa-quote-right"></i></p>
          <h3>Iltun Huseynli</h3>
          <span>PHP Developer</span>
      </div>
      <div class="review-item">
        <img src="img/reviews/4.jpg" alt="">
        <p><i class="fa fa-quote-left"></i> Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis totam modi, optio reprehenderit excepturi eum ipsa vero officia tenetur voluptas.
          <i class="fa fa-quote-right"></i></p>
          <h3>Karam Afandi</h3>
          <span>React JS Developer</span>
      </div>
    </div>
  </div>
</section>
<!--  REVIEW SECTION END-->
<!--  CONTACT SECTION START-->
<section class="contact-section sec-padding" id="contact">
  <div class="container">
    <div class="row">
      <div class="section-title">
        <h2><span>Contact</span></h2>
      </div>
    </div>
    <div class="row">
      <div class="contact-img">
        <img src="img/contact-img.png" alt="">
      </div>
      <div class="contact-form">
        <form >
          <div class="input-group">
            <input type="text" placeholder="Name" class="form-control">
          </div>
          <div class="input-group">
            <input type="text" placeholder="E-mail" class="form-control">
          </div>
          <div class="input-group">
            <input type="text" placeholder="Phone" class="form-control">
          </div>
          <div class="input-group">
           <textarea placeholder="Your message" class="form-control"></textarea>
          </div>
          <button type="submit" class="btn btn-1">Send</button>
        </form>
      </div>
    </div>
  </div>
</section>
<!--  CONTACT SECTION END-->

<!--  FOOTER SECTION START-->
<footer class="footer">
  <div class="container">
    <div class="row">
      <div class="footer-item footer-about">
        <h2>About</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repudiandae neque eum optio fugiat quo officia corrupti voluptatibus.</p>
        <div class="social-links">
          <a href="#"><i class="fa fa-facebook-f"></i></a>
          <a href="#"><i class="fa fa-twitter"></i></a>
          <a href="#"><i class="fa fa-instagram"></i></a>
          <a href="#"><i class="fa fa-youtube"></i></a>
          <a href="#"><i class="fa fa-linkedin"></i></a>
        </div>
      </div>
      <div class="footer-item footer-quick-links">
        <h2>Links</h2>
        <ul>
          <li><a href="#">Courses</a></li>
          <li><a href="#">Stories</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Log In</a></li>
          <li><a href="#">Sign Up</a></li>
        </ul>
      </div>
      <div class="footer-item footer-contact">
        <h2>Contact</h2>
        <p><i class="fa fa-map-marker"></i>Azerbaycan,Baku</p>
        <p><i class="fa fa-phone"></i>+994 77 317 22 77</p>
        <p><i class="fa fa-envelope"></i>link@yahoo.com</p>
      </div>
      <div class="footer-item  footer-news">
        <h2>Subscribe</h2>
        <form >
          <div class="input-group">
            <input type="text" placeholder="Email" class="form-control">
          </div>
          <button type="submit" class="btn btn-1">Subscribe</button>
        </form>
      </div>
    </div>
  </div>
</footer>
<!--  FOOTER SECTION END-->
</body>
</html>
