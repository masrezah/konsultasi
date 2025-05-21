<script setup lang="ts">
import {
  MDBFooter,
  MDBContainer,
  MDBRow,
  MDBCol,
  MDBIcon
} from 'mdb-vue-ui-kit';
</script>

<template>
  <!-- Footer -->
  <MDBFooter :text="['center', 'lg-start', 'muted']">
    <!-- Section: Social media -->
    <section class="
        d-flex
        justify-content-center justify-content-lg-between
        p-4
        border-bottom
      ">
      <!-- Left -->
      <div class="me-5 d-none d-lg-block">
        <span>Terhubung dengan kami di media sosial:</span>
      </div>
      <!-- Left -->
      <!-- Right -->
      <div>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="facebook-f"></MDBIcon>
        </a>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="twitter"></MDBIcon>
        </a>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="google"></MDBIcon>
        </a>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="instagram"></MDBIcon>
        </a>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="linkedin"></MDBIcon>
        </a>
        <a href="" class="me-4 text-reset">
          <MDBIcon iconStyle="fab" icon="github"></MDBIcon>
        </a>
      </div>
      <!-- Right -->
    </section>
    <!-- Section: Social media -->
    <!-- Section: Links  -->
    <section class="">
      <MDBContainer class="text-center text-md-start mt-5">
        <!-- Grid row -->
        <MDBRow class="mt-3">
          <!-- Grid column -->
          <MDBCol md="3" lg="4" xl="3" class="mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold mb-4">
              <i class="fas fa-gem me-3"></i>Nama Perusahaan
            </h6>
            <p>
              Di sini Anda dapat menggunakan baris dan kolom untuk mengatur konten footer Anda.
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            </p>
          </MDBCol>
          <!-- Grid column -->
          <!-- Grid column -->
          <MDBCol md="2" lg="2" xl="2" class="mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Produk</h6>
            <p>
              <a href="#!" class="text-reset">Angular</a>
            </p>
            <p>
              <a href="#!" class="text-reset">React</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Vue</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Laravel</a>
            </p>
          </MDBCol>
          <!-- Grid column -->
          <!-- Grid column -->
          <MDBCol md="3" lg="2" xl="2" class="mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Link Berguna</h6>
            <p>
              <a href="#!" class="text-reset">Harga</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Pengaturan</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Pesanan</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Bantuan</a>
            </p>
          </MDBCol>
          <!-- Grid column -->
          <!-- Grid column -->
          <MDBCol md="4" lg="3" xl="3" class="mx-auto mb-md-0 mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">Kontak</h6>
            <p>
              <i class="fas fa-home me-3"></i> Jakarta, JKT 10012, ID
            </p>
            <p>
              <i class="fas fa-envelope me-3"></i>
              info@contoh.com
            </p>
            <p>
              <MDBIcon icon="phone" class="me-3" /> + 62 234 567 88
            </p>
            <p>
              <MDBIcon icon="print" class="me-3" /> + 62 234 567 89
            </p>
          </MDBCol>
          <!-- Grid column -->
        </MDBRow>
        <!-- Grid row -->
      </MDBContainer>
    </section>
    <!-- Section: Links  -->
    <!-- Copyright -->
    <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05)">
      © 2025 Hak Cipta:
      <a class="text-reset fw-bold" href="https://mdbootstrap.com/">WebsiteAnda.com</a>
    </div>
    <!-- Copyright -->
  </MDBFooter>
  <!-- Footer -->
</template>