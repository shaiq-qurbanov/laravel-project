<template>
    <div>hello test</div>
    <div class="show">{{ show }}</div>
</template>
<script>
import {ref} from 'vue'
export default {
    name:'Test',
    setup(){
       const show =ref('zzzzzzzzzz')


    }
}
</script>
<style scoped>

</style>
