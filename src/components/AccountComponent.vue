<template>
    <div class="container">
        <form> <!-- if not logged in -->
            <input type="text" v-model="username" placeholder="username">
            <input type="password" v-model="password" placeholder="password">
            <button @click.prevent="handleLogin">login</button>
            <button @click.prevent="hanldeSignUp">sign up</button>
        </form>
    </div>
</template>

<script>

export default {
    data() {
        return {
            username: "",
            password: "",
        }
    },
    methods: {
        handleLogin() {
            return //TODO;
        }
    }
}

</script>

<style lang="scss">

form {
    height : 100%;
    display : flex;
    align-items : center;
    * {
        margin: 4px;
        padding: 2px;
    }
}

</style>