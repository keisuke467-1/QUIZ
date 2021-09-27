<template>
  <div>
    <div ref="ans" v-on:click="doAction">{{ ans }}</div>
    <p></p>
  </div>
</template>

<script>
export default {
  name: 'Ans',
  props: {
      ans: String,
  },
  methods: {
        doAction(){
            if (this.ans === "D:イーグル"){
            this.$refs.ans.innerHTML = "正解";
            }else if(this.ans !== "D:イーグル"){
                this.$refs.ans.innerHTML = "不正解"
            }
        }
    },
}
</script>