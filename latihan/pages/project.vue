<template>
  <div>
		<!-- banner -->
		<div class="hero-wrapper">
			<div class="hero-content">
				<h2>Project</h2>
			</div>
		</div>
		<!-- banner -->

		<!-- projek -->
		<div class="container" style="margin-top: -15%;">
			<div class="row text-center mt-5">
				<div class="col-md-4" style="background-color: #1E34C6; color: white; border-radius: 20px;">
          			<p class="mt-4">Our Profile</p>
        		</div>
				<div class="col-md-4" style="background-color: #007F00; color: white; border-radius: 20px;">
          			<p class="mt-4">Our Profile</p>
        		</div>
				<div class="col-md-4" style="background-color: #FF6401; color: white; border-radius: 20px;">
          			<p class="mt-4">Our Profile</p>
        		</div>
			</div>
		</div>
		<!-- projek -->

		<!-- maps -->
		<div class="maps">
			<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d32659996.625956167!2d95.8783706438947!3d-2.2228861948089245!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2c4c07d7496404b7%3A0xe37b4de71badf485!2sIndonesia!5e0!3m2!1sen!2sid!4v1704541137812!5m2!1sen!2sid" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
		</div>
		<!-- maps -->

		<!-- slide -->
			<p style="font-size: 39px; margin-left: 13%; font-weight: bold; margin-top: 5%;">Client</p>
			<div class="wrapper">
				<div class="slider">
					<div class="slide">
						<img src="https://www.mipcon.co.id/berkas/pertamina.jpg" alt="pertamina">
						<img src="https://www.mipcon.co.id/berkas/santos.png" alt="santos">
						<img src="https://www.mipcon.co.id/berkas/siemen.png" alt="siemens">
						<img src="https://www.mipcon.co.id/berkas/sinarmas.png" alt="sinarmas">
						<img src="https://www.mipcon.co.id/berkas/smart.jpg" alt="smart">
						<img src="https://www.mipcon.co.id/berkas/conocophilips.png" alt="conocophilips">
						<img src="https://www.mipcon.co.id/berkas/bp.png" alt="bp">>
					</div>

					<div class="slide">
						<img src="https://www.mipcon.co.id/berkas/conocophilips.png" alt="conocophilips">
						<img src="https://www.mipcon.co.id/berkas/pertamina.jpg" alt="pertamina">
						<img src="https://www.mipcon.co.id/berkas/smart.jpg" alt="smart">
						<img src="https://www.mipcon.co.id/berkas/santos.png" alt="santos">
						<img src="https://www.mipcon.co.id/berkas/siemen.png" alt="siemens">
						<img src="https://www.mipcon.co.id/berkas/bp.png" alt="bp">
						<img src="https://www.mipcon.co.id/berkas/sinarmas.png" alt="sinarmas">
					</div>
				</div>
			</div>
		<!-- slide -->
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
  background-image: url(../assets/img/26.png);
  background-size: cover;
  display: flex;
  height: 100vh;
}
.hero-content h2{
  color: white;
  font-size: 55px;
  margin-top: -120%;
  text-shadow: #000 9px 9px 9px;
  display: flex;
}
.pj{
	margin-top: -10%;
	padding-left: 3%;
	display: flex;
	justify-content: center;
}
.maps  iframe{
	width: 86%;
	margin-left: 7%;
	height: 80vh;
	margin-top: 5%;
}
.wrapper{
	width: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}
.slider{
	width: 1000px;
	height: 100px;
	position: relative;
	display: flex;
	overflow: hidden;
}
.slide{
	height: 100px;
	display: flex;
	align-items: center;
	animation: slideshow 8s linear infinite;
}
.slide img{
	height: 78px;
	padding: 0 15px 0 15px;
}
@keyframes slideshow{
	0% {transform: translateX(0);}
	100% {transform: translateX(-100%);}
}
</style>