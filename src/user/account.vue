<template>
    <div>
        <el-form :model="userInfo" label-width="120px" style="width: 50%;">
            <el-form-item label="手机号码">
                {{ userInfo.phone }}
            </el-form-item>
            <el-form-item label="修改密码">
                <el-input v-model="userInfo.password" type="password"></el-input>
            </el-form-item>
            <el-form-item>
                <el-button type="primary">修改密码</el-button>
            </el-form-item>
        </el-form>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                userInfo: {
                    phone: '1130935894',
                    password: ''
                }
            };
        }
    };
</script>
<style>

</style>