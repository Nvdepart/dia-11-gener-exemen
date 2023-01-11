<template>
    <v-card class="md-h5 font-weight-bold" align="center">
        
        <div >
            <h2>Atlas-Expo</h2>
            <v-btn v-for="(s, i) in sm" :key="i" icon>
                <v-icon size="30">
                    {{ s.icon }}
                </v-icon>
            </v-btn>
        </div>
        <v-card-text >
            &copy; {{ new Date().getFullYear() }}
        </v-card-text>
    </v-card>
</template>

<script>
export default {
  data(){
    return {
        sm:[
            {icon:'mdi-facebook', link:'https://www.facebook.com'},
            {icon:'mdi-twitter', link:'https://www.twitter.com'},
            {icon:'mdi-instagram', link:'https://www.instagram.com'},
            {icon:'mdi-youtube', link:'https://www.youtube.com'},
        ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>