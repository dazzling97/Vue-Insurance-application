<template>
   <div class="hello">
    <nav class="navbar navbar-expand-lg navbar-light bg-light nav-custom-style">
    <!-- Just an image -->
    <nav class="navbar">
    <a class="navbar-brand" href="#">
       <img class="brand-logo" src="../assets/fame-logo.png" width="157" height="30" alt="">
    </a>
    </nav>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
            <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2 search-team-leaders" type="search" placeholder="Search Team Leaders" aria-label="Search">
       
        </form>
        </li>
        </ul>

        <div class="form-inline my-2 my-lg-0">
       
         <img class="logged-user-profile" src="../assets/profile.jpg" width="40" height="40" alt="">
            <p class="logged-user-name">Robert perera</p>
       
        </div>
    </div>
    </nav>
   </div>
</template>

<script>
export default{
    components:{
        
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "../styles/varibles.scss";
@import "../styles/mixin.scss";

 .brand-logo{
    position: relative;
    left: -28%;
}

.nav-custom-style{
    background-color:$primary-color !important;
}

.search-team-leaders{
    width: 470px;
    height: 40px;
    border-radius: 7px;
    border: solid 0.3px #a9a9a9;
    background-color: #ffffff;
}

.logged-user-profile{
    @include border-radius(100px)
    border-radius: 100px;
    position: relative;
    right: 49%;
}

.logged-user-name{
    color: #ffff;
    position: relative;
    right: 35%;
    top: 7px;
}

</style>
