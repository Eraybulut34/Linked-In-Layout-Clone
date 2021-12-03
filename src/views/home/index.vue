<template>
  <div class="home">
    <div class="identity">
      <div class="feed-identity-module">
        <img
          src="https://media-exp1.licdn.com/dms/image/C4E16AQG7jEhbbJ_Vww/profile-displaybackgroundimage-shrink_200_800/0/1630768785648?e=1643846400&v=beta&t=cmDcbyJbGgWvTyX-io8-zGX_CPL-cFbk8Ph1uisZbFs"
          alt=""
        />
      </div>
      <div class="community-module"></div>
    </div>
    <div class="timeline">
      <div class="entry-module"></div>
      <div class="post"></div>
    </div>
    <div class="sidebar">
      <div class="feed-follows"></div>
      <div class="ad-banner"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {}
}
</script>

<style scoped>
.home {
  min-width: 605px;
  margin-left: auto;
  margin-right: auto;
  padding-top: 80px;
  min-width: none;
  display: grid;
  grid-template-columns: 225px 540px 315px;
  grid-gap: 30px;
}
.identity {
  border-radius: 15px;
}
.timeline {
  border-radius: 15px;
}
.sidebar {
  border-radius: 15px;
}

.feed-identity-module {
  background-color: rgb(255, 255, 255);
  border-radius: 15px;
  width: 225px;
  height: 373px;
}
.community-module {
  background-color: rgb(216, 43, 43);
  border-radius: 15px;
  width: 225px;
  height: 133px;
  margin-top: 30px;
}
.entry-module {
  background-color: rgb(216, 43, 43);
  border-radius: 15px;
  height: 116px;
}

.post {
  background-color: rgb(216, 43, 43);
  border-radius: 15px;
  height: 947px;
  margin-top: 30px;
}
.feed-follows {
  background-color: rgb(216, 43, 43);
  border-radius: 15px;
  height: 373px;
}
.ad-banner {
  background-color: rgb(216, 43, 43);
  border-radius: 15px;
  height: 250px;
  margin-top: 30px;
}
</style>
