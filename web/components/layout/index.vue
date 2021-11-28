<template>
    <div class="container">
        <Header/>
        <div class="layout">layout</div>
        <Footer/>
    </div>
</template>
<script lang="ts">
    import Header from '../header/index.vue'
    import Footer from '../footer/index.vue'
    export default {
        components:{
            Header,
            Footer
        },
        data(){
            return {}
        }
    }
</script>
