<template>
  <div>
    <div>
      <b-navbar toggleable="lg" type="dark" class="navbar">
        <b-navbar-brand class="navbar"></b-navbar-brand>
        <img src="~assets/img/lgo67.png" style="width: 7%; margin: 20px; margin-left: 2%; margin-top: 20px;">
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="navbar-nav m-auto d-flex">
            <b-nav-item href="/"><li>Home</li></b-nav-item>
            <b-nav-item href="/about_us"><li>About Us</li></b-nav-item>
            <b-nav-item href="/thegroup"><li>The group</li></b-nav-item>
            <b-nav-item href="/wed"><li>What We Do</li></b-nav-item>
            <b-nav-item href="/project"><li>Project</li></b-nav-item>
            <b-nav-item href="/qhse"><li>QHSE</li></b-nav-item>
            <b-nav-item href="/news"><li>News & Career</li></b-nav-item>
            <b-nav-item href="/contact"><li>Contact</li></b-nav-item>
          </b-navbar-nav>

          <span class="btn btn-1">
            <input type="checkbox" name="" id="switch">
            <label for="switch"></label>
          </span>  
        </b-collapse>
      </b-navbar>
    </div>


  </div>
</template>

<script>
export default {
   
}
</script>

<style>
.navbar{
  position: sticky;
  top:0; left:0; right:0;
  background-color: white;
  z-index: 1000;
}
li{
  color: #0F1655;
  position: relative;
}
li:hover{
  background-color: #0F1655;
  color: white;
  border-radius: 20px;
}
.btn{
  position: relative;
  height: 56px;
}
.btn input{
  position: relative;
  background-color: #2D325A;
  width: 87px;
  height: 32px;
  margin-top: 6%;
  border-radius: 25px;
  outline: none;
  cursor: pointer;
  appearance: none;
  font-size: 'Raleway',sans-serif;
  font-weight: bolder;
  box-shadow: 1px 6px 11px #000000;
}
.btn input:before,
.btn input:after{
  z-index: 2;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  color: white;
}
.btn input:before{
  content: "IN";
  left: 13px;
}
.btn input:after{
  content: "EN";
  right: 13px;
}
.btn label{
  z-index: 1;
  position: absolute;
  top: 18px;
  bottom: 10px;
  border-radius: 20px;
}
.btn .btn-1 input{
  transition: 0.2s -0.1s;
}
.btn .btn-1 input:checked{
  background: white;
}
.btn.btn-1 input:checked:before{
  color: #111;
  transition: color 0.5s 0.2s;
}
btn.btn-1 input:checked:after{
  color: black;
  transition: color 0.5s;
}
.btn.btn-1 input:checked + label{
  left: 19px;
  right: 53px;
  height: 24px;
  margin-top: -2px;
  background: white;
  transition: left 0.5s, right 0.4s 0.2s;
}
.btn.btn input:not(:checked){
  background: #2D325A;
  transition: background 0.5s -0.1s;
}
.btn.btn-1 input:not(:checked):before{
  color: white;
  transition: color 0.5s;
}
.btn.btn-1 input:not(:checked) + label{
  left: 53px;
  right: 19px;
  margin-top: -2px;
  height: 24px;
  background: white;
  transition: left 0.4s 0.2s, right 0.5s, background 0.35s;
}
</style>