<template>
    <ul class="nav-list">
        <li class="nav-item"><a href="/">Home</a></li>
        <li class="nav-item"><a href="/about_us/whybizzcon">About</a></li>
        <!-- <li class="nav-item"><a href="/about_us/leaders">Our Team</a></li> -->
        <li class="nav-item"><a href="/services">Services</a></li>
        <li class="nav-item"><a href="/industries">Industrial Practices</a></li>
        <li class="nav-item"><a href="/jobs/search">Find Talent</a></li>
        <li class="nav-item"><a href="/jobs/post"> Find a Job</a></li>
        <li class="nav-item"><a href="/insights">Insights</a></li>
        <li class="nav-item"><a href="/contact_us">Contact Us</a></li>
        <!-- <li class="nav-item"><a href="/login">Emp. Log</a></li> -->
 </ul>
</template>
<style scoped>
    .nav-list {
        list-style: none;
        padding: 0;
        margin: 0;
    }
    .nav-item {
        margin: 0 10px;
    }
    .nav-item a {
        
        text-decoration: none;
        color: rgba(255,181,17,255);
    }
    .nav-item a:hover,
    .nav-item a:active{
        color: #b4b4b4;
    }
    @media (max-width: 1250px) {
        .nav-list {
            display: block;
        }
        .nav-item{
            margin-top: 16px;
            margin-bottom: 16px;
        }
    }
    @media (min-width: 1250px) {
        .nav-list {
            display: flex;
        }
    }
</style>