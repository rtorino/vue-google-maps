<template>
  <input
    ref="input"
    v-bind="$attrs"
    v-on="$listeners"
    />
</template>

<script>
import autocompleteImpl from './autocompleteImpl'
export default (function (x) { return x.default || x })(autocompleteImpl)
</script>
