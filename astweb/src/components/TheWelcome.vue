<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Ecosistema digital</template>
    <ul>
      <li>Medios noticiosos</li>
      <li>Fanpages en facebook</li>
      <li>Canales de Telegram, Instagram, TikTok y Twitter</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Listening</template>

    Pasamos del "social listening" al "cultural listening", donde más que escuchar, es participar en la conversación con el mismo lenguaje de las tribus sociales.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Mediciones</template>

    Las mediciones del impacto, más que cuantitativa es cualitativa. No solo es conseguir números de respuestas, sino respuestas de calidad, midiendo el sentimiento.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Mensajes claves</template>

    Identificamos los mensajes clave, y respondemos a lo que hay que responder, sin desgastarse en discusiones sin sentido.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Troles</template>

    No somos troles, ni los usamos. Las respuestas orgánicas de la comunidad pesan más que cientos de opiniones generadas por troles falsos.
  </WelcomeItem>
</template>
