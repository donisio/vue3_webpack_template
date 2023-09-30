<template>
    <h1>{{ message }}</h1>
    <HelloWorld></HelloWorld>
</template>

<script>
import HelloWorld from '~/components/HelloWorld';
export default{
    components:{
        HelloWorld
    },
    data() {
        return {
            message: 'Hello vue3!!'
        };
    },
    components: { HelloWorld }
}
</script>