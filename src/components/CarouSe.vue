<template>
  


    

    <div class="section full-height over-hide px-4 px-sm-0">
        <div class="container">
            <div class="row full-height justify-content-center">
                <div class="col-lg-10 col-xl-8 align-self-center padding-tb">
                    <div class="section mx-auto text-center slider-height-padding">
                        <input class="checkbox frst" type="radio" id="slide-1" name="slider" checked/>
                        <label for="slide-1"></label>
                        <input class="checkbox scnd" type="radio" name="slider" id="slider-2"/>
                        <label for="slider-2"></label>
                        <input class="checkbox thrd" type="radio" name="slider" id="slider-3"/>
                        <label for="slider-3"></label>
                        <input class="checkbox foth" type="radio" name="slider" id="slider-4"/>
                        <label for="slider-4"></label>
                        <ul>
                        
                            <li href="#google1">
                            
                                <a href="#google1"><span>CREATE TOKEN 👆</span></a>
                            </li>

                            
                            <li>
                            <a href="#google2">
                                <span>MINT NFT 👆</span>
                                   </a>
                            </li>
                         
                            <li>
                            <a href="#google3">
                                <span>SPL GAMBLE 👆</span>
                                  </a>
                            </li>
                            <li>
                                <span>WALLET/DEX 👆</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>



label {
    
    background-size: 60% !important;
    
    cursor: url(https://i.imgur.com/ek44f48.png), auto !important;

}

/* Please ❤ this if you like it! */


/* ========================================= * 
                BEST VIEWED FULLSCREEN
   https://codepen.io/ig_design/full/NWxwBvw
 * ========================================= */
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700,800,900');

body{
    font-family: 'Poppins', sans-serif;
    font-weight: 300;
    font-size: 15px;
    line-height: 1.7;
    color: #343434;
    background-color: #f1f2f6;
    overflow-x: hidden;
}
a {
    cursor: pointer;
}
a:hover {
    text-decoration: none;
}

.section{
  position: relative;
  width: 80%;
  display: block;
     
    margin-right: 10%;
}
.full-height{
  
}
.over-hide{
  overflow: hidden;
}
.padding-tb{
  padding: 100px 0;
  
}
[type="radio"]:checked,
[type="radio"]:not(:checked){
  position: absolute;
  left: -9999px;
}
.checkbox:checked + label,
.checkbox:not(:checked) + label{
  position: relative;
    cursor: pointer;
    margin: 0 auto;
    text-align: center;
    margin-right: 1em;
    margin-left: 1em;
    display: inline-block;
    width: 50px;
    height: 50px;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: 50%;
    box-sizing: border-box;
    transition: all .2s ease;
    background-image: url(https://i.imgur.com/uKGL9BF.png);

    
}
.checkbox.scnd + label{
  background-image: url(https://i.imgur.com/PfdVSvr.png);
}
.checkbox.thrd + label{
  background-image: url(https://i.imgur.com/HlRhfGw.png);
}
.checkbox.foth + label{
  background-image: url('https://i.imgur.com/Qa9kTYj.png');
}

.checkbox:checked + label{
  
  transform: scale(1.3);
    
    background-size: 100%!important;
  
    
}
@keyframes border-transform {
  0%, 100% { 
    border-radius: 63% 37% 54% 46% / 55% 45% 55% 45%; 
  } 
  7% { 
    border-radius: 50% 50% 60% 40% / 50% 50% 40% 60%; 
  }
  14% { 
    border-radius: 40% 60% 54% 46% / 49% 51% 49% 51%; 
  } 
  21% { 
    border-radius: 45% 55% 50% 50% / 60% 40% 60% 40%; 
  }
  28% { 
    border-radius: 54% 46% 38% 62% / 49% 51% 49% 51%; 
  } 
  35% { 
    border-radius: 60% 40% 45% 55% / 40% 60% 40% 60%; 
  }
  42% { 
    border-radius: 61% 39% 55% 45% / 61% 39% 61% 39%; 
  } 
  49% { 
    border-radius: 55% 45% 50% 50% / 55% 45% 55% 45%; 
  }
  56% { 
    border-radius: 61% 39% 67% 33% / 70% 30% 70% 30%; 
  } 
  63% { 
    border-radius: 50% 50% 60% 40% / 50% 50% 40% 60%; 
  }
  70% { 
    border-radius: 50% 50% 34% 66% / 56% 44% 56% 44%; 
  } 
  77% { 
    border-radius: 55% 45% 50% 50% / 40% 60% 40% 60%; 
  }
  84% { 
    border-radius: 46% 54% 50% 50% / 35% 65% 35% 65%; 
  }
  91% { 
    border-radius: 50% 50% 60% 40% / 55% 45% 55% 45%; 
  }
}
.slider-height-padding {
  padding-top: 440px;
}

ul {
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  width: 100%;
  z-index: auto;
  padding: 0;
  margin: 0;
  transition: 2s;
  list-style: none;
}
ul li {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  display: block;
  padding: 0;
  transition:2s;
  margin: 0;
  list-style: none;
  height: 400px;
  filter:drop-shadow(2px 4px 6px black);
  background-size: contain;
  background-repeat:no-repeat;
  background-position: center;
  background-image: url('https://i.imgur.com/stPqqFI.png');
  border-radius: 50%;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  font-weight: 900;
  font-size: 16px;
  letter-spacing: 2px;
  line-height: 2.7;
  color: #343434;
  writing-mode: vertical-rl;
  opacity: 0;
  pointer-events: none;
  -webkit-transition: all 2s linear;
  transition: all 2s ease;
  cursor: e-resize;
animation: myyAnim 1s ease 0s 1 reverse forwards;
  animation-delay:4.5s;
}

.checkbox:not(:checked)+label {
    opacity: 0.5;
    filter: drop-shadow(2px 4px 6px grey);
}

ul li span {
  
    font-size: 1em;
    font-weight: 900;
    font-family: Sora;
    color: #fff;
    line-height: 10px;
    background: #0000;
    padding: 10px;
    border-radius: 13px;
    animation-delay: 6s;
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    width: 100%;
    height: 100%;
    text-shadow: 2px 3px 7px black;
    
    
}
ul li:nth-child(2) {
  background-image: url('https://i.imgur.com/dBKrI4q.png');
}
ul li:nth-child(3) {
  background-image: url('https://i.imgur.com/CdlytDl.png');
}
ul li:nth-child(4) {
  background-image: url('https://i.imgur.com/LcecQpl.gif');
}


.checkbox.frst:checked ~ ul li:nth-child(1) {
  opacity: 1;
  pointer-events: auto;
  border-radius: 16px;
}
.checkbox.scnd:checked ~ ul li:nth-child(2) {
  opacity: 1;
  pointer-events: auto;
  border-radius: 16px;
}
.checkbox.thrd:checked ~ ul li:nth-child(3) {
  opacity: 1;
  pointer-events: auto;
  border-radius: 16px;
}
.checkbox.foth:checked ~ ul li:nth-child(4) {
  opacity: 1;
  pointer-events: auto;
  border-radius: 16px;
}

li:hover {
    transition: 1s;
    transform: scale(0.95);
}

.logo {
    position: absolute;
    top: 30px;
    right: 30px;
    display: block;
    z-index: 100;
    transition: all 250ms linear;
}
.logo img {
    height: 26px;
    width: auto;
    display: block;
}



@media (max-width: 767px) {
  .slider-height-padding {
    padding-top: 340px;
  }


.checkbox:checked + label,
.checkbox:not(:checked) + label{
  
   
    filter:none!important;
    
    
}

  ul li {
    height: 300px;
    font-size: 13px;
    letter-spacing: 1px;
  }
}

@media (max-width: 575px) {
  .slider-height-padding {
    padding-top: 240px;
  }

ul li span {

  
  
    
    
    

}

label {
    
    margin-top: 50px !important;
}

  .section {
    width:100%!important;
     scale: inherit!important;
    margin-top: inherit!important;
    margin-right: inherit!important;
  }
  ul li {
    height: 200px;
    zoom:130%;
  }
}

@keyframes myyAnim {
  0%,
  100% {
    transform: translateX(0%);
    transform-origin: 50% 50%;
  }

  15% {
    transform: translateX(-30px) rotate(-6deg);
  }

  30% {
    transform: translateX(15px) rotate(6deg);
  }

  45% {
    transform: translateX(-15px) rotate(-3.6deg);
  }

  60% {
    transform: translateX(9px) rotate(2.4deg);
  }

  75% {
    transform: translateX(-6px) rotate(-1.2deg);
  }
}

ul:hover {
    scale: 1.05;
    transition: 1s;
}

</style>
