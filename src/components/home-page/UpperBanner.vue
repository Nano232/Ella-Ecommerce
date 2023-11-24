<template>
  <div class="upper-banner">
    <div class="parent">
      <v-container>
        <v-row>
          <v-col cols="6">
            <div class="content">
              <h3><span>Huge Saving</span> on UHD Televisions</h3>
              <p>Sale up tp 70% off on selected items*</p>
              <v-btn
                variant="outlined"
                style="border-radius: 30px; text-transform: none"
                class="py-5 px-10 d-flex"
                >Shop Now</v-btn
              >
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </div>
</template>
<style scoped lang="scss">
.parent {
  height: 400px;
  width: 100%;
  background-image: url(../../assets/images/banner-bg.jpg);
  background-size: cover;
  background-position: left top;
  .content {
    color: white;
    padding: 70px 0 0 0;
    h3 {
      font-size: 40px;
      font-weight: 900;
      span {
        color: rgb(0, 251, 242);
      }
    }
    p {
      padding: 20px 0;
    }
  }
}
</style>
