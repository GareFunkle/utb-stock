<template>
    <header>
        <div class="background">
            <img src="..\assets\Logo\logo.png">
        </div>
    </header>

    <nav class="nav-area">
        <ul>
            <li>
                <a href="#">Bois</a>
                <ul>
                    <li>
                        <a href="">Itauba</a>
                    </li>
                    <li>
                        <a href="">IPE</a>
                    </li>
                    <li>
                        <a href="">Cumaru</a>
                    </li>
                    <li>
                        <a href="">Structures</a>
                    </li>
                </ul>
            </li>
            <li>
                <a href="#">Quincailleries</a>
                <ul>
                    <li>
                        <a href="">Terrasses</a>
                    </li>
                    <li>
                        <a href="">Structures</a>
                    </li>
                    <li>
                        <a href="">Bétons</a>
                    </li>
                    <li>
                        <a href="">????</a>
                    </li>
                </ul>
            </li>
            <li>
                <a href="#">Services</a>
                <ul>
                    <li>
                        <a href="#">Web Design</a>
                    </li>
                    <li>
                        <a href="#">Web Development</a>
                    </li>
                    <li>
                        <a href="#">Email Marketing</a>
                    </li>
                    <li>
                        <a href="#">Graphics Design</a>
                        <ul>
                            <li>
                                <a href="#">Logo Design</a>
                            </li>
                            <li>
                                <a href="#">Card Design</a>
                            </li>
                            <li>
                                <a href="#">Poster Design</a>
                            </li>
                            <li>
                                <a href="#">Template Design</a>
                                <ul>
                                    <li>
                                        <a href="#">Web Template</a>
                                    </li>
                                    <li>
                                        <a href="#">Email Template</a>
                                    </li>
                                    <li>
                                        <a href="#">News Template</a>
                                    </li>
                                    <li>
                                        <a href="#">Bio Template</a>
                                    </li>
                                    <li>
                                        <a href="#">Wedding Template</a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="#">Brochure Design</a>
                            </li>
                        </ul>
                    </li>
                    <li>
                        <a href="#">SEO</a>
                    </li>
                </ul>
            </li>
            <li>
                <a href="#">Portfolio</a>
            </li>
            <li>
                <a href="#">Contact</a>
            </li>
        </ul>
    </nav>

</template>

<script>
export default {
    name: 'BestMenu'
}


</script>

<style>
@import 'bulma/css/bulma.min.css';

* {
    margin: 0;
    padding: 0;
}

header {
    position: relative;
}

.background {
    background: #ddcdba;
    display: flex;
    justify-content: center;
    align-items: center;
}

.background img {
    width: 450px;
}

a {
    font-size: 15px;
    text-transform: uppercase;
}

.nav-area {
    background: #262626;
}

.nav-area:after {
    content: '';
    clear: both;
    display: block;
}

.nav-area ul {
    list-style: none;
    margin: 0;
    display: flex;
    justify-content: space-around;
}

.nav-area>ul>li {
    float: left;
    position: relative;
}

.nav-area ul li a {
    text-decoration: none;
    color: #fff;
    padding: 15px 20px;
    display: block;
}

.nav-area ul li:hover a {
    background: #9E522F;
}

.nav-area ul ul {
    position: absolute;
    padding: 0;
    min-width: 160px;
    display: none;
    top: 100%;
    left: 0;
}

.nav-area ul li:hover>ul {
    display: block;
}

.nav-area ul ul li:hover a {
    background: #262626;
}

.nav-area ul ul li {
    position: relative;
}

.nav-area ul ul ul {
    top: 0;
    left: 100%;
}

.nav-area ul ul ul li:hover a {
    background: #34495e;
}
</style>

