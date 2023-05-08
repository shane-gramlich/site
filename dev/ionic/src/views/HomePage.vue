<template>
  <ion-page id="main-content">
    
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button autoHide="false" menu="left"></ion-menu-button>
        </ion-buttons>
        <ion-searchbar animated="true" placeholder="Animated"></ion-searchbar>
        <!-- <ion-title class="ion-text-center">Shane Gramlich</ion-title> -->
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
    
    <ion-content ref="content" @ionScroll="onContentScroll">
      <ion-button expand="block" @click="scrollToBottom()">Scroll to Bottom</ion-button>
      
      <ion-card>
        <ion-card-header>
          <ion-card-title>Ionic - Vue</ion-card-title>
          <ion-card-subtitle>Ready to create an app?</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          <p>Start with Ionic <a target="_blank" rel="noopener noreferrer"
              href="https://ionicframework.com/docs/components">UI Components</a></p>
        </ion-card-content>
      </ion-card>

      <ion-card>
        <img alt="Avatar 3" src="../assets/images/avatar3.png" SameSite="Secure" />
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
        <img alt="Silhouette of mountains" src="../assets/images/avatar3.png" SameSite="Secure" />
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <img alt="Avatar 3" src="../assets/images/avatar3.png" SameSite="Secure" />
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <img alt="Avatar 3" src="../assets/images/avatar3.png" SameSite="Secure" />
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <ion-card>
        <img alt="Avatar 3" src="../assets/images/avatar3.png" SameSite="Secure" />
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

      <p>
        Nulla tristique ultricies suscipit. Donec non ornare elit. Vivamus id pretium mauris, nec sagittis leo. Fusce
        mattis eget est id sollicitudin. Suspendisse dictum sem magna, in imperdiet metus suscipit et. Suspendisse enim
        enim, venenatis et orci eu, suscipit congue lacus. Praesent vel ligula non eros tempor interdum. Proin justo orci,
        ultricies vitae diam sed, semper consectetur ligula. Aenean finibus ante velit, nec efficitur libero cursus
        cursus. Duis mi nunc, imperdiet sed condimentum vel, porttitor ut lacus. Quisque dui ipsum, vehicula sed
        vestibulum id, semper vel libero. Suspendisse tincidunt mollis condimentum. Nulla facilisi. Etiam neque nisl,
        egestas nec iaculis sed, tristique faucibus sem. Sed mollis dui quis ligula cursus rutrum.
      </p>

      <ion-button expand="block" fill="clear" color="primary" class="scroll-btn"
        :class="{ 'scroll-btn-hidden': !showScrollBtn }" @click="scrollToTop">
        Scroll To Top
      </ion-button>

      <ion-card>
        <img alt="Avatar 3" src="../assets/images/avatar3.png" SameSite="Secure" />
        <ion-card-header>
          <ion-card-title>Card Title</ion-card-title>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
        </ion-card-header>
        <ion-card-content>
          Here's a small text description for the card content. Nothing more, nothing less.
        </ion-card-content>
      </ion-card>

    </ion-content>

    <ion-footer>
      <ion-toolbar>
        <ion-title>
          <p>Footer</p>
          <p>
            Nulla tristique ultricies suscipit. Donec non ornare elit. Vivamus id pretium mauris, nec sagittis leo. Fusce
            mattis eget est id sollicitudin. Suspendisse dictum sem magna, in imperdiet metus suscipit et. Suspendisse
            enim
            enim, venenatis et orci eu, suscipit congue lacus. Praesent vel ligula non eros tempor interdum. Proin justo
            orci,
            ultricies vitae diam sed, semper consectetur ligula. Aenean finibus ante velit, nec efficitur libero cursus
            cursus. Duis mi nunc, imperdiet sed condimentum vel, porttitor ut lacus. Quisque dui ipsum, vehicula sed
            vestibulum id, semper vel libero. Suspendisse tincidunt mollis condimentum. Nulla facilisi. Etiam neque nisl,
            egestas nec iaculis sed, tristique faucibus sem. Sed mollis dui quis ligula cursus rutrum.
          </p>
        </ion-title>
      </ion-toolbar>
    </ion-footer>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import {
  IonButton,
  IonButtons,
  IonCard,
  IonCardContent,
  IonCardHeader,
  IonCardSubtitle,
  IonCardTitle,
  IonContent,
  IonHeader,
  IonMenu,
  IonMenuButton,
  IonPage,
  IonSearchbar,
  IonTitle,
  IonToolbar
} from '@ionic/vue';

export default defineComponent({
  data() {
    return {
      showScrollBtn: false,
    };
  },
  components: { IonButton, IonContent },
  methods: {
    onContentScroll(event) {
      const scrollTop = event.target.scrollTop;
      this.showScrollBtn = scrollTop > 100;
    },
    scrollToBottom() {
      // Passing a duration to the method makes it so the scroll slowly
      // goes to the bottom instead of instantly
      this.$refs.content.$el.scrollToBottom(500);
    },
    scrollToTop() {
      this.$refs.content.$el.scrollToTop(500);
      setTimeout(() => {
        this.showScrollBtn = false;
      }, 3000);
    }
  },
});
</script>

<style scoped>
.scroll-btn {
  position: fixed;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  opacity: 0.8;
  transition: opacity 0.3s ease-out;
}

.scroll-btn:hover {
  opacity: 1;
}

.scroll-btn-hidden {
  opacity: 0;
}
</style>