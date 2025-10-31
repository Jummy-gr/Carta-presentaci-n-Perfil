<template>
    <div class="header-personal text-center q-pa-lg">
    <!-- Foto o Avatar -->
    <q-avatar size="140px" class="q-mb-md" color="primary" text-color="white">
    <q-icon name="person" size="80px" />
    <!-- Para agregar tu foto después: -->
    <!-- <img src="~assets/mi-foto.jpg" alt="Tu foto"> -->
    </q-avatar>
    
    <!-- Nombre y título -->
    <h1 class="text-h3 text-weight-bold q-mb-sm">Jummy Juvanita Gave Ramirez</h1>
    <p class="text-h5 text-grey-8 q-mb-md">Ingeniería de Tecnologías de la Información y Sistemas</p>
    
    <!-- Etiquetas -->
    <div class="q-gutter-sm">
    <q-chip color="primary" text-color="white" icon="school">
        Estudiante
    </q-chip>
    <q-chip color="secondary" text-color="white" icon="code">
        Desarrollador
    </q-chip>
    <q-chip color="positive" text-color="white" icon="favorite">
        Apasionado
    </q-chip>
    </div>
</div>
</template>

<script>
export default {
name: 'HeaderPersonalSection'
}
</script>

<style scoped>
.header-personal {
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
color: rgb(252, 245, 255);
border-radius: 15px;
margin-bottom: 20px;
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}
</style>