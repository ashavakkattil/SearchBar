<template>
    <v-container>
        <AppHeader/>
        <search-bar></search-bar>
        <appFooter/>
    </v-container>
</template>
<script>
import AppHeader from '@/components/AppHeader'
import AppFooter from '@/components/AppFooter' 
import SearchBar from '@/components/SearchBar'

export default {
    components:{
        AppHeader,
        'search-bar': SearchBar,
        'appFooter': AppFooter
    }
}
</script>