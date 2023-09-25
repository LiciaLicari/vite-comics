<script>
export default {

    name: 'AppServices',

    data() {
        return {

            services: [
                {
                    pic: 'src/assets/img/buy-comics-digital-comics.png',
                    name: 'DIGITAL COMICS',
                    link: ''

                },
                {
                    pic: 'src/assets/img/buy-comics-merchandise.png',
                    name: 'DC MERCHANDISE',
                    link: ''

                },
                {
                    pic: 'src/assets/img/buy-comics-subscriptions.png',
                    name: 'SUBSCRIPTIONS',
                    link: ''

                },
                {
                    pic: 'src/assets/img/buy-comics-shop-locator.png',
                    name: 'COMIC SHOP LOCATOR',
                    link: ''

                },
                {
                    pic: 'src/assets/img/buy-dc-power-visa.svg',
                    name: 'DC POWER VISA',
                    link: ''

                },

            ]
        }
    }

}
</script>

<template>
    <section id="services">
        <div class="container ">

            <ul class="service d-flex justify-content-between mb-0 list-unstyled">
                <li v-for="service in services">
                    <a href="#" class="text-decoration-none"><img :src=service.pic alt={{service.name}} class="service_pic">
                    <span class="service">{{service.name}}</span></a>
                </li>
            </ul>


        </div>
    </section>
</template>


<style lang="scss" scoped></style>