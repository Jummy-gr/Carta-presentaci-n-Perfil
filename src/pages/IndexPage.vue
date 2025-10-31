<template>
  <q-page class="q-pa-md">
    <HeaderPersonal />
    <SobreMi />
    <Habilidades />
    <Pasatiempos />
    <Contacto />
  </q-page>
</template>

<script>
import HeaderPersonal from 'components/HeaderPersonal.vue'
import SobreMi from 'components/SobreMi.vue'
import Habilidades from 'components/Habilidades.vue'
import Pasatiempos from 'components/Pasatiempos.vue'
import Contacto from 'components/Contacto.vue'

export default {
  name: 'IndexPage',
  components: {
    HeaderPersonal,
    SobreMi,
    Habilidades,
    Pasatiempos,
    Contacto
  }
}
</script>