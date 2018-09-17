<template>
  <div>
    <div v-for="(task, key) in tasks" :key="key">
        <input type="checkbox"
        :checked="task.done"
        />
        <div>
          {{task.title}}
        </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    tasks: [
      {id: 1, title: 'Task 1', done: false},
      {id: 12, title: 'Task 2', done: true},
    ]
  })
}
</script>

<style lang="css">
</style>
