<template>
  <sample-component>
    Hello Slot!
    <div slot="named">
      named slot
    </div>
    <div slot="named2">
      test
    </div>
  </sample-component>
</template>


<script>
import SampleComponent from '~/components/SampleComponent.vue'
export default {
  components: {
    SampleComponent
  },
  data() {
    return {
      indexTitle: 'nuxt.js data'
    }
  }
}
</script>
