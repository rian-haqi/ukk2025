<template>
    <div class="card text-bg-dark">
        <img src="assets/bg.png" class="card-img" alt="...">
        <div class="card-img-overlay">
            <h1 class="card-title "><img src="assets/logo.png" alt="logo" width="150px" height="150px"> <p></p>Informasi
                Mengenai Smkn 4 Tasikmalaya</h1>
            <p class="berita ">Sambutan </p>
            <p class="berita">Daftar guru</p>
            <Nuxt-Link to="./bacaselengkapnya" class="nav-link active" aria-current="page" style="color: aqua;">
                <button class="baca rounded-2"><h6 style="color: blue;">Baca Selengkapnya</h6></button>
                </Nuxt-link>
        </div>
    </div>

</template>

<style scoped>
.card-title {
    padding-top: 11%;
    color: black;
    justify-content: center;
}
.berita{
    color: rgb(0, 0, 0);
    margin: 0%;
}

.nav-items{
    text-align: center;
}

.nav-link{
    padding: 1%;
}
</style>