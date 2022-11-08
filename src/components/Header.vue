<template>
    <header>
        <h1> {{title}} </h1>
        <addButton text="Add Task" color="green" />
    </header>
</template>



<script>
import addButton from './Button.vue'
export default {
    name:'head_der',
    props:{
        title:String
    },
    components: {
        addButton,
}
}

</script>

 
<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
</style>