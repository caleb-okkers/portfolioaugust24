<template>
  <div class="container d-flex justify-content-center align-items-center">
    <div class="row d-flex justify-content-center align-items-center">
        <div class="col d-flex justify-content-end">
            <div class="intro-div pb-5">
                <h1 class="intro">I'M CALEB OKKERS</h1>
                <h3 class="title">Web Developer</h3>
                <p class="intro-text">I design exquisite interfaces, build pixel perfect projects and I inspire innovation.</p>
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
}

h3 {
    font-size: 2rem;
}

p {
    font-size: 1.2rem;
}

.about-button {
    margin: 0 auto;
    border: 2px solid #fff;
    padding: 1rem;
    background: #001a34;
    color: #fff;
}

</style>