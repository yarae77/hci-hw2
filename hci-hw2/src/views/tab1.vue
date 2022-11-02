<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <div id="container">
        <ion-grid>
          <ion-row>
            <IonCol>
              <h1 class="TittleText">Home</h1>
            </IonCol>
            <IonCol></IonCol>
            <IonCol></IonCol>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Kolam</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1><b>10</b></h1>
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Kolam Aktif</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1><b>8</b></h1>
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Ikan Hidup</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><b>182</b></h1> Ekor
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Ikan Mati</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><b>89</b></h1> Ekor
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Panen 2022</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><b>109</b></h1> kg
                </ion-card-content>
              </ion-card>
            </ion-col>
            <ion-col>
              <ion-card color="dark">
                <ion-card-header>
                  <ion-card-title><b>Total Pakan</b></ion-card-title>
                </ion-card-header>
                <ion-card-content>
                  <h1 id="inline"><b>223</b></h1> kg
                </ion-card-content>
              </ion-card>
            </ion-col>
          </ion-row>
        </ion-grid>
        <div class="TittleText">
          <h1>TOTAL BERAT IKAN</h1>
        </div>
        <ion-row>
          <ion-col>
            <ion-card class="Berat">
              <img alt="Lele" src="https://img.freepik.com/premium-vector/catfish-vector-illustration_175152-258.jpg?strip=all" style="width: 500px;height: 150px;"/>
              <ion-card-header>
                <ion-card-title>Ikan Lele</ion-card-title>
                <ion-card-subtitle><span class="textcolor">200 Kg</span></ion-card-subtitle>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card class="Berat">
              <img alt="Nila" src="https://1.bp.blogspot.com/-dHe3dP4w4qA/WwhdaIk3VvI/AAAAAAAABeU/QPy2RklSfRgOQ1R2Dg6Fb-sv6B_OKVGOgCLcBGAs/s1600/11.jpg" style="width: 500px;height: 150px;"/>
              <ion-card-header>
                <ion-card-title>Ikan Nila</ion-card-title>
                <ion-card-subtitle><span class="textcolor">220 Kg</span></ion-card-subtitle>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
        
        <div class="TittleText">
          <h1>KUALITAS AIR</h1>
        </div>
        <ion-row>
          <ion-col>
            <ion-card class="Kualitas">
              <ion-card-header>
                <ion-card-title><b>pH</b></ion-card-title>
                <ion-card-subtitle>Normal: <span class="textcolor">6 Kolam</span></ion-card-subtitle>
                <ion-card-subtitle>Abnormal: <span class="textcolor">6 Kolam</span></ion-card-subtitle>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card class="Kualitas">
              <ion-card-header>
                <ion-card-title><b>DO</b></ion-card-title>
                <ion-card-subtitle>Normal: <span class="textcolor">6 Kolam</span></ion-card-subtitle>
                <ion-card-subtitle>Abnormal: <span class="textcolor">6 Kolam</span></ion-card-subtitle>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </div>
      </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonContent, IonCol, IonGrid, IonRow, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle } from '@ionic/vue';
export default  defineComponent({
  name: 'Tab1Page',
  components: { IonContent, IonPage, IonCol, IonGrid, IonRow, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle }
});
</script>
<style scoped> 
ion-title{
  font-weight: bold;
  font-size: 20px;
 }
 ion-card{
  border-radius: 20px;
 }
 ion-card-title{
  color: black;
  font-weight: bold;
  font-size: 20px;
 }
 #inline{
  display: inline;
 }
 .textcolor{
  color: lightskyblue;
  font-weight: bold;
 }
 .TittleText{
  color: white;
  padding-left: 17px;
  font-weight: bold;
 }
 .Berat{
  background-color: white;
 }
 .Kualitas{
  background-color: white;
 }
</style>