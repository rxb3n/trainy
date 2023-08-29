<template>
    <div class="description-container">

        <img class="desc-img" src="../assets/description-img.jpg" alt="">

        <div class="desc-wrapper">
        <p class="bold">About us</p>
        <p class="description-text">
            Trainy is a personal training business located in Abidjan, Côte d'Ivoire. Our team of
            <br>experienced trainers is dedicated to helping our clients achieve their fitness goals
            <br>through personalized workout plans and nutrition guidance.
            <br>
            <br>
            <br>
            At Trainy, we believe that fitness should be accessible to everyone, regardless of their
            fitness level or background. We strive to create a welcoming and supportive
            environment where our clients feel motivated and empowered to reach their full
            potential. Whether you are looking to lose weight, build muscle, or simply improve
            your overall health, we are here to help you every step of the way.
        </p>
    </div>
        
    </div>
</template>


<style scoped>

.description-container {
    display: flex;
    flex-direction: row-reverse;
    justify-content: space-around;
    padding-top: 7%; padding-bottom: 7%;
}

.description-text {
    font-size: 1.15em;
}

.desc-wrapper {
    display: flex;
    flex-direction: column;
    width: 40%;

}

.desc-img {
    border-radius: 18px;
    width: 45%;
}

.bold {
    font-weight: 500;
    font-size: 2em;
}

.desc-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 2%;
    color: white;
    font-size: 1.25em;
}

@media screen and (max-width: 1000px) {
    .description-container {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 100%;
    }
    .desc-img {
        width: 90dvw;
    }
}

</style>