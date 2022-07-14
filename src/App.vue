<template>
    <div style="box-shadow: 0 0 3rem rgba(0,0,0,.175) !important; width: 50%; margin: 0 auto; margin-top: 35px;     min-width: 622px;">
        <MyHeader/>
        <MyMain/>
    </div>
</template>  

<script>
import MyHeader from "@/components/MyHeader.vue";
import MyMain from "@/components/MyMain.vue";

export default {
    components: {
        MyHeader, MyMain
    }
}
</script>

<style>
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    color: rgba(0, 0, 0, 0.723);

}
</style>

