<template>
    <div class="hero-container">
        <p class="hero-text bold">Transform Your Body <br>Today!</p>
        <p class="hero-text">Get a stunning website that showcases your business and <br>attract more customers</p>
        <div class="hero-btn-container">
            <button class="hero-btn">Get Started</button>
        </div>

    </div>
</template>

<style scoped>

.hero-container {
    background: linear-gradient(rgba(136, 13, 30, 0.5), rgba(136, 13, 30, 0.5)), url('../assets/hero-banner.webp');
    display: flex;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    padding: 10%;
}

.hero-text {
    color: white;
    font-size: 1.5em;
}

.bold {
    font-weight: 700;
    font-size: 3.5em;
}

.hero-btn {
    background-color: var(--bg-secondary);
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 1%;
    color: white;
    font-size: 1.25em;
}

.hero-btn-container {
    display: flex;
    justify-content: center;
}

</style>