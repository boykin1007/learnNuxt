<template>
    <div class="header">
        <div class="title">{{ title }}</div>
        <div class="login">{{ login }}</div>
    </div>
</template>

<script setup lang="ts">
const title:String = '这里是头部信息'
const login:String = '登录'
</script>

<style>
.header {
    color: #fff;
    background-color: #ffffff6b;
    display: flex;
    justify-content: space-between;
    padding: 0 36px;
    height: 50px;
}
</style>