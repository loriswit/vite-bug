<template>
  <p>VITE_VAR: {{ viteVar }}</p>
  <p>VITE_EXPOSED: {{ viteExposed }}</p>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    viteVar: import.meta.env.VITE_VAR,
    viteExposed: import.meta.env.VITE_EXPOSED
  })
}
</script>
