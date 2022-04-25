<form class="suscribe-form" autocomplete="off" id="form" onsubmit="validateform()">
	<input class="enter" placeholder="Enter your email" type="text" name="Enter your email" id="email">
	<button class="suscribe-btn" type="submit">Subscribe</button>
</form>

.suscribe-form
{
	 /* display: flex; */
     /* flex-wrap: wrap; */
     align-items: center;
     padding-top: 50px;
	 padding-left:400px;
	 padding-bottom:50px;
}
.suscribe-form .enter 
{
	 border:1px solid black;
     /* padding: 0px 19px; */
     width: 50%;
     height: 50px;
     /* background: #fff; */
     /* color: #000; */
     font-size: 16px;
     font-weight: 500;
     border-radius: 35px;
	 align-items:center;
}
.suscribe-btn
{
	 /* font-size: 17px; */
     /* transition: ease-in all 0.5s; */
     background-color: #6fc754;
     /* color: #fff; */
     padding: 10px 0px;
     width: 150px;
     /* width: 100%; */
     /* display: block; */
     font-weight: 500;
     /* text-transform: ; */
     border-radius: 35px;
     border: #fff solid 4px;
     margin-left: -160px;
}

<nav class="navbar navbar-expand-xxl bg-secondary navbar-dark fixed-top">
 		  	<div class="container-fluid">
  				<a href="index.html" class="navbar-brand wow animate__zoomInLeft" data-wow-duration="1s"><img src="img/logo.png"></a>
   			 	<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar">
      			<i class="icon fa-solid fa-bars"></i>
    			</button>
    			<div class="collapse navbar-collapse" id="collapsibleNavbar">
      			<ul class="navbar-nav">
        			<li class="nav-item wow animate__lightSpeedInLeft " data-wow-duration="1s"><i class="fa-solid fa-house-chimney text-black awesome"></i>
          			<a href="index.html"><b>HOME</b></a>
        			</li>
        			<li class="nav-item wow animate__lightSpeedInRight " data-wow-duration="1s"><i class="fa-solid fa-address-card text-black awesome"></i>
          			<a href="portfolio.html"><b>PORTFOLIO</b></a>
        			</li>
        			<li class="nav-item wow animate__lightSpeedInLeft " data-wow-duration="1s"><i class="fa-brands fa-blogger text-black awesome"></i>
          			<a href="blog.html"><b>BLOG</b></a>
        			</li> 
        			<li class="nav-item wow animate__lightSpeedInRight " data-wow-duration="1s"><i class="fa-solid fa-phone-volume text-black awesome"></i>
          			<a href="contactpage.html"><b>CONTACT</b></a>
        			</li> 
      			</ul>
    			</div>
  			</div>
			</nav>
			
			<div class="col-12 col-lg-6">
				<div class="contact-form">
					<h2>SEND A MESSAGE</h2>
					<form>
					<table>
						<tr><td><label>First Name</label></td>
						<td><input type="text" placeholder="First Name"/></td></tr>
						<tr><td><label>Email</label></td>
						<td><input type="email" placeholder="Enter Mail"/></td></tr>
					</table>
					</form>
				</div>
			</div>


