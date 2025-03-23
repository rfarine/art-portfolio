<template>
    <header>
        <div class="nav">
            <router-link to="/">home</router-link>
            <router-link to="/about">about</router-link>
        </div>
    </header>

    <slot />
</template>

<style>
@import '~/assets/base.css';
</style>
