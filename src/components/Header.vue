<script setup>

</script>

<template>
  
  <div class="headerLayout">
    <div class="header-container container">
        <div class="headerContent">
            <div class="text-space">
                <h1 class="titleBar">РЕАЛИЗУЕМ КРУПНЕЙШИЕ ПРОЕКТЫ В РОССИИ</h1>
                <h3 class="addonBar">стадионы, газопроводы, мосты, дамбы</h3>                
            </div>
            <div class="cards-list">
                <div class="card-item">
                    <h2 class="card-number">26</h2>
                    <h3 class="card-name">лет</h3>
                    <p class="card-subname">на рынке</p>
                </div>
                <div class="card-item">
                    <h2 class="card-number">26</h2>
                    <h3 class="card-name">лет</h3>
                    <p class="card-subname">на рынке</p>
                </div>
                <div class="card-item">
                    <h2 class="card-number">26</h2>
                    <h3 class="card-name">лет</h3>
                    <p class="card-subname">на рынке</p>
                </div>
                <div class="card-item">
                    <h2 class="card-number">26</h2>
                    <h3 class="card-name">лет</h3>
                    <p class="card-subname">на рынке</p>
                </div>

            </div>
        </div>
    </div>
  </div>
</template>

<style scoped>

    .headerLayout{
        /* min-width: 1920px; */
        height: 740px;
        background-image: url(../images/Rectangle.png);
        background-position: center;
    }

    .header-container{
        display: flex;
        flex-direction: column;
        justify-content: flex-end;
    }
    .headerContent{
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 50px;
    }
    .titleBar{
        /* align-self: center; */
        margin: 0 auto;

        width: 734px;
        height: 171px;
        flex-shrink: 0; 

        color: var(--White, #FFF);
        text-align: center;
        font-size: 64px;
        font-style: normal;
        font-weight: 500;
        line-height: normal;
        letter-spacing: 1.28px;
        text-transform: uppercase; 
    }

    .addonBar{
        width: 734px;
        height: 22px;
        flex-shrink: 0; 
        color: var(--White, #FFF);
        text-align: center;
        font-size: 18px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        text-transform: uppercase; 
        margin: 0;
    }

    .text-space{
        display: flex;
        flex-direction: column;
        gap:35px;
    }

    .cards-list{
        background-color: #FFF;
        width: 100%;
        height: 300px;

        display: flex;
        flex-direction: row;
        justify-content: center;
    }

    .card-item{
        width: 190px;
        height: 186px; 
    }

    .card-number{
        width: 190px;
        height: 86px; 

        color: var(--Accent, #F7654A);
        text-align: center;
        font-size: 72px;
        font-style: normal;
        font-weight: 500;
        line-height: normal;
        text-transform: uppercase; 

        margin-bottom: 25px;
    }
    .card-name{
        width: 190px;
        height: 43px; 

        color: #000;
        text-align: center;
        font-family: Oswald;
        font-size: 36px;
        font-style: normal;
        font-weight: 500;
        line-height: normal;
        text-transform: uppercase; 

        margin-bottom: 10px;
    }

    .card-subname{
        width: 190px;
        height: 22px; 

        color: var(--gray, #999);
        text-align: center;
        font-family: Oswald;
        font-size: 18px;
        font-style: normal;
        font-weight: 500;
        line-height: normal; 

        margin: 0;
    }
</style>