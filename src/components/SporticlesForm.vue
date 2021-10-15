<template>
  <v-container>
    <!DOCTYPE html> <html lang="en"> <head> <meta charset="utf-8" /> <meta name="viewport" content="width=device-width, initial-scale=1" /> <title>National Sports Story Competition</title> <style>*{margin:0;padding:0;} html,body,#wrapper{width:100%;height:100%;} iframe{border-radius:0 !important;}</style> </head> <body> <div id="wrapper" data-tf-widget="FPg7rXg9" data-tf-inline-on-mobile></div> <script src="//embed.typeform.com/next/embed.js"></script> </body> </html>
  </v-container>
</template>

<script>
  export default {
    name: 'SporticlesForm',

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
