<template>
    <h1>Home compenent {{ "MuhammadNawaz".length }}</h1>
    <h1>Email:{{ getData().email }}</h1>
    <h1>Mobile:{{ getData().Mobile }}</h1>
    <h1>Framwork:{{ getName("I am good software Enginner") }}</h1>
</template>
<script>
export default {
    name: 'Home',
    data() {
        return {

            email: "sardarnawaz122@gmail.com",
            Mobile: 3435281821,

        }
    },
    methods: {
        getName(title) {
            return title
        },
        getData() {
            return {
email:"Hafiz@gmail.com",
Mobile:this.Mobile


            }
        }
    },


}

</script>
<style scoped>
h1 {

    color: red;




}
</style>