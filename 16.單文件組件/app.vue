<template>
  <div>
    <school></school>
    <student></student>
  </div>
</template>

<script setup lang="ts">
import school from './school.vue';
import student from './student.vue';
export default {
  name: 'APP',
  components: {
    school,
    student,
  },
};
</script>
