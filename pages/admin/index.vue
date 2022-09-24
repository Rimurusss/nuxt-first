<template>
     <!-- <b-container>
        <postList isAdmin/>
    </b-container> -->
    <div class="my-2">
        <nuxt-link to="/admin/posts" class="btn btn-primary">ดูบทความ</nuxt-link>
        <nuxt-link to="/admin/posts/create" class="btn btn-success">เขียนบทความ</nuxt-link>
    </div>
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