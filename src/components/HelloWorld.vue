<template>
  <div class="hello">
    <h1>{{ msgFromClassToImport }}</h1>
    
  </div>
</template>

<script>
import MyClassToImport from '../class/MyClassToImport.js';
export default {
  name: 'HelloWorld',
  data: function () {
	return {
      msgFromClassToImport: MyClassToImport.getMessage()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
