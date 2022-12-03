<template>
    <label class="item"><input type="checkbox" name="html" :value="value">
      <slot name="text"></slot>
    </label><br />
</template>

<script>
</script>

  <style scoped>
   .item{
    display: flex;
   }
  .check-text{
    margin-left: 5px;
  }

  </style>
  