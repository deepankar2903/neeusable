<template>
    <div align="center">
    <v-form>
    <v-container>
      <v-row>

        <v-col cols="12" sm="6">
          <v-text-field
            v-model="accname"
            label="Account Name"
            filled
          ></v-text-field>
        </v-col>

        <v-col cols="12" sm="6">
          <v-text-field
            v-model="projectid"
            label="Project ID"
            filled
          ></v-text-field>
        </v-col>
        <v-col cols="12" sm="6">
          <v-text-field
            v-model="assettype"
            label="Asset Type"
            filled
          ></v-text-field>
        </v-col>
        <v-col cols="12" sm="6">
          <v-text-field
            v-model="assetcat"
            label="Asset Category"
            filled
          ></v-text-field>
        </v-col>

      </v-row>
      <v-btn rounded color="primary" dark>Download Assets</v-btn>
      <v-btn rounded color="primary" dark>View Reports</v-btn>
     </v-container>
  </v-form>
  <ATable></ATable>
  </div>
   
 
</template>

<script>
import ATable from '../components/ATable';

export default {
  components: {
    ATable,
  },
};
</script>
