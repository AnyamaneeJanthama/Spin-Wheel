<template>
    <div>
        <nav class="navbar navbar-expand-sm bg-warning justify-content-center">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <router-link class="nav-link" :to="{ name: 'Home' }">Home</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'About' }">About</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'Login' }">Login</router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link" :to="{ name: 'Register' }">Register</router-link>
                </li>
            </ul>
        </nav>
        <router-view></router-view>
    </div>
</template>