<!DOCTYPE html>
<html>

<head>
  <title>School Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>

  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <link rel="stylesheet" href="style (3).css">
<style>
  .travel_mainDiv
{
    border: 1px solid lightgrey;
}

.travel_mainDiv img
{
width: 100%;
}

.travel_mainDiv h5 , .travel_mainDiv p
{
margin: 20px;
}
.movie_head
{
font-size: 20px;
padding: 6px 22px; border-radius: 10px;
margin-bottom: 15px;
}
.movie_head i
{
float: right;
}
.achievement_text span
{
color: orange;
}
</style>
</head>

<body>

  <!--
Navigation bar code here
-->
<nav class="navbar-inverse" style="position:sticky;top:0;z-index:99999">
  <div class="navbar-header">
  <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar"> <span class="icon-bar"></span> <span class="icon-bar"></span> <span class="icon-bar"></span> </button>
  <a class="navbar-brand" href="#">St.Xavier's School</a> </div>
  <div class="collapse navbar-collapse" id="myNavbar"> <ul class="nav navbar-nav">
  <li><a href="#campus_life">Campus Life</a></li> <li><a href="#achievements">Achievements</a></li> <li><a href="#new">What's New</a></li>
  School name Campus life
  Achievements
  What's New
  </ul>
  Contact us
  </div>
  </nav>
  <li><a href="#contactUs">Contact Us</a></li>

  <iframe id="Video"src="https://youtu.be/xgT4705EX_U"></iframe>
  <div class="container">
    <h2 class="page-header" id="campus_life">Campus Life</h2>
    <center>
    <div class="travel_mainDiv">
    <img src="church.jpg">
    <h4 class="text-capitalize"><kbd>School Church</kbd></h4>
    <hr>
    <h5 class="text-success text-capitalize" >was established in 1978</h5> <p class="text-muted">write something about the mentioned place</p> </div> </center>
    
    
    <br><br>
    <center>
    <div class="travel_mainDiv">
    <img src="st2.jpg">
    <h4 class="text-capitalize"><kbd>school library</kbd></h4> <hr>
    <h5 class="text-success text-capitalize" >was build in 1980</h5> <p class="text-muted" >write something about the mentioned place</p>
    </div> </center>
    <br><br>
    <center>
      <br><br>
<center>
<div class="travel_mainDiv">
<img src="st3.jpg">
<h4 class="text-capitalize"><kbd>school auditorium</kbd></h4> <hr>
<h5 class="text-success text-capitalize" >was build in 1982</h5> <p class="text-muted" >write something about the mentioned place</p> </div>
</center>
<h2 class="page-header" id="achievements">School Achievements</h2>
<div class="bg-primary movie_head" data-toggle="collapse" data-target="#school_achievement1">
Inter School Debate On Environment Pollution<i class="fa fa-sort-desc"></i>
</div>
<div id="school_achievement1" class="collapse">
<div class="achievement_text">
<img src="sel.jpg" class="img-responsive ing-thumbnail">
<h5 class="text-success text-capitalize">won first prize in inter school debate on environment pollution <span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span>
<span class="glyphicon glyphicon-star"></span>
<span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span> </h5>
<p>write about this achievement</p> </div>
</div>
<div class="bg-primary movie_head" data-toggle="collapse" data-target="#school_achievement2"> Inter School Football Competition<i class="fa fa-sort-desc"></i>
</div>
<div id="school_achievement2" class="collapse">
<div class="achievement_text">
<img src="sm2.jpg" class="img-responsive ing-thumbnail">
<h5 class="text-success text-capitalize">came second in inter school football competition <span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span>
<span class="glyphicon glyphicon-star"></span>
<span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span> </h5>
<p>write about this achievement</p> </div>
</div>
<div class="bg-primary movie_head" data-toggle="collapse" data-target="#school_achievement3"> Inter School Science Project Competition<i class="fa fa-sort-desc"></i>
</div>
<div id="school_achievement3" class="collapse">
<div class="achievement_text">
<img src="sm3.jpg" class="img-responsive ing-thumbnail">
<h3 class="text-success text-capitalize">won second price in inter school Science Project competition <span class="glyphicon glyphicon-star"></span>
<span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span> <span class="glyphicon glyphicon-star"></span> </h5>
<p>write about this achievement</p> </div>
</div>

</body>

</html>
