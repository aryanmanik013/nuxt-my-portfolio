<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark" class="changeNav">
      <b-navbar-brand></b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar type="dark" variant="dark" class="changeNav">
          <b-navbar-nav>
            <b-nav-item>
              <NuxtLink to="/">Home</NuxtLink>
            </b-nav-item>
            <b-nav-item>
              <NuxtLink to="/work">Work</NuxtLink>
            </b-nav-item>

            <b-nav-item>
              <NuxtLink to="/aboutus">About Us</NuxtLink>
            </b-nav-item>
            <b-nav-item>
              <NuxtLink to="/contactus">Contact Us</NuxtLink>
            </b-nav-item>
          </b-navbar-nav>
        </b-navbar>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NuxtTutorial",
};
</script>
<style scoped>
/deep/.nav-link a {
  color: white !important;
}
</style>
