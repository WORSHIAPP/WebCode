<!-- code for web -->




#<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

	<title>Worshiapp</title>
	<style type="text/css">
		.navbar-default {
  background-color:lavender;
  background-image: none;
  background-repeat: no-repeat;
 }
 .img-thumbnail
 {
 	height: 50px;
 	width: 70px;
 }

.font
{
	font-family: verdana;
}
.card
{
	border-style: solid;
	border-color: blue;
	border-radius: 5px;
	height: 300px;
	margin: 45px;
}
#contact
{
	background-color: lavender;
}
.pimage{
	margin-top: 10px;
}
.check
{
	background-color: lavender;
	text-align: center;
	font-family: vardana;
	font-size: 20px;
}

	</style>
</head>
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">

<nav class="navbar navbar-default navbar-fixed-top container-fluid">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage"><img class="img-thumbnail" src="png_worshii.png"></a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">KNOW YOUR SITE</a></li>
        <li><a href="#services">BOOK A PRIEST</a></li>
        <li><a href="#portfolio">VASTU SIMPLIFIED</a></li>
        <li><a href="#pricing">FESTIVITIES AHEAD</a></li>
        <li><a href="#contact">LOGISTICS</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="jumbotron text-center">
  <h1>Worshiapp</h1> 
  <p>Digitizing the world of worship</p> 
  <form>
    <div class="input-group container">
      <input type="email" class="form-control" size="5" placeholder="Search " required>
      <div class="input-group-btn">
        <button type="button" class="btn btn-danger">Search</button>
      </div>
    </div>
  </form>
</div>






<div id="about" class="container">
  <div class="row">
    <div class="col-sm-8 font">
      <h2>About Worshiapp</h2><br>
      <h4>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</h4><br>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      <br><button class="btn btn-default btn-lg">Get in Touch</button>
    </div>
    
  </div>
</div>





<div class="container">
  <h2>Know us from a little closer</h2>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner">

      <div class="item active">
        <img src="divine1.jpg" alt="Los Angeles" style="width:100%;">
        <div class="carousel-caption">
          <h3>He protects</h3>
          <p></p>
        </div>
      </div>

      <div class="item">
        <img src="divine1.jpg" alt="Chicago" style="width:100%;">
        <div class="carousel-caption">
          <h3>He protects</h3>
          <p></p>
        </div>
      </div>
    
      <div class="item">
        <img src="divine1.jpg" alt="New York" style="width:100%;">
        <div class="carousel-caption">
          <h3>He protects</h3>
          <p></p>
        </div>
      </div>
  
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>




<hr><h1 class="container" style="text-align: center; color: teal;"><a href="#"> Book Your Priest</a></a></h1><hr>


<div class="container">
  <h2>Premium Priests of the week</h2>
  <div class="row">
    <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>
  </div>
</div>
 


<hr><h1 class="container" style="text-align: center; color: teal;"><a href="#">World class vastu shastri's</a></a></h1><hr>





<div class="container">
  <h2>Premium Vastushastri's of the week</h2>
  <div class="row">
    <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>
  </div>
</div>



<hr><h1 class="container" style="text-align: center; color: teal;"><a href="#">FESTIVE CALENDER</a></a></h1><hr>






<div class="container">
  <h2>Festivities Ahead</h2>
  <div class="row">
    <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>
  </div>
</div>




<hr><h1 class="container" style="text-align: center; color: teal;"><a href="#">We Deliver</a></a></h1><hr>





<div class="container">
	<a href="#">
  <h2>E-comm Web Portal</h2></a>
  <div class="row">
    <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>



     <div class="card col-sm-3">
    	<div class="img pimage">
    		<img class="img-responsive img" src="divine1.jpg" alt="pundit">
    	</div>
    	<hr>
    	<h3>Name</h3>
    	<h3>Location</h3>
    	<button class="btn btn-primary">Connect</button>
  </div>
  </div>
</div>
<hr>









<!-- Container (Contact Section) -->
<div id="contact" class="container-fluid bg-grey">
  <h2 class="text-center">CONTACT</h2>
  <div class="row">
    <div class="col-sm-5">
      <p>Contact us and we'll get back to you within 24 hours.</p>
      <p><span class="glyphicon glyphicon-map-marker"></span> Patna, Bihar</p>
      <p><span class="glyphicon glyphicon-phone"></span> +918209186342</p>
      <p><span class="glyphicon glyphicon-envelope"></span> vsrworshiapp@gmail.com</p>
    </div>
    <div class="col-sm-7 slideanim">
      <div class="row">
        <div class="col-sm-6 form-group">
          <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>
        </div>
        <div class="col-sm-6 form-group">
          <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>
        </div>
      </div>
      <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea><br>
      <div class="row">
        <div class="col-sm-12 form-group">
          <button class="btn btn-default pull-right" type="submit">Send</button>
        </div>
      </div>
    </div>
  </div>
</div>


<div class="container-fluid check">
	<a href="#">
c@divine developers
</a>
</div>

<nav class="navbar navbar-default navbar-bottom container-fluid">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage"><img class="img-thumbnail" src="png_worshii.png"></a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#about">KNOW YOUR SITE</a></li>
        <li><a href="#services">BOOK A PRIEST</a></li>
        <li><a href="#portfolio">VASTU SIMPLIFIED</a></li>
        <li><a href="#pricing">FESTIVITIES AHEAD</a></li>
        <li><a href="#contact">LOGISTICS</a></li>
      </ul>
    </div>
  </div>
</nav>

</body>
</html>
