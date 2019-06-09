<template>
    <div>
        <nav class="navbar navbar-expand-lg">
            <span class="navbar-brand mb-0 h1">
                <font-awesome-icon :icon="['fas', 'clipboard-list']"></font-awesome-icon>
                Community Notice Board
            </span>
            <div class="collapse navbar-collapse navbar-light">
                <ul class="ml-auto p-2 navbar-nav">
                    <li class="nav-item active">
                        <router-link class="nav-link" to="/">Home<span class="sr-only">(current)</span></router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/profile">Profile</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/subscriptions">Subscriptions</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/register">Register</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/login">Login</router-link>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "NavBar"
}
</script>

<style>
#nav{
    color: #003249;
}

#nav a.router-link-exact-active {
  color: #E9724C;
}
</style>