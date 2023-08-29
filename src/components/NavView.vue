<template>
    <div class="nav-container">

        <div class="nav-socials">
            <img src="../assets/facebook.png" height="48">
            <img src="../assets/insta.png" height="48">
            <img src="../assets/twitter.png" height="48">
        </div>

        <div class="nav-title">
            <h1>Trainy</h1>
        </div>
    </div>
</template>


<style scoped>

.nav-container {
    display: flex;
    justify-content: space-around;
    background-color: var(--bg-primary);
    height:10dvh;
    align-items: center;
    color: white;
}

.nav-socials {
    width: 15dvw;
    display: flex;
    justify-content: space-around;
    filter: invert();
}

.nav-title {
    text-align: center;
    font-size: 1.5em;
}


</style>