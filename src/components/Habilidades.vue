<template>
  <div class="habilidades q-pa-lg">
    <h2 class="text-h4 text-weight-bold q-mb-md">💻 Habilidades</h2>
    
    <div class="row q-gutter-md">
      <!-- Habilidades Técnicas -->
      <q-card class="col-12 col-md-5">
        <q-card-section>
          <h3 class="text-h6 text-weight-bold">🛠️ Técnicas</h3>
          <div class="q-mt-sm">
            <div v-for="(skill, index) in habilidadesTecnicas" :key="'tech-' + index" class="q-mb-sm">
              <div class="text-caption">{{ skill.nombre }}</div>
              <q-linear-progress :value="skill.nivel" color="primary" class="q-mt-xs" />
            </div>
          </div>
        </q-card-section>
      </q-card>

      <!-- Habilidades Blandas -->
      <q-card class="col-12 col-md-5">
        <q-card-section>
          <h3 class="text-h6 text-weight-bold">🌟 Blandas</h3>
          <div class="q-mt-sm">
            <q-chip v-for="(skill, index) in habilidadesBlandas" :key="'soft-' + index" 
                   color="secondary" text-color="white" class="q-ma-xs">
              {{ skill }}
            </q-chip>
          </div>
        </q-card-section>
      </q-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Habilidades',
  data() {
    return {
      habilidadesTecnicas: [
        { nombre: 'HTML/CSS', nivel: 0.8 },
        { nombre: 'JavaScript', nivel: 0.7 },
        { nombre: 'Vue.js', nivel: 0.6 },
        { nombre: 'Quasar', nivel: 0.5 },
        { nombre: 'Git', nivel: 0.6 }
      ],
      habilidadesBlandas: [
        'Trabajo en equipo',
        'Comunicación',
        'Resolución de problemas', 
        'Adaptabilidad',
        'Creatividad'
      ]
    }
  }
}
</script>