<template>
  <nav class="uk-navbar-container" uk-navbar>
    <div class="uk-navbar-left">

      <ul class="uk-navbar-nav">
        <li>
          <a href="#">WordPress</a>
          <div class="uk-navbar-dropdown">
            <ul class="uk-nav uk-navbar-dropdown-nav">
              <li class="uk-active">
                <n-link to="/wordpress/wp-schedule">WP Schedule</n-link>
              </li>
              <li>
                <n-link to="/wordpress/">Simplified WordPress</n-link>
              </li>
              <li><a href="#">Item</a></li>
            </ul>
          </div>
        </li>
        <li>
          <n-link to="/api/screengrab">URL Screen Grab</n-link>
        </li>
        <li>
          <n-link to="/api/image-optimizer">Image Optimizer</n-link>
        </li>
      </ul>

    </div>
  </nav>
</template>

<script>
  export default {
    name: "Navigation"
  }
</script>

<style scoped>

</style>
