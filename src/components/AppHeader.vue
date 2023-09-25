<script>
export default {

    name: 'AppHeader',

    data() {


        return {

            activeLink: 0,

            navSelections: [
                {
                    name: 'CHARACTERS',
                    link: ''
                },
                {
                    name: 'COMICS',
                    link: ''
                },
                {
                    name: 'MOVIES',
                    link: ''
                },
                {
                    name: 'TV',
                    link: ''
                },
                {
                    name: 'GAMES',
                    link: ''
                },
                {
                    name: 'COLLECTIBLES',
                    link: ''
                },
                {
                    name: 'VIDEOS',
                    link: ''
                },
                {
                    name: 'FANS',
                    link: ''
                },
                {
                    name: 'NEWS',
                    link: ''
                },
                {
                    name: 'SHOP',
                    link: ''
                }
            ]
        }
    },
    methods: {
        activeClass(index) {
            this.activeLink = index
        }
    }




}
</script>


<template>
    <header id="app_header">
        <nav class="navbar navbar-expand-lg p-0">
            <div class="container d-flex justify-content-between">
                <img src="../assets/img/dc-logo.png" alt="" srcset="">
                <div class="navbar p-0" id="navbarNav">
                    <ul class="navbar-nav">
                        <li v-for="(selection, index) in navSelections" class="nav-item">
                            <a class="nav-link py-5" :class="index === activeLink ? 'cm_active' : ''"
                                @click="activeClass(index)" aria-current="page" href="#">{{ selection.name }}</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
</template>





<style lang="scss" scoped></style>