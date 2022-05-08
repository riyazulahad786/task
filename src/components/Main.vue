<template>
    <div>
        <h1>parent comp</h1>
        <h3>{{childUser}}</h3>
        <MiniChild :getData="name"/>
    </div>
</template>
<script>
import MiniChild from "./MiniChild.vue"
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"Main",
    // data()
    // { 
    //    return{
    //        childUser:""

    //    }
    // },
    components:{
        MiniChild
         },
    // methods:{
    //     getName(name)
    //     {
    //       this.childUser=name
    //     }
    // }
}
</script>