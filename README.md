# NFLteam-
<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>CodePen - Assignment8_cssflexbox</title>
  <link rel="stylesheet" media="screen and (min-width: 900px)" href="./style1.css">
  <link rel="stylesheet" media="screen and (min-width: 600px)" href="./style1.css">
</head>
<body>
<!-- partial:index.partial.html -->
<head>
<style>
  @media (min-width: 30em) and (max-width: 50em) {
  /* … */
    
}
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}

.tiledbackground{
    background-image: url("https://i.postimg.cc/XNKRmsns/unicorncolor.jpg");
    background-size: 580px;
    width: 1890px;
    height: 2900px;
    border: 1px solid;
}

.flex-container {
  display: flex;
  flex-wrap: wrap;
  background-color: DodgerBlue;
}
.flex-container > div {
  background-color: #f1f1f1;
  width: 300px;
  margin: 10px;
  text-align: left;
  line-height: 45px;
  font-size: 15px;
}
h2 {
    text-align: left;
    font-size: 25px;
    color: black;
}
.dropbtn {
  background-color: #3498DB;
  color: white;
  padding: 16px;
  font-size: 35px;
  border: none;
  cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
  background-color: #2980B9;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  overflow: auto;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}
}
h3 {
    text-align: center;
    font-size: 55px;
    color: black;
} 
  </style>
  
  <script>
    /* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>
</style>
</head>
<body>
  
  <div class = "tiledbackground">

<h1><p><p style = "color:darkblue;"> This flexbox self create a own NFL profile Flex Container by Carol Chang</p></p></h1>
    

<p><p style = "color:darkred;"><b> *******The Logo next the Name so show really logo symbollic on NFL flexible items.</b></p></p>
<div class="flex-container">

  <div><b>Name:</b>Arizona Cardinal <p>Logo: <img src='https://i.postimg.cc/34NwJV3Y/ARI.jpg'  alt='ARI'/></a></p>
 <p> Location: Arizona </p>
 <h2><p> win :12</p>
 <p>lose :10</p>
   <p>ties: 2</p></div></h2>
    
 <div><b>Name:</b> Atlanta Falcons <p>Logo: <a href='https://postimg.cc/QH1dtpZ9' target='_blank'><img src='https://i.postimg.cc/QH1dtpZ9/ATL.png' border='0' alt='ATL'/></a></p>
 <p> Location :Atlanta, GA</p>
  <h2><p> win :1</p>
 <p>lose :1</p>
 <p>ties: 2</p></div></h2>
    
    
<div><b>Name:</b> Carolina Panthers <p>Logo:<a href='https://postimg.cc/G9ZpdXVn' target='_blank'><img src='https://i.postimg.cc/G9ZpdXVn/CAR.png' border='0' alt='CAR'/></a></p>
<p>Location: N. or S. Carolinas</p>
<h2><p> win :1</p>
<p>lose :1</p>
<p>ties: 2</p></div></h2>
    
        
 <div><b>Name:</b>Chicago Bears <p>Logo:<a href='https://postimg.cc/WtD4BB97' target='_blank'><img src='https://i.postimg.cc/WtD4BB97/CHI.png' border='0' alt='CHI'/></a></p>
 <p>Location: Chicago, IL</p>
 <h2><p> win :7</p>
 <p>lose : 9</p>
 <p>ties: 3</p></div></h2>
    
    
<div><b>Name:</b>Dallas Cowboys <p>Logo:<a href='https://postimg.cc/8JYzF4CW' target='_blank'><img src='https://i.postimg.cc/8JYzF4CW/DAL.jpg' border='0' alt='DAL'/></a></p>
<p>Location: Dallas, TX</p>
<h2><p> win :1</p>
<p>lose :1</p>
<p>ties: 2</p></div></h2>
    
  
<div><b>Name:</b>Detroit Lions <p>Logo:<a href="https://postimg.cc/zHRXThLQ" target="_blank"><img src="https://i.postimg.cc/zHRXThLQ/DET.jpg" alt="DET"/></a></p>
<p>Location: Detroit, Mi</p>
<h2><p> win :1</p>
<p>lose :1</p>
<p>ties: 2</p></div></h2>
    
    
 <div><b>Name:</b>Jacksonville Jaguars  <p>Logo:<a href="https://postimg.cc/NKGvcTsw" target="_blank"><img src="https://i.postimg.cc/NKGvcTsw/JAX.jpg" alt="JAX"/></a></p>
<p>Location: Jacksonville, FL</p>
<h2><p> win :1</p>
<p>lose :1</p> 
<p>ties: 2</p></div></h2>
    
    
<div><b>Name:</b> Green Bay Packers <p> Logo:<a href="https://postimg.cc/jLkChhv3" target="_blank"><img src="https://i.postimg.cc/jLkChhv3/GB.jpg" alt="GB"/></a></p>
<p>Location: Green Bay, WI</p>
<h2><p> win :1</p>
<p>lose :1</p>
<p>ties: 2</p></div></h2>
    
<div><b>Name:</b> Los Angeles Rams <p>Logo :<a href="https://postimg.cc/GH9m9yrF" target="_blank"><img src="https://i.postimg.cc/GH9m9yrF/LA.jpg" alt="LA"/></a></p>
<p>Location: Los Angeles, CA</p>
<h2><p> win :3</p>
<p>lose :1</p>
<p>ties: 2</p></div></h2>
    
    
<div><b>Name:</b>Minnesota Vikings <p>Logo:<a href="https://postimg.cc/mPhR9M0y" target="_blank"><img src="https://i.postimg.cc/mPhR9M0y/MIN.jpg" alt="MIN"/></a></p>
<h2><p>Location: MN</p>
<p> win :7</p>
<p>lose :4</p>
<p>ties: 3</p></div></h2>
    
   
 <div><b>Name:</b>  New Orleans Saints <p>Logo: <a href="https://postimg.cc/tsrQCTJn" target="_blank"><img src="https://i.postimg.cc/tsrQCTJn/NO.jpg" alt="NO"/></a></p>
  <p>Location: New Orleans, LA</p> 
 <h2> <p> win :1</p>
  <p>lose :1</p>
   <p> ties: 2</p></div></h2>
    
 <div><b>Name:</b> New York Giants <p>Logo:<a href="https://postimg.cc/ZWdYxzW0" target="_blank"><img src="https://i.postimg.cc/ZWdYxzW0/NYG.jpg" alt="NYG"/></a></p>
  <p>Location: New York</p>
  <h2><p> win :1</p>
  <p>lose :1</p>
    <p>ties: 2</p></div></h2>
    
  <div><b>Name:</b>Denver Broncos <p>Logo:<a href="https://postimg.cc/jDxZ54nZ" target="_blank"><img src="https://i.postimg.cc/jDxZ54nZ/DEN.png" alt="DEN"/></a></p>
  <p>Location: Denver, CO</p>
   <h2> <p> win :1</p>
  <p>lose :1</p>
  <p>ties: 2</p></div>  </h2>
    
     <div><b>Name:</b>Houston Texan <p>Logo:<a href="https://postimg.cc/4nHHYVB6" target="_blank"><img src="https://i.postimg.cc/4nHHYVB6/HOU.jpg" alt="HOU"/></a></p>
 <p>Location: Houston, TX</p>
<h2> <p> win :24</p>
  <p>lose :15</p>
  <p>ties: 9</p></div></h2>
    
     
  <div><b>Name:</b>Miami Dolphins <p>Logo:<a href="https://postimg.cc/DSDhP0hk" target="_blank"><img src="https://i.postimg.cc/DSDhP0hk/MIA.jpg" alt="MIA"/></a></p>
  <p>Location: Miami, FL</p>
  <h2><p> win :7</p>
  <p>lose :3</p>
    <p>ties: 4</p></div></h2>
    
  <div><b>Name:</b>Tennessee Titans <p>Logo:<a href="https://postimg.cc/v4b42jMh" target="_blank"><img src="https://i.postimg.cc/v4b42jMh/TEN.jpg" alt="TEN"/></a></p>
  <p>Location: Tennessee</p>
  <h2><p> win :3</p>
  <p>lose :3</p>
    <p> ties: 5</p></div></h2>
  
  
   <div><b>Name:</b> Buffalo Bills <p>Logo:<a href="https://postimg.cc/3drD1NhN" target="_blank"><img src="https://i.postimg.cc/3drD1NhN/BUF.jpg" alt="BUF"/></a></p>
  <p>Location:Buffalo, NY</p>
 <h2> <p> win :5</p>
  <p>lose :5</p>
  <p> ties: 5</p></div> </h2>
  </main>
</div>


<h2>Clickable Dropdown</h2>
<p>Click on the button to open the dropdown menu.</p>

<div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Dropdown</button>
  <div id="myDropdown" class="dropdown-content">
    <a href="#Date">Date</a>
    <a href="#HomeTeam">HomeTeam</a>
    <a href="#AwayTeam">AwayTeam</a>
    <a href="#HomePoints">HomePoints</a>
    <a href="#AwayPoints">AwayPoints</a>
  </div>
</div>

</body>
</html>
<!-- partial -->
   <script src="nfl.js"></script>
</body>
</html>
