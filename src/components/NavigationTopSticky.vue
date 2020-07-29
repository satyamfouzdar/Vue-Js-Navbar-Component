<template>
    <nav class="navbar navbar-default navbar-fixed-top navbar-shrink">
        <div class="container">
            <!-- Brand and toggle get grouped for better mobile display -->
            <div class="navbar-header page-scroll">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand page-scroll" href="#page-top">Company Name</a>
            </div>

            <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
                <ul class="nav navbar-nav navbar-right">
                    <li class="hidden active">
                        <a href="#page-top"></a>
                    </li>
                    <li class="">
                        <a class="page-scroll" href="#services">Services</a>
                    </li>
                    <li class="">
                        <a class="page-scroll" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="">
                        <a class="page-scroll" href="#about">About</a>
                    </li>
                    <li class="">
                        <a class="page-scroll" href="#team">Team</a>
                    </li>
                    <li class="">
                        <a class="page-scroll" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
            <!-- /.navbar-collapse -->
        </div>
        <!-- /.container-fluid -->
    </nav>
</template>

<script>
export default {
  name: 'NavigationTopSticky',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-default {
    border-color: transparent;
    background-color: #222;
}

.navbar-default .navbar-brand {
    font-family: "Kaushan Script","Helvetica Neue",Helvetica,Arial,cursive;
    color: #1ee2e7;
}

.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus,
.navbar-default .navbar-brand:active,
.navbar-default .navbar-brand.active {
    color: #fec503;
}

.navbar-default .navbar-collapse {
    border-color: rgba(255,255,255,.02);
}

.navbar-default .navbar-toggle {
    border-color: #1ee2e7;
    background-color: #1ee2e7;
}

.navbar-default .navbar-toggle .icon-bar {
    background-color: #fff;
}

.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
    background-color: #1ee2e7;
}

.navbar-default .nav li a {
    text-transform: uppercase;
    font-family: Montserrat,"Helvetica Neue",Helvetica,Arial,sans-serif;
    font-weight: 400;
    letter-spacing: 1px;
    color: #fff;
}

.navbar-default .nav li a:hover,
.navbar-default .nav li a:focus {
    outline: 0;
    color: #1ee2e7;
}

.navbar-default .navbar-nav>.active>a {
    border-radius: 0;
    color: #fff;
    background-color: #1ee2e7;
}

.navbar-default .navbar-nav>.active>a:hover,
.navbar-default .navbar-nav>.active>a:focus {
    color: #fff;
    background-color: #17d0d5;
}

@media(min-width:768px) {
    .navbar-default {
        padding: 25px 0;
        border: 0;
        background-color: transparent;
        -webkit-transition: padding .3s;
        -moz-transition: padding .3s;
        transition: padding .3s;
    }

    .navbar-default .navbar-brand {
        font-size: 2em;
        -webkit-transition: all .3s;
        -moz-transition: all .3s;
        transition: all .3s;
    }

    .navbar-default .navbar-nav>.active>a {
        border-radius: 3px;
    }

    .navbar-default.navbar-shrink {
        padding: 10px 0;
        background-color: #222;
    }

    .navbar-default.navbar-shrink .navbar-brand {
        font-size: 1.5em;
    }
}
</style>
