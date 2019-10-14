<template>
  <v-app>
        <v-navigation-drawer

      v-model="drawer"

      app

    >

      <v-list dense>

        <v-list-item @click="$router.push('/addasset')">

          <v-list-item-action>
           
          </v-list-item-action>

          <v-list-item-content>

            <v-list-item-title>Add Asset</v-list-item-title>

          </v-list-item-content>

        </v-list-item>

        <v-list-item @click="$router.push('/approveasset')">

          <v-list-item-action>

          </v-list-item-action>

          <v-list-item-content>

            <v-list-item-title>Approve Asset</v-list-item-title>

          </v-list-item-content>

        </v-list-item>

        <v-list-item @click="$router.push('/consumeasset')">

          <v-list-item-action>

          </v-list-item-action>

          <v-list-item-content>

            <v-list-item-title>Consume Asset</v-list-item-title>

          </v-list-item-content>

        </v-list-item>
        <v-list-item @click="$router.push('/reports')">

          <v-list-item-action>

          </v-list-item-action>

          <v-list-item-content>

            <v-list-item-title>Report</v-list-item-title>

          </v-list-item-content>

        </v-list-item>

      </v-list>

    </v-navigation-drawer>



    <v-app-bar

      app

      color="light blue"

      dark

    >

      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title @click="$router.push('/')">NEE Usable Portal</v-toolbar-title>

    </v-app-bar>



   

    <v-footer

      color="light blue"

      app

    >

      <span class="white--text">All Rights Reserved</span>

    </v-footer>
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      drawer:false
    }
  }

};
</script>
