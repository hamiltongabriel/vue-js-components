<template>
  <label class="label">
    <input class="input" [checked]="checked" (change)="check($event.target.checked)" type="checkbox"/>
  </label>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
