<template>
  <div class="container d-flex justify-content-center align-items-center">
    <div class="row d-flex justify-content-center align-items-center">
        <div class="col d-flex justify-content-end">
            <div class="intro-div pb-5">
                <h1 class="intro">Hi I'm Caleb Okkers</h1>
                <h3 class="title">Web Developer</h3>
                <h3 class="intro-text">I build pixel perfect projects for the web.</h3>
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
    width: 120%;
}

.intro-div {
    color: #fff;
}

.intro {
    font-size: 4rem;
}

</style>