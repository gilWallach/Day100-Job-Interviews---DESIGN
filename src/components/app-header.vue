<template>
    <section class='app-header'>
        <header class="flex justify-between">
            <div class="logo">
                <logo />
            </div>
            <nav class="flex align-center">
                <ul>
                    <li class="nav-link">
                        <RouterLink to="/">Features</RouterLink>
                    </li>
                    <li class="nav-link">
                        <RouterLink to="/about">Team</RouterLink>
                    </li>
                    <li class="nav-link">
                        <RouterLink to="/about">Sign In</RouterLink>
                    </li>
                </ul>
            </nav>
        </header>
    </section>
</template>
<script>
import logo from '../assets/svg/logo.vue'
export default {
    name: 'app-header',
    props: {},
    data() {
        return {}
    },
    created() { },
    methods: {},
    computed: {},
    components: {
        logo,
    }
}
</script>