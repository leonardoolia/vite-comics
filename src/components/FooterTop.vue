<script></script>

<template>
    <footer>
        <div class="container">
            <div class="links">
                <div>
                    <h4>DC COMICS</h4>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <h4>SHOP</h4>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>

                </div>
                <div>
                    <h4>DC</h4>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div>
                    <h4>SITES</h4>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>

            </div>

            <div class="logo">
                <img src="@/assets/img/dc-logo-bg.png" alt="Logo DC">
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
footer {
    background-image: url('@/assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

div.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

div.links {
    display: flex;
    justify-content: flex-start;
    flex-wrap: wrap;
    color: white;
    flex-basis: 60%;

    a {
        color: white;
    }

    h4 {
        font-weight: bold;
        font-size: 1.5rem;
        margin-bottom: 10px;
    }

    ul {
        margin-bottom: 1rem;
    }


    div {
        flex-basis: calc(100% / 3);
    }
}
</style>