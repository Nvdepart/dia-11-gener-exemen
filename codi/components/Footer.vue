<template>
    <v-card>
        <h2>Atlas-Expo</h2>
        <div>
            <v-btn v-for="(s, i) in sm" :key="i" icon>
                <v-icon >
                    {{ s.icon }}
                </v-icon>
            </v-btn>
        </div>
        <v-card-text></v-card-text>
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