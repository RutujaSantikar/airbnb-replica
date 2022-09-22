<template>
  <div>
    <section>
      <footer class="footer-content sm-none">
        <div class="left-cont">
          <div>
            &copy; 2022 Airbnb,Inc. <span>.</span> Privacy <span>.</span> Terms
            <span>.</span> Sitemap <span>.</span> Company Details
            <span>.</span> Destinations
          </div>
        </div>
        <div class="right-cont">
            <div><strong><i class="fas fa-globe "></i> English (IN)</strong></div>
            <div><strong><i class="fas fa-rupee-sign"></i> INR</strong></div>
            <div><strong> Support & resources <i class="fas fa-chevron-up"></i></strong></div>
        </div>
      </footer>

      <footer class="footer-content-sm lg-none">
        <div>
            <div><i class="fas fu fa-search"></i></div>
            <div>Explore</div>
        </div>
        <div>
            <div><i class="far  fu fa-heart"></i></div>
            <div>Wishlists</div>
        </div>
        <div>
            <div><i class="fas fu  fa-user-circle"></i></div>
            <div>Login</div>
        </div>

      </footer>
    </section>
  </div>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.lg-none{
    display: none;
}
section {
  width: 100%;
  border-top: 1px solid lightgray;
  position: fixed;
  top:508px;
  background-color: white;
}
.footer-content {
  width: 88%;
  margin: 0 auto;
  display: flex;
  justify-content:space-between;
  align-items: center;
  padding: 14px 0;
}
.right-cont{
    display: flex;

}
.right-cont >div{
    padding: 0 10px;
} 
.fa-rupee-sign,.fa-globe {
    font-size: 12px;
}
.left-cont{
    color:rgb(65, 70, 75);
}
@media (max-width:743px){
    .sm-none{
        display: none;
    }
   section{
    bottom:-60px;
    height: 100px;
    width: 100%;
    top:550px;
  border-top: 1px solid lightgray;
  position: fixed;
  background-color: white;
   }
   .footer-content-sm{
    width: 88%;
  margin: 0 auto;
  display: flex;
  justify-content: space-evenly;
  text-align: center;
  
  padding: 15px 0;

   }
   .fu{
    font-size: 25px;
   }
   .fa-heart, .fa-user-circle{
    color: lightslategrey;
   }
   .fa-search{
    color: #ff385c;
   }
}

</style>
