<template>
    <b-row class="py-2">
            <PostContent title="test A" image="https://cdn.pixabay.com/photo/2018/08/12/16/59/parrot-3601194_1280.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="1"
            :isAdmin=isAdmin
            />
            <PostContent title="test A" image="https://cdn.pixabay.com/photo/2012/06/19/10/32/owl-50267__340.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="2"
            :isAdmin=isAdmin
            />
            <PostContent  image="https://cdn.pixabay.com/photo/2016/11/14/04/45/elephant-1822636__340.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="3"
            :isAdmin=isAdmin
            />
            <PostContent title="asdasd" image="https://cdn.pixabay.com/photo/2017/02/20/18/03/cat-2083492__340.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="4"
            :isAdmin=isAdmin
            />
            <PostContent title="test A" image="https://cdn.pixabay.com/photo/2017/01/14/12/59/iceland-1979445__340.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="5"
            :isAdmin=isAdmin
            />
            <PostContent title="test A" image="https://cdn.pixabay.com/photo/2015/11/16/14/43/cat-1045782__340.jpg"
            content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. "
            id="6"
            :isAdmin=isAdmin
            />
            </b-row>
</template>
<script>
import PostContent from '@/components/posts/PostContent'

export default {
    components:{
        PostContent
    },
    props:{
        isAdmin:{
            type:Boolean,
            required:false
        }
    }
}
</script>