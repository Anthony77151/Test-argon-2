<template>
<main>
    <header class="header">
        <nav class="navbar navbar-expand-lg navbar-dark pr-0 pb-0 pt-0">
            <a id="logoace" class="navbar-brand" href="index.html">A.C.E.</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-lg-end" id="navbarNav">
                <ul class="navbar-nav menu">
                    <li class="nav-item active">
                        <a class="nav-link pr-4 pl-4" href="#">Sécurité & Contrôle</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link pr-4 pl-4" href="automatisme.html">Automatisme</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link pr-4 pl-4" href="entretien.html">Contrats d'entretiens</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link pr-4 pl-4" href="depannage.html">Dépannage</a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link pr-4 pl-4" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
  </main>  
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>

* {
    margin: 0;
    padding: 0;
}

.header {
    background-color: rgb(22, 22, 22);
    border-top: 2px solid ghostwhite;
    border-bottom: 2px solid ghostwhite;
    position: fixed;
    width: 100%;
    z-index: 100;
    font-family: "Font global";
}
.header ul {
    list-style: none;
    overflow: hidden;
    background-color: rgb(22, 22, 22);
}
.header li a {
    display: block;
    padding: 35px 35px;
    text-decoration: none;
    
}
#logoace {
    font-family: "Ma fonte";
    font-size: 3em;
}

.header .menu {
    clear: none;
    max-height: none;
}
</style>
