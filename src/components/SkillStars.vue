<template>
  <div class="skill-set">
              <span class="skill-title">{{skill}}</span>
              <span class="skill-score">
                <span v-for="i in 5" :key="i" class="far fa-star" :class="{fas: i <= stars}"></span>
              </span>
            </div>
</template>

<script>

export default {
  props: {
    stars: {
      type: Number
    },
    skill: {
      type: String
    }
  },
}
</script>

<style>
  .skill-set:hover{
    background: #c9c9c9;
  }
  .skill-score{
    float: right;
  }
</style>