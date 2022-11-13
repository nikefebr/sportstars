<template>
  <div
    style="width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden"
  >
    <footer class="footer-static py-5" style="background-color: #24326F">
      <b-row>
        <b-col cols="5" lg="5" md="5" sm="5">
          <b-img 
            center
            fluid alt="Responsive image" 
            :src="require('@/assets/images/logo/sportstars_footer.svg')">
          </b-img>
          <b-card-text class="ml-4 pl-5 pt-3 text-white">
            Conect with us: <br>
          </b-card-text>
          <b-row class="py-3 ml-4 pl-5">
            <b-col lg="2" md="2" sm="6">
              <b-button size="md" variant="light" class="px-3 pt-0 py-1 pb-2">
                <img src="../assets/images/icons/facebook.svg" alt="facebook">
              </b-button>
            </b-col>
            <b-col lg="2" md="2" sm="6">
              <b-button size="md" variant="light">
                <b-icon-twitter aria-label="twitter" style="color: #070D59;"></b-icon-twitter>
              </b-button>
            </b-col>
            <b-col lg="2" md="2" sm="6">
              <b-button size="md" variant="light">
                <b-icon-instagram aria-label="instagram" style="color: #070D59;"></b-icon-instagram>
              </b-button>
            </b-col>
            <b-col lg="2" md="2" sm="6">
              <b-button size="md" variant="light">
                <b-icon-youtube aria-label="youtube" style="color: #070D59;"></b-icon-youtube>
              </b-button>
            </b-col>
            <b-col lg="2" md="2" sm="6">
              <b-button size="md" variant="light" class="px-3 pt-0 py-1 pb-2">
                <img src="../assets/images/icons/tiktok.svg" alt="tiktok" fluid>
              </b-button>
            </b-col>
          </b-row>
        </b-col>
        <b-col cols="2" lg="2" md="2" sm="2">
          <ul style="list-style-type:none">
            <li>
              <h5 class="font-weight-bold text-white">ABOUT US</h5>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Tentang Kami
              </b-link>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Disclaimer
              </b-link>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Kode Etik
              </b-link>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Term of Service
              </b-link>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Privacy Policy
              </b-link>
            </li>
            <li>
              <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                Kontak Kami
              </b-link>
            </li>
          </ul>
        </b-col>
        <b-col cols="4" lg="4" md="4" sm="4">
          <b-row>
            <b-col>
              <ul style="list-style-type:none">
                <li>
                  <h5 class="font-weight-bold text-white">KANAL UTAMA</h5>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Beranda
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Bola
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Balap
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Ragam
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Sportainment
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Hobi
                  </b-link>
                </li>
              </ul>
            </b-col>
            <b-col class="pt-4" cols="12" lg="4" md="4" sm="4">
              <ul style="list-style-type:none">
                <li>
                  <h5></h5>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Data Statistik
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Multimedia 
                  </b-link>
                </li>
                <li>
                  <b-link style="text-decoration: none; color: #CCCCCC" href="#">
                    Index
                  </b-link>
                </li>
              </ul>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </footer>

    <footer class="footer-static py-3 text-center" style="background-color: #070D59; color: #CCCCCC">
      &#169; Copyrights 2021. Sportstars.id All rights reserved
    </footer>
  </div>
</template>

<script>
import { BIconTwitter, BIconInstagram, BIconYoutube } from 'bootstrap-vue'

export default {
  name: 'FooterSportStars',
  components: {
    BIconTwitter,
    BIconInstagram,
    BIconYoutube
  }
}
</script>
