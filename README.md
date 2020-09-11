 <head>
    <title>Google Homepage</title>
    <link rel="stylesheet" type="text/css" href="stylesheet.css" media="screen" />
  </head>
  <body>
    <header>
      <nav>
        <ul id="nav_bar">
          <li class="nav-links" id="gmail"><a href="http://www.google.com">Gmail</a></li>
          <li class="nav-links"><a href="#">Images</a></li>
          <li id="sign_in"><a href="#">Sign In</a></li>
        </ul>  
      </nav>  
    </header>  
    
    <!-- GOOGLE IMG -->  
    <div class="google">
      <a href="#" id="google_logo"><img src="C:\Users\Windows 10\Desktop\Nikhil.jpg" alt="Wait Image is Loading"/></a>
    </div>

    
    <!-- FORM SEARCH -->  
    <div class="form">  
      <form id="frmSearch"  method="get" />
<input  type="text" id="txtSearch"     
placeholder="Feel Free to Search"  />

 <!-- BUTTONS -->
<div class= "buttons">  
      <input type="submit" value="Google Search" id="google_search">
      <input type="submit" value="I'm Feeling Lucky" id="im_feeling_lucky">
    </div>

<script type="text/javascript">
    document.getElementById('frmSearch').onsubmit = function() {
        window.location = 'http://www.google.com/search?q=' + document.getElementById('txtSearch').value;
        return false;
    }
</script>

    <!-- FOOTER -->
    <footer>
        <ul class="footer-left">
          <li><a href="https://ads.google.com/">Advertising</a></li>
          <li><a href="#">Business</a></li>
          <li><a href="#">About</a></li> 
        </ul>
        <ul class="footer-right">    
          <li><a href="#">Privacy</a></li>
          <li><a href="#">Terms</a></li>
          <li><a href="#">Settings</a></li>
        </ul>       
    </footer>      
  </body>
