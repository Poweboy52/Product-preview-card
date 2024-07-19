<template>
    <div class="page">
        <div class="container">
            <div class="image-card">
                <img class="image" src=".\assets\image-product-desktop.jpg" />
            </div>
            <div class="text-card">
                <p class="top-text">perfume</p>
                <h1 class="heading">Gabrielle Essence Eau De Parfum</h1>
                <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                <div class="prices-box">
                    <p class="sale-price">$149.99</p>
                    <p class="original-price">$169.99</p> 
                </div>
                <a class="link" href="https://www.google.com">
                    <img class="link-image" src=".\assets\icon-cart.svg"/>
                    <p class="link-text">Add to Cart</p>
                </a>
            </div>
        </div> 
    </div>   
</template>

<style scoped>
    .container {
        border-radius: 8px;
        width: 666px;
        height: 500px;
        display: flex;
        overflow: hidden;
        background-color: white;
        justify-content: center;
        align-items: center;
    }
    .image-card {
        width: auto;
        height: 100%;
        display: flex;
    }

    .text-card {
        width: 258px;
        height: 424px;
        padding: 38px;
    }
    .page {
        height: 100vh;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: hsl(30, 38%, 92%);
    }
    .prices-box {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        margin-top: 0;
        gap: 16px;
        padding: 10px 0px 32px;
    }
    .top-text {
        margin-top: 0px;
        font-size: 10px;
        color: hsl(228, 12%, 48%);
        font-family: "Montserrat", sans-serif;
        text-transform: uppercase;
        letter-spacing: 6px;
    }
    .text {
        margin-top: 0px;
        font-size: 16px;
        color: hsl(228, 12%, 48%);
        line-height: 28px;
        font-family: "Montserrat", sans-serif;
    }
    .sale-price {
        margin: 0px;
        font-size: 38px;
        color: hsl(158, 36%, 37%);
        line-height: 28px;
        font-family: "Fraunces", serif;
        font-weight: 700;
    }
    .original-price {
        margin: 0px;
        font-size: 16px;
        color: hsl(228, 12%, 48%);
        font-family: "Montserrat", sans-serif;
        text-decoration: line-through;
    }
    .link-text {
    font-size: 19px;
    color: white;
    margin: 0px;
    margin-left: 6;
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
    }
    .heading {
        color: hsl(212, 21%, 14%);
        font-family: "Fraunces", serif;
        font-size: 34px;
        margin-top: 18px;
        font-weight: 700;
    }
    .link {
        height: fit-content;
        padding: 20px 40px;
        background-color: hsl(158, 36%, 37%);
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 12px;
        text-decoration: none;
        gap: 16px;
    }
    .link-image {
        max-height: 100%;
        width: auto;
    }

    @media screen and (max-width: 640px){
    .container {
      flex-direction: column;
    }
    .image-card {
        height: auto;
        width: 100%;
    }
    .text-card {
    }
  }
</style>