<template>
  <div id="test">
      <button v-on:click= "aw">pencet saya</button>
  </div>
</template>
<script>
export default {
    
        methods: {
            aw : function(){
                console.log('aw bang jangan tekan saya')
                alert('malah di pencet')

        }

    }

    };
    
</script>

