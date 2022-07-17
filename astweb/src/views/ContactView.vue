<template lang="">
    <div class="row justify-content-center pt-5 pt-sm-0">
        <div class="col-lg-11 text-center">
            <h1 class="green">Contáctenos</h1>
            <div class="embed-responsive embed-responsive-21by9">
            <video src="/videos/ast_media.mp4" class="embed-responsive-item w-100" autoplay controls></video>
            </div>
        </div>
        <div class="row align-items-center mb-10 pt-3">
            <div class="col-lg-4 text-center mb-5 mb-lg-0">
                <p>Mándanos un mensaje</p>
                <span><font-awesome-icon icon="fa-brands fa-whatsapp" />&nbsp;</span>
                <a href="https://api.whatsapp.com/send?phone=50688289091&text=Hola!+Me+interesa+contactarme+con+usted" target="_blank">Whatsapp</a>
            </div>
            <div class="col-lg-4 text-center mb-5 mb-lg-0">
                <p>Mandanos un correo</p>
                <span><font-awesome-icon icon="fa-regular fa-envelope" />&nbsp;</span>
                <a href="mailto:alejandro@astmediacr.com?subject=Contacto%20para%20mas%20informacion&body=Buenas%2C%20vi%20la%20p%C3%A1gina%20web%20y%20me%20interesar%C3%ADa%20m%C3%A1s%20informaci%C3%B3n%20acerca%20de%20sus%20servicios" target="_blank">Correo</a>
            </div>
            <div class="col-lg-4 text-center mb-5 mb-lg-0">
                <p>Haz una llamada</p>
                <span><font-awesome-icon icon="fa-solid fa-phone" />&nbsp;</span>
                <a href="tel:+50688289091" target="_blank">Teléfono</a>
            </div>
        </div>
    </div>
</template>
<script>
import { library } from '@fortawesome/fontawesome-svg-core'
/* import specific icons */
import { faTwitter, faWhatsapp } from '@fortawesome/free-brands-svg-icons'
import { faEnvelope } from '@fortawesome/free-regular-svg-icons'
import { faPhone } from '@fortawesome/free-solid-svg-icons'
library.add(faTwitter, faWhatsapp, faEnvelope, faPhone)
export default {
    
}
</script>
<style lang="">
    
</style>