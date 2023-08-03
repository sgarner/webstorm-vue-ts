<template>
  <div>
    <script src="https://example.com" />
    {{ foo }}
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  methods: {
    foo(bar: string) {
      return bar;
    }
  }
})
</script>
