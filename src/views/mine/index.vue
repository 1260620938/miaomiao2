<template>
    <div id="main">
        <Header title="我的喵喵"></Header>
        <div id="content">
            <login />
        </div>
        <Footer></Footer>
    </div>
</template>

<script>

import Header from '@/components/Header'
import Footer from '@/components/TabBar'
import login from '@/components/login'

export default {
    name:'mine',
    components:{
        Header,
        Footer,
        login
    }
}
</script>

<style>

</style>
