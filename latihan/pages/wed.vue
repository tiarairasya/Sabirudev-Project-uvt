<template>
  <div>
    <!-- banner -->
    <div class="banner">
        <b-img src="~assets/img/fut.png"></b-img>
        <h1 style="margin-top: -15%; color: white; margin-left: 7%;">Vision</h1>
    </div>
    <!-- banner -->

    <!-- breadcrumb -->
    <b-container>
        <b-row>
            <b-col>
                <b-breadcrumb :items="items"></b-breadcrumb>
            </b-col>
        </b-row>
    </b-container>
    <!-- breadcrumb -->


    <!-- media -->
    <b-container my-4>
        <b-row gx-lg-5 style="margin-top: 2%;">
            <div class="col-lg-6 mb-5"> 
                <b-img src="~assets/img/tyu.jpg" style="width: 100%; border-radius: 15px;"></b-img>
            </div>
            <div class="col-lg-6 mt-5">
                <p class="mt-3"> Our diversified services are delivered for Onshore & Offshore <br>
                Facilities included in midstream, downstream, onshore processing and<br> infrastructure.</p><br>
                <b-row>
                    <b-col cols="6">
                        <button style="border: none; width: 15rem; height: 7vh; border-radius: 5px;" class="gt">Chemical</button>
                    </b-col>
                    <b-col cols="6">
                        <button style="border: none; width: 15rem; height: 7vh; border-radius: 5px;" class="gt">Power</button>
                    </b-col>
                </b-row>
                <b-row style="margin-top: 2%;">
                    <b-col cols="6">
                        <button style="border: none; width: 15rem; height: 7vh; border-radius: 5px;" class="gt">Mining Mineral</button>
                    </b-col>
                    <b-col cols="6">
                        <button style="border: none; width: 15rem; height: 7vh; border-radius: 5px;" class="gt">Agro Industry</button>
                    </b-col>
                </b-row>
            </div>
        </b-row>
    </b-container>
    <!-- media -->

    <!-- dokumentasi -->
    <b-jumbotron style="margin-top: 10%; background-color: #1D355A; height: 500px;">
        <h5 style="color: white; font-size: 24px; margin-top: 5px; margin-left: 8px;">DOCUMENTATION</h5>
        <div class="documentation">
            <b-img src="~/assets/img/mg8.jpg"></b-img>
            <b-img src="~/assets/img/mg9.jpg"></b-img>
            <b-img src="~/assets/img/mg10.jpg"></b-img>
            <b-img src="~/assets/img/mg11.jpg"></b-img>
            <b-img src="~/assets/img/mg12.jpg"></b-img>
        </div>
        <hr style="background-color: white; margin-top: 4%; width: 55%;">
    </b-jumbotron>

    <!-- dokumentasi -->

    <!-- text -->
    <div class="text">
        <h6>Our capabilities for Oil & Gas sectors :</h6><span><h6 style="margin-top: 34px;">Modular Package</h6></span>
        <p>Fuel Gas Condition Package, Heat Transfer Package, Sand Removal Package, Chemical Injection package, Electric <br>Heater Control Panel, Lube oil Blending Package, Fuel Gas Conditioning Package, Custody Transfer metering System,<br> Vapor Recovery Package, Heat Transfer / Hot Oil Package, Modular Pipeline Pump Package,<br> Fuel oil Pumping Package, Oil Pipeline Pump Package, Automation & Control, Tank yard Leakage Control, waste water processing package.</p>

        <h6>Pipeline</h6>
        <p>Feasibility Study, Front Engineering Design, Detail Engineering, Supply, Intallation, Pre-commissioning & Commissioning,<br> Project Management</p>

        <h6>Gas Processing Facilities</h6>
        <p>Feasibility Study, Front Engineering Design, Detail Engineering, Specialty Engineering Services, Plant Assessment, Energy Management<br> Turnarround, Project Management, Static Equipment Chemical Cleaning, Change Out Chatalyst, Flange<br> Management, Maintenance Management Development Services.</p>

        <h6>Oil Refinery</h6>
        <p>Front End Engineering Design, Detail Engineering, Specialty Engineering Services, Plant Assessment, Energy Management, <br>Turnaround, Project Management, Static Equipment Chemical Cleaning, Change Out Chatalyst, Flange Management,<br> Maintenance Management Development Services.</p>
    </div>
    <!-- text -->

  </div>
</template>

<script>
export default{
    data() {
      return {
        items: [
          {
            text: 'Home',
            href: '#'
          },
          {
            text: 'Market Expertise',
            href: '#'
          },
        ]
      }
    }

}
</script>

<style>
.banner img{
    width: 100%;
    display: flex;
}
.gt{
    background-color: #C6BABA;
}
.gt:hover{
    background-color: #1D355A;
    color: white;
}
.breadcrumb{
    margin-top: 17%;
    background-color: white;
    margin-left: 1%;
}
.breadcrumb li a{
    color: red;
    margin-top: 40%;
    margin: 2%;
}
.documentation{
    display: flex;
}
.documentation img{
    width: 20%;
    margin-top: 6%;
    padding: 8px;
}
.text h6{
    margin-left: 8%;
    margin-top: 5%;
    font-weight: bold;
    font-size: 17px;
}
.text p{
    margin-left: 8%;
    margin-top: 2%;
}
</style>