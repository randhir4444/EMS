<template>
    <v-bottom-navigation
    class="d-flex d-sm-none"
    :value="activeBtn"
    grow
    app
    shift
    color="black"
    >
        <v-btn router-link to="/">
        <span>Home</span>
        <v-icon>fa-home</v-icon>
        </v-btn>

        <v-btn router-link to="/allevents">
        <span>All Events</span>
        <v-icon>fa-calendar</v-icon>
        </v-btn>

        <v-btn router-link to="/addevent">
        <span>Add Event</span>
        <v-icon>fa-plus-square</v-icon>
        </v-btn>

        <v-btn router-link to="/organisers">
        <span>Organisers</span>
        <v-icon>fa-sitemap</v-icon>
        </v-btn>

        <v-btn router-link to="/signin">
        <span>SignIn</span>
        <v-icon>fa-sign-in</v-icon>
        </v-btn>
    </v-bottom-navigation>
</template>

<script>
export default {
    data () {
        return {
            activeBtn: 0,
        }
    }
};
</script>