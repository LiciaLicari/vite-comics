<script>
export default {

    name: 'AppServices',

    data() {
        return {

            services: [
                {
                    pic: 'buy-comics-digital-comics.png',
                    name: 'DIGITAL COMICS',
                    link: ''

                },
                {
                    pic: 'buy-comics-merchandise.png',
                    name: 'DC MERCHANDISE',
                    link: ''

                },
                {
                    pic: 'buy-comics-subscriptions.png',
                    name: 'SUBSCRIPTIONS',
                    link: ''

                },
                {
                    pic: 'buy-comics-shop-locator.png',
                    name: 'COMIC SHOP LOCATOR',
                    link: ''

                },
                {
                    pic: 'buy-dc-power-visa.svg',
                    name: 'DC POWER VISA',
                    link: ''

                },

            ]
        }
    },
    methods: {
        getImagePath(img) {
            return new URL(`../assets/img/${img}`, import.meta.url).href;
        }
    }

}

</script>

<template>
    <section id="services">
        <div class="container ">

            <ul class="service d-flex justify-content-between mb-0 list-unstyled">
                <li v-for="service in services">
                    <a href="#" class="text-decoration-none"><img :src="getImagePath(service.pic)" :alt=service.name
                            class="service_pic">
                        <span class="service">{{ service.name }}</span></a>
                </li>
            </ul>


        </div>
    </section>
</template>


<style lang="scss" scoped></style>