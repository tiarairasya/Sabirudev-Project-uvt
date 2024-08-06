<template>
  <div>
     <!-- banner -->
      <b-container fluid>
        <b-row>
          <div class="banner">
            <b-img src="~assets/img/oy.png"></b-img>
            <h3 class="heading" style="margin-left: 8%; margin-top: -15%; color: white;  text-shadow: #000 9px 9px 9px;">Management Comitment & Certification</h3>
          </div>
        </b-row>
      </b-container>
		<!-- banner -->  

    <!-- sertifikat -->
    <b-container fluid>
      <b-row>
        <b-col class="sertifikat">
          <b-img src="~assets/img/sec31.jpg"></b-img>
          <b-img src="~assets/img/sec31.jpg"></b-img>
          <b-col style="background-color: #255FB6; border-radius: 12px; position: absolute; width: 45%; margin-left: 37%; height: 38vh; margin-top: 8%;">
          <h4 style="margin-top: 11%; text-align: right; color: white;">Certification</h4>
          <p style="text-align: right; color: white;">Some of our official certificates, like safety management,
          qualit management, occupational health and others</p>
          <button class="button"><a href="#">Read More</a></button>
        </b-col>
        </b-col>
      </b-row>
    </b-container>
    <!-- sertifikat -->

    <!-- iso -->
     <b-container fluid>
      <b-row>
        <div class="wrapper">
          <div class="iso">
            <h5>ISO Cartification</h5>
          </div>
          <div class="bg">
            <div class="vertical-line"></div>
            <b-col>
              <b-img src="~assets/img/3ser.jpg"></b-img>
              <b-img src="~assets/img/2ser.jpg"></b-img>
            </b-col>
          </div>
        </div>
      </b-row>
     </b-container>
    <!-- iso -->

  </div>
</template>

<script>
export default {

}
</script>

<style>
.banner img{
  width: 100%;
  display: flex;
}
.heading{
  position: absolute;
}
.text{
  position: relative;
  margin-left: 8%;
  text-align: left;
}
.text h2{
  color: black;
  font-size: 30px;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
}
.text p{
  margin-right: 5%;
}
.sertifikat{
  margin-left: 6%;
  display: flex;
}
.sertifikat img{
  width: 19%;
  padding: 5px;
}
.button{
  border: none;
  background-color: #D9D9D9;
  width: 27%;
  height: 6vh;
  border-radius: 5px;
  float: right;
}
.button a{
  color: black;
  text-decoration: none;
}
.wrapper{
  background-color: #255FB6;
  display: flex;
  width: 100%;
  margin-top: 20%;
  border-radius: 90px;
  height: 117vh;
}
.iso h5{
  position: absolute;
  margin-left: 10%;
  margin-top: 5%;
  font-weight: bold;
  font-size: 28px;
  color: white;
}
.bg{
  background-color: #D9D9D9;
  width: 94%;
  border-radius: 85px;
  height: 90vh;
  margin-top: 11%;
  margin-left: 3%;
}
.bg img{
  width: 30%;
  margin-left: 12%;
  margin-top: 2%;
}
.vertical-line{
  width: 1px;
  height: 90vh;
  background-color: black;
  margin-left: 45%;
  position: absolute;
}
</style>