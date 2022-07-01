<template>
  <footer style="margin: 25px auto; text-align: center; float: center">
    <p>Copyright <a href="#" style="color: #355E3B;">Odin Love</a> &copy; {{ year }}</p>
  </footer>
</template>
<script>
import { computed } from 'vue'
export default {
  setup () {
    const year = computed(() => new Date().getFullYear())
    return { year }
  }
}
</script>
