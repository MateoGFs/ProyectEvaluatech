<template>
  <div class="container">
    <h2>Evaluaciones</h2>

<div class="filtroConsulta"> 
     <table class="table">
       <thead>
       <tr>
         <th scope="col">
    <select class="form-select" aria-label="Default select example" >
        <option selected>Seleccione área</option>
        <option value="1">Matemáticas</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
    </select>
         </th>
         <th scope="col">
   <select class="form-select" aria-label="Default select example" >
        <option selected>Seleccione Subárea</option>
        <option value="1">Matemáticas</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
    </select>
    </th>
      <th scope="col">
   <select class="form-select" aria-label="Default select example">
        <option selected>Seleccione grupo</option>
        <option value="1">Matemáticas</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
    </select>
    </th>

    <th><button type="button" class="btn btn-outline-primary">Consultar</button></th>

    </tr>
    </thead>
     </table>
</div>

    <br>

    <table class="table  table table-primary table-striped" >
            <thead>
                <tr class="table-secondary">
                    <th scope="col">Código Evaluación</th>
                    <th scope="col">Núm. Preguntas</th>
                    <th scope="col">Fecha</th>
                    <th scope="col">Hora de inicio</th>
                    <th scope="col">Hora fin</th>
                    <th scope="col">Grupo</th>
                    <th scope="col">Nombre</th>
                    <th scope="col">Área</th>
                    <th scope="col">Subárea</th>
                    <th scope="col">
                      <a href="#" title="Adicionar">
                        <img id="img" src="../assets/añadir.png" />
                        </a>
                    </th>
                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
                    <td>10</td>
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
img{
  width: 35px;
}
h2{padding: 35px; text-align: center; }
</style>