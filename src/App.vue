<template>
  <Header />
  <div class="text-center m-20">
    <router-view />
  </div>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header,
  },
}
</script>
