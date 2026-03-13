<!DOCTYPE html>

<html>

<head>

&nbsp; <meta name="viewport" content="width=device-width, initial-scale=1.0">

&nbsp;  <style>

&nbsp;   \*{

&nbsp;       margin: 10px;

&nbsp;       padding: 0;

&nbsp;       box-sizing: border-box;

&nbsp;       background: #c1eaf0;

&nbsp;   }



&nbsp;   nav{

&nbsp;       width: 40%;

&nbsp;       height: 2vh;

&nbsp;       margin: auto;

&nbsp;       padding: 20px 0;

&nbsp;       display: flex;

&nbsp;       align-items: center;

&nbsp;       justify-content: space-between;

&nbsp;        border-radius: 2cqb;

&nbsp;      



&nbsp;   }

&nbsp;   nav ul li{

&nbsp;       display: inline-block;

&nbsp;       list-style: none;

&nbsp;       margin: 10px 20px;

&nbsp;   }

&nbsp;    nav ul li a{

&nbsp;       text-decoration: none;

&nbsp;       color:#606163;



&nbsp;   }

&nbsp;   nav ul li a:hover{

&nbsp;       color:#ff4321;

&nbsp;   }

&nbsp;   .text{

&nbsp;       font-family: 'Poppins', sans-serif;

&nbsp;   }

&nbsp;   .menu-toggle{

&nbsp;   display: none;

&nbsp;   font-size: 28px;

&nbsp;   cursor: pointer;

}

.close-btn{

&nbsp;   position: absolute;

&nbsp;   top: 15px;

&nbsp;   right: 20px;

&nbsp;   font-size: 30px;

&nbsp;   cursor: pointer;

}





&nbsp;   nav{

&nbsp;       width: 100%;

&nbsp;       background: transparent;

&nbsp;       justify-content: flex-start;

&nbsp;   }



&nbsp;   .menu-toggle{

&nbsp;       display: block;

&nbsp;       margin-left: 10px;

&nbsp;   }

nav ul{

&nbsp;   position: fixed;

&nbsp;   top: 0;

&nbsp;   left: -100%;

&nbsp;   height: 100vh;

&nbsp;   width: 60%;

&nbsp;   background: #7ba2f0;

&nbsp;   flex-direction: column;

&nbsp;   align-items: flex-start;

&nbsp;   padding-top: 60px; /\* para dili matabonan sa X \*/

&nbsp;   transition: 0.3s ease;

}

&nbsp;   



&nbsp;   nav ul li{

&nbsp;       display: block;

&nbsp;       margin: 20px;

&nbsp;   }



&nbsp;   nav.active ul{

&nbsp;       left: 0;

&nbsp;   }



&nbsp;   

&nbsp;  

&nbsp;  </style>

&nbsp;  </head>

&nbsp;  

&nbsp;  <div class="header"><nav>



&nbsp;   <div class="menu-toggle">\&#9776;</div>



&nbsp;   <ul>

&nbsp;       <div class="close-btn">\&times;</div>



&nbsp;       <li><a href="Home.html">Home</a></li>

&nbsp;       <li><a href="Projects.html">My Projects</a></li>

&nbsp;       <li><a href="Aboutme.html">About me</a></li>

&nbsp;       <li><a href="Contacts.html">Contacts</a></li>

&nbsp;   </ul>



</nav>

&nbsp;       

&nbsp;       </nav>

&nbsp;       <div class="text">

&nbsp;           <h1><br> <br>Hello!<span>Welcome to my Website</span></h1>

&nbsp;           <h3>Enjoy your visit here</h3>

&nbsp;           <p>Your pressence is welcome, feel free to explore my website.</p>

&nbsp;          

&nbsp;       </div>



&nbsp;   </div>

&nbsp;   <script>

&nbsp;   const toggle = document.querySelector('.menu-toggle');

&nbsp;   const closeBtn = document.querySelector('.close-btn');

&nbsp;   const nav = document.querySelector('nav');



&nbsp;   toggle.addEventListener('click', function(){

&nbsp;       nav.classList.add('active');

&nbsp;   });



&nbsp;   closeBtn.addEventListener('click', function(){

&nbsp;       nav.classList.remove('active');

&nbsp;   });

</script>

&nbsp;  

&nbsp;  

&nbsp;  

</body>

</html>

Berlyn

<!DOCTYPE html>

<html>

<head>

&nbsp; <meta name="viewport" content="width=device-width, initial-scale=1.0">

&nbsp;  <style>

&nbsp;   \*{

&nbsp;       margin: 10px;

&nbsp;       padding: 0;

&nbsp;       box-sizing: border-box;

&nbsp;       background: #c1eaf0;

&nbsp;   }



&nbsp;   nav{

&nbsp;       width: 40%;

&nbsp;       height: 2vh;

&nbsp;       margin: auto;

&nbsp;       padding: 20px 0;

&nbsp;       display: flex;

&nbsp;       align-items: center;

&nbsp;       justify-content: space-between;

&nbsp;        border-radius: 2cqb;

&nbsp;      



&nbsp;   }

&nbsp;   nav ul li{

&nbsp;       display: inline-block;

&nbsp;       list-style: none;

&nbsp;       margin: 10px 20px;

&nbsp;   }

&nbsp;    nav ul li a{

&nbsp;       text-decoration: none;

&nbsp;       color:#606163;



&nbsp;   }

&nbsp;   nav ul li a:hover{

&nbsp;       color:#ff4321;

&nbsp;   }

&nbsp;   .text{

&nbsp;       font-family: 'Poppins', sans-serif;

&nbsp;   } .menu-toggle{

&nbsp;   display: none;

&nbsp;   font-size: 28px;

&nbsp;   cursor: pointer;

}

.close-btn{

&nbsp;   position: absolute;

&nbsp;   top: 15px;

&nbsp;   right: 20px;

&nbsp;   font-size: 30px;

&nbsp;   cursor: pointer;

}





&nbsp;   nav{

&nbsp;       width: 100%;

&nbsp;       background: transparent;

&nbsp;       justify-content: flex-start;

&nbsp;   }



&nbsp;   .menu-toggle{

&nbsp;       display: block;

&nbsp;       margin-left: 10px;

&nbsp;   }

nav ul{

&nbsp;   position: fixed;

&nbsp;   top: 0;

&nbsp;   left: -100%;

&nbsp;   height: 100vh;

&nbsp;   width: 60%;

&nbsp;   background: #7ba2f0;

&nbsp;   flex-direction: column;

&nbsp;   align-items: flex-start;

&nbsp;   padding-top: 60px; /\* para dili matabonan sa X \*/

&nbsp;   transition: 0.3s ease;

}

&nbsp;   



&nbsp;   nav ul li{

&nbsp;       display: block;

&nbsp;       margin: 20px;

&nbsp;   }



&nbsp;   nav.active ul{

&nbsp;       left: 0;

&nbsp;   }



&nbsp;   

&nbsp;  

&nbsp;  </style>

&nbsp;  </head>

&nbsp;  

&nbsp;  <div class="header"><nav>



&nbsp;   <div class="menu-toggle">\&#9776;</div>



&nbsp;   <ul>

&nbsp;       <div class="close-btn">\&times;</div>



&nbsp;       <li><a href="Home.html">Home</a></li>

&nbsp;       <li><a href="Projects.html">My Projects</a></li>

&nbsp;       <li><a href="Aboutme.html">About me</a></li>

&nbsp;       <li><a href="Contacts.html">Contacts</a></li>

&nbsp;   </ul>

&nbsp;  

&nbsp;       </nav>



<h1><br>My Projects</h1>



<div class="card">

<img src="project1.png">

<h3>Pattern Searching Program</h3>

<p>C program that searches patterns inside text.</p>

</div>



<div class="card">

<img src="project2.png">

<h3>Binary Search Program</h3>

<p>Efficient searching algorithm using O(log n).</p>

</div>



<button onclick="showMessage()">View Projects</button>



<script>

function showMessage(){

&nbsp;   alert("These are my completed projects.");

}

</script><script>

&nbsp;   const toggle = document.querySelector('.menu-toggle');

&nbsp;   const closeBtn = document.querySelector('.close-btn');

&nbsp;   const nav = document.querySelector('nav');



&nbsp;   toggle.addEventListener('click', function(){

&nbsp;       nav.classList.add('active');

&nbsp;   });



&nbsp;   closeBtn.addEventListener('click', function(){

&nbsp;       nav.classList.remove('active');

&nbsp;   });

</script>

&nbsp;



</body>

</html>



