<template>
    <div class="user__wrap">
        <div class="user" v-for="user in users">
            <div class="user__img">
                <img :src="mainRoute + user.img" alt="">
            </div>
            <div class="user__info">
                <h3 class="user__info__name">{{user.name}}</h3>
                <p>{{user.position}}</p>
                <a :href="'mailto:' + user.mail"
                   rel="nofollow">{{user.mail}}</a>
                <a class="user__info__phone">{{user.phone}}</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Users",
        data() {
            return {
                mainRoute: 'http://45.j2landing.com/abz/',
                users: [
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-noah-2x.jpg',
                        name: 'Noah',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    },
                    {
                        img:'img/user-adolph-2x.png',
                        name: 'Adolph Blaine Charles David Earl',
                        position: 'Leading specialist of the Control Department',
                        mail: 'noah.controldepartment@gmail.com',
                        phone: '+38 (050) 678 03 24'
                    }
                ]
            }
        }
    }
</script>

<style scoped>

</style>