<template>
    <div class="main">
        <div class="info">
            <h1 style="margin-left: 20px;padding-bottom:20px;" >Обо мне</h1>
            <img src="./photo.png" width="150"/>

            <div class="about-me">
                <h3>Оразование</h3>
                <p>Закончил 3 курс в уральском радиотехническом колледже им. А. С. Попова, учусь по специальности программирование в компьютерных системах(09.02.03).</p>

                <h3>Опыт</h3>
                <p>Имеется опыт работы с linux в качестве основной OC.</p>
                <p>Недавно закончил курсовую работу по wpf с разработкой базы данных и дальнейшим взаимодействием с ней через wpf приложение.</p>

                <h3>Навыки</h3>
                
                <ul>
                    <li>html</li>
                    <li>css</li>
                    <li>javaScript</li>
                    <li>c++</li>
                    <li>c#</li>
                    <li>sql</li>
                    <li>python</li>
                </ul>
                
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
h1 {
    width: 150px;
    color: rgba(78, 78, 78, 0.723);
}
h3 {
    width: 150px;
    color: rgba(0, 0, 0, 0.723);
    font-size: 28px;
    padding-top: 20px;
}
li {
    list-style: none;
    padding-top: 5px;
}
img {
    margin-left: 20px;
    vertical-align:top;
}

.about-me {

    padding: 0 20px;
    display: inline-block;
    min-width: 300px;
    width: 800px;
    
}
.info {
    padding: 10px;
    display: inline-block;
}
.main {
    margin: 0 auto;
    padding: 15px;
}

</style>