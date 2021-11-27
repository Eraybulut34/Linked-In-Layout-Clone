<template>
  <div class="story-bar">

    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>    <div class="story"><Avatar :size="55" /></div>
    <div class="story"><Avatar :size="55" /></div>
  </div>
</template>

<script>
import Avatar from '@/components/Avatar'

export default {
  name: 'StoryBar',
  components: {
    Avatar
  }
}
</script>

<style scoped>
.story-bar {
  height: 70px;
  display: flex;
  align-items: center;
  padding-left: 16px;
  padding-right: 16px;
  justify-content: center;
  margin-bottom: 10px;

}
.story {
min-width: 80px;
justify-content: center;
align-items: center;

}
</style>