<template>
    <div class="container-fluid pl-0 pr-0 sticky-top ">
        <nav id="nav" class="navbar navbar-expand-lg navbar-light bg-light pl-5 pr-5 pt-3 pb-3">
            <a class="navbar-brand ml-0 ml-lg-3 mr-0 align-middle d-flex align-items-center justify-content-center" href="#">
                <img 
                    class="nav-brand d-inline-block align-top" 
                    src="@/assets/mirantis-logo-2color-horizontal-rgb@2x.png" 
                    alt="Mirantis"
                    width="170"
                    height="20"
                >
            </a>
            <button class="navbar-toggler collapsed" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="icon-bar top-bar"></span>
                <span class="icon-bar middle-bar"></span>
                <span class="icon-bar bottom-bar"></span>				
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <li class="nav-item mr-3 d-flex align-items-center">
                        <a class="nav-link">
                            PRODUCTS
                        </a>
                    </li>
                    <li class="nav-item mr-3 d-flex align-items-center">
                        <a class="nav-link" href="#">
                            USE CASES
                        </a>
                    </li>
                    <li class="nav-item mr-3 d-flex align-items-center">
                        <a class="nav-link" href="#">
                            DELIVERY APPROACH
                        </a>
                    </li>
                    <li class="nav-item mr-3 d-flex align-items-center">
                        <a class="nav-link" href="#" tabindex="-1">
                            TRAINING
                        </a>
                    </li>
                    <li class="nav-item mr-3 d-flex align-items-center">
                        <a class="nav-link" href="#" tabindex="-1">
                            RESOURCES
                        </a>
                    </li>
                    <li class="nav-item mr-3 contact-sales">
                        <a class="btn nav-link _nav-link" href="https://info.mirantis.com/contact-us" tabindex="-1">
                            CONTACT SALES
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style lang="scss" scoped>

    #nav {
        background-color: #fff!important;
        border-bottom: 1px solid #ef2369;
    }

    #nav .navbar-brand {
        padding-bottom: 0!important;
    }

    #nav ul li a{
        color: #262626;
        font-size: smaller;
        cursor: default;
        white-space: nowrap;
    }

    .contact-sales a {
        color: #ef2369!important;
        font-weight: bold;
        border: 1px solid #ef2369;
        border-radius: 0px;
        cursor: pointer!important;
    }
    
    .contact-sales a:hover {
        color: #fff!important;
        background-color: #ef2369;
        border: 1px solid #ef2369;
    }

    .contact-sales .btn:focus {
        box-shadow: none!important;
    }

    button.navbar-toggler:focus { 
        outline: 1px none; 
    }

    .icon-bar {
        width: 22px; 
        height: 2px;
        background-color: #ef2369;
        display: block;
        transition: all 0.2s;
        margin-top: 4px
    }
    
    .navbar-toggler {
        border: none;
        background: transparent !important;
    }
    
    .navbar-toggler .top-bar {
        transform: rotate(45deg);
        transform-origin: 10% 10%;
    }
    
    .navbar-toggler .middle-bar {
        opacity: 0;
    }
    
    .navbar-toggler .bottom-bar {
        transform: rotate(-45deg);
        transform-origin: 10% 90%;
    }
    
    .navbar-toggler.collapsed .top-bar {
        transform: rotate(0);
    }
    
    .navbar-toggler.collapsed .middle-bar {
        opacity: 1;
    }
    
    .navbar-toggler.collapsed .bottom-bar {
        transform: rotate(0);
    }
</style>
