<template>
    <v-app>
        <app-navigation></app-navigation>
        <side-bar></side-bar>
        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
import SideBar from '@/components/SideBar';

export default {
    name: 'App',
    components: {
        AppNavigation,
        SideBar
    }
};
</script>

<style>
</style>