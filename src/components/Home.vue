<template>
    <div>
        <h1>Parent comp</h1>
        <User name="syed"/>
    </div>
</template>
<script>
import User from './User.vue'
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"Home",
    components:{
        User
    }
}
</script>