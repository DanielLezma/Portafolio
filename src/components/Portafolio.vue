<template>
  <div class="hello">
    <H1>Portafolio</H1>
    <H2>Daniel Ledezma</H2>

    <h3>Enlaces a Páginas</h3>
    <div class="button-container">
      
      <a href="https://github.com/DanielLezma/LNG_IV.git" target="_blank" class="button">Proyectos</a>

      <a href="https://github.com/DanielLezma/ExchangeApp.git" target="_blank" class="button">Proyectos</a>
      <a href="https://github.com/DanielLezma/Calculadora.git" target="_blank" class="button">Proyectos</a>
      <a href="https://github.com/DanielLezma/CV.git" target="_blank" class="button">Proyectos</a>
    </div>
    <br>

    <h2>Acerca de</h2>
      <p>Hola soy Daniel Ledezma estudiante de ingenieria en sistemas y este es mi portafolio 
      </p>
      <br>
      <br>
   
   
      <h2>Habilidades</h2>
      <br>
      <ul class="skills-list">
          Conocimiento de Windows
          <br>
          Principios básicos de seguridad informática.
          <br>
          Desarrollo de Aplicaciones Móviles en Android estudio
          <br>
          Principios básicos de aplicaciones para Android.
          <br>
          Uso de herramientas como Android Studio.
          <br>
          Adaptabilidad:
          <br>
          Facilidad para aprender nuevas tecnologías y adaptarse a cambios.
        <br>
        <li>Python: medio</li>
        <li>Java: medio</li>
        <li>Android: basico</li>
        <li>Vue.js: vacico</li>
        <br>

      </ul>

    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
    }
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
  font-size: 18px;
}

.button-container {
  display: flex;
  justify-content: left;
  gap: 10px;
  margin-top: 20px;
}

button, .button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  text-decoration: none;
  color: inherit;
  border: none;
  background-color: #8f8f8fc8;
}

button:hover, .button:hover {
  background-color: #0000ff;
  color: rgb(4, 3, 3);
}

.section {
  margin-top: 20px;
  color: rgb(17, 15, 15);
}

.skills-list {
  list-style-type: none; 
  padding-left: 0; 
}
#skills {
  margin: 150px;
}
.skills-list li {
  font-size: 18px; 
  line-height: 1.6; 
}


#about {
  margin: 150px;
}


h2 {   
  font-size: 24px;
}

p {
  font-size: 18px;
  line-height: 1.6;
}




</style>
