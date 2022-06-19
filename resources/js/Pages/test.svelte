<script lang="ts">
  export let text: string
</script>

<div>
  <h1 class="text-red-500">Hello <span class="text-blue-500">{text}!</span></h1>

  <div class="example">
    <p>some text here</p>
  </div>
</div>

<style lang="scss">
  .example {
    p {
      color: green;
    }
  }
</style>
