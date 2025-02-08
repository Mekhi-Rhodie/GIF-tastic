<template>
    <header class="container rounded">
        <span class="row">
            <h1 class="display-1">GIF-tastic!</h1>
            <span class="auth-button-group">
                <button class="auth-btn btn btn-primary">Login</button>
                <button class="auth-btn btn btn-secondary">Register</button>
            </span>
        </span>
    </header>
</template>

<style scoped>
    header {
        background-image: linear-gradient(to left,#00E682, #0D6EFD, #7B11D8);
        border: 2px solid #131416;
    }
</style>

<script>
    export default {
        data () {
            return {

            }
        }
    }
</script>