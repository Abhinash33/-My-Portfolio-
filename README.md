# -My-Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portflio website</title>
    <!--font awesome link-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">

</head>
<body>
<!--header section-->

<header>
    <div class="user">
        <img src="abhinash singh pic.jpeg" alt="">
        <h3 class="name">Abhinash Kumar Singh</h3>
        <p class="post">Java developer</p>

    </div>
    <nav class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#portfolio">Portfolio</a></li>
            <li><a href="#contact">Contact</a></li>
            
        </ul>
    </nav>
</header>
<!--header end-->
<div id="menu" class="fas fa-bars"></div>
<!--home section starts-->

<section class="home" id="home">
    <h3>HI THERE</h3>
    <h1>I'M <span>Abhinash Kumar Singh</span></h1>
    <p> CURENTLY I AM PURSUING B.TECH IN INFORMATION TECHNOLOGY FROM ASANSOL ENGINEERING COLLEGE.I'M A JAVA DEVELOPER AND SKILLED IN HTML,CSS,BOOTSTART ,JAVA ETC.
        I HAVE PROFICIENCY AT GRASPING NEW TECHNICAL CONCEPTS QUICKLY AND UTILISING IT IN A PRODUCTIVE MANNER </P>
         <a href="#about"><button class="btn">about me <i class="fas fa-user"></i></button></a>

</section>
<!--home section ends-->
<!--about section starts-->
<section class="about" id="about">
    <h1 class="heading"><span>About </span>Me</h1>
    <div class="row">
    <div class="info">
        <h3><span>Name:</span>Abhinash Kumar Singh</h3>
        <h3><span>Qualification:</span>B.tech</h3>
        <h3><span>Age:</span>22</h3>
        <h3><span>Gender:</span>Male</h3>
        <h3><span>Location:</span>Asansol,West Bengal</h3>
        <a href="abhi resume.pdf"><button class="btn">download CV <i class="fas fa-download"></i></button></a>

    </div>
    <div class="counter">
        <div class="box">
            <span>Fresher</span>
            <h3>Experience</h3>
        </div>
        <div class="box">
            <span>8+</span>
            <h3>Project Completed</h3>
        </div>
        <div class="box">
            <span>2+</span>
            <h3>awards won</h3>
        </div>
    </div>
    </div>

</section>
<!--about section ends-->
<!-- education section starts  -->

<section class="education" id="education">

    <h1 class="heading"> my <span>education</span> </h1>
    
    <div class="box-container">
        
    
        <div class="box">
            <i class="fas fa-graduation-cap"></i>
            <span>2024</span>
            <h3>B.tech</h3>
            <p>ASANSOL ENGINEERING COLLEGE</p>
        </div>
    
        <div class="box">
            <i class="fas fa-graduation-cap"></i>
            <span>2020</span>
            <h3>Diploma</h3>
            <p>BENGAL COLLEGE OF POLYTECHNIC </p>
        </div>
    
        <div class="box">
            <i class="fas fa-graduation-cap"></i>
            <span>2017</span>
            <h3>Higher Secondary Education</h3>
            <p>DAV HIGHER SECONDARY(H.S)</p>
            
        </div>
        <div class="box">
            <i class="fas fa-graduation-cap"></i>
            <span>2015</span>
            <h3> Secondary Education</h3>
            <p>DAYANAND VIDHYALAYA HIGH SECHOOL</p>
            
        </div>
    </div>

</section>

<!-- education section ends -->

<!-- portfolio section starts  -->
<section class="portfolio" id="portfolio">

    <h1 class="heading"> my <span>portfolio</span> </h1>
    
    <div class="box-container">
    
        <div class="box">
            <img src="2023-02-15.png" alt="">
        </div>
    
        <div class="box">
            <img src="2023-02-15 (1).png" alt="">
        </div>
    
        
    </div>
    
    </section>
    
    <!-- portfolio section ends -->
    
    <!-- contact section starts  -->
    
    <section class="contact" id="contact">
    
    <h1 class="heading"> <span>contact</span> me </h1>
    
    <div class="row">
    
        <div class="content">
    
            <h3 class="title">contact info</h3>
    
            <div class="info">
                <h3> <i class="fas fa-envelope"></i> abhinashsingh333@gmail.com </h3>
                <h3> <i class="fas fa-phone"></i> 7031081941 </h3>
                <h3> <i class="fas fa-map-marker-alt"></i> ASANSOL, INDIA - 713301. </h3>
            </div>
    
        </div>
    
        <form action="">
    
            <input type="text" placeholder="name" class="box">
            <input type="email" placeholder="email" class="box">
            <input type="text" placeholder="project" class="box">
            <textarea name="" id="" cols="30" rows="10" class="box message" placeholder="message"></textarea>
            <button type="submit" class="btn"> send <i class="fas fa-paper-plane"></i> </button>
    
        </form>
    
    </div>
    
    </section>
    
    <!-- contact section ends -->
    
    
    <!-- scroll top button  -->
    
    <a href="#home" class="top">
        <img src="scroll-top-img.png" alt="">
    </a>
    
    
    
    
    
        





    <!--jquery link-->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>

    <script src="/script.js"></script>
</body>
</html>
