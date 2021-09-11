<template>
  <div>
    {{ message }}

    <button
      class="
        py-3
        px-4
        bg-red-600
        rounded-3xl
        hover:bg-yellow-700
        cursor-pointer
        my-button
      "
      @click="greeting"
    >
      Greeting
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'hello',
      title: 'boom',
      form: {
        email: '',
      },
    }
  },

  methods: {
    greeting() {
      alert('hello')
    },
  },
}
</script>


<style>
.my-button {
  background-color: chartreuse;
}
.my-button:hover {
  background-color: indigo;
}
</style>