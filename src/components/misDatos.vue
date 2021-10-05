<template>
<div class="footer">
    <footer>
        {{ nombre }} <br/>
      Grupo: {{ Grupo }}<br/>
        Materia: {{ Materia }}<br/>
      Carrera: {{ Carrera }}
    </footer>
</div>
</template>

<script>
export default {
  name: "misDatos",
  props: {
    nombre: String,
  },
  data() {
    return {
      Grupo: '4° A',
      Materia: 'Aplicaciones Web Orientadas a Servicios.',
      Carrera: 'Tecnologias de la Informacion Desarrollo de Software Multiplataforma.'
    };
  },
};
</script>

<style scoped>
.footer{
    margin: 20px 0px 20px 0;
    background-color: yellow;
    color: rgb(255, 10, 10);
    text-align: center;
}
</style>