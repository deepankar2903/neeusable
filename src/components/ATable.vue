<template align="center">
  <v-simple-table height="300px">
    <template v-slot:default>
      <thead>
        <tr>
          <th></th>
      <th>Asset ID</th>
      <th>Asset Title</th>
      <th>Asset Description</th>
      <th>Asset Owner Name</th>
      <th>Asset Status</th>
      <th></th>
      <th></th>
        </tr>
      </thead>
      <tbody>
        <tr>
         <td><input type="checkbox"/></td>
        <td>{{assetId}}</td>
        <td>{{assetTitle}}</td>
        <td>{{assetDescp}}</td>
        <td>{{assetowner}}</td>
        <td>{{assetStatus}}</td>
        <td><v-btn small color="primary" dark>View Details</v-btn></td>
        <td><v-btn small color="primary" dark>Edit</v-btn></td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>
</template>
<script>
</script>