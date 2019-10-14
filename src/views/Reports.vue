<template>
 <v-form align="center">
    <v-container>
      <v-row>

        <v-col cols="12" sm="6">
          <v-text-field
            v-model="accid"
            label="Account ID"
            filled
          ></v-text-field>
        </v-col>
          <v-col cols="12" sm="6">
          <v-text-field
            v-model="rtype"
            label="Report Type"
            filled
          ></v-text-field>
        </v-col>
      </v-row>
      <v-btn rounded color="primary" dark>Cancel</v-btn>
      <v-btn rounded color="primary" dark>Submit</v-btn>
     </v-container>
  </v-form>

</template>