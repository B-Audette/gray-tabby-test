<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/3_morris_label.jpg')"
          class="my-3"
          contain
          height="300"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-1 font-weight-bold mb-3" style="color: #004D40">
          Homemade candles inspired by kitten mischief.
        </h1>

        <p class="subheading font-weight-bold">
          Welcome to Gray Tabby Candle Co! </p>
          <p class="subheading font-weight-normal">
          <br>I'm Lauren, and the mascot of this new lil business is Morris Troublepaws, my rambunctous young cat. 
          <br>We're making homemade soy candles in recycled jars in simple, clean scents to brighten up the spaces you love. 
      <v-spacer></v-spacer>
          <br>
          <a
            href="https://graytabbycandle.us7.list-manage.com/subscribe?u=ec6f681656de4414ab68a913f&id=9aa7514018"
            target="_blank"
          >Sign up for my email list</a>
          for updates on what's in stock, what's new, custom orders, and how to purchase! 
        </p>
        <br>
        <p>You can also email me at
          <a
          href="mailto:graytabbycandle@gmail.com"
          target="blank"
          >graytabbycandle@gmail.com</a>
          to order!</p>
      </v-col>
      <Notice />


      <!-- <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          What's next?
        </h2>

        <v-row justify="center">
          <a
            v-for="(next, i) in whatsNext"
            :key="i"
            :href="next.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ next.text }}
          </a>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Important Links
        </h2>

        <v-row justify="center">
          <a
            v-for="(link, i) in importantLinks"
            :key="i"
            :href="link.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ link.text }}
          </a>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Ecosystem
        </h2>

        <v-row justify="center">
          <a
            v-for="(eco, i) in ecosystem"
            :key="i"
            :href="eco.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ eco.text }}
          </a>
        </v-row>
      </v-col> -->
    </v-row>
  </v-container>
</template>

<script>
import Notice from './Notice'
  export default {
    name: 'HelloWorld',
components: {
        Notice
      },
    data: () => ({
      
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
<style scoped>
a {
  text-decoration: none;
  color: #00695C !important;
}
</style>
