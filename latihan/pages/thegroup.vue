<template>
  <div>
    <!-- banner -->
      <div class="banner">
        <b-img src="~assets/img/nj.png"></b-img>
        <h3 class="heading" style="margin-left: 8%; margin-top: -15%; color: white;  text-shadow: #000 9px 9px 9px;">We Deliver Industrial Solution And<br>Services</h3>
      </div>
		<!-- banner -->  

    <!-- paragraf -->
      <div class="paragraf">
        <h6 style="margin-top: 15%; text-align: center; font-weight: bold;">PT. MIPCON PRIMA INDUSTRI ( MPI ) under the holding company PT. MIPCON GLOBAL PRATAMA</h6>
        <p style="text-align: center;">having the operating office at Jln. Siaga 2, No.25 South Jakarta – Indonesia, wich has it expertise <br>in EPCIC-OM such as EPC, Construction, Fabrication, Installation, Commissioning, Operation & Maintenance, Turnarround / Shutdown, Plant Revamping ,<br> Plant Relocation , and Other services related to any Plant ( Industrial, Chemical, Oil & gas & Energy ) which under operating and require maintenance.</p>
      </div>
    <!-- paragraf -->   

    <!-- percobaan-->
    <div class="index-section1" style="margin-top: 10%;">
      <div class="page-width feature-row-wrapper">
        <div class="feature-row1">
          <div class="feature-row1__item feature-row__item--overlap-images aos-init aos-animate" style="max-width: 700px" data-aos="">
            <div>
              <div class="image-wrap" style="height: 0; padding-bottom: 147.39941118743866%;">
                <img class="feature-row__image lazyautosizes lazyloaded" data-widths="[180, 360, 540, 750, 900, 1080]" data-aspectratio="0.6654" data-sizes="auto" alt="" src="~assets/img/yut.jpg" style="width: 22rem;">
              </div>
            </div>
            <div>
              <div class="image-wrap" style="height: 0; padding-bottom: 150.28554253080853%;">
                  <img class="feature-row__image lazyautosizes lazyloaded" data-widths="[180, 360, 540, 750, 900, 1080]" data-aspectratio="0.6784287616511319" data-sizes="auto" alt="" src="~assets/img/9ju.jpg" style="width: 22rem;">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- percobaan-->

    <!-- service -->
      <b-container my-4>
        <b-row gx-lg-5>
          <b-col lg="12" style="margin-top: 20%;">
            <b-img src="~assets/img/rut.png" style="width:  80rem; margin-left: -7%;"></b-img>
            <div class="overlay-text">
              <h3>SERVICE</h3>
              <ul>
                <li>Modular Package</li>
                <li>EPC</li>
                <li>Precommissioning</li>
                <li>Commissioning Star Up</li>
                <li>Plant Operation and Maintenance</li>
                <li>Plant Turnarround</li>
                <li>Equitmen Repair and Overhaul</li>
              </ul>
            </div>
          </b-col>
        </b-row>
      </b-container>
    <!-- service -->
        
    <!-- percobaan-->
    <div class="index-section" style="margin-top: 10%;">
      <div class="page-width feature-row-wrapper">
        <div class="feature-row">
          <div class="feature-row__item feature-row__text feature-row__text--right text-left aos-init aos-animate" data-aos="">
            <div class="h4 appear-delay-1">Our Vision</div>
            <div class="rte appear-delay-2">
              <p>To Become a global leader one stop services company which reliable, trustworthy, responsive in plant services business.</p>
            </div>
            <div class="h4 appear-delay-1">Our Mision</div>
            <div class="rte appear-delay-2">
              <p>As a centre of high qualified experiences technical engineers and specialist in Industrial Plant.</p>
            </div>
          </div>
          <div class="feature-row__item feature-row__item--overlap-images aos-init aos-animate" style="max-width: 700px" data-aos="">
            <div>
              <a href="/pages/investing-in-women">
                <div class="image-wrap" style="height: 0; padding-bottom: 150.28554253080853%;">
                  <img class="feature-row__image lazyautosizes lazyloaded" data-widths="[180, 360, 540, 750, 900, 1080]" data-aspectratio="0.6654" data-sizes="auto" alt="" src="~assets/img/yut.jpg" style="width: 22rem; margin-left: 10%;">
                </div>
              </a>
            </div>
            <div>
              <a href="/pages/investing-in-women">
                <div class="image-wrap" style="height: 0; padding-bottom: 147.39941118743866%;">
                  <img class="feature-row__image lazyautosizes lazyloaded" data-widths="[180, 360, 540, 750, 900, 1080]" data-aspectratio="0.6784287616511319" data-sizes="auto" alt="" src="~assets/img/9ju.jpg" style="width: 22rem;">
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>

</div>
    <!-- percobaan-->     
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
.box{
    z-index: 9999;
    padding: 15px;
}
/* service */
.overlay-text {
  position: absolute;
  top: 55%; 
  left: 15%; 
  transform: translate(-50%, -50%);   
}
.overlay-text h3{
    margin-left: 5%;
}
.overlay-text ul{
    margin-top: 10%;
}
.overlay-text li{
    color: black;
}
.overlay-text li:hover{
    background-color: bisque;
}
/* service */


/* percobaan */
@media only screen and (min-width:769px){
  .index-section{
    margin:75px 0;
  }

  .index-section--small{
    margin:30px 0;
  }

  .section--divider{
    padding-top:75px;
  }

  .index-section--faq{
    margin:75px 0 37.5px;
  }

  .newsletter-section{
    padding:75px 0;
  }

  .testimonials-section{
    padding:75px 0;
  }
}

.page-blocks--flush .page-width{
  padding:0;
}

.page-blocks>div:first-child .index-section{
    margin-top:0;
  }

.feature-row-wrapper{
  overflow:hidden;
  direction:ltr;
}

.feature-row{
  margin:0 auto;
  display:flex;
  justify-content:space-between;
  align-items:center
}

@media only screen and (min-width:1050px){

.feature-row{
    margin:0 6%
}
  }

@media only screen and (max-width:768px){

.feature-row{
    flex-direction:column;
    margin:0
}
  }

@media only screen and (max-width:959px){
  .feature-row--small-none{
    display:block;
  }
}

.feature-row__item{
  flex:0 1 57%;
  margin:0 auto
}

@media only screen and (max-width:768px){

.feature-row__item{
    flex:1 1 auto;
    max-width:100%;
    min-width:100%
}
  }

.feature-row__item--overlap-images{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:0 0 15px;
  margin:0 0 0 -30px
}

@media only screen and (min-width:769px){

.feature-row__item--overlap-images{
    padding: 50px 0;
    margin:0 auto;
}
  }

.feature-row__item--overlap-images>*{
    width:50%
  }

.feature-row__item--overlap-images>:first-child{
      z-index:1;
      transform:translate(30px, 30px)
    }

@media only screen and (min-width:769px){

.feature-row__item--overlap-images>:first-child{
        transform:translate(50px, 50px)
    }
      }

.feature-row__item--overlap-images svg{
    border:2px solid;
    border-color:#ffffff;
    border-color:var(--colorBody);
  }

.feature-row__image{
  display:block;
  margin:0 auto;
  order:1
}

@media only screen and (min-width:769px){

.feature-row__image{
    order:2
}
  }

.feature-row__text{
  min-width:43%;
  flex:0 1 43%;
  padding:0;
  margin-left: 5%;
}

@media only screen and (max-width:768px){

.feature-row__text{
    order:2;
    margin-top:0;
    padding:30px 20px 0;
    padding-bottom:0;
}
  }

.feature-row__text .rte{
    margin:0;
  }
@media only screen and (min-width:769px){
  .feature-row__text--left{
    padding-left:60px;
  }

  .feature-row__text--right{
    padding-right:60px;
  }
}
/* percobaan */
</style>