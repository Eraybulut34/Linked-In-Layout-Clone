<template>
  <div class="profile-banner">
    <Avatar :size="140" />
    <div class="info">
      <div class="username">
     eraybulut34
      </div>
      <div class="info-info">
        <div class="posts"><b>42</b> Posts</div>
        <div class="followers"><b>1000</b> Followers</div>
        <div class="following"><b>1000</b> Following</div></div>
        <div class="name"><b>Eray Bulut</b></div>
      </div>
    </div>
</template>

<script>
import Avatar from '@/components/Avatar'


export default {
  name: 'ProfileBanner',
  components: {
    Avatar,

  }
}
</script>

<style scoped>
.profile-banner {
  display: flex;
  padding-left: 70px;
}
.info{
  margin-left: 70px;
}
.username {
  font-size: 25px;
}

.info-info{
  margin-top: 28px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.posts{
min-width: 85px;
}
.followers{
min-width: 85px;
}
.following{
margin-left: 30px;
}
.name{
  padding-top: 22px;
  font-size: 22px;
}
</style>