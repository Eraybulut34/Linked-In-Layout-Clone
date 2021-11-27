<template>
<div class="posts">
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
<div class="post"><ProfilePost/></div>
</div>
</template>

<script>
import ProfilePost from '@/components/ProfilePost'
export default {
  name: 'Post',
  components: {
ProfilePost
  }
}
</script>

<style scoped>
.posts{
  margin-top: 12px;
align-items: center;
  justify-content: space-around;
}
.post{
  max-width: 305px;
display: inline-block;
grid-gap: 11px;
margin-right: 8px;
margin-bottom: 8px;
}

</style>
