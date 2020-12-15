<template>
  <ion-item>
    
    <ion-select value="brown">
      <ion-select-option value="brown">Brown</ion-select-option>
      <ion-select-option value="blonde">Blonde</ion-select-option>
      <ion-select-option value="black">Black</ion-select-option>
      <ion-select-option value="red">Red</ion-select-option>
    </ion-select>
  </ion-item>
</template>

<script>
import { IonItem,  IonSelect, IonSelectOption } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { IonItem, IonSelect, IonSelectOption }
});
</script>