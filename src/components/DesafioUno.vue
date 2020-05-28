<template>
  <div id="desafio1">
    <div class="container">
      <div class="row mx-auto">
        <div class="col-12 d-flex justify-content-center py-5">
          <header>
            <h3>Tabla de Usuarios</h3>
          </header>
        </div>
        <div class="col-12">
          <table class="table table-hover">
            <thead class="thead-light">
              <tr>
                <th scope="col">#</th>
                <th scope="col">{{ headers[0] }}</th>
                <th scope="col">{{ headers[1] }}</th>
                <th scope="col">{{ headers[2] }}</th>
                <th scope="col">{{ headers[3] }}</th>
                <th scope="col">{{ headers[4] }}</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th scope="row">1</th>
                <td>{{ people[0].nombre }}</td>
                <td>{{ people[0].apellido }}</td>
                <td>{{ people[0].run }}</td>
                <td>{{ people[0].nacimiento }}</td>
                <td>{{ people[0].edad }}</td>
              </tr>
              <tr>
                <th scope="row">2</th>
                <td>{{ people[1].nombre }}</td>
                <td>{{ people[1].apellido }}</td>
                <td>{{ people[1].run }}</td>
                <td>{{ people[1].nacimiento }}</td>
                <td>{{ people[1].edad }}</td>
              </tr>
              <tr>
                <th scope="row">3</th>
                <td>{{ people[2].nombre }}</td>
                <td>{{ people[2].apellido }}</td>
                <td>{{ people[2].run }}</td>
                <td>{{ people[2].nacimiento }}</td>
                <td>{{ people[2].edad }}</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>

  
</template>

<script>

export default {
  name: "DesafioUno",
  components: {},
  data() {
    return {
      headers: ["Nombre", "Apellido", "RUN", "Nacimiento", "Edad"],
      people: [
        {
          nombre: "José",
          apellido: "Pérez",
          run: "123456-2",
          nacimiento: "12-04-67",
          edad: 52,
        },
        {
          nombre: "María",
          apellido: "Rodriguez",
          run: "654321-1",
          nacimiento: "30-11-90",
          edad: 29,
        },
        {
          nombre: "Manuel",
          apellido: "Patiño",
          run: "14223456-6",
          nacimiento: "02-12-59",
          edad: 60,
        },
      ],
    };
  },
};
</script>

<style lang="scss">
#desafio1 {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
