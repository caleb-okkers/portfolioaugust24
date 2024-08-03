<template>
  <div class="container d-flex justify-content-center align-items-center">
    <div class="row d-flex justify-content-center align-items-center">
        <div class="col d-flex justify-content-end">
            <div class="intro-div pb-5">
                <p>Hi, my name is</p>
                <h1 class="intro">CALEB OKKERS.</h1>
                <h3 class="title">Web Developer</h3>
                <p class="intro-text">I design and build pixel perfect projects that inspire innovation and provides satisfying digital experiences.</p>
                <button class="about-button mx-auto">About me</button>
            </div>
        </div>
        <div class="col me-auto">
            <img class="profile" src="https://github.com/caleb-okkers/portfolioaugust24/blob/master/src/assets/caleb-whiteshirt-duotoneclassic.png?raw=true" alt="">
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
    width: 110%;
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

.about-button {
    margin: 0 auto;
    border: 2px solid #fff;
    padding: 1rem;
    background: #001a34;
    color: #fff;
}

</style>