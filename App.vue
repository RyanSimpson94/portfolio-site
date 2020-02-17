<template>
  <main id="app">
    <header-component></header-component>
    <nav class="navigation">
      <button>CV</button>
      <button>Contact</button>
    </nav>
  </main>
</template>

<script type="text/javascript">
  export default {
    name: 'App',
    components: {
      'header-component': () => import('./components/header')
    }
  }
</script>