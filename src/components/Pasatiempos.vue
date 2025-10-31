<template>
<div class="pasatiempos q-pa-lg">
    <h2 class="text-h4 text-weight-bold q-mb-md">🎯 Mis Pasatiempos</h2>
    
    <div class="row q-gutter-md">
    <q-card v-for="(hobby, index) in pasatiempos" :key="index" 
            class="col-12 col-sm-5 col-md-3">
        <q-card-section class="text-center">
        <q-icon :name="hobby.icono" size="40px" :color="hobby.color" class="q-mb-sm" />
        <div class="text-h6 text-weight-medium">{{ hobby.nombre }}</div>
        <p class="text-caption q-mt-sm">{{ hobby.descripcion }}</p>
        </q-card-section>
    </q-card>
    </div>
</div>
</template>

<script>
export default {
name: 'PasatiemposSection',
data() {
    return {
    pasatiempos: [
        {
        nombre: 'Programación',
        descripcion: 'Crear proyectos y aprender nuevas tecnologías',
        icono: 'code',
        color: 'primary'
        },
        {
        nombre: 'Videojuegos',
        descripcion: 'Juegos de estrategia y aventura',
        icono: 'sports_esports', 
        color: 'secondary'
        },
        {
        nombre: 'Música',
        descripcion: 'Escuchar diversos géneros musicales, entre ellos el Kpop, pop, musica clásica',
        icono: 'music_note',
        color: 'positive'
        },
        {
        nombre: 'Voley',
        descripcion: 'Voley y realizar actividades al aire libre',
        icono: 'sports_soccer',
        color: 'accent'
        }
    ]
    }
}
}
</script>