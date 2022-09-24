<template>
    <b-container fluid>
        <Header/>
        <postList/>
        
    </b-container>
</template>
<script>
import Header from '@/components/posts/Header'
import postList from '@/components/posts/postList'

export default {
    layout:"coreLayout",
    components:{
        Header,
        postList
    }
}
</script>