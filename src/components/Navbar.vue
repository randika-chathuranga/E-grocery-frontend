<template>
  <div>
    <v-app-bar color="deep-purple accent-4" dense dark>
      <v-icon large class="ma-2">mdi-cart</v-icon>
      <v-toolbar-title>E grocery</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-avatar size="30" class="ml-2">
        <v-img src="men.png"></v-img>
      </v-avatar>
      <v-btn icon dark>
          <v-icon small color="#fff">mdi-chevron-down</v-icon>
        </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {
    
}
</script>