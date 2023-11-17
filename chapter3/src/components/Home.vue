<template>

    <h1>Home compenent {{ "MuhammadNawaz".length }}</h1>
    <h1>Email:{{ email }}</h1>
    <h1>Password:{{ Mobile }}</h1>
    <h1>Framwork:{{ getName() }}</h1>


</template>
<script>
export default {
    name: 'Home',
data(){
    return {

email :"sardarnawaz122@gmail.com",
Mobile: 3435281821,
getName(){
return "Vue is popular front-end js framework"

}
    }
    
}


}

</script>
<style scoped>
h1{

color:red;




}
</style>