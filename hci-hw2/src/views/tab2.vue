<template>
    <ion-page>
      <ion-header :translucent="true">
        <ion-toolbar>
          <ion-grid>
            <ion-row>
              <ion-col>
                <ion-title>Kolam</ion-title>
              </ion-col>
              <ion-col size="1">
                <img src="public/img/Sorting.svg" alt="">
              </ion-col>
              <ion-col size="1.1">
                <img src="public/img/Vector.svg" alt="">
              </ion-col>
            </ion-row>
          </ion-grid>
        </ion-toolbar>
      </ion-header>    
      <ion-content :fullscreen="true">
        <ion-card color="dark">
          <ion-item lines="full" color="dark">
            <ion-label><strong>Alpha</strong></ion-label>
            <ion-button  size="small" color="success">
              Aktif
            </ion-button>
          </ion-item>
          <ion-card-content>
            <ion-grid>
              <ion-row>
                <ion-col size="1">
                  <img src="public/img/Calendar.svg" alt="">
                </ion-col>
                <ion-col size="auto">
                  01-09-2022
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Timesheet.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  90 hari
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/fish.png"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                200 Ekor
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-card-content>
        </ion-card> 
  
          <ion-card color="dark">
          <ion-item lines="full" color="dark">
            <ion-label><strong>Beta</strong></ion-label>
            <ion-button slot="end" size="small" color="danger">
              Tidak Aktif
            </ion-button>
          </ion-item>
          <ion-card-content>
            <ion-grid>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Calendar.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                 01-09-2022
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Timesheet .svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  90 hari
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Whole Fish.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  200 Ekor
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-card-content>
        </ion-card> 
  
          <ion-card color="dark">
          <ion-item lines="full" color="dark">
            <ion-label><strong>Charlie</strong></ion-label>
            <ion-button slot="end" size="small" color="success">
              Aktif
            </ion-button>
          </ion-item>
          <ion-card-content>
            <ion-grid>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Calendar.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  01-09-2022
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Timesheet .svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  90 hari
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Whole Fish.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                  200 Ekor
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-card-content>
        </ion-card> 
  
          <ion-card color="dark">
          <ion-item lines="full" color="dark">
            <ion-label><strong>Delta</strong></ion-label>
            <ion-button slot="end" size="small" color="success">
              Aktif
            </ion-button>
          </ion-item>
          <ion-card-content>
            <ion-grid>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Calendar.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                01-09-2022
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Timesheet .svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                90 hari
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Whole Fish.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                200 Ekor
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-card-content>
        </ion-card> 
  
          <ion-card color="dark">
          <ion-item lines="full" color="dark">
            <ion-label><strong>Epsilon</strong></ion-label>
            <ion-button slot="end" size="small" color="success">
              Aktif
            </ion-button>
          </ion-item>
          <ion-card-content>
            <ion-grid>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Calendar.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                01-09-2022
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Timesheet .svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                90 hari
                </ion-col>
              </ion-row>
              <ion-row>
                <ion-col size="1">
                  <ion-icon src="public/img/Whole Fish.svg"></ion-icon>
                </ion-col>
                <ion-col size="auto">
                200 Ekor
                </ion-col>
              </ion-row>
            </ion-grid>
          </ion-card-content>
        </ion-card>
      </ion-content>
  
      <ion-fab vertical="bottom" horizontal="end" slot="fixed">
              <ion-fab-button color="tertiary">
              
              </ion-fab-button>
          </ion-fab>
    </ion-page>
  </template>
  
  <script lang="ts">
  import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar, IonCol, IonGrid, IonRow, IonFab, IonFabButton, IonIcon} from '@ionic/vue';
  import { defineComponent } from 'vue';
  export default defineComponent({
    name: 'PageSecond',
    components: {IonContent,IonHeader,IonPage,IonTitle,IonToolbar,IonCol,IonGrid,IonRow,IonFab,IonFabButton,IonIcon
    }
  });
  </script>
  
  <style scoped>
   ion-title{
    font-weight: bold;
    font-size: 30px;
   }
    ion-card{
    border-radius: 20px;
    margin-top: 20px;
    font-size: 50px;
   }
   ion-icon{
    font-size: 30px;
   }
   ion-col{
    font-weight: bold;
    font-size: 20px;
   }
   ion-button{
    border-radius: 20px;
    font-size: 15px;
   }
   ion-item{
    font-weight: bold;
    font-size: 30px;
   }
  </style>