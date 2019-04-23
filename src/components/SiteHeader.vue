<template>
  <div class="site-header">
    <div class="header-content">
      <h1>Joseph Sheraden</h1>
      <SiteNav/>
    </div>
  </div>
</template>

<style>
.site-header {
  width: 100%;
  margin: 0;
  padding: 0;
  color: #ffffff;
  background-color: #336699;
}

.header-content {
  font-size: 150%;
  padding: 50px 0;
}

.header-content h1 {
  margin-top: 0;
}
</style>

<script>
import SiteNav from '@/components/SiteNav'

export default {
  name: 'SiteHeader',
  components: { SiteNav }
}
</script>
