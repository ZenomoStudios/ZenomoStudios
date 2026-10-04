<div align="center">

<style>
  .glint-container {
    position: relative;
    display: inline-block;
    width: 100%;
    overflow: hidden;
  }
  
  .glint-container img {
    display: block;
    width: 100%;
  }
  
  .glint {
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(
      90deg,
      transparent 0%,
      rgba(255, 255, 255, 0.3) 25%,
      rgba(255, 255, 255, 0.6) 50%,
      rgba(255, 255, 255, 0.3) 75%,
      transparent 100%
    );
    animation: glintSlide 3s infinite;
    pointer-events: none;
  }
  
  @keyframes glintSlide {
    0% {
      left: -100%;
    }
    100% {
      left: 100%;
    }
  }
</style>

<div class="glint-container">
  <img src="https://raw.githubusercontent.com/ZenomoStudios/ZenomoStudios/main/assets/AssetD.png" width="100%" alt="">
  <div class="glint"></div>
</div>

<br>

<div class="glint-container">
  <img src="https://raw.githubusercontent.com/ZenomoStudios/ZenomoStudios/main/assets/AssetB.webp" width="100%" alt="">
  <div class="glint"></div>
</div>

<br>

<div class="glint-container">
  <img src="https://raw.githubusercontent.com/ZenomoStudios/ZenomoStudios/main/assets/AssetD.png" width="100%" alt="">
  <div class="glint"></div>
</div>

</div>
