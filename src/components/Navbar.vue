<template>
  <div class="hello">
 <nav>
    <div class="nav-wrapper ">
      <a href="#!" class="brand-logo center">Logo</a>
      <ul class="left hide-on-med-and-down">
         <router-link tag="li" to="/">
          <a href="">Home</a>
        </router-link>
        <router-link tag="li" to="/about">
       <a href="">About</a>
        </router-link>
      </ul>
    </div>
  </nav>

  </div>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style leng="scss">
</style>
