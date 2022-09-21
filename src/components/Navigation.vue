<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
            <RouterLink class="navbar-item" to="/">
                JOBS
            </RouterLink>

            <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false"
                data-target="navbarBasicExample">
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
                <span aria-hidden="true"></span>
            </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
            <div class="navbar-start">
                <RouterLink to="/" class="navbar-item">
                    Home
                </RouterLink>
                <RouterLink to="/vacancies" class="navbar-item">
                    Vacancies
                </RouterLink>
            </div>




            <div class="navbar-end">
                <div class="navbar-item">
                    <div class="buttons">
                        <RouterLink to="/posts" class="button is-primary">
                            <strong>Post</strong>
                        </RouterLink>
                        <a class="button is-light">
                            Log in
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>