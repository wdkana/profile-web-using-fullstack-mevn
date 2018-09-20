<template>
    <b-navbar toggleable type="dark" style="background:#">
        <b-navbar-toggle target="nav_text_collapse"></b-navbar-toggle>
        <b-navbar-brand class="navtext"><h3><b-link to="/">Afrizaldea</b-link></h3></b-navbar-brand>
        <b-collapse is-nav id="nav_text_collapse">
            <b-navbar-nav>
                <b-nav-item href="#/apps" class="navtext"><h3>Portofolio</h3></b-nav-item>
                <b-nav-item href="#/blog" class="navtext"><h3>Blog</h3></b-nav-item>
                <b-nav-item href="#/contact" class="navtext"><h3>Contact</h3></b-nav-item>
                <b-nav-item href="#/resume" class="navtext"><h3>My Resume</h3></b-nav-item>
            </b-navbar-nav>
        </b-collapse>
    </b-navbar>
</template>

<script>
export default {

}
</script>

<style>
    .navtext{
        font-size: 32px
    }
</style>
