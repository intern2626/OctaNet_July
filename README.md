<!DOCTYPE html>
<html lang="en">

<head>
<link rel="stylesheet" href="type.css">
<title>Landing Page</title>
</head>

<body>
<nav>
<div class="heading">Landing Page</div>
<span class="sideMenuButton"
            Onclick="openNavbar()">
            ☰
</span>

<div class="navbar">
<ul>
<li><a href="#Home">Home</a></li>
<li><a href="#About">About</a></li>
<li><a href="#Sign Up">Sign Up</a></li>
</ul>
</div>
</nav>

<!—Side navigation bar for 
        Responsive website 
<div class="sideNavigationBar" 
        Id="sideNavigationBar">
<a href=”#” class="closeButton" 
            Onclick="closeNavbar()>
</a>
</div>

<!—Content 
<div class="Home" id="Home">
<div class="side1">
<h1><center><b>Courseshala </center></b></center></h1>
<button>
<a href= "Courseshala offers various courses in tech there are to latest courses on or website">Explore More</a>
</button>
</div>
<div class="side2">
</div>
</div>

<section class="About" id="Explore">
<div class="content">
<div class="title">
<span>Courses</span>
</div>
<div class="boxes">
<div class="box">
<div class="topic">
<a href="" target="_blank">
                            <b>MACHINE LEARNING</b>
</a>
</div>
<p>
                        Machine learning is a branch of 
                        Artifiial Intelligence which focuses
                        on the use of data and algorithm to 
                        imiate the way that human learns ,
                        to improve the accuracy of prediction.  
                        
</p>
</div>
<div class="box">

<div class="topic">

</div>

<div class="box">
<div class="topic">
<a href="" target="_blank">
                           <b> Web Developement</b>
</a>
</div>
<p>
                        Web Development is the work invovlved  
                        in developing a website for the Internet
                        or Intranet. 
</p>
</div>
</div>
</section>

<section class="Sign Up" id="Sign Up">
<div class="content">
<div class="title"><span>Sign Up</span></div>
<div class="contactMenu">
<div class="input1">
<div class="label1">Your Name</div>
<div class="input2">
<input type="text" 
                            Placeholder="Enter your Name here">
</div>
<div class="label1">
<label>Your Email</label>
</div>
<div class="input2">
<input type="text"
                            Placeholder="Enter your Email here">
</div>
<div class="label1">
<label>Your Password</label>
</div>
<div class="input2">
<input type="text" 
                            Placeholder="Enter your Password here">
</div>
<div class="button">
<button>Sign Up</button>
</div>
</div>
<div class="input3">
<div class="rightside1">
<div class="title1">
<span>
                                Contact Us
</span>
</div>
<div class="content1">
                            B236, 5th Floor, xyz
                            Corporate Tower, Sector-124, 
                            Manesar, Gurgaon– 123456
</div>
</div>
</div>
</div>
</div>
</section>
<footer>
<div class="footer">
<span>
                <h2><b>Thank you !</b></h2>
<a >
                    Have a nice day.
</a>
</span>
</div>
</footer>
<script >
    Function closeNavbar() {
    Document.getElementById("sideNavigationBar")
        .style.width = "0%";
}

</script>
</body> 
</html>
