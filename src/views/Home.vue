<template>
  <div>
    <the-header />
    <the-container />
    <the-footer />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue'
import TheContainer from '@/components/TheContainer.vue'
import TheFooter from '@/components/TheFooter.vue'

export default {
  name: 'Home',
  components: {
    TheHeader,
    TheContainer,
    TheFooter
  }
}
</script>
