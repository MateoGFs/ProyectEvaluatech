<template>
  <div class="container">
    <h2>Grupos</h2>

        <table class="table  table table-primary table-striped" >
            
            <thead>
                <tr class="table-secondary">
                    
                    <th scope="col">Código</th>
                    <th scope="col">Nombre</th>
                    <th scope="col">
                        <a href="#" title="Adicionar">
                        <img src="../assets/añadir.png" />
                        </a>
                    </th>
                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row">1</th>
                    <td>Grupo 90</td>
                    <td>(M)(E)</td>
                    
                </tr>
                <tr>
                    <th scope="row">2</th>
                    <td>Grupo 53</td>
                    
                </tr>
                <tr>
                    <th scope="row">3</th>
                    
                    <td colspan="1">Grupo 23</td>
                    
                </tr>
              </tbody>
            </table>
           


  </div>
</template>


<script>
export default{

    data() {
        return {
            grupos:[]
            
        }
    },

    created() {
        
    },

    methods: {

    }
}
</script>

<style>
img{
  width: 35px;
}

h2{padding: 35px; text-align: center; }
</style>