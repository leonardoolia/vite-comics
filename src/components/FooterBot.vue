<script></script>

<template>
    <div>
        <button>SIGN-UP NOW!</button>

        <div class="footer-social">
            <span>FOLLOW US</span>
            <ul>
                <li><a href="#"><img src="@/assets/img/footer-facebook.png" alt=""></a></li>
                <li><a href="#"><img src="@/assets/img/footer-twitter.png" alt=""></a></li>
                <li><a href="#"><img src="@/assets/img/footer-youtube.png" alt=""></a></li>
                <li><a href="#"><img src="@/assets/img/footer-pinterest.png" alt=""></a></li>
                <li><a href="#"><img src="@/assets/img/footer-periscope.png" alt=""></a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
div {
    padding: 1rem 0 1rem 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #303030;

    button {
        padding: 10px;
        background-color: #303030;
        color: white;
        font-weight: bold;
        border-color: #0282f9;
        border-style: solid;
        border-image: none;
        cursor: pointer;
    }

    .footer-social {
        display: flex;
        align-items: center;
        gap: 1rem;

        span {
            font-weight: bold;
            color: #0282f9;
        }

        ;

        ul {
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }
    }
}
</style>