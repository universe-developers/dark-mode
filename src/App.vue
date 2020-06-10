<template>
    <v-app>
        <app-bar></app-bar>
        <v-content>
            <v-container>
                <HelloWorld/>
            </v-container>
        </v-content>
    </v-app>
</template>

<script>
    import HelloWorld from './components/HelloWorld';
    import AppBar from "./components/shared/Navbar";

    export default {
        name: 'App',
        components: {
            AppBar,
            HelloWorld,
        },
        data: () => ({
            //
        }),
    };
</script>
