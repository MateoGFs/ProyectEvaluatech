<template>
<div class="about">

<img alt="Vue logo" src="../assets/logo.png">

<div class="container">

    <h1>EvaluaTech</h1>
    <h3>Crea tu cuenta para EvaluaTech</h3>
    <h5>Docente</h5>

    <div class="form">

        <form>
                    <div class="form-floating mb-3">
                    <input type="nombres" class="form-control" id="floatingInput" placeholder="Nombres">
                    <label for="floatingInput">Nombres</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="apellidos" class="form-control" id="floatingInput" placeholder="Apellidos">
                    <label for="floatingInput">Apellidos</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="identificación" class="form-control" id="floatingInput" placeholder="Identificación">
                    <label for="floatingInput">Identificación</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="email" class="form-control" id="floatingInput" placeholder="Correo electrónico">
                    <label for="floatingInput">Correo electrónico</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="contraseña" class="form-control" id="floatingInput" placeholder="Contraseña">
                    <label for="floatingInput">Contraseña</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="confirmar contraseña" class="form-control" id="floatingInput" placeholder="Confirmar contraseña">
                    <label for="floatingInput">Confirmar contraseña</label>
                    </div>

                    <div class="form-floating mb-3">
                    <input type="telefono" class="form-control" id="floatingInput" placeholder="Teléfono">
                    <label for="floatingInput">Teléfono</label>
                    </div>

                    <button type="button" class="btn-primary">Registro</button>

        </form>


    </div> <!-- /form -->
</div>
</div>
</template>

<style>

img {width: 100px;
    height: 100px;
    float: left;
  }

h1 {text-align:center;
    color:rgb(0, 0, 0);
    font-weight:thin;
    margin:15px;
  }

h3 {text-align:center;
    color:rgb(0, 0, 0);
    font-weight:thin;
    margin:15px;
  }
h5 {text-align:left;
    color:rgb(0, 0, 0);
    font-weight:thin;
    margin:15px;
  } 

.container{background:rgb(255, 255, 255);
    border: solid black 4px;
    padding: 40px;
    max-width:600px;
    margin:40px auto;
  }
  /* .body{
    background: rgb(105, 155, 211);
  } */

.about{
     background: rgb(105, 155, 211); 
    /* background-color: rgb(13, 65, 47); */
    border: solid black 4px;
    /* padding: 40px;
    max-width:1300px; */
    /* margin:40px auto; */
    border-color: black;
  }

.form-control{background: rgb(105, 155, 211);
    border: solid black 4px;
  }

.btn-primary{border: solid black 4px;
    padding: 5px;
  }

</style>

