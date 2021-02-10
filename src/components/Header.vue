<template>
    <header class="flex flex-col w-full container">
        <Title msg="My To Do List" />
        <NewTodo placeholder="What needs to get done?"/>       
    </header>    
</template>

<script setup>
import Title from './Title.vue'
import NewTodo from './NewTodo.vue' 
</script>