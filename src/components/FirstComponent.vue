<template>
  <div id="FirstComponent">
    {{myData}}
  </div>
</template>

<script>
export default {
  name: 'FirstComponent',
  data () {
    return {
      myData: 20
    }
  }
}
</script>
