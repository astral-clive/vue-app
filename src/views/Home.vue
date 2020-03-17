<template>
  <div class="home">
    <h1>Home View</h1>
    <EventCard msg="Rotenburg Museum" />
    <EventCard msg="Amsterdam Museum" />
    <EventCard msg="National Library" />
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from '@/components/EventCard.vue'

export default {
  name: 'Home',
  components: {
    EventCard
  }
}
</script>
