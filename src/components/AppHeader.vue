<template>
  <div>
    <section>
      <header class="header-content sm-none">
        <div><img v-bind:src="airbnbLogo" /></div>
        <div class="btn-cont">
          <button class="bg-transparent btn-one">
            <strong>Anywhere</strong></button
          ><span>|</span>
          <button class="bg-transparent btn-two">
            <strong> Any week</strong></button
          ><span>|</span>
          <button class="bg-transparent btn-three">Add guests</button>
          <i class="fas fa-search bg-search"></i>
        </div>
        <div class="right-cont">
          <div class="header-link center">Become a host</div>
          <i class="fas fa-globe center"></i>
          <div class="profile-btn">
            <i class="fas fu fa-bars"></i>
            <i class="fas fu fa-user-circle"></i>
          </div>
        </div>
      </header>
         
         <header class="header-content-sm lg-none">
          <div class="mid-cont">
          <div class="btn-cont-sm-flex">
          <div><i class="fas fa-search"></i></div>
          <div class="text">Where to ?</div>
         
          </div>
          <button class="bg-transparent-sm btn-one-sm">
            Anywhere</button
          ><span>.</span>
          <button class="bg-transparent-sm btn-two-sm">
          Any week</button
          ><span>.</span>
          <button class="bg-transparent-sm btn-three-sm">Add guests</button> 
          </div>
           
            
         </header>
      
    </section>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
  data() {
    return {
      airbnbLogo: require("../assets/airbnb_logo.jpg"),
    };
  },
};
</script>

<style scoped>
section {
  width: 100%;
  border-bottom: 1px solid lightgray;
}
.header-content {
  width: 88%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 80px;
}
img {
  width: 100px;
}
.bg-transparent {
  background: none;
  border: none;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 20px;
  padding-right: 20px;
}
.btn-cont {
  box-shadow: 0.2px 0.2px 0.2px 0.2px lightgrey;
}
.bg-search {
  color: white;
  background-color: #ff385c;
  padding: 8px;
  border-radius: 20px;
  font-size: 12px;
  margin-right: 8px;
}
.btn-three {
  color: lightslategray;
}
.btn-cont,
.profile-btn {
  border: 1px solid lightgrey;
  border-radius: 5em;
}
.header-link{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

.right-cont {
  display: flex;
}
.fa-globe {
  margin-left: 25px;
  margin-right: 20px;
}
.fa-user-circle {
  font-size: 30px;
}

.fu {
  color: gray;
}
.center {
  line-height: 2.5em;
}

.profile-btn {
  padding-top: 5px;
  padding-bottom: 5px;
  padding-left: 15px;
  padding-right: 15px;
}
.lg-none{
  display:none;
}

@media (max-width:743px){
  .sm-none{
    display:none;
  }
  section{
    border: none;
  }
  .header-content-sm {
  width: 90%;
  margin: 0 auto;
  display: flex;
  /* justify-content: space-between;  */
  align-items: center;
  
}
.mid-cont{
  border: 1px solid lightgrey;
  border-radius: 5em;
  width:100%
}
.btn-cont-sm-flex {

  display: flex;
}
.bg-transparent-sm{
  background: none;
  border: none;
  color:rgb(156, 151, 151);
  margin-bottom: 5px ;
  margin-left: 15px;
}
.mid-cont,.btn-cont-sm-flex{
  padding:2px 6px 2px 6px;
}
}
</style>
