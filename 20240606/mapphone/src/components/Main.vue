<template>
    <div class="total">
        <header class="navigation">
            <div class="first">
                <div class="logo">
                    <img src="https://img.icons8.com/?size=100&id=pSoAxHFPLpWF&format=png&color=000000" alt="logo">
                </div>
                <div class="gps">
                    <div>
                        위치
                    </div>
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=3723&format=png&color=000000" alt="gps">
                    </div>
                </div>
            </div>
            <div class="second">
                <div><img src="https://img.icons8.com/?size=100&id=63207&format=png&color=000000" alt="corectgps"></div>
                <div class="serch">
                    <input type="text" placeholder="위치를 입력하세요">
                    <button>버 튼</button>
                </div>
            </div>
        </header>

        <body>
            <div class="totalbody">
                <div class="one">
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=aeLEOHJU5cpb&format=png&color=000000" alt="식당">
                    </div>
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=fR0OOR9q4nZg&format=png&color=000000" alt="술집">
                    </div>
                </div>
                
                <div class="two">
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=BXrlpBmUDxLJ&format=png&color=000000" alt="카페">
                    </div>
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=18160&format=png&color=000000" alt="미용실">
                    </div>
                </div>
                
                <div class="three">
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=pTc17tvX2kMn&format=png&color=000000" alt="병원">
                    </div>
                    <div>
                        <img src="https://img.icons8.com/?size=100&id=3rJFC2vi1fHH&format=png&color=000000" alt="약국">
                    </div>
                </div>
            </div>
        </body>

        <footer>
            <nav class="botom">
                <div class="Bookmark">
                    <a href="">즐겨찾기</a>
                </div>
                <div class="home">
                    <a href="">홈</a>
                </div>
                <div class="logout">
                    <a href="">로그아웃</a>
                </div>
            </nav>
        </footer>
    </div>
</template>

<style scoped>
/* 전체 */
html, body {
    height: 100%;
    margin: 0;
}

.total {
    border: 1px solid black;
    width: 600px;
    height: 90vh;
    background-color: white;
    /* 백그라운드 색상 예시 */
    box-shadow: 0 0 10px rgba(255, 84, 84, 0.1);
    /* 그림자 예시 */
    /* justify-content: center;
    align-items: center; */
    flex-direction: column;
    justify-content: space-between;
}

/* 헤더파트 */
.navigation {
    border: 1px solid rgb(255, 150, 150);
}

.first {
    display: flex;
    justify-content: space-between;
    /* justify-content: space-around; */
}

.logo img {
    width: 25px;
    /* 원하는 너비로 설정 */
    height: 25px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
}

.gps {
    display: flex;
}

.gps img {
    width: 25px;
    /* 원하는 너비로 설정 */
    height: 25px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
}

.second {
    display: flex;
    justify-content: space-between;
}

.second img {
    width: 25px;
    /* 원하는 너비로 설정 */
    height: 25px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
}

/* 바디 부분 */

.totalbody {
    display: flex;
    height: 75vh;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex-grow: 1;
}

.one {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.one img {
    width: 150px;
    /* 원하는 너비로 설정 */
    height: 150px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
    margin: 0 10px;
    justify-content: space-between;
}

.two {
    display: flex;

}

.two img {
    width: 150px;
    /* 원하는 너비로 설정 */
    height: 150px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
    margin: 0 10px;
    justify-content: space-around;
}

.three {
    display: flex;
    justify-content: space-around;
}

.three img {
    width: 150px;
    /* 원하는 너비로 설정 */
    height: 150px;
    /* 원하는 높이로 설정 */
    object-fit: cover;
    /* 이미지를 자르지 않고 비율을 유지하며 맞추기 */
    margin: 0 10px;
    justify-content: space-around;
}

/* 풋터 부분 */
footer {
    border: 1px solid violet;
    height: 7vh;
    background-color: rgb(249, 96, 211);
}

.botom {
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 10px;

}
</style>