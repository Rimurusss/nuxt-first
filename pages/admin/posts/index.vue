<template>
     <b-container>
      
        <postList isAdmin/>
        
    </b-container>
</template>

<script>
import postList from '@/components/posts/postList'

export default {
    layout:"coreLayout",
    components:{
        postList
    }
}
</script>