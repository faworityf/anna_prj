<template>
    <div class="relationships">
        <div class="relationships__block" v-for="about in abouts">
            <img :src="mainRoute + about.img" alt="">
            <div>
                <h3>{{about.title}}</h3>
                <p>{{about.text}}</p>
            </div>
        </div>

    </div>
</template>


<script>
    export default {
        name: "About",
        data() {
            return {
                mainRoute: 'http://45.j2landing.com/abz/',
                abouts: [
                    {
                        img:'img/css.svg',
                        title: 'CSS is my best friend<',
                        text: 'Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web\n' +
                            '                    applications.'
                    },
                    {
                        img:'img/html.svg',
                        title: 'I\'m in love with HTML',
                        text: 'Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web\n' +
                            '                    applications.'
                    },
                    {
                        img:'img/javascript.svg',
                        title: 'JavaScript is my passion',
                        text: 'Hypertext Markup Language (HTML) is the standard markup language for creating web pages and web\n' +
                            '                    applications.'
                    }
                ]
            }
        }

    }
</script>

<style scoped>

</style>