<template>
    <div>
        <img src="~/assets/img/26.png" class="0" alt=""  width="100%" margin-top="15px">
        <h2 style="color: white; font-weight: bolder; font-size: 50px; margin-left: 7%; margin-top: -50%;">Contact</h2>


		<!-- login -->
		<div class="container-fluid">
			<div class="row">
				<div class="col">
					<div class="card" style="background-color: #E2D8D8; margin-right: 5%; height: 80vh;">
						<div class="card-body" style="margin-top: 2%;">
							<div class="form-group">
								<input type="name" class="form-control" placeholder="Name" style="height: 7vh">
							</div>
							<div class="form-group">
								<input type="name" class="form-control" placeholder="Comapny Name" style="height: 7vh">
							</div>
							<div class="form-group">
								<input type="name" class="form-control" placeholder="Phone Number" style="height: 7vh">
							</div>
							<div class="form-group">
								<input type="name" class="form-control" placeholder="Email" style="height: 7vh">
							</div>
							<div class="form-group">
								<input type="name" class="form-control" placeholder="Subject" style="height: 7vh">
							</div>
							<div class="form-group">
    							<textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="message"></textarea>
							</div>
							<button class="lgn">Login</button>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- login -->

		<!-- sosial media -->
		<b-container fluid>
			<b-row style="margin-left: 4%;">
				<div class="col-lg-6 mt-5">
					<button class="button" style="background-color: #44B865; text-decoration: none; color: #E2D8D8; width: 45%; height: 8vh; font-weight: bold;"><a href="#">Registered Office</a></button>
					<b-row>
						<b-col>
							<b-img src="~assets/img/mps.png" style="width: 7%; margin-left: 1%; width: 8%;"></b-img>
							<span style="margin-left: 2%;">Jl. Dewi Sartika No. 4A, Kel. Cililitan,Kec. Keramat Jati, Jakarta Timur</span>
						</b-col>
					</b-row>
					<button class="button" style="background-color: #44B865; text-decoration: none; color: #E2D8D8; width: 45%; height: 8vh; font-weight: bold;"><a href="#">Registered Office</a></button>
					<b-row style="margin-top: 3%;">
						<b-col>
							<b-img src="~assets/img/mps.png" style="width: 7%; margin-left: 1%; width: 8%;"></b-img>
							<span style="margin-left: 2%;">Jl. Dewi Sartika No. 4A, Kel. Cililitan,Kec. Keramat Jati, Jakarta Timur</span>
						</b-col>
					</b-row>
					<b-row style="margin-top: 3%;">
						<b-col>
							<b-img src="~assets/img/9uy.png" style=" margin-left: 3%;  width: 6%;"></b-img>
							<span style="margin-left: 2%;">( +62 21 ) 798 - 8087</span>
						</b-col>
					</b-row>
					<b-row style="margin-top: 3%;">
						<b-col>
							<b-img src="~assets/img/109.png" style="margin-left: 2%;  width: 8%;"></b-img>
							<span style="margin-left: 2%;">( +62 21 ) 798 - 8087</span>
						</b-col>
					</b-row>
					<b-row style="margin-top: 3%;">
						<b-col>
							<b-img src="~assets/img/r11.png" style="margin-left: 2%; width: 6%;"></b-img>
							<span style="margin-left: 2%;">info@mipcon.co.id</span>
						</b-col>
					</b-row>
                </div>
				<div class="col-lg-6 mb-5"> 
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3965.9082629153772!2d106.84125897378081!3d-6.275791461431148!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f24054023d6b%3A0xf26fa09dd6a9f12a!2sMipcon%20Group!5e0!3m2!1sid!2sid!4v1704698936893!5m2!1sid!2sid" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" style="width: 90%; height: 70vh; margin-top: 8%;"></iframe>
                </div>
			</b-row>
		</b-container>
		<!-- sosial media -->

    </div>
</template>

<script>
</script>
<style>
.lgn{
	border: none;
	width: 20%;
	height: 6vh;
	background-color: rgb(131, 127, 127);
	color: white;
	font-weight: bold;
}
.lgn:hover{
	background-color: black;
	color: white;
}
.button{
    border: none;
    margin-top: 5%;
    border-radius: 5px;
    width: 8rem;
    height: 5vh;
}
.button a{
    text-decoration: none;
    color: black;
}
.bgk{
    background-color: green;
    width: 90%;
    height: 150vh;
    margin-top: 10%;
    margin-left: 5%;
    border-radius: 15px;
}
</style>