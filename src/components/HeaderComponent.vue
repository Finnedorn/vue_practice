<template>
    <header>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <!-- <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item" v-for="item in menu" :key="item.index">
                            <router-link class="nav-link" active-class="active" :to="{name: item.name}">{{item.label}}</router-link>
                        </li>
                    </ul> -->
                </div>
            </div>
        </nav>
    </header>
</template>

<script>

export default {
    name: "HeaderComponent",
    components: {
    },
    data() {
        return {
            menu: [
                {
                    label: "Home",
                    name: "home",
                },
                {
                    label: "Projects",
                    name: "projects",
                },
                {
                    label: "Contacts",
                    name: "contacts",
                }
            ]
        }
    },
};
</script>

<style lang="scss" scoped></style>