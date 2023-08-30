<template>
    <div class="HeaderBox">
        <div class="Logo">
            <img src="../assets/vue.svg" alt="" id="Logo">
        </div>
        <div class="AccountComponent">
            <AccountComponent></AccountComponent>
        </div>
    </div>
</template>

<script>

import AccountComponent from './AccountComponent.vue';

export default {
    data() {
        return {

        }
    },
    methods: {

    },
    computed: {

    },
    components: {
        AccountComponent,
    },
}

</script>

<style lang="scss" scoped>

.HeaderBox {
    background-color: #DDD;
    border-radius: 30px;
    padding: 0 20px;
    width: calc(100% - 40px);
    height: 60px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    .Logo {
        min-width : 60px;
        #Logo {
            object-fit : cover;
            height: 100%;
            width: 100%;
        }
    }
    .AccountComponent {
        min-width : 60px;
    }
}

</style>