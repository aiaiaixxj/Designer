<template>
    <div id="smartTown">
        智能小镇管理系统
        <!-- <span ref='countup'></span> -->
         <Count-up :start="2020" :duration="3"></Count-up>
    </div>
</template>
<script>
import {CountUp} from 'countup.js'
export default {
    name: 'smartTown',
    data(){
        return{
              numAnim:null
        }
    }
}
</script>
<style scoped>

</style>

