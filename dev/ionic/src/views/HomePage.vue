<template>

  <ion-header>
    <ion-toolbar>
      <ion-buttons slot="start">
        <ion-menu-button autoHide="false" menu="left"></ion-menu-button>
      </ion-buttons>
      <ion-title class="text-center">Shane Gramlich</ion-title>
      <ion-buttons slot="end">
        <ion-menu-button autoHide="false" menu="right"></ion-menu-button>
      </ion-buttons>
    </ion-toolbar>
  </ion-header>

  <ion-menu side="start" content-id="main-content" menuId="left">
    <ion-header>
      <ion-toolbar>
        <ion-title>Left Menu Content</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">This is the left menu content.</ion-content>
  </ion-menu>

  <ion-menu side="end" content-id="main-content" menuId="right">
    <ion-header>
      <ion-toolbar>
        <ion-title>Right Menu Content</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">This is the right menu content.</ion-content>
  </ion-menu>

  <ion-page id="main-content">
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
        <ion-title>Shane Gramlich</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-scroll scrollY="true">
    
      <ion-card>
        <img alt="Silhouette of mountains" src="../assets/images/avatar3.png" SameSite="Secure"/>
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          <ion-list>
            <ion-item>
              <ion-thumbnail slot="start">
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
              </ion-thumbnail>
              <ion-label>Item</ion-label>
            </ion-item>

            <ion-item>
              <ion-thumbnail slot="start">
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
              </ion-thumbnail>
              <ion-label>Item</ion-label>
            </ion-item>

            <ion-item>
              <ion-thumbnail slot="start">
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
              </ion-thumbnail>
              <ion-label>Item</ion-label>
            </ion-item>

            <ion-item lines="none">
              <ion-thumbnail slot="start">
                <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/thumbnail.svg" />
              </ion-thumbnail>
              <ion-label>Item</ion-label>
            </ion-item>
          </ion-list>
        </ion-card-content>
      </ion-card>

      <ion-card>
        <img alt="Silhouette of mountains" src="../assets/images/avatar3.png" SameSite="Secure"/>
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>
    </ion-scroll>

    <!--
    <ion-content :fullscreen="true">
      <div id="container">
        <strong>Ready to create an app?</strong>
        <p>Start with Ionic <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/docs/components">UI Components</a></p>
      </div>
    </ion-content>
    -->

  </ion-page>
</template>

<script setup lang="ts">
  import {
    IonButtons,
    IonContent,
    IonHeader,
    IonMenu,
    IonMenuButton,
    IonPage,
    IonTitle,
    IonToolbar,
    IonCard,
    IonCardContent,
    IonCardHeader,
    IonCardSubtitle,
    IonCardTitle
  } from '@ionic/vue';

  import { defineComponent } from 'vue';

</script>

<style scoped>
#container {
  text-align: center;
  
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
