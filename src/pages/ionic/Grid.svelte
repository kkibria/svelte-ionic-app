<style>
  :root {
    --ion-safe-area-top: 20px;
    --ion-safe-area-bottom: 22px;
  }
  ion-col > div {
    background-color: #f7f7f7;
    border: solid 1px #ddd;
    padding: 10px;
  }
</style>

<svelte:head>
  <title>Ionic UI Companion App - Grid</title>
</svelte:head>

<ion-header translucent>
  <ion-toolbar>
    <ion-buttons slot="start">
      <ion-menu-button />
    </ion-buttons>
    <ion-title>Grid</ion-title>
  </ion-toolbar>
</ion-header>
<ion-content fullscreen>
  <ion-grid>
    <ion-row>
      <ion-col>
        <div>1 of 2</div>
      </ion-col>
      <ion-col>
        <div>2 of 2</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col>
        <div>1 of 3</div>
      </ion-col>
      <ion-col>
        <div>2 of 3</div>
      </ion-col>
      <ion-col>
        <div>3 of 3</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col>
        <div>1 of 3</div>
      </ion-col>
      <ion-col col-6>
        <div>2 of 3</div>
      </ion-col>
      <ion-col>
        <div>3 of 3</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col col-6>
        <div>1 of 3</div>
      </ion-col>
      <ion-col>
        <div>2 of 3</div>
      </ion-col>
      <ion-col>
        <div>3 of 3</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col offset-4>
        <div>1 of 2</div>
      </ion-col>
      <ion-col>
        <div>2 of 2</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col>
        <div>1 of 2</div>
      </ion-col>
      <ion-col offset-4>
        <div>2 of 2</div>
      </ion-col>
    </ion-row>
    <ion-row>
      <ion-col>
        <div>1 of 4</div>
      </ion-col>
      <ion-col>
        <div>2 of 4</div>
      </ion-col>
      <ion-col>
        <div>3 of 4</div>
      </ion-col>
      <ion-col>
        <div>4 of 4</div>
      </ion-col>
    </ion-row>
  </ion-grid>
</ion-content>
