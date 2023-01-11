<template>
    <div>
            <h1>Je suis la barre de menu</h1>
            <v-app-bar
                    :clipped-left="clipped"
                    fixed
                    app
            >
            <v-toolbar-title>
                Atlas-Expo
            </v-toolbar-title>
            <v-spacer />
            <v-btn icon>
            <v-icon>mdi-home</v-icon>
            </v-btn>
            <v-btn icon>
                <v-icon>mdi-account-box-outline</v-icon>
            </v-btn>

            </v-app-bar>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>