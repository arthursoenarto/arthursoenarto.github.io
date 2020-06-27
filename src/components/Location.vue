<template>
    <div class="location">
          <i class="fa fa-map-marker"></i>
          <p style="padding-left: 5px;">{{loc}}</p>
        </div>
</template>

<script>

export default {
  props: {
    loc: {
      type: String
    },
  },
}
</script>

<style>
.location{
  color: blue;
}
</style>