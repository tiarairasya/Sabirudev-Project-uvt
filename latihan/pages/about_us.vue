<template>
  <div>
    <!-- banner -->
		<div class="hero-wrapper">
			<div class="hero-content">
				<h1>Our Value</h1>
			</div>
		</div>

		<!-- profil -->
    <div class="container" style="margin-top: 10%;">
      <div class="row text-center mt-5">
        <div class="col-md-4">
          <b-img src="~assets/img/profile.jpg" class="profil"></b-img>
          <h6 class="mt-4">Our Profile</h6>
        </div>
        <div class="col-md-4">
          <b-img src="~assets/img/note.jpg" style="width: 31%; margin-top: 2%;"></b-img>
          <h6 class="mt-4">Our vision & mission value</h6>
        </div>
        <div class="col-md-4">
          <b-img src="~assets/img/51.jpg" style="width: 26%;"></b-img>
          <h6 class="mt-4">Our Managemen</h6>
        </div>
        <hr>
      </div>
    </div>
    <!-- profil -->
   

    <!-- visimisi -->
    <b-container my-4>
      <b-row gx-lg-5 style="margin-top: 10%; margin-left: -5%;">
        <b-col sm="6">
          <b-img src="~assets/img/54.jpg" style="width: 35rem;"></b-img>
          <div class="overlay-text">
            <h3>VISION</h3>
            <p style=" color: white;  font-size: 16px; text-align: center; padding: 10px 20px; ">•To become a global one stop services company which reliable, 
              trustworthy, responsive in plant services Business</p>
              <button class="th"><a href="#">Selangkapnya</a></button>
          </div>
        </b-col>
        <b-col sm="6">
          <b-img src="~assets/img/55.jpg" style="width: 35rem;"></b-img>
          <div class="overlay-text">
            <h3>MISSION</h3>
            <p style=" color: white;  font-size: 15px; text-align: center; padding: 10px 20px; ">• As a center of high qualified experienced technical engineers and specialist in industrial plant
              • To increase the number of local Indonesian expert in industrial plant services</p>
            <button class="th"><a href="#">Selangkapnya</a></button>
          </div>
        </b-col>
      </b-row>
    </b-container>
    <!-- visimisi -->
     
    <!--mision value-->
    <div class="news-container bg-grey">     
      <div class="news-entry">
        <div style="color:green;border-top:solid 1px white;font-size: 20px; height: 12vh;">
	        <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Mutuality</span>
        </div>
        <div style="color:green;border-top:solid 1px lightgray; font-size:20px; height: 12vh;">
          <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Incredible</span>
        </div>
        <div style="color:grey;border-top:solid 1px lightgray;font-size: 20px; height: 12vh;">
          <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Problem solving</span>
        </div>
        <div style="color:grey;border-top:solid 1px lightgray;font-size: 20px; height: 12vh;">
          <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Continuous Learning</span>
          </div>
        <div style="color:grey;border-top:solid 1px lightgray;font-size: 20px; height: 12vh;">
          <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Ownership</span>
          </div>
        <div style="color:grey;border-top:solid 1px lightgray;font-size: 20px; height: 12vh;">
          <img src="~/assets/img/56.jpg" style="color: rgb(34, 34, 34); font-size: 12px; margin-top: 2%; height: 25px; width: 35px;">
          <span style="color: rgb(34, 34, 34); font-family: arial, sans-serif; margin-top: 2%; position: absolute;">Never Give Up</span>
          </div>
        <div style="color:grey;border-top:solid 1px lightgray;font-size: 20px; height: 12vh;"></div>
      </div>
    </div>
    <!--mision value-->
    
  </div>
</template>

<script>
export default {

}
</script>

<style>
.hero-wrapper{
  align-items: center;
  background-repeat: no-repeat;
  background-image: url(../assets/img/wall.png);
  background-size: cover;
  display: flex;
}
.hero-content h1{
  color: white;
  text-shadow: #000 9px 9px 9px;
  position: relative;
  margin-left: 75px;
  margin-top: 10px;
}
.hero-content button{
  background-color:  #FAE84B;
  border: none; 
  width: 55%; 
  margin-left: 73px;
  height: 35px; 
  border-radius: 5px;
}
.hero-content button a{
  text-decoration: none;
  color: #000;
}
.hero-content button:hover{
  background-color: orangered;
}
.hero-content button:hover a{
  color: white;
}

/* profil */
hr{
  background-color: blue;
  width: 25%;
  height: 4px;
  border-radius: 45px;
  display: flex;
  margin-left: 37%;
  margin-top: 5%;
}
/* profil */

/* vision mision */
.overlay-text {
  position: absolute;
  top: 50%; 
  left: 50%; 
  transform: translate(-50%, -50%);  
  color: #fff; 
  padding: 9px 19px; 
  font-size: 20px; 
  text-align: center;
  font-weight: bold;
}
.th{
  background-color: #2A93A2;
  width: 22rem;
  height: 7vh;
}
.th:hover{
  background-color: red;
}
.th a{
  text-decoration: none;
  color: white;
}
/* vision mision */

.news-container {
  text-align: left;
}
.news-container {
  margin-left: 6%;
  margin-top: 7%;
}
</style>