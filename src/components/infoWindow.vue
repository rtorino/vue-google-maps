/* vim: set softtabstop=2 shiftwidth=2 expandtab : */

<template>
  <div>
    <div ref="flyaway"> <!-- so named because it will fly away to another component -->
      <slot>
      </slot>
    </div>
  </div>
</template>

<script>
import infoWindowImpl from './infoWindowImpl'
export default (function (x) { return x.default || x })(infoWindowImpl)
</script>
