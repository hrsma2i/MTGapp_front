<template>
  <!-- <v-container fill-height> -->
    <v-layout
      fill-height
      text-xs-center
      wrap
      justify-center
      column
      class="mx-3"
    >
      <!-- <v-spacer></v-spacer> -->
      <v-layout align-end>
        <v-flex
            display-1
            font-weight-medium
            text-xs-center
        >
          Time is<br>
          M💰ney Pacquio!
        </v-flex>
      </v-layout>
      <v-layout align-center>
        <v-flex>
          <div>
            <v-text-field
              color="light-blue"
              label="メールアドレス"></v-text-field>
          </div>
        </v-flex>
      </v-layout>
      <v-flex>
        <div>
          <v-btn color="light-blue">
          <!-- <v-btn color=rgba(69,142,202,255)> -->
            ログイン
          </v-btn>
        </div>
      </v-flex>
    </v-layout>
  <!-- </v-container> -->
</template>

<script>
  export default {
   
  }
</script>

<style>

</style>
