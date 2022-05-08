<template>
    <div>
        <h2>pass data to child</h2>
        <h1>{{name}}    child comp</h1>
        </div>
</template>
<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name:"User",
    props:{
        name:String
    }
}
</script>