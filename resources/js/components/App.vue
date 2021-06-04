<template>
  <div>
    <h1>Привет</h1>
    <h3>Меня зовут Адам. Ниже есть крутая фотка</h3>
    <img :src="'avatar.png'" />
  </div>
</template>

<script>
  export default {
    mounted() {
      console.log('Привет еще раз!')
    }
  }
</script>
