<template>
    <footer class="container-fluid">
        <div class="row d-flex justify-content-center align-items-center">
            <p class="lead">Caleb Okkers &copy; <span class="shadow">{{ cYear }}</span></p>
        </div>
    </footer>
</template>
<script>
export default {
    name: "FooterComp",
    data() {
        return {
            cYear: new Date().getUTCFullYear()
        }
    }
}
</script>
<style scoped>
    
    footer {
    color: #fff;
    background: #001a34;
    font-family: "JetBrains Mono", monospace;
    font-optical-sizing: auto;
    font-style: normal;
    font-style: normal;
    margin: 0 auto;

}

footer p {
    padding-top: 1rem;
    text-align: center;
}
</style>