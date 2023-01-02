<template>
  <v-app>
    <!-- TEXT AOE AND THE IMAGE  -->


    <div class="text-center">
      <img src="../assets/prog.png" alt="" height="50" width="50" class="mt-2">
      <h3 class="my-2 blue--text"> AOE </h3>

    </div>
    <hr class="font-weight-bold mx-2">

    <!-- TOOLBAR AND ITS ATTRIBUTES  -->


    <nav class="pa-2 mx-2">
      <v-toolbar dense flat color="blue darken-3">

        <span class="mx-6 white--text font-weight-bold">COMPANIES</span>
        <span class="mx-6 white--text font-weight-bold">JOBS</span>
        <span class="mx-6 white--text font-weight-bold">CAREER</span>

        <v-spacer></v-spacer>

        



        <!-- <v-menu>
          <template v-slot:activator="{ on, attrs }">
            <v-btn dark depressed flat color="primary" v-bind="attrs" v-on="on">
              Register
            </v-btn>
          </template>
          <v-list>
            <v-list-item v-for="(item, index) in items" :key="index">
              <v-list-item-title>
                <v-btn flat depressed class="orange--text">{{ item.title }}</v-btn>
              </v-list-item-title>
            </v-list-item>
          </v-list>
        </v-menu> -->



      </v-toolbar>
    </nav>

        <!-- ALERT  -->

    <v-alert
      dense
      text
      type="success"
      class="mx-5"
    >
       <strong>Sign In Successsful </strong> 
    </v-alert>

  </v-app>
</template>

<script>

export default {
  data() {
    return {
      







    }
  }
}


</script>
