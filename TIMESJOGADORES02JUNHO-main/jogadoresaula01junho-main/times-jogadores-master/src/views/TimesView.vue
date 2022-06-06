<template>
  <div class="container">
    <div class="title">
      <h2>gerenciamento de times</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Ações</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>???</td>
          </tr>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>???</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style>
.title {
  text-align: center;
}
.form-input {
  display: flex;
  justify-content: center;
}

.form-input input {
  width: 50%;
  border: 1px solid black;
  border-radius: 10px;
  padding: 0 2rem;
  height: 40px;
}

.form-input button {
  height: 40px;
  margin-left: 1%;
  background-color: rgb(255, 255, 255);
  font-weight: bold;
  color: rgb(7, 6, 6);
}

.list-times {
  display: flex;
  justify-content: center;
  margin: 2rem 0;
}

table {
  width: 40%;
  border: 1px solid;
  border-collapse: collapse;
  text-align: center;
}

table thead {
  background-color: rgb(1, 143, 148);
  color: rgb(255, 255, 255);
}

table thead th {
  font-weight: bolder;
}

table tbody tr:nth-child(odd) {
  background-color: rgb(0, 112, 116);
}
</style>
