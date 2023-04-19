
<template>
    <v-app-bar   class="bar"   color="white" :elevation="3">
        
        <v-btn :ripple="false" v-for="btn in menu1btn "><a :href=btn.link>{{btn.name}}</a></v-btn>
        <v-spacer></v-spacer>
        <v-img src="img/logo.png" class="logo"></v-img>
        <v-spacer></v-spacer>
        <v-btn :ripple="false" v-for="btn in menu2btn "><a :href=btn.link>{{btn.name}}</a></v-btn>
        
    </v-app-bar>
  
</template>


<style>

.bar{padding:10px;}
a
{   
    color:black;
    text-decoration: none;
}
.logo{width:10%;}
.v-menu:before
{
  background-color:none ;
}
</style>
<script>
export default
{
    data() {
        return {
            menu1btn:[{name:"HOME",link:"/"},{name:"PRODUCTS",link:"/products"}],
            menu2btn:[{name:"PROJECTS",link:"/projects"},{name:"ABOUT US",link:"/about"}]
        }
    },    
}
</script>
