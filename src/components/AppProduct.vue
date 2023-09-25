<script>
import product from './AppProducts.vue';
export default {

    name: 'AppProduct',

    data(){
        return{
            product //Single object
        }

    },

    props:{
        img:'String',
        price:'String',
        series:'String',
        category:'String'
    }
}
</script>

<template>
            <div class="col-2 mb-5">
                <div class="comic_img">
                    <img  :src="img" />
                </div>
                
                <h6 class="comic_text">{{ series }}</h6>
            </div>
</template>


<style lang="scss" scoped></style>