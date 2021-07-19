<template>
    <div id="main"></div>    
</template>
<script>
import cesium from 'cesium'

export default {
    mounted() {
        var view = new cesium.Viewer("main", {
            
        })
        window.console.log(view)
    }
}
</script>
<style lang="less" scoped>

</style>



