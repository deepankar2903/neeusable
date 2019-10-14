
<template>
  <div align="center">
    <v-simple-table-title display-3>Add Asset</v-simple-table-title>
  <v-simple-table>
    <template v-slot:default>

      <tbody>
     <tr>
       <td>Asset ID</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Asset Title</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Asset Description</td>
       <td><textarea/></td>
     </tr>
     <tr>
       <td>Project ID</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Project Manager ID</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Asset Attachment</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Estimated Effort savings on reuse</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Estimated Dollar savings on reuse</td>
       <td><input/></td>
     </tr>
     <tr>
       <td>Asset Owner(s)</td>
       <td><input/></td>
     </tr>
      </tbody>
      
  </template>
  </v-simple-table>
  <v-btn rounded color="primary" dark>Cancel</v-btn>
  <v-btn rounded color="primary" dark>Submit</v-btn>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>