<template>
    
    <div>
        <b-carousel id="slider"
        :interval="4000"
        controls
        indicatora
        >
        <div v-for="item in items">
            <b-carousel-slide
                :caption="item.caption"
                :text="item.text"
                :img-src="item.image"
            ></b-carousel-slide>
        </div>
        </b-carousel>
    </div>
</template>
<script>
export default {
    data() {
        return{
            items:[
                {caption:"A",image:require("@/assets/image/p11.jpeg"),text:"Some quick example text to build on the card title and make up the bulk of the card's content."},
                {caption:"B",image:require("@/assets/image/p22.jpeg"),text:"Some quick example text to build on the card title and make up the bulk of the card's content."},
                {caption:"C",image:require("@/assets/image/p33.jpeg"),text:"Some quick example text to build on the card title and make up the bulk of the card's content."},
            ]
        }
    },
}
</script>

