<template>
  <div class="event-list">
    <h1>Event Listing</h1>
    <EventCard/>
  </div>
</template>

<script>
import EventCard from "@/components/EventCard.vue";

export default {
  name: "EventList",
  components: {
    EventCard
  }
};
</script>
<style scoped>
</style>
