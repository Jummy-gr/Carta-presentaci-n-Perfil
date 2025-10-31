<template>
<div class="contacto q-pa-lg">
    <h2 class="text-h4 text-weight-bold q-mb-md">📞 Contacto</h2>
    
    <q-card class="q-pa-md">
    <q-card-section>
        <div class="row q-gutter-md">
        <div class="col-12 col-md-6">
            <q-list bordered>
            <q-item>
                <q-item-section avatar>
                <q-icon name="email" color="primary" />
                </q-item-section>
                <q-item-section>
                <q-item-label>Email</q-item-label>
                <q-item-label caption>jummygaverz@gmail.com</q-item-label>
                </q-item-section>
            </q-item>
            
            <q-item>
                <q-item-section avatar>
                <q-icon name="phone" color="primary" />
                </q-item-section>
                <q-item-section>
                <q-item-label>Teléfono</q-item-label>
                <q-item-label caption>+51 930 712 300</q-item-label>
                </q-item-section>
            </q-item>
            
            <q-item>
                <q-item-section avatar>
                <q-icon name="location_on" color="primary" />
                </q-item-section>
                <q-item-section>
                <q-item-label>Ubicación</q-item-label>
                <q-item-label caption>Lima, Peru</q-item-label>
                </q-item-section>
            </q-item>
            </q-list>
        </div>
        
        <div class="col-12 col-md-5">
            <div class="text-h6 q-mb-sm">🌐 Redes Sociales</div>
            <div class="q-gutter-sm">
            <q-btn color="black" icon="fab fa-github" label="GitHub" />
            <q-btn color="light-blue" icon="fab fa-linkedin" label="LinkedIn" />
            <q-btn color="pink" icon="fab fa-instagram" label="Instagram" />
            </div>
        </div>
        </div>
    </q-card-section>
    </q-card>
</div>
</template>

<script>
export default {
name: 'ContactoSection'
}
</script>