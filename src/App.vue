
<template>
<div class="app">
<navbar/>
<router-view />
</div>
</template>

<script>
import navbar from "./components/navbar"
export default {
name: 'app',

data(){
return {}
},

computed:{},

methods:{},

components:{navbar}
}

</script>


<style scoped>

</style>







