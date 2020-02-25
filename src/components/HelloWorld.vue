<template>
  <div class="hello">
    <span>Enter the weight in kilograms:</span>
    <input v-model="someNum" type="number">
    <div>The weight in pounds is: {{ someNum * 2.20 }}</div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      someNum: "1"
    };
  }
};
</script>
