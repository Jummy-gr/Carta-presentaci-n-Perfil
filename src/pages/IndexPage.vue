<template>
  <q-page class="q-pa-md">
    <HeaderPersonalSection />
    <SobreMiSection />
    <HabilidadesSection />
    <PasatiemposSection />
    <ContactoSection />
  </q-page>
</template>

<script>
import HeaderPersonalSection from 'components/HeaderPersonal.vue'
import SobreMiSection from 'components/SobreMi.vue'
import HabilidadesSection from 'components/Habilidades.vue'
import PasatiemposSection from 'components/Pasatiempos.vue'
import ContactoSection from 'components/Contacto.vue'

export default {
  name: 'IndexPage',
  components: {
    HeaderPersonalSection,
    SobreMiSection,
    HabilidadesSection,
    PasatiemposSection,
    ContactoSection
  }
}
</script>