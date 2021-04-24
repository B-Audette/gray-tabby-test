<template>
  <div>
    <v-alert
      v-model="alert"
      border="left"
      close-text="Close Alert"
      color="teal darken-3"
      dark
      dismissible
    >
     From here until the end of May (at least), $1 of every candle sold from GTCC will benefit mutual aid and community resources in my home community of North Minneapolis. Northside, largely Black, faces enormous challenges to overcome both the effects of the pandemic, infrastructure inequity, and racial profiling from police and other law enforcement. But it is a beautiful, kind, and welcoming place that many are working to help thrive.

Candle scents, pricing, and info about custom candles available on the website. Email orders to graytabbycandle@gmail.com.

Donation amounts, selected recipients, and receipts will be posted on IG @graytabbycandle once a week.

Thank you for your support.
    </v-alert>
    <div class="text-center">
      <v-btn
        v-if="!alert"
        color="teal darken-3"
        dark
        @click="alert = true"
      >
        Reset
      </v-btn>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        alert: true,
      }
    },
  }
</script>