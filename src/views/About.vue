<template>
  <div class="about">
    <h1>This is an about page</h1>
    {{ test }}
    <card></card>
  </div>
</template>

<script>
import card from '@/components/Card.vue'
export default {
  components: {
    card
  },
  data () {
    return {
      test: 1
    }
  }

}
</script>
