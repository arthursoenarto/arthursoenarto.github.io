<template>
  <div class="about">
    <h1>This is an about page</h1>
    <skill-stars skill="Python" stars="4"></skill-stars>
    <skill-stars skill="Javascript" stars="1"></skill-stars>
    <skill-stars skill="Node" stars="3"></skill-stars>
    <skill-stars skill="Math" stars="5"></skill-stars>
  </div>
</template>

<script>
import SkillStars from "../components/SkillStars"
export default {
  components: {
    SkillStars,
  },
}
</script>
