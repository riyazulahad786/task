<template>
    <div>
        <h1>child</h1>
        <button v-on:click="getData(userName)">CLICK</button>
    </div>
</template>
<script>
export default {
    name:"MiniChild",
    data()
    {
        return {
            userName:'Kiwi'
        }
    },
    props:{
        getData:Function
    }
}
</script>