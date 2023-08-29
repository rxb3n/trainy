<template>
    <div class="client-container">
        <div class="client-text">
            <p class="bold">Fitness Consultation and Assessment</p>
            <p>Our personalized fitness consultation and assessment service is designed to help you <br>
                understand your current fitness level and create a tailored training plan. Our expert <br>
                trainers will assess your goals, lifestyle, and body composition to provide you with a <br>
                comprehensive fitness plan that fits your needs and helps you achieve your health and <br>
                wellness goals.</p>
        </div>
            <img class="client-img" src="../assets/gym-img.jpg" alt="">
    </div>
</template>


<style scoped>
.client-container {
    display: flex;
    justify-content: space-around;
    background-color: var(--bg-secondary);
    text-align: center; 
    padding-top:5% ;padding-bottom: 5%;
    color: white;
}

.client-text {
    display: flex;
    text-align: center;
    flex-direction: column;
    font-size: 1.25em;
}

.bold {
    font-weight: 500;
    font-size: 2em;
}


.client-img {
    width: 35%;
    height: 50%;
    border-radius: 18px;
}

@media screen and (max-width: 1000px) {
    .client-img {
        display: none;
    }
}


</style>