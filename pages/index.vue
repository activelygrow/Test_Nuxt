<template>
  <div class="mainBox">
    <div class="tex">Blog test</div>
        <ContentDoc :path="'/test'"/>
  </div>
</template>

<script setup>
definePageMeta({ layout: "default" });

</script>

<style lang="scss" >
.mainBox{
  width: 100%;
  height: 100%;
}
</style>