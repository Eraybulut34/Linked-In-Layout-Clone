<template>
  <Container>
    <ProfileBanner /> <br />
    <div class="nav">
      <router-link class="posts" to="/profile">Posts</router-link>
      <router-link class="igtv" to="/igtv">IGTV</router-link>
      <router-link class="save" to="/save">Save</router-link>
      <router-link class="tag" to="/tag">Tag</router-link>
    </div>
    
    <router-view />
 
  </Container>
</template>

<script>
import ProfileBanner from '@/components/ProfileBanner'
import Container from '@/components/Container'

export default {
  name: 'Profile',
  components: {
    ProfileBanner,
    Container
  }
}
</script>

<style scoped>
.home {
  min-width: 605px;
  margin-left: auto;
  margin-right: auto;

  @media (--t) {
    min-width: none;
    display: grid;
    grid-template-columns: 1fr 295px;
    grid-gap: 30px;
  }
}
.nav {
 display: flex;
  align-items: center;
  justify-content: space-around;
}
.contents{
  
}
</style>
