<template>
    <nav class="sticky-top navbar-india-funds container-fluid">
        <div class="row">
            <div class="col-12 col-lg-3 offset-lg-2">
                <img src="@/assets/logo.svg" alt="india Funds Logo">
                <h1>India Funds</h1>
            </div>
            <div class="nav-options col-12 col-lg-6">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a href="" class="nav-link home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a href="" class="nav-link">About</a>
                    </li>
                    <li class="nav-item">
                        <a href="" class="nav-link">Testimonials</a>
                    </li>
                    <li class="nav-item">
                        <a href="" class="nav-link">Blogs</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .navbar-india-funds h1 {
        font: 400 2rem 'Hahmlet', sans-serif; 
        color: white; 
        margin-bottom: 0px !important; 
        padding: 0 20px;
    }
    .nav-item a {
        text-decoration: none; 
        font: 200 1rem 'Roboto', sans-serif; 
        color: white !important; 
        padding: 8px 10px;
    }
    .nav-item .home {
        font-weight: 300;
    }

    nav{
        background-color: black;
    }

    .navbar-nav { display: inline-flex;
        flex-direction: unset;
        padding-left: 0;
        margin-bottom: 0;
        list-style: none;
    }
    .nav-options {
        text-align: right !important;
    }
</style>