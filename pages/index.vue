<template>
  <div>
    <NuxtLogo></NuxtLogo>
    <div>
      <form>
        <input type="text" :class="inputStyle">
        <button>Confirm</button>
      </form>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@nuxtjs/composition-api'
export default defineComponent({
  name: 'Home',
  setup() {
    return {
      inputStyle: 'outline-none ring-2 ring-red-400 focus:ring-blue-400 rounded-lg py-2 px-4'
    }
  }
})
</script>
