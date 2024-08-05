<template>
    <nav class="navbar">
     <ul class="navbar-nav">
       <li class="logo">
         <!-- <span class="link-text logo-text">Explore</span> -->
         <svg
           aria-hidden="true"
           focusable="false"
           data-prefix="fad"
           data-icon="angle-double-right"
           role="img"
           xmlns="http://www.w3.org/2000/svg"
           viewBox="0 0 448 512"
           class="svg-inline--fa fa-angle-double-right fa-w-14 fa-5x"
         >
           <g class="fa-group">
             <path
               fill="currentColor"
               d="M224 273L88.37 409a23.78 23.78 0 0 1-33.8 0L32 386.36a23.94 23.94 0 0 1 0-33.89l96.13-96.37L32 159.73a23.94 23.94 0 0 1 0-33.89l22.44-22.79a23.78 23.78 0 0 1 33.8 0L223.88 239a23.94 23.94 0 0 1 .1 34z"
               class="fa-secondary"
             ></path>
             <path
               fill="currentColor"
               d="M415.89 273L280.34 409a23.77 23.77 0 0 1-33.79 0L224 386.26a23.94 23.94 0 0 1 0-33.89L320.11 256l-96-96.47a23.94 23.94 0 0 1 0-33.89l22.52-22.59a23.77 23.77 0 0 1 33.79 0L416 239a24 24 0 0 1-.11 34z"
               class="fa-primary"
             ></path>
           </g>
         </svg>
     </li>
       <li class="nav-item">
         <a href="#home" class="nav-link">
           <i class="fa-sharp fa-solid fa-house-chimney"></i>
           <span class="link-text">Home</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#about" class="nav-link">
           <i class="fa-sharp fa-solid fa-circle-info"></i>
           <span class="link-text">About</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#resume" class="nav-link">
           <i class="fa-sharp fa-solid fa-id-card"></i>
           <span class="link-text">Resume</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#skills" class="nav-link">
           <i class="fa-sharp fa-solid fa-horse-head"></i>
           <span class="link-text">Skills</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#projects" class="nav-link">
           <i class="fa-solid fa-display"></i>
           <span class="link-text">Projects</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#testimonials" class="nav-link">
           <i class="fa-solid fa-people-group"></i>
           <span class="link-text">Testimonials</span>
         </a>
       </li>
       <li class="nav-item">
         <a href="#contact" class="nav-link">
           <i class="fa-sharp fa-regular fa-paper-plane"></i>
           <span class="link-text">Contact</span>
         </a>
       </li>
     </ul>
    </nav>


 </template>

 <script>
 export default {};
 </script>


 <style scoped>
 

.navbar {
width: 5rem;
height: 100vh;
position: fixed ;
background-color: #001a34;
top: 0;
left: 0;
z-index: 11;
transition: width 200ms ease;
}

.navbar-nav {
 list-style: none;
 padding: 0;
 margin: 0;
 display: flex;
 flex-direction: column;
 align-items: center;
}

.nav-item {
 width: 100%;
}

.nav-item:last-child {
 margin-top: auto;
}

.nav-link i {
 /* min-width: 2rem; */
 width: 2rem;
 margin: 0 1.5rem;
 color: #fff;
}

.nav-link i:hover {
 /* color: rgb(21, 200, 200); */
 color: #f5f5f5;
 
}

.navbar:hover {
 width: 16.5rem;
 background: #000;
}

.navbar:hover .link-text {
 display: block;
}

.navbar:hover .link-text:hover {
 /* color: rgb(21, 200, 200); */
 color: #fff;
}

.nav-link:hover i,
.nav-link:hover .link-text {
 /* color: rgb(21, 200, 200); */
 /* color: #a8a8a8; */
 /* text-shadow: 1px 1px #fff; */
 color: #fff;
}

/* .nav-link:hover {
  background: #000;
} */



.nav-link {
 display: flex;
 align-items: center;
 height: 5rem;
 color: #fff;
 text-decoration: none;
 transition: color 0.3s ease;
 /* filter: grayscale(100%) opacity(0.8); */
}



.nav-link {
 color: #fff;
 /* font-family: "JetBrains Mono", monospace; */
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-weight: 500;
  font-style: normal;
 font-size: 1.3rem;
 text-align: left;
 /* margin-left: 2rem; */
 display: flex;
 align-items: center;
 height: 5rem;
 position: relative;
}

.nav-link::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px; /* Adjust the height of the line */
    bottom: 0;
    left: 50%;
    background-color: #fff; /* Adjust the color of the line */
    transition: width 0.3s ease, left 0.3s ease;
}

/* .nav-link:hover {
    color: #fff !important; /
} */

.nav-link:hover::after {
    width: 80%;
    left: 8%;
}

.link-text {
 display: none;
 /* margin-left: 1rem; */
 color: #fff;
}

.logo {
 font-weight: bold;
 text-transform: uppercase;
 text-align: center;
 color: #fff;
 background: rgba(0, 0, 0, 0);
 font-size: 1.5rem;
 letter-spacing: 0.3ch;
 width: 50%;
 
}


.logo svg {
 transform: rotate(0deg);
 transition: 0.3s;
}

.logo-text
{
 display: inline;
 position: absolute;
 left: -999px;
 transition: 0.3s;
}

.navbar:hover .logo svg {
 transform: rotate(-180deg);
 /* color: rgb(21, 200, 200); */
 /* color: #a8a8a8; */
 color: #fff;
 width: 35%;
 
}




.hometext {
 font-size: 1.3rem;
 font-family: "Orbitron", monospace;
 font-optical-sizing: auto;
 font-style: normal;
 font-size: 2rem;
 margin-left: 2rem;
}


@media only screen and (max-width: 600px) {
 .navbar {
   bottom: 0;
   width: 100vw !important;
   height: 5rem;
   transition: height 200ms ease;
   margin: 0 auto;
   display: flex;
   justify-content: center;
 }

 .navbar:hover {
 width: 100vw !important;
 height: 5rem;
}

 .logo {
   display: none;
 }

 .navbar-nav {
   flex-direction: row;
 }

 .nav-link {
   justify-content: center;
   flex-direction: column;

 }

 .link-text {
   font-size: 12px;
   display: none;
 } 

 .nav-link i {
   margin-left: 1.2rem; 
   margin-right: 1.2rem; 
   width: 1rem;
   
 }

 .navbar:hover .link-text {
 display: none;
}
 
}

@media only screen and (max-width: 475px) {

 .nav-link i {
   margin-left: 0.8rem; 
   margin-right: 0.8rem; 
   width: 1rem;
   
 }
}
</style>