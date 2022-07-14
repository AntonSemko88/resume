<template>
    <header class="row">
        <div  class="logo">Семко Антон</div>
        <hr/>
        <ul class="header-items">
            <li class="header-item"><a href="https://vk.com/nnsrslst">Вконтакте</a></li>
            <li class="header-item"><a href="https://t.me/dhdihxhd">Telegram</a></li>
            <li class="header-item"><a href="mailto:semcko.anton@yandex.ru.ru?subject=Junior frontend программист">Почта</a></li>
        </ul>
    </header>
</template>

<script>

</script>
<style scoped>

header {
    height: 100px;

    background-color: white;
    font-weight: 400;
    margin: 0 auto;
    padding: 10px;
    border-bottom:2px solid rgba(0,0,0,.175);
    /*box-shadow: 0 0 3rem rgba(0,0,0,.175) !important;*/

}
hr {
    height: 80px;
    border: 1px solid rgba(0,0,0,.175);
}
.row {
    display: flex;
    flex-wrap: wrap;
    width: 91%;
}
.logo {
    padding: 20px;
    font-size: 40px;
    font-weight: 700;
    color: rgba(78, 78, 78, 0.723);
}
.header-items {
    float: right;
    display:flex;
    text-align: right;
    align-self: center;

}
.header-item{
    padding: 10px 15px;
    border: 1px solid rgba(0,0,0,.175);
    border-radius: 10px;
	display: inline-block;
    list-style-type: none;
    margin-left: 5px; 
}
a {

    text-decoration:none;
}
</style>