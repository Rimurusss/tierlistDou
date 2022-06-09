<template>
  <div>
    <v-app-bar color="deep-purple accent-4" dense dark>
      <div class="container">
        <div class="row">
          <a class="barlogo">logo</a>

          <!-- <v-spacer></v-spacer> -->
          <ul class="nav-links ml-auto">

            <li class="">
              <a class="nav-link opacity-50 text-white " href="/tierlist">tierlist</a>
            </li>
            <li class="">
              <a class="nav-link opacity-50 text-white" href="/team">team</a>
            </li>
            <li class="">
              <a class="nav-link opacity-50 text-white" href="/Characters">Characters</a>
            </li>
          </ul>
        </div>
      </div>
    </v-app-bar>
    <nuxt/>
  </div>
</template>

<script>
export default {};
</script>

<style>
.nav-link {
  display: flex;
    align-items: center;
    position: relative;
    height: 100%;
    color: #fff;
    font-size: 16px;
    font-weight: 500;
    padding: 0 20px;
    opacity: .6;
    transition: all .3s;
}
.ml-auto {
  margin-left: auto !important;
  display: flex;
}
.nav-link :hover{
    color: black;
}
</style>