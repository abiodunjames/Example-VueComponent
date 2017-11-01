<template>
    <div id="app">
        <navbar-component></navbar-component>
        <section class="container">
            <page-heading-component></page-heading-component>
            <staff-list-component></staff-list-component>
        </section>
    </div>
</template>

<script>
    import PageHeadingComponent from './PageHeadingComponent.vue'
    import StaffListComponent from './StaffListComponent.vue'
    import NavbarComponent from './NavbarComponent.vue'
    export default {
        name: 'app',
        components: {NavbarComponent, PageHeadingComponent, StaffListComponent}
    }
</script>

<style>
</style>
