<template>
    <h1 v-on:mousemove="getConsole()">Home compenent {{ "MuhammadNawaz".length }}</h1>
    <h1>Email:{{ getData().email }}</h1>
    <h1>Mobile:{{ getData().Mobile }}</h1>
    <h1>Framwork:{{ getName("I am good software Enginner") }}</h1>
    <button v-on:click="test()">Button1</button><br>
    <button v-on:dblclick="test('button 2 is clicked')">Button2</button>
    <h1>{{ count }}</h1>
</template>
<script>
export default {
    name: 'Home',
    data() {
        return {

            email: "sardarnawaz122@gmail.com",
            Mobile: 3435281821,
            count: 0

        }
    },
    methods: {
        getName(title) {
            return title
        },
        getData() {
            return {
                email: "Hafiz@gmail.com",
                Mobile: this.Mobile


            }
        },
        test() {
            // this.count=this.count+1
            this.count=70
        },
        getConsole() {

            return console.warn("this is mousemove event")
        }
    },


}

</script>
<style scoped>
h1 {

    color:blue;




}
</style>