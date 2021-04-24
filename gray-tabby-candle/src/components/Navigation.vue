<template>
  <div>
    <v-card class="overflow-hidden">
      <v-app-bar
        absolute
        color="#6A76AB"
        dark
    
        src="https://lh4.googleusercontent.com/K5CQA1mAIGTiGekzchwxMolosw-iC1lDZBHK8j2Zy5ED_qDaJefJHE7RA_K2coYy6llQEGHeHEfho_urj6WfU2U=w16383"
      >
        <template v-slot:img="{ props }">
          <v-img
            v-bind="props"
            gradient="to top right, rgba(0,61,65,.6), rgba(0,77,64,.3)"
          ></v-img>
        </template>

        <v-app-bar-title>Gray Tabby Candle</v-app-bar-title>
        <v-spacer></v-spacer>

        <v-spacer></v-spacer>

        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>

        <v-btn icon>
          <v-icon>mdi-dots-vertical</v-icon>
        </v-btn>

        <template v-slot:extension>
          <v-tabs align-with-title>
            <v-tab>Home</v-tab>
            <!-- <v-tab>Tab 2</v-tab> -->
            <v-tab>Candles</v-tab>
          </v-tabs>
        </template>
      </v-app-bar>
      
        <v-container style="height: 112px"></v-container>

    </v-card>
  </div>
</template>