<script>
export default{

    data(){
        return{
                buildings:[
            {id: 1, title: 'Многофункциональное здание', description: 'Мы сделали самую красивую арену в Европе. Это открытие стало для нас прорывной точкой для разивтия на следующие десятилетия.', image: 'https://teletype.in/files/f8/f6/f8f60304-dd5c-4a98-930b-4e1166160f8e.jpeg'},
            {id: 2, title: 'IT Колледж', description: 'Современный колледж на базе западной системе образования. Задача стояла в формировании многофункционального здания для решения всех современных проблем колледжа.', image: 'https://vmrucdn.servicecdn.ru/2021.05/original/60afa87282682c3df243a65c.jpg'},
            {id: 3, title: 'Здание выставки', description: 'Самое красивое здание в комплексе выставки достижений народного хозяйства. Данная архитекутура получила самые высокие награды', image: 'https://vdnh.ru/upload/resize_cache/iblock/b7f/1000_1000_1/b7fcf4db2c6bfdef5f1423a06fdd381d.jpg'}
            ]
        }
    }
} 


</script>

<template>
    <div class="container">
        <div class="places-content">
            <h1 class="title">НАШИ САМЫЕ БОЛЬШИЕ ПРОЕКТЫ</h1>
            <div class="project-list">
                <div class="project-item" v-for="building in buildings" :key="building.id">
                    <img :src="building.image" class="image" alt="img">
                    <div class="smol"></div>
                    <h3 class="build-title">{{ building.title }}</h3>
                    <p class="build-desc">{{ building.description }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .places-content{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 50px;

        height: 980px; 

        background-color: #FFF;
    }

    .title{
        width: 506px;
        height: 43px; 

        color: var(--Dark, #404149);
        text-align: center;

        font-family: Oswald;
        font-size: 36px;
        font-style: normal;
        font-weight: 500;
        line-height: normal;
        text-transform: uppercase; 
    }

    .project-list{
        display: flex;
        flex-direction: row;
        gap: 30px;
    }

    .image{
        width: 350px;
        height: 380px; 
    }

    .smol{
        margin-top: 45px;

        width: 55px;
        height: 6px; 
        background: var(--Accent, #F7654A); 
    }

    .build-title{
        color: var(--Dark, #404149);
        font-size: 24px;
        font-style: normal;
        font-weight: 500;
        line-height: normal; 
    }

    .build-desc{
        color: #999;
        font-family: "Open Sans";
        font-size: 16px;
        font-style: normal;
        font-weight: 400;
        line-height: normal; 
    }
</style>