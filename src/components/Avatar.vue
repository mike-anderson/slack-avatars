<template>
  <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 viewBox="-955 -219 1000 1000" style="enable-background:new -955 -219 1000 1000;" xml:space="preserve">
    <g>
      <g id="color_x5F_bg">
        <path :fill="colors.st0" d="M-454.8,781L-454.8,781c-275,0-500-225-500-500l0,0c0-275,225-500,500-500l0,0c275,0,500,225,500,500l0,0
          C45.2,556-179.8,781-454.8,781z"/>
      </g>
      <ComponentLink :data="colors" :type="'hair/bg/' + hair" />
      <ComponentLink :data="colors" :type="'head/' + head" />
      <ComponentLink :data="colors" :type="'eyes/' + eyes" />
      <ComponentLink :data="colors" :type="'mouth/' + mouth" />
      <ComponentLink :data="colors" :type="'nose/' + nose" />
      <ComponentLink :data="colors" :type="'hair/fg/' + hair" />
    </g>
  </svg>
</template>

<script>
  import ComponentLink from './ComponentLink';

  export default {
    name: 'Avatar',
    props: {

    },
    components: {
      ComponentLink
    },
    data () {
      return {
        head:   '',
        hair:   '',
        eyes:   '',
        mouth:  '',
        nose:   '',
        colors: {
          st0: "#57AD57",
          st1: "#2A5083",
          st2: "#FFE1A4",
          st3: "#F4C37D",
        },
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .st0{fill:#57AD57;}
  .st1{fill:#2A5083;}
  .st2{fill:#FFE1A4;}
  .st3{fill:#F4C37D;}
</style>
