<template>
    <h1>Home Component</h1>
    <h1>Email {{ email }}</h1>
    <h1>Number {{ number }}</h1>
    <h1>Name {{ getName("Harshal") }}</h1>
    <h1>Address {{ address="Pune" }}</h1>

</template>
<script>

export default {
    name:"HomeComponent",
    data(){
        return{
            email:"harshal@agkiya.com",
            number:7756985642,
            address:"Wakad",
            getName(a){
                return a
            }
        }
    }
}
    
</script>

<style scoped>
h1{
    color: orange;
}
</style>