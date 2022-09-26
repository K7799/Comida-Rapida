<template>
  <headerNav
    nombreEmpresa="La Cocina de Elisa"
    nombreAlumno="Karla Vazquez Amador"
    grupo="10° A - DGS"
  />
  <br />
  <div class="container">
    <br />
    <h3 class="text-center">Ensaladas y Entrantes</h3>
    <br />
    <card
      url="https://i.blogs.es/a87bbf/ensalada-poke-de-atun-y-algas-con/1366_2000.jpeg"
      nombre="Ensalada poke de atún y algas con aguacate"
      descripcion="Si usamos pescado congelado, descongelar la noche antes sobre una rejilla en la parte menos fría de la nevera. Secar bien con papel de cocina y cortar en cubos de tamaño de un bocado con un buen cuchillo. Reservar"
      costo="$30.00"
    />
    <card
      url="https://i.blogs.es/89fba0/panzanella-italiana/1366_2000.jpg"
      nombre="Panzanella italiana"
      descripcion="Perfecta para usar trozos de pan que tengáis por casa y para sacar todo el potencial de esos tomates cherry que tan buen resultado dan."
      costo="$60.00"
    />
    <card
      url="https://i.blogs.es/0299ab/ensalada-caprese-de-pasta/1366_2000.jpg"
      nombre="Ensalada caprese de pasta"
      descripcion="Otro icono de la frescura italiana que podemos resolver con sólo un par de ingredientes: mozzarella y tomate."
      costo="$90.00"
    />
    <card
      url="https://i.blogs.es/bec38d/5.-ensalada-griega/1366_2000.jpg"
      nombre="Ensalada griega"
      descripcion="El Mediterráneo nos sirve de ejemplo para irradiar frescura desde sus platos y en este caso hacemos una versión griega donde no falta el queso feta y la aceituna negra."
      costo="$120.00"
    />
    <card
      url="https://i.blogs.es/001d17/7.-ensalada-de-pepino-al-estilo-japones/1366_2000.jpg"
      nombre="Ensalada de pepino al estilo japonés"
      descripcion="El truco está en mantener el frescor del pepino y reforzarlo con hierbas aromáticas y con una sutil vinagreta, típicamente japonesa, cuyos productos puedes encontrar en cualquier tienda oriental."
      costo="$150.00"
    />
    <card
      url="https://i.blogs.es/90a618/namasu-de-zanahoria-y-nabo/1366_2000.jpg"
      nombre="Namasu de zanahoria y nabo"
      descripcion="Es fresca, es sabrosa y además tiene ese puntito crocante que le dan sus ingredientes principales, siendo muy agradable al paladar."
      costo="$180.00"
    />
  </div>
  <myFooter fecha="22-09-2022" />
</template>
<script>
import HeaderNav from "./components/HeaderNav.vue";
import Card from "./components/Card.vue";
import MyFooter from "./components/MyFooter.vue";
export default {
  components: { Card, HeaderNav, MyFooter },
};
</script>
<style scoped>
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
</style>
