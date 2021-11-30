<template>
  <div class="home">
  
    <div class="identity"><br>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
      tempore, minima eligendi minus animi voluptate, incidunt exercitationem
      inventore facilis eos rem nisi dicta possimus alias obcaecati explicabo
      adipisci unde corrupti! Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Ipsa autem ut ab reprehenderit earum amet deserunt nemo natus eum
      atque minima in magni iste placeat, eaque eligendi animi fuga officia nisi
    
      provident atque recusandae porro, quas obcaecati asperiores doloremque
      distinctio voluptas iure! Nostrum debitis eligendi necessitatibus
      praesentium iusto minus incidunt eum repudiandae repellendus? Corrupti
      eligendi est laborum quasi et explicabo ex suscipit rem sed voluptatem
      maiores, iste officia itaque officiis dicta, impedit, sequi quo tenetur
      excepturi molestiae iure blanditiis?
    </div>
        <div class="timeline"><br>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
      tempore, minima eligendi minus animi voluptate, incidunt exercitationem
      inventore facilis eos rem nisi dicta possimus alias obcaecati explicabo
      adipisci unde corrupti! Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Ipsa autem ut ab reprehenderit earum amet deserunt nemo natus eum
      atque minima in magni iste placeat, eaque eligendi animi fuga officia nisi
    
      provident atque recusandae porro, quas obcaecati asperiores doloremque
      distinctio voluptas iure! Nostrum debitis eligendi necessitatibus
      praesentium iusto minus incidunt eum repudiandae repellendus? Corrupti
      eligendi est laborum quasi et explicabo ex suscipit rem sed voluptatem
      maiores, iste officia itaque officiis dicta, impedit, sequi quo tenetur
      excepturi molestiae iure blanditiis?
    </div>
        <div class="sidebar"><br>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate
      tempore, minima eligendi minus animi voluptate, incidunt exercitationem
      inventore facilis eos rem nisi dicta possimus alias obcaecati explicabo
      adipisci unde corrupti! Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Ipsa autem ut ab reprehenderit earum amet deserunt nemo natus eum
      atque minima in magni iste placeat, eaque eligendi animi fuga officia nisi
    
      provident atque recusandae porro, quas obcaecati asperiores doloremque
      distinctio voluptas iure! Nostrum debitis eligendi necessitatibus
      praesentium iusto minus incidunt eum repudiandae repellendus? Corrupti
      eligendi est laborum quasi et explicabo ex suscipit rem sed voluptatem
      maiores, iste officia itaque officiis dicta, impedit, sequi quo tenetur
      excepturi molestiae iure blanditiis?
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

  @media (--t) {
    min-width: none;
    display: grid;
    grid-template-columns: 225px 540px 315px;
    grid-gap: 30px;
  }
}
.identity{
background-color: #fff;
border-radius: 15px;
}
.timeline{
background-color: #fff;
border-radius: 15px;
}
.sidebar {
background-color: #fff;
border-radius: 15px;
}
</style>
