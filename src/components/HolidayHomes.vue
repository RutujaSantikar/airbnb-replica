<template>
  <section>
    <div class="homes-info">
      <div class="grid-box box-one">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayOne" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-homestayTwo">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayTwo" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-three">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayThree" /></div>
        <div class="place-heading">
          <strong>Sindun,South Korea</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,638 kilometers</div>
        <div class="date-avail fade-color">3-8 Oct</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-four">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayFour" /></div>
        <div class="place-heading">
          <strong>Tambon Nong,Thailand</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">2,989 kilometers</div>
        <div class="date-avail fade-color">4-9 Oct</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>8,620</strong> night
        </div>
      </div>
      <div class="grid-box box-five">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayFive" /></div>
        <div class="place-heading">
          <strong>Uluwatu,Indonesia</strong>
          <span><i class="fas fa-star">4.7</i></span>
        </div>
        <div class="place-distance fade-color">5,571 kilometers</div>
        <div class="date-avail fade-color">7-14 Oct</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>15,126</strong> night
        </div>
      </div>
      <div class="grid-box box-six">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestaySix" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-seven">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestaySeven" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-eight">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayEight" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-nine">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayNine" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-ten">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayTen" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-eleve">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayEl" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
      <div class="grid-box box-tweleve">
        <div class="home-img"><i class="far fa-heart"></i><img v-bind:src="homestayTwl" /></div>
        <div class="place-heading">
          <strong>Abiansemal,Indonesia</strong>
          <span><i class="fas fa-star">4.8</i></span>
        </div>
        <div class="place-distance fade-color">5,565 kilometers</div>
        <div class="date-avail fade-color">18-25 Apr</div>
        <div class="place-price">
          <strong><i class="fas fa-rupee-sign"></i>27,101</strong> night
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HolidayHomes",
  data() {
    return {
      homestayOne: require("../assets/image_card_1.webp"),
      homestayTwo: require("../assets/image_card_2.webp"),
      homestayThree: require("../assets/image_card_3.webp"),
      homestayFour: require("../assets/image_card_4.webp"),
      homestayFive: require("../assets/image_card_5.webp"),
      homestaySix: require("../assets/image_card_6.webp"),
      homestaySeven: require("../assets/image_card_7.webp"),
      homestayEight: require("../assets/image_card_8.webp"),
      homestayNine: require("../assets/image_card_9.webp"),
      homestayTen: require("../assets/image_card_10.webp"),
      homestayEl: require("../assets/image_card_11.webp"),
      homestayTwl: require("../assets/image_card_12.webp"),
    };
  },
};
</script>

<style scoped>
.far{
  
  position:absolute;
  color: white;
  margin-left: 8.5em;
  margin-top: 0.9em;
  font-size: 22px;
  background: rgba(0,0,0,0.5) ;
  border-radius:100em;
}
img {
  width: 230px;
  height: 217px;
  border-radius: 12px;
}
section {
  width: 88%;
  margin: 0 auto;

  font-weight: 50;
}
.homes-info {
  display: grid;
  grid-template-columns: auto auto auto auto;
  width: 100%;
  grid-gap: 20px;
  padding: 5px;
}
.fa-star {
  float: right;
  font-size: 12px;
}
.fa-rupee-sign {
  font-size: 12px;
}
.fade-color {
  color: lightslategrey;
}
.place-heading,
.place-price {
  margin-top: 5px;
}

@media (max-width: 743px) {
  .far{
    margin-left: 12em;
  }
  .homes-info {
    grid-template-columns: 100%;
  }
  .fa-star {
    float: none;
    margin-left: 80px;
  }
  img {
    width: 100%;
    height: 100%;
  }
}
</style>
