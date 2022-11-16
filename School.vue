<template>
  <div>
    <h2>学校名称：{{name}}</h2>
    <h2>学校地址：{{address}}</h2>
    <button @click="showName">点我提示学校名</button>
  </div>
</template>

<script>
export default {
data() {
    return {
        name:'尚硅谷',
        address:'北京平昌'
    }
},
methods: {
    showName(){
        alert(this.showName)
    }
},
}
</script>

<style>

</style>