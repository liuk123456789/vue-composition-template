<script lang="ts" setup>
import { Image, Layout, LayoutContent, LayoutFooter, LayoutHeader } from 'ant-design-vue'
</script>

<template>
  <Layout>
    <LayoutHeader class="flex justify-between flex-items-center">
      <Image :width="50" :height="50" src="https://aliyuncdn.antdv.com/vue.png" />
    </LayoutHeader>
    <LayoutContent>Content</LayoutContent>
    <LayoutFooter>Footer</LayoutFooter>
  </Layout>
</template>
