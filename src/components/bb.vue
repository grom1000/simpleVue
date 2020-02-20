<template>
  <div>
    <div>
    </div>
    <component-a message="message0000000000000"></component-a>
  </div>
</template>

<script>
import aa from './aa.vue'

export default {
  name: 'bb',
  data: function () {
    return {
      message: 'Hello'
    }
  },
  components: {
    'component-a': aa
  }
}
</script>