<template lang="">
    <div class="container vh-100 overflow-auto pt-3">
        <h1 class="green">Nuestro equipo</h1>
        <section >
            <div class="container py-5 h-100">
                <div class="row d-flex justify-content-center align-items-center h-100">
                <div class="col-md-12 col-xl-10">
                    <div class="card mb-4 shadow-sm rounded-3" v-for="perfil in perfiles">
                    <div class="card-body text-center">
                        <div class="mt-3 mb-4">
                        <img :src="`/img/fotos/${ perfil.foto}`"
                            class="rounded-circle img-fluid" style="width: 100px;" />
                        </div>
                        <h4 class="mb-2">{{ perfil.nombre }}</h4>
                        <p class="text-muted mb-4">{{ perfil.titulo }}</p>
                        <div class="d-flex justify-content-between text-center mt-2 mb-2">
                            <p class="mb-2">{{ perfil.descripcion }}</p>
                        </div>
                    </div>
                    </div>

                </div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
import datos from '../assets/json/perfiles.json';
export default {
   
  data() {
    return {
      perfiles: datos
    }
  }
}
</script>
<style scoped>
    .card {
        
        background: #f7fbfc; /* Old browsers */
        background: -moz-linear-gradient(-45deg,  #f7fbfc 0%, #d9edf2 40%, #add9e4 100%); /* FF3.6-15 */
        background: -webkit-linear-gradient(-45deg,  #f7fbfc 0%,#d9edf2 40%,#add9e4 100%); /* Chrome10-25,Safari5.1-6 */
        background: linear-gradient(135deg,  #f7fbfc 0%,#d9edf2 40%,#add9e4 100%); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
        filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f7fbfc', endColorstr='#add9e4',GradientType=1 ); /* IE6-9 fallback on horizontal gradient */

    }
    .card img.rounded-circle.img-fluid {
    border: 3px solid #fff;
    outline: 3px solid var(--vt-c-naranja);
}
</style>



