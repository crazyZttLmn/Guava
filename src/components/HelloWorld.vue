<template>
<div class="">
  <slot name="header"></slot>
  <com-header></com-header>
</div>
</template>

<script>
import ComHeader from "@/components/Header.vue"
export default {
  methods: {
    onSubmit() {
      console.log('submit!');
    }
  },
  components: {
    ComHeader
  }
}
</script>
