<script setup>
</script>

<template>
  <el-container>

    <el-header class="flex items-center">
      <el-space>
        <router-link to="/">
          <el-link
            type="primary"
            :underline="false"
          >Home</el-link>
        </router-link>
        <router-link to="/about">
          <el-link
            type="primary"
            :underline="false"
          >About</el-link>
        </router-link>
      </el-space>
    </el-header>

    <el-container>

      <el-aside>
        <el-menu>
          <el-menu-item index="1">
            <span>Navigator One</span>
          </el-menu-item>
          <el-menu-item index="2">
            <span>Navigator Two</span>
          </el-menu-item>
          <el-menu-item index="3">
            <span>Navigator Three</span>
          </el-menu-item>
          <el-menu-item index="4">
            <span>Navigator Four</span>
          </el-menu-item>
        </el-menu>
      </el-aside>

      <el-main>
        <router-view></router-view>
      </el-main>

    </el-container>

  </el-container>
</template>

<style scoped></style>
