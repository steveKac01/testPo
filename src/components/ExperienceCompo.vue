<template>
  <div>

<h1>EXPERIENCE {{this.isDarkMode?"Theme NUIT":"theme JOUR"}}</h1>
<ul>
  <li>2022: Actuellement en recherche de stage.</li>
  <li>2021-2022: Formation développeur web et web mobile à la CCI lyon.
    <div class="formation-caroussel">SOME IMAGES HERE</div>
  </li>
</ul>

</div> 
</template>

<script>
export default {
  name: 'ExperienceCompo',
  props: {
    isDarkMode: Boolean
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul{

  padding:0;
}
li{
   margin: 0;
  padding:10px;
  background-color: white;
}
li:nth-child(even){
  color: white;
  background: var(--background-footer);
}
.formation-caroussel{ /*  check typo*/
margin-top: 10px;

}
</style>
