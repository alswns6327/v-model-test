<template>
    <input @input="$emit('update:name', $event.target.value)" :value="name"/>
</template>
<script>
    export default{
        name : "InputName",
        props : ["name"]
    }
</script>