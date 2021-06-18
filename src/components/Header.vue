<template>
  <div class="container py-4">
    <div>
      <h1 class="title">
        <a href="/">Anthony Gilbert</a>
      </h1>
      <hr />
      <div class="links">
        <router-link to="/projects" rel="noopener noreferrer" class="button--green">Projects</router-link>
        <!-- <a href="/blog" rel="noopener noreferrer" class="button--green">
          Blog
        </a> -->

        <!-- <router-link to="/projects" rel="noopener noreferrer" class="button--green">Projects Router Link</router-link> -->
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'App',
  components: {},
}
</script>

<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
a {
  color: rgb(87, 189, 109);
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 2.25rem;
  color: rgb(87, 189, 109) !important;
  letter-spacing: 1px;
}
.links {
  padding-top: 15px;
}
.container {
  margin: 0 auto;
  min-height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid rgb(87, 189, 109);
  color: rgb(87, 189, 109);
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}
</style>
