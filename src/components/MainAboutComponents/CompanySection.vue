<script>
export default {
  name: "CompanySection",
};
</script>
<template>
  <div class="container py-5">
    <div class="row">
      <div class="col-6">
        <h6>ABOUT THE NETWORK</h6>
        <h2>The Company</h2>

        <p class="first-p">
          For 12 years we have been providing audit and warranty, financial
          advice, risk advice, taxes and related services to select clients.
        </p>
        <div class="row">
          <div class="col-6 cardt">
            <a href="#">
              <font-awesome-icon :icon="['fas', 'hourglass-end']" />
              <label for="#">Tradition</label>
            </a>
            <p class="second-p">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </p>
          </div>
          <div class="col-6 cardt">
            <a href="#">
              <font-awesome-icon :icon="['fas', 'lock']" />
              <label for="#">Security</label>
            </a>
            <p class="second-p">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            </p>
          </div>
          <div class="col-6 cardt">
            <a href="#">
              <font-awesome-icon :icon="['fas', 'apple-whole']" />
              <label for="#">Certificate</label>
            </a>
            <p class="second-p">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </p>
          </div>
          <div class="col-6 cardt">
            <a href="#">
              <font-awesome-icon :icon="['fas', 'user-tie']" />
              <label for="#">Expertise</label>
            </a>
            <p class="second-p">
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            </p>
          </div>
        </div>
      </div>
      <div class="col-5 img mx-4"><img src="../../assets/img/about-3.jpg"</div>
    </div>
  </div>
</template>
<style scoped lang="scss">
.col-6 {
  h6 {
    color: #18a6a6;
  }
  h2 {
    font-weight: 700;
    font-size: 50px;
    margin-top: 30px;
    color: #21333e;
  }
  .first-p {
    margin: 25px 0;
    font-weight: 400;
    color: #606d75;
  }

  i {
    font-size: 30px;
    color: #058283;
  }
  label {
    margin: 0 0.8rem;
    font-size: 25px;
    font-weight: 700;
    color: #21333e;
  }
  .second-p {
    margin-top: 10px;
    color: #606d75;
  }
}
.img {
  img {
    width: 115%;
    border-radius: 20px;
  }
}
</style>
