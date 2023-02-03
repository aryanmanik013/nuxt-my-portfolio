<template>
  <div>
    <b-navbar type="dark" variant="dark" class="changeNav">
      <b-navbar-nav>
         <b-nav-item>
            <NuxtLink to="/">Home</NuxtLink>
        </b-nav-item>
        <b-nav-item>
            <NuxtLink to="/">Work</NuxtLink>
        </b-nav-item>

        <b-nav-item>
            <NuxtLink to="/aboutus">About Us</NuxtLink>

        </b-nav-item>
        <b-nav-item>
            <NuxtLink to="/">Contact Us</NuxtLink>

        </b-nav-item>
      </b-navbar-nav>

      <div class="ml-auto">
        <b-navbar-nav>
          <b-nav-item>Contact</b-nav-item>
        </b-navbar-nav>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",
};
</script>
<style scoped>
/deep/.nav-link a{
  color: white !important;
}
</style>
