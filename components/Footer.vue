<template>
    <div class="container">
        <div class="lists-wrapper d-flex">
            <div class="footer-list">
            <div class="footer-list-title">
                <h4>About Us</h4>
            </div>
            <div class="footer-list-body">
                <ul>
                    <li>
                        <a href="#">Support Center</a>
                    </li>
                    <li>
                        <a href="#">Customer Support</a>
                    </li>
                    <li>
                        <a href="#">About Us</a>
                    </li>
                    <li>
                        <a href="#">Copyright</a>
                    </li>
                    <li>
                        <a href="#">Popular Campaign</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="footer-list">
            <div class="footer-list-title">
                <h4>Our Information</h4>
            </div>
            <div class="footer-list-body">
                <ul>
                    <li>
                        <a href="#">Return Policy </a>
                    </li>
                    <li>
                        <a href="#">Privacy Policy</a>
                    </li>
                    <li>
                        <a href="#">Terms & Conditions</a>
                    </li>
                    <li>
                        <a href="#">Site Map</a>
                    </li>
                    <li>
                        <a href="#">Store Hours</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="footer-list">
            <div class="footer-list-title">
                <h4>My Account</h4>
            </div>
            <div class="footer-list-body">
                <ul>
                    <li>
                        <a href="#">Press inquiries</a>
                    </li>
                    <li>
                        <a href="#">Permissions</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="footer-list">
            <div class="footer-list-title">
                <h4>Policy</h4>
            </div>
            <div class="footer-list-body">
                <ul>
                    <li>
                        <a href="#">Application security</a>
                    </li>
                    <li>
                        <a href="#">Software principles</a>
                    </li>
                    <li>
                        <a href="#">Unwanted software policy</a>
                    </li>
                    <li>
                        <a href="#">Responsible supply chain</a>
                    </li>
                </ul>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Footer",
    data() {
        return {
            message: "Привет, Nuxt 222!"
        };
    }
};
</script>

<style lang="scss" scoped>
body {
    margin: 0;
    padding: 0;
}
a {
    text-decoration: none;
}
h1 {
    color: #2c3e50;
}
ul {
    li {
        list-style-type: none;
    }
}
</style>