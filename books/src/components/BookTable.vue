<template>
  
  <table class="styled-table">
    <thead>
      <tr>
        <th>Titel</th>
        <th>Autor Vorname</th>
        <th>Autor Name</th>
        <th>Erscheinungsjahr</th>
        <th>Seitenanzahl</th>
        <th>bewertung</th>
        <th>Gelesen</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Die leiden des Dom</td>
        <td>dom</td>
        <td>Dimtes</td>
        <td>1996</td>
        <td>2991</td>
        <td>10.0</td>
        <td>nein</td>
      </tr>
      <tr>
        <td>Die leiden des Dom</td>
        <td>dom</td>
        <td>Dimtes</td>
        <td>1996</td>
        <td>2991</td>
        <td>10.0</td>
        <td>nein</td>
      </tr>



    </tbody>
  </table>
</template>

<script></script>

<style scoped>
.styled-table {
  border-collapse: collapse;
  width: 100%;
  margin: 25px 0;
  font-size: 0.9em;
  font-family: sans-serif;
  min-width: 400px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);
}
.styled-table thead tr {
  background-color: #24316b;
  color: #ffffff;
  text-align: left;
}
.styled-table th,
.styled-table td {
  padding: 12px 15px;
}
.styled-table tbody tr {
  border-bottom: 1px solid #dddddd;
}

.styled-table tbody tr:nth-of-type(even) {
  background-color: #f3f3f3;
}

.styled-table tbody tr:last-of-type {
  border-bottom: 2px solid #707776;
}

</style>
