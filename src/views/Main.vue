<script setup>
import CommonAside from '@/components/CommonAside.vue'
</script>

<template>
    <div class="common-layout">
        <el-container class="lay-container">
            <!-- 自定义左侧的组件 -->
            <common-aside />
            <el-container>
                <el-header>
                    <common-header />
                </el-header>
                <el-main class="right-main">
                    main
                </el-main>
            </el-container>
        </el-container>
    </div>
</template>

<style scoped>
.common-layout,
.lay-container {
    height: 100%;
}
.el-header{
    background-color: #333;
}
</style>
