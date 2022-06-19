<script lang="ts">
  export let text: string
</script>

<h1>Hello <span>{text}!</span></h1>

<style lang="scss">
  h1 {
    color: red;

    span {
      color: blue;
    }
  }
</style>
