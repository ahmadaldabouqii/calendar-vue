<template>
  <Header />
  <div class="w-full flex">
    <Calendar />
  </div>
</template>

<script>
import Header from './components/AppHeader';
import Calendar from './components/Calendar';

export default {
  name: 'App',
  components: { Header, Calendar },
};
</script>
