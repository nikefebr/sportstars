<template>
  <div
    style="width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden"
  >
    <div>
      <b-navbar class="p-0 pl-2">
        <b-navbar-nav class="pt-2 pl-5">
          <b-nav-item href="#">RCTI+</b-nav-item>
          <b-nav-item href="#">Vision+</b-nav-item>
          <b-nav-item href="#">Okezone.com</b-nav-item>
          <b-nav-item href="#">SINDOnews.com</b-nav-item>
          <b-nav-item href="#">iNews.id</b-nav-item>
          <b-nav-item-dropdown>
            <b-dropdown-item href="#">AladinMall</b-dropdown-item>
            <b-dropdown-item href="#">IDX Channel</b-dropdown-item>
            <b-dropdown-item href="#">Roov</b-dropdown-item>
            <b-dropdown-item href="#">Celebrities.id</b-dropdown-item>
            <b-dropdown-item href="#">MNC Trijaya</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto px-3">
          <b-navbar-brand href="https://www.facebook.com/Sportstarsdotid-105132665009326" class="px-2">
            <img src="../assets/images/icons/facebook.svg" alt="facebook">
          </b-navbar-brand>
          <b-navbar-brand href="https://twitter.com/sportstarsdotid?s=09" class="px-2">
            <img src="../assets/images/icons/twitter.svg" alt="twitter">
          </b-navbar-brand>
          <b-navbar-brand href="https://instagram.com/sportstarsdotid?igshid=1dr8m1hpkcbem" class="px-2">
            <img src="../assets/images/icons/instagram.svg" alt="instagram">
          </b-navbar-brand>
          <b-navbar-brand href="https://youtube.com/channel/UCntKP7FCjdOj63z1-JV2X9g" class="px-2">
            <img src="../assets/images/icons/youtube.svg" alt="youtube">
          </b-navbar-brand>
          <b-navbar-brand href="#">
            <img src="../assets/images/icons/tiktok.svg" alt="tiktok">
          </b-navbar-brand>
        </b-navbar-nav>
      </b-navbar>
    </div>

    <hr style="background-color: #24326F; height: 1px">

    <div>
      <b-navbar class="pb-4">
        <b-navbar-nav class="px-5">
          <b-navbar-brand href="#">
            <img src="../assets/images/logo/sportstars.svg">
          </b-navbar-brand>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto">
          <b-navbar-brand href="#">
            <img src="../assets/images/banner/image1.svg">
          </b-navbar-brand>
        </b-navbar-nav>
      </b-navbar>
    </div>

    <div align="center">
      <b-navbar style="background-color: #24326F" class="font-weight-bolder px-5" type="dark">
        <b-navbar-nav class="px-1">
          <b-nav-item href="#">BERANDA</b-nav-item>
          <b-nav-item href="#">BOLA</b-nav-item>
          <b-nav-item href="#">BALAP</b-nav-item>
          <b-nav-item href="#">RAGAM</b-nav-item>
          <b-nav-item href="#">SPORTAIMENT</b-nav-item>
          <b-nav-item href="#">HOBI</b-nav-item>
          <b-nav-item href="#">DATA STATISTIK</b-nav-item>
          <b-nav-item href="#">MULTIMEDIA</b-nav-item>
          <b-nav-item href="#">INDEX</b-nav-item>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto">
          <b-button size="sm" style="background-color: #ED1C24">
            <b-icon-search aria-label="search" style="color: #FFFFFF;"></b-icon-search>
          </b-button>
        </b-navbar-nav>
      </b-navbar>
    </div>
  </div>
</template>

<script>
import { BIconSearch } from 'bootstrap-vue'

export default {
  name: 'NavbarSportStars',
  components: {
    BIconSearch
  }
}
</script>
