<template>
    <nav class=" nav navbar navbar-expand-lg bg-body-tertiary ">
        <div class="container-fluid ">
            <a class="navbar-brand col-9" href="#"><img src="assets/logo.png" alt="logo" width="80px" height="80px">SMKN 4 TASIKMALAYA</a>
            <button class="navbar-toggler " type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <nuxt-link to="../" class="nav-link active " aria-current="page"
                            style="color: blue;">Beranda</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="./profil" class="nav-link active " aria-current="page"
                            style="color: blue;">Profil</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="./ekskul" class="nav-link active " aria-current="page"
                            style="color: blue;">Ekstakulikuler</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="./galeri" class="nav-link active " aria-current="page"
                            style="color: blue;">Galeri</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="./jurusan" class="nav-link active " aria-current="page"
                            style="color: blue;">Jurusan</nuxt-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

</template>


<style scoped>

.container-fluid{
    background-color: rgb(124, 128, 126);
    max-height: fit-content;
}


.navbar-brand{
    
}

*{
    padding: 0%;
    margin: 0%;
}



</style>