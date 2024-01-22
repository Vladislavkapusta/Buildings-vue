<script>

</script>

<template>
        <div class="req-plate">
            <div class="container req-cont">
                    <div class="text-space">
                        <h1 class="big-font">САМЫЕ УМНЫЕ ПРОЕКТЫ</h1>
                        <h3 class="small-font">РЕАЛИЗУЕМ САМЫЕ СМЕЛЫЕ РЕШЕНИЯ В РОССИИ!</h3>
                    </div>
                    <div class="button-space">
                        <button class="footer-button">ВАШ ЗАПРОС</button>
                    </div>
            </div>
        </div>
        <footer>
            <div class="container foot-cont">
                <div class="info">© 2019 Строительная компания</div>
                <div class="info">Разработано лучшей студей</div>
            </div>
        </footer>


</template>

<style scoped>
.req-plate{
    /* width: 1920px; */
    height: 181px;
    flex-shrink: 0; 

    flex-direction: row;

    background: var(--Accent, #F7654A); 
}

.req-cont{
    display: flex;
    flex-direction: row;
}

.text-space{
    width: 50%;
    display: flex;
    flex-direction: column;

    margin-top: auto;
    margin-bottom: auto;

    gap: 20px;
}



.big-font{
    width: 537px;
    height: 57px; 
    margin: 0;

    color: #FFF;
    font-size: 48px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    letter-spacing: 0.96px; 

    /* align-self: flex-end; */
}

.small-font{
    width: 537px;
    height: 29px; 
    margin: 0;

    color: #FFF;
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
    line-height: normal;
    letter-spacing: 0.48px; 

    /* align-self: flex-end; */
}

.button-space{
    width: 50%;
    display: flex;
    flex-direction: column;
}

.footer-button{
    width: 175px;
    height: 49px; 

    color: #000;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    letter-spacing: 0.7px; 

    align-self: flex-end;

    margin-top: auto;
    margin-bottom: auto;
}

footer{
    /* width: 1920px; */
    height: 82px; 

    background: var(--Dark, #404149); 
}

.foot-cont{
    display: flex;
    flex-direction: row;

    justify-content: space-between;
}

.info{
    margin-top: auto;
    margin-bottom: auto;

    color: var(--White, #FFF);
    text-align: right;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal; 
}

</style>