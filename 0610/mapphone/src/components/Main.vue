<template>
    <div class="container">
        <div class="total">
            <header class="navigation">
                <div class="first">
                    <div class="logo">
                        <!-- <img src="https://img.icons8.com/?size=100&id=pSoAxHFPLpWF&format=png&color=000000" alt="logo"> -->
                    </div>
                    <div class="gps">
                        <div>위치</div>
                        <div>
                            <img src="https://img.icons8.com/?size=100&id=3723&format=png&color=000000" alt="gps">
                        </div>
                    </div>
                </div>
                <div class="second">
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=63207&format=png&color=000000" alt="corectgps">
                    </div>
                    <div class="serch">
                        <input type="text" placeholder="위치를 입력하세요">
                        <button class="button">검 색</button>
                    </div>
                </div>
            </header>
            <div class="totalbody">
                <div class="one">
                    <div class="menu-item">
                        <router-link to="main/foodmap">
                            <img src="https://img.icons8.com/?size=100&id=koNbh1XwujSO&format=png&color=000000"
                                alt="식당">
                                <div class ="menu">식당</div>
                        </router-link>
                    </div>
                    <div class="menu-item">
                        <router-link to="main/bankmap">
                        <img src="https://img.icons8.com/?size=100&id=zJRQAXUs76EX&format=png&color=000000" alt="은행">
                        <div class ="menu">은행</div>
                    </router-link>
                  
                    </div>
                </div>
                <div class="two">
                    <div class="menu-item">
                        <img src="https://img.icons8.com/?size=100&id=nOcivOyW0Qr9&format=png&color=000000" alt="카페">
                        <div class ="menu">카페</div>
                    </div>
                    <div class="menu-item">
                        <img src="https://img.icons8.com/?size=100&id=2ndaoUiYY2z4&format=png&color=000000" alt="호텔">
                        <div class ="menu">호텔</div>
                    </div>
                </div>
                <div class="three">
                    <div class="menu-item">
                        <router-link to="main/hospitalmap">
                        <img src="https://img.icons8.com/?size=100&id=qObz5FFrXebr&format=png&color=000000" alt="병원">
                        <div class ="menu">병원</div>
                    </router-link>
                    </div>
                    <div class="menu-item">
                        <img src="https://img.icons8.com/?size=100&id=cq3pqXaneXhq&format=png&color=000000" alt="약국">
                        <div class ="menu">약국</div>
                    </div>
                </div>
            </div>
            <footer>
                <nav class="botom">
                    <div class="Bookmark">
                        <a href="">
                            <img src="https://img.icons8.com/ios/50/000000/bookmark-ribbon--v1.png" alt="즐겨찾기">
                        </a>
                    </div>
                    <div class="home">
                        <RouterLink to="/main">
                            <img src="https://img.icons8.com/ios/50/000000/home-page.png" alt="홈">
                        </RouterLink>
                    </div>
                    <div class="logout">
                        <RouterLink to="/">
                            <img src="https://img.icons8.com/ios/50/000000/logout-rounded-left.png" alt="로그아웃">
                        </RouterLink>
                    </div>
                </nav>
            </footer>
        </div>
    </div>
</template>

<style scoped>

</style>

<script>
import "../css/mainstyle.css";

</script>