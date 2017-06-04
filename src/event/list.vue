<template>
    <div>
        <el-tabs v-model="activeTab">
            <el-tab-pane label="进行中" name="tab1">
                <p>线上积分送酒</p>
            </el-tab-pane>
            <el-tab-pane label="未开始" name="tab2">
                <p>未开始</p>
            </el-tab-pane>
            <el-tab-pane label="已结束" name="tab3">
                <p>已结束</p>
            </el-tab-pane>
        </el-tabs>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                activeTab: 'tab1',
            };
        },
    };
</script>
<style>

</style>