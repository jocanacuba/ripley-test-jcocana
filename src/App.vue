<template>
    <v-app>
        <v-app-bar app>
            <v-toolbar-title class="headline text-uppercase">
                <span>RIPLEY</span>
                <span class="font-weight-light">TEST JCOCANA</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
        </v-app-bar>

        <v-content>
            <HelloWorld/>
        </v-content>
    </v-app>
</template>

<script>
    import HelloWorld from './components/HelloWorld';

    export default {
        name: 'App',
        components: {
            HelloWorld,
        },
        data: () => ({
            //
        }),
    };
</script>
