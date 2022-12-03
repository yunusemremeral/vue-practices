<template>
    <button class="item">
      <slot name="text"></slot>
    </button>
</template>

<script>
</script>

<style scoped>
.item{
  display: flex;
  height: 40px;
  width: 100px;
  align-self: flex-end;
  justify-content: center;
  align-items: center;
  background: #E81932;
  border: none;
  border-radius: 5%;
  color: white;
}


</style>
  