<script setup lang="ts"></script>

<template>
    <header>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
                <NuxtLink class="navbar-brand" to="/">Navbar</NuxtLink>
                <button
                    class="navbar-toggler"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup"
                    aria-controls="navbarNavAltMarkup"
                    aria-expanded="false"
                    aria-label="Toggle navigation"
                >
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <NuxtLink
                            class="nav-link active"
                            aria-current="page"
                            to="/"
                            >Home
                        </NuxtLink>
                        <NuxtLink class="nav-link" to="/room">Room</NuxtLink>
                        <a class="nav-link" href="#">Pricing</a>
                        <a class="nav-link disabled" aria-disabled="true"
                            >Disabled</a
                        >
                    </div>
                </div>
            </div>
        </nav>
    </header>
    <main>
        <slot />
    </main>
</template>

<style scoped></style>
