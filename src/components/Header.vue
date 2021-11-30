<template>
  <header class="header">
    <Container class="header-inner">
   <router-link to="/" class="logo"> <IconGlobal/> </router-link>
      <form class="search">
        <input type="text" placeholder="Search" class="search" />
      </form>
      <nav class="navigation">
        <router-link to="/" class="home-icon">
          <IconHome/>
        </router-link>
        <router-link to="/direct" class="network-icon">
          <IconNetwork/>
        </router-link>
        <router-link to="/explore" class="jobs-icon">
          <IconJobs/>
        </router-link>
        <router-link to="/profile"><IconMessaging/></router-link>
        <router-link to="/profile"><IconNotifications/></router-link>
      </nav>
    </Container>
  </header>
</template>

<script>
import IconGlobal from '@/icons/global.svg'
import IconHome from '@/icons/home.svg'
import IconJobs from '@/icons/jobs.svg'
import IconMessaging from '@/icons/messaging.svg'
import IconNetwork from '@/icons/network.svg'
import IconNotifications from '@/icons/notifications.svg'

export default {
  name: 'MainHeader',
  components: {
    IconHome,
    IconGlobal,
    IconJobs,
    IconMessaging,
    IconNotifications,
    IconNetwork
  }
}
</script>

<style scoped>
.header {
  border-bottom: 1px solid rgb(var(--b6a));
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  border-bottom: 1px solid rgb(var(--b6a));
  background-color: white;
}
.header-inner {
height: var(--header-height);
  display: flex;
  align-items: center;
  @media (--t) {
    grid-template-columns: 1fr 1fr 1fr;

    height: 53px;
  }
}
.logo {
  font-weight: bold;
  padding-left: 76px;
  margin-top: 1px;

  color: rgb(31, 93, 173);
}
.search {
  display: none;

    display: block;
    text-align: center;

   
}
 input {
      border: 2px solid rgb(var(--b6a));
      border-radius: 5px;
      background-color: rgb(var(--b3f));
      margin-left: 5px;
      height: 32px;
      margin-bottom: 2px;
      background-color: rgb(240, 242, 247);
      width: 280px;


  }

.navigation {
  z-index: 90;
  position: fixed;
  padding-left: 155px;
  right: 0;
  bottom: 0;
  background-color: white;
  border-top: 1px solid rgb(var(--b6a));
  height: 80px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
  align-items: center;
  justify-content: center;
  margin-top: 3px;
  width: 400px;
  
  @media (--t) {
    height: auto;
    border: 0;
    position: static;
    justify-content: flex-end;
  
  }
}
.left{

}
</style>