<template>
  <div></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import axios from '../utils/axios'

export default defineComponent({
  setup() {
    axios
      .get('/user/XPost')
      .then((res) => {
        console.log('res:', res)
      })
      .catch((err) => {
        console.log('err:', err)
      })
  }
})
</script>
<style lang="scss" scoped></style>
