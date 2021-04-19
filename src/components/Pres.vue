<template>
<div class="pres" style="background-color: #121212;">
<h1>Lucas Lubasinski</h1>
<p class="text-pres">Étudiant à l'école de Webstart en développement Web et mobile,<br> passionné par la codage depuis plusieurs années.<br>
  Je suis à la recherche d'un contrat pro en développement informatique. <br>
  Je connais et utilise plusieurs langages dont Php, Javascript, Html/CSS, C++ et Python <br>( j'utilise aussi Vue.js, Node.js, Laravel, Bootstrap, Tailwinds, Ionic ).
</p>
  
<br>
  <a href="/cv.pdf" download="CV de Lucas Lubasinski">
      <button class=" animate-pulse bg-blue-500 px-5 py-2 text-lg font-semibold tracking-wider text-white rounded-full hover:bg-blue-600" style="background-color: #5D19FF">Télécharger mon CV</button>
  </a>
  <br>
<div style="display:flex; justify-content: center; margin-top: 1%;">
  <a href="https://github.com/Lucasinho11" style="margin-right:2%; color:#36FFB0;" class="gitin">Mon Github</a>
  <a href="https://www.linkedin.com/in/lucas-lubasinski/" style="margin-left:2%;color:#36FFB0;" class="gitin">Mon LinkedIn</a>
</div>

</div>
<br>


<div class="arrow">
    <img  class="animate-bounce" src="/arrow.svg" alt="" style="width:5%;">   
</div>
<div>
  <h1 class="projects-title">Mes projets en ligne</h1>
  <div class="projects">
    <a href="https://vitality-laravel.herokuapp.com/" class="project1" target="_blank">
      <svg style="margin-right:1%;" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="php" width="2%" class="svg-inline--fa fa-php fa-w-20" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512"><path fill="currentColor" d="M320 104.5c171.4 0 303.2 72.2 303.2 151.5S491.3 407.5 320 407.5c-171.4 0-303.2-72.2-303.2-151.5S148.7 104.5 320 104.5m0-16.8C143.3 87.7 0 163 0 256s143.3 168.3 320 168.3S640 349 640 256 496.7 87.7 320 87.7zM218.2 242.5c-7.9 40.5-35.8 36.3-70.1 36.3l13.7-70.6c38 0 63.8-4.1 56.4 34.3zM97.4 350.3h36.7l8.7-44.8c41.1 0 66.6 3 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7h-70.7L97.4 350.3zm185.7-213.6h36.5l-8.7 44.8c31.5 0 60.7-2.3 74.8 10.7 14.8 13.6 7.7 31-8.3 113.1h-37c15.4-79.4 18.3-86 12.7-92-5.4-5.8-17.7-4.6-47.4-4.6l-18.8 96.6h-36.5l32.7-168.6zM505 242.5c-8 41.1-36.7 36.3-70.1 36.3l13.7-70.6c38.2 0 63.8-4.1 56.4 34.3zM384.2 350.3H421l8.7-44.8c43.2 0 67.1 2.5 90.2-19.1 26.1-24 32.9-66.7 14.3-88.1-9.7-11.2-25.3-16.7-46.5-16.7H417l-32.8 168.7z"></path></svg>
      <p class="logos" style="font-weight:bold;">Site de réservation réalisé avec Laravel</p>
    </a>
    <a href="https://vitality-ionic.herokuapp.com/tabs/Home" class="project1" target="_blank">
    <svg  style="margin-right:1%;" width="2%" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="vuejs" class="svg-inline--fa fa-vuejs fa-w-14" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M356.9 64.3H280l-56 88.6-48-88.6H0L224 448 448 64.3h-91.1zm-301.2 32h53.8L224 294.5 338.4 96.3h53.8L224 384.5 55.7 96.3z"></path></svg>
       <p class="logos" style="font-weight:bold;"> Version mobile du site de réservation avec du Vue.js et Ionic</p>
    </a>
  </div>
  
</div>


</template>

<script>
export default {
  name: "Pres",

};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.pres{
  width: 100%;
  height: 50vh;
}

.arrow{
  margin-top: 3%;
  display: flex;
  justify-content: center;
}
h1 {
  padding-top: 5%;
  color: #36FFB0;
  font-size: 50px;
  font-weight: bold;
}
h2{
  color: #5D19FF;
  font-size: 20px;
  font-weight: bold;
}
.projects{
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.project1{
  margin-top: 2%;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  color: black;

}
.project1:hover{
  color:#36FFB0;
  
}
.projects-title {
  color: #5D19FF;
  font-size: 30px;
  font-weight: bold;
}
.text-pres{
  text-align: center;
  color:white;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.gitin:hover{
  color: #5D19FF;
}
@media (max-width: 600px) {
h1 {
  padding-top: 5%;
  color: #36FFB0;
  font-size: 30px;
  font-weight: bold;
}
.text-pres{
  text-align: center;
  color:white;
  font-size:90%;
}
.projects-title {
  color: #5D19FF;
  font-size: 20px;
  font-weight: bold;
}
.svg-inline--fa{
  width: 5%;
  display: none;
}
.logos{
  font-size: 75%;
}
.project1{
  margin-top: 1%;
  border-radius: 20px;
  display: flex;
  justify-content: center;
  color: black;

}
}

</style>
