- 👋 Hi, I’m @sarinaziraksima
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


<!DOCTYPE html>
<html>
<head>
<style>


  .circle {
    position: absolute;
    width: 20px;
    height: 20px;
    border-radius: 100%;
    background-color: turquoise;
    animation: move-the-circle 1s infinite;
    transform-origin: center center;
  }
  
  @for $num from 1 through 8 {
    .circle:nth-child(#{$num}) {
      left: ($num - 1) * 30px;
      animation-delay: $num * .1s;
    }
  }
  
  @keyframes move-the-circle {
    0% {
      transform: translate(0, 0) scale(1);
      opacity: 1;
      background-color: turquoise;
    }
    50% {
      transform: translate(0, 50px) scale(.4);
      opacity: .5;
      background-color: blue;
    }
    100% {
      transform: translate(0, 0) scale(1);
      opacity: 1;
      background-color: turquoise;
    }
  }



</style>
</head>
<body>
<!-- HTML -->
<div class="animation-wrapper">
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
</div>


</body>
</html>



<!---

--->
