FIRST ATTEMT FOR personal webpage on jekyll
----
<!DOCTYPE html>
<html>

<head>
<style>
* { margin: 9px;}
body {height:550px;
  background-color: ;
  color: ;
  padding:5px;
  border-radius: 15px;
  border: 3px solid black;}
  
  .container{
  background-color: black;
   border-radius: 15px;
  height: 530px;}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 200px;}
/* Change the link color on hover */

strong:hover {
   background-color: black;
  color: ;
}
#name {
  background-color: black;
  padding-top: 5px;
  padding-left: 3in;
  color: white;
  font-size: 1in;
  font-family: "AppleGothic", "Century Gothic", "AppleGothic", sans-serif;
}
.face{
  float: right;
  margin-right: 100px;
  padding-top: 30px;
  }
.line{
  margin-left: 0px;
  margin-bottom: px;
  height: 2px;
  }
b {
  color:  #ffaa00;
  #ffaa00
}
b:hover {
    text-decoration: none;
    background-color: black;
}
.insideBody{
  font-family: Tahoma, Verdana, Segoe, sans-serif;
  margin: 1px;
  padding-left: 45px;
  color: white;
  background-color: black;
  font-size: 16px;
}
.logo{
  width: 300px;
  margin-top: 56px;
  margin-left: 4.5in;
  padding-left: 10px;
  background-color: white;
}
.text strong {
  background-color:black;
  #1a1a00
}

 #1a1a00
/*Hover over name CODE*/

a.tooltip {
  outline: none;
}
a.tooltip strong {
  line-height: 30px;
}
a.tooltip:hover {
background-color: black;
}
img{
   border-radius: 15px;}
a.tooltip span {
  z-index: 0;
  display: none;
  padding: 0px 0px;
  margin-top: -30px;
  margin-left: 0px;
  line-height: 16px;
  border-radius: 15px;
  text-decoration: none;}

a.tooltip:hover span {
  display: inline;
  position: absolute;
  color: #111;
  border: 1px solid #DCA;
  background: #fffAF0;
}
.callout {
  z-index: 20;
  position: absolute;
  top: 30px;
  border: 0;
  left: 12px;

}
/*link CODE*/
section{
  margin: 10px;
  padding-top: 15px;
  margin-left: 5in;
  width:180px;
  background-color: black;}
a:link {
  text-decoration: none;
}
#link{
 color: white;   
 font-size: 16px;
}
fieldset{
  border-radius: 5px;
}
/*Toggel Email animation*/
.toggler {
    width: 500px;
    height: 200px;
  }
  #button {
    padding: .5em 1em;
    text-decoration: none;
  }
  #effect {
    position: relative;
    width: 240px;
    height: 135px;
    padding: 0.4em;
  }
  #effect h3 {
    margin: 0;
    padding: 0.4em;
    text-align: center;
  }

</style>
<script>
  $(function() {
    // run the currently selected effect
    function runEffect() {
      // get effect type from
      var selectedEffect = $( "#effectTypes" ).val();
 
      // most effect types need no options passed by default
      var options = {};
      // some effects have required parameters
      if ( selectedEffect === "scale" ) {
        options = { percent: 0 };
      } else if ( selectedEffect === "size" ) {
        options = { to: { width: 200, height: 60 } };
      }
 
      // run the effect
      $( "#effect" ).toggle( selectedEffect, options, 500 );
    };
 
    // set effect from select menu value
    $( "#button" ).click(function() {
      runEffect();
    });
  });
  </script>
<title>John Espinoza</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta charset="utf-8">
  <link rel="stylesheet" type="text/css" href="main2.css"/>
  <link rel="stylesheet" type="text/css" href="photograpy.html">
 
        <link rel='stylesheet' type='text/css' href='http://code.jquery.com/ui/1.9.2/themes/base/jquery-ui.css'/>
        <script type='text/javascript' src='script.js'></script>
        <script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.9.2/jquery-ui.min.js"></script>

</head>
</style>

<script type="text/javascript" src="jquery.js"></script>
<script type="text/javascript">
</script>

<body>
<div class="container"> 
  <div class="id">
    <p id="name">John Espinoza</p>

  </div>
    <img class="face" src="john1.jpg" > 

     <br /> 
    <!--SECOND BODY>-->

              <div class="insideBody">
                  I live in<a href="#" class="tooltip"><b>New York</b>
                    <span><img src="img_1263.jpg" height="150" width="150" ></span></a>
                  <br> 
                  <br>
                  I am form <a href="#" class="tooltip"><b>Ecuador</b>
                  <span><img src="Ecuador 2.jpg" height="150" width="150" ></span></a>
                  <br> 
                  <br>
                  I Enjoy working on my<a href="#" class="tooltip"><b>MotorCycle</b><span><img src="img_1454.jpg" height="150" width="150"></span></a>

                  <br /> 
                  <br> 
                  I Watch a lot<a href="#" class="tooltip"><b>Movies</b></a>,Work out when I Can.
                  <span></span></a>
                  <br> 
                  <br> 
                  I have a Twin<a href="#" class="tooltip"><b>Brother</b></a> Puddle name<a href="#" class="tooltip"><b>Maya</b> 
                         <span></span></a>
                  <br> 
                  <br> 
                  I Have travled to<a href="#" class="tooltip"><b>Spain</b><span><img src="img_1456.jpg" height="150" width="165"></span></a>,<a href="#" class="tooltip"><b>Italy</b><span></span></a>,<a href="#" class="tooltip"><b>Ecuador</b><span></span></a><a href="#" class="tooltip"><b>Barcelona</b><span></span></a>
                  <br> 
                  <br> 
                  I write<a href="#" class="tooltip"><b>Code</b><span></span></a>and<a href="#" class="tooltip"><b>idiot comments</b>
                            <span></span></a>Too.

                  <br>
                  <br> 
                   I celecbreate<a href="#" class="tooltip"><b>$@)</b>
                            <span></span></a>

                  
            </div>
            <section>
            <div id="link"><a href="http://codepen.io/JOHNESPINOZA/"><b>For past projects</b></a></div>
              
            </section>
               
               

               <!--LOGO SECTION-->
     <div class="logo">
                    <a href="https://www.facebook.com/john.espinoza.129"/><img src="02_facebook.png" width="50" height="50" id="faceBook" alt="facebook">

                    <a href="google.com"><img src="14_google.png" width="50" height="50" id="google" alt="google"></a>

                    <a href="https://www.instagram.com/?hl=en"><img src="10_instagram.png" width="50" height="50" id="insta" alt="instagram"/></a>
        </div>
  </div>    
      
 
</div>
 <br><br><br><br>
 
   <div class="toggler">
  <div id="effect" class="ui-widget-content ui-corner-all">
    <h3 class="ui-widget-header ui-corner-all">Animate</h3>
     
  <form class="email">
            <fieldset>
              <div>
                <label for="firstname">Firstname</label>
                <input id="firstname" name="firstname" title="Please provide your firstname.">
              </div>
              <div>
                <label for="lastname">Lastname</label>
                <input id="lastname" name="lastname" title="Please provide also your lastname.">
              </div>
              <div>
                <label for="address">Address</label>
                <input id="address" name="address" title="Your home or work address.">
              </div>
            </fieldset>
          </form>
  </div>
</div>
 
<button id="button" class="ui-state-default ui-corner-all">Toggle Effect</button>

# ABOUT  john 

stuff about my page
