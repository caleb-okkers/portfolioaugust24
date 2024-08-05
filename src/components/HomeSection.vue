<template>
  <div class="container d-flex justify-content-center align-items-center">
    <div class="row d-flex justify-content-center align-items-center">
        <div class="col d-flex justify-content-end">
            <div class="intro-div pb-5">
                <p class="intro-text">Hi, my name is</p>
                <h1 class="intro">CALEB OKKERS.</h1>
                <h3 class="title">Web Developer</h3>
                <p class="intro-text">I design and build pixel perfect projects that inspire innovation and provides satisfying digital experiences.</p>
                <button class="about-button btn mx-auto"><span class="text-light">About me</span></button>
                <button class="btn sort m-2 " type="button" id="sort"><span class="text-light">My work</span></button>
            </div>
        </div>
        <div class="col me-auto">
            <img class="profile" src="https://github.com/caleb-okkers/portfolioaugust24/blob/master/src/assets/6.png?raw=true" alt="">
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'HomeSection'
}
</script>

<style scoped>

.profile {
    aspect-ratio: 1;
    width: 105%;
    margin-right: -10rem;
}

.intro-div {
    color: #fff;
    margin-right: 0;
    margin-left: 8rem;
}

.intro {
    font-size: 4rem;
}

h1 {
    font-size: 4rem !important;
    font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-weight: 500;
  font-style: normal;
  color: #fff;
  text-shadow: 1px 1px #000;
}

.title {
    font-size: 2rem;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
    font-weight: 400;
    font-style: normal;
}

p {
    font-size: 1.18rem;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
    font-weight: 300;
    font-style: normal;
}

/* .about-button {
    margin: 0 auto;
    border: 2px solid #fff;
    padding: 1rem;
    background: #001a34;
    color: #fff;
} */


.about-button {
  position: relative;
  overflow: hidden;
  background-color: #001a34 !important;
  color: #fff !important;
  border-color: #001a34 !important;
  text-align: center !important;
  padding: 10px 20px;
  cursor: pointer;
  transition: color 0.5s ease;
  border-radius: 0 !important;
  z-index: 1;
  will-change: color;
  font-size: 1.18rem;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
    font-weight: 300;
    font-style: normal;
}

.btn {
  position: relative;
  overflow: hidden;
  background-color: #001a34 !important;
  color: #fff !important;
  border-color: #fff !important;
  text-align: center !important;
  padding: 10px 20px;
  cursor: pointer;
  transition: color 0.5s ease;
  border-radius: 0 !important;
  z-index: 1;
  will-change: color; 
  font-size: 1.18rem;
    font-family: "Montserrat", sans-serif;
    font-optical-sizing: auto;
    font-weight: 300;
    font-style: normal;
}

.btn::before,
.about-button::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #000;
  z-index: 0;
  transition: transform 0.5s ease;
  transform: scaleX(0);
  transform-origin: left;
  backface-visibility: hidden; 
  will-change: transform; 
}

.btn:hover::before,
.about-button:hover::before {
  transform: scaleX(1);
}

.btn:hover,
.about-button:hover::before {
  color: #001a34 !important; 
}

.btn span,
.about-button span {
  position: relative;
  z-index: 2;
  backface-visibility: hidden; 
  will-change: color; 
  color: #fff;
  
}

.btn:hover span,
.about-button:hover span {
  position: relative;
  z-index: 2;
  backface-visibility: hidden; 
  will-change: color; 
  color: #fff !important;
  
}


</style>