<template>
    <header class="header">
        <div class="container text-center d-flex w-100">
            <div class="logo">
                <img src="../assets/logo.svg" alt="">
            </div>
            <div class="menu">
                <ul>
                    <li>
                        <p>Home</p>
                    </li>
                    <li>
                        <p>Adversite</p>
                    </li>
                    <li>
                        <p>Supports</p>
                    </li>
                    <li>
                        <p>Contact</p>
                    </li>
                </ul>
            </div>
            <div class="buttons">
                <button>
                    <span>Get started</span>
                </button>
            </div>
        </div>    
    </header>
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            message: "Привет, Nuxt 222!"
        };
    },
    props: ['emptyBackground']
};
</script>

<style lang="scss" scoped>
header {
    padding: 20px 0;
    height: 90px;
    display: flex;
    align-items: center;
    z-index: 100;
    position: relative;
    .container {
        justify-content: space-between;
        .logo {
            border: 1px solid green;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .menu {
            border: 1px solid red;
            display: flex;
            align-items: center;
            justify-content: center;
            ul {
                border: 1px solid blue;
                gap: 20px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
        }
    }
}
</style>