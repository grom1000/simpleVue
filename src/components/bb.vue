<template>
  <div>
    <div>
      img="/img/cancun.jpg"
      imgAlt="Beach in Cancun"
      eyebrow="Private Villa"
      title="Relaxing All-Inclusive Resort in Cancun"
      pricing="$299 USD per night"
      url="/vacations/cancun"
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