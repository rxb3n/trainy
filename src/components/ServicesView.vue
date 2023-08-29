<template>
    <div class="serv-container">
        <p class="big bold" id="services">Our Services</p>

        <div class="serv-wrapper">

            <div class="serv-card">
                <img class="serv-img" src="../assets/serv1.jpeg" alt="">
                <p class="bold">Weight Loss Programs</p>
                <p>Effective and personalized weight loss programs tailored to your <br>unique needs</p>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv2.jpg" alt="">
                <p class="bold">Strength Training</p>
                <p>Customized strenght training sessions to help you build muscle <br>and improve overall strength</p>
            </div>

        </div>

    </div>

</template>


<style scoped>

#services {
    text-align: center;
}
.serv-container {
    color: white;
    background-color: var(--bg-tertiary);
    font-family: 'Roboto', sans-serif;
    padding-top: 3%; padding-bottom: 3%;
}

.serv-wrapper {
    background-color: var(--bg-tertiary);
    color: white;
    display: flex;
    justify-content: space-around;
}

.serv-img {
    border-radius: 18px;
    height: 40dvh;
    width: 25dvw;
}

.bold {
    font-weight: 700;
    font-size: 1.25em;
}

.big {
    font-size: 2.5em;
}

.serv-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 2%;
    color: white;
    font-size: 1.25em;
}

@media screen and (max-width: 1000px) {
    .serv-wrapper {
        display: flex;
        flex-wrap: wrap;
    }

    .serv-img {
        width: 90dvw;
    }
}

</style>