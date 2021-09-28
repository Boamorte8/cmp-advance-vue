<template>
  <ul>
    <li v-for="goal in goals" :key="goal">
      <slot :item="goal" another-propt="..Test.."></slot>
    </li>
  </ul>
</template>

<script>
export default {
  data() {
    return {
      goals: [
          'Finish the course',
          'Learn Vue',
          'Improve my skills',
      ],
    }
  },
}
</script>