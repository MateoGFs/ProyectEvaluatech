<template>
  <div class="container">
    <h2>Estudiantes</h2>

    <div class="custom-select" style="width:200px;">
      
    <select class="form-select" aria-label="Default select example">
        <option selected>Seleccione grupo</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
    </select>
    </div>
    <br>

    <table class="table  table table-primary table-striped" >
            <thead>
                <tr class="table-secondary">
                    <th scope="col">Identificación</th>
                    <th scope="col">Nombres</th>
                    <th scope="col">Apellidos</th>
                    <th scope="col">Teléfono</th>
                    <th scope="col">Email</th>
                    <th scope="col">
                      <a href="#" title="Adicionar">
                        <img src="../assets/adduser2.png" />
                        </a>
                    </th>
                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row">1</th>
                    <td>Mateo</td>
                    <td>Rodriguez</td>
                    <td>1234324</td>
                    <td>mateo@gmail.com</td>
                    <td>(M)(D)</td>
                    
                </tr>
                <tr>
                   
                    
                </tr>
                <tr>
                    
                    
                </tr>
              </tbody>
            </table>
            
  </div>
</template>

<style>
h2{padding: 35px; text-align: center; }
</style>