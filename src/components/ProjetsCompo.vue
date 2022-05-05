<template>
  <div>
<h1>PROJETS {{this.isDarkMode?"Theme NUIT":"theme JOUR"}}</h1>
<div class="project-container">
                <!-- 
                <div class="empty one"><img src="img/projet_01.jpg" alt="Exemple frontpage">
                    <figcaption>Frontpage exemple</figcaption>
                </div>
                <div class="empty two"></div>
                <div class="empty three"></div>
                <div class="empty four"></div>-->
                <!-- PROJECT 1 -->
                <div class="project">
                    <div class="project-img"><img src="@/assets/img/project1.png" alt="Exemple frontpage">
                        
                    </div>
                    <div class="desc-project">
                        <H4>Projet de fin de formation (WIP)</H4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores quae animi, tenetur optio
                            magni dolorum vel repudiandae? Minima recusandae iste iure voluptates assumenda ut illo.</p>
                        <a href="githublink">GITHUB</a>
                    </div>

                </div>
                <!-- PROJECT 2 -->
                <div class="project">
                    <div class="empty one"><img src="@/assets/img/project1.png" alt="Exemple frontpage">
                        <figcaption>Architecture MVC</figcaption>
                    </div>
                    <div class="desc-project">
                        <H4>Mini blog suivant l'architecture MVC et DAO</H4>

                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores quae animi, tenetur optio
                            magni dolorum vel repudiandae? Minima recusandae iste iure voluptates assumenda ut illo.</p>
                        <a href="githublink"><font-awesome-icon icon="fab fa-github "   alt="github-icon" /> GITHUB</a>
                    </div>
                </div>

                  <!-- PROJECT 3 -->
                  <div class="project">
                    <div class="empty one"><img src="@/assets/img/project3.jpg" alt="Exemple frontpage">
                        
                    </div>
                    <div class="desc-project">
                        <H4>Exemple de front page</H4>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores quae animi, tenetur optio
                            magni dolorum vel repudiandae? Minima recusandae iste iure voluptates assumenda ut illo.</p>
                        <a href="githublink"><font-awesome-icon icon="fab fa-github "   alt="github-icon" /> GITHUB</a>
                    </div>

                </div>
<!-- Deplo-->
            </div>
            
  </div>
</template>

<script>
export default {
  name: 'ProjetsCompo',
  props: {
    isDarkMode: Boolean
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "@/assets/style/projects.css";
</style>
