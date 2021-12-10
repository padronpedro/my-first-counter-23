<template>
  <div class="counter">
    <button @click="counter++">Click me</button>
    {{ counter }}
  </div>
</template>

<script>
export default {
  data: () =>({
    counter: 0
  })
}
</script>
