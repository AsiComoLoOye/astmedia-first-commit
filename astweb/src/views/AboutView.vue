<script setup>
import WelcomeItem from '../components/WelcomeItem.vue'
import VisionIcon from '../components/icons/IconVision.vue'
import TodoIcon from '../components/icons/IconTodo.vue'
import AboutusIcon from '../components/icons/IconAboutus.vue'
</script>

<template>
  <div class="about">
    <WelcomeItem>
    <template #icon>
      <AboutusIcon />
    </template>
    <template #heading>Acerca de AST Media</template>
    <p>AST Media es la primera agencia especializada en comunicación y estrategia de medios sociales en Costa Rica. Con experiencia desde 2007 en atención a clientes en Costa Rica, Panamá, Centro América, Suramérica, México, República Dominicana y España, nuestra visión nos lleva un paso más adelante del manejo tradicionales de medios sociales.</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <VisionIcon />
    </template>
    <template #heading>Visión</template>
    <p>Ser una empresa dinámica adaptada a las necesidades de comunicación de las marcas en la nueva sociedad digital, cuyo modelo de negocio se basa en una estrategia de interacción en los Medios Sociales con las personas y personajes que interactúan en ellas para crear verdaderas redes sociales.</p>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <TodoIcon />
    </template>
    <template #heading>Misión</template>
    <p>Permitir a personas físicas y jurídicas el acceso a las estrategias más modernas de los Medios Sociales; acompañandoles en la correcta y óptima gestión de las herramientas y aplicaciones que se disponen, para aplicar dichas estrategias según sus necesidades particulares.</p>

  </WelcomeItem>
    
    
  </div>
</template>

<style>
@media (min-width: 1024px) {
  
}
</style>
