<template>
  <div id="app">
    <section class="section">
      <div class="container">
        <h1 class="title has-text-centered mb-6">Weekly Calendar App</h1>
        <CalendarWeek />
        <CalendarEntry />
      </div>
    </section>
  </div>
</template>

<script>
import CalendarWeek from './app/components/CalendarWeek.vue';
import CalendarEntry from './app/components/CalendarEntry.vue';

export default {
  name: 'App',
  components: {
    CalendarWeek,
    CalendarEntry
  }
};
</script>
