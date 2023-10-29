<template>
  <ion-page color="primary">
    <ion-content :fullscreen="true" color="primary">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Blank</ion-title>
        </ion-toolbar>
      </ion-header>

      <!-- Use an iframe to embed the external website -->
      <iframe
        src="https://www.dcexmarket.top/"
        width="100%"
        height="100%"
        frameborder="0"
      ></iframe>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonButton } from '@ionic/vue';
import { useRoute, useRouter } from 'vue-router';

const route = useRoute();
const router = useRouter();
</script>
