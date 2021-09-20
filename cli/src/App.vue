<template id="temp">
  <div id="app">
    <div id="nav">
      <section>
     <header>
      <nav>
      
      <ul>
      <li><router-link id="i" to="/">Inicio</router-link></li> 
      <li><router-link id="i" to="/grupos">Grupos</router-link></li>
      <li><router-link id="i" to="/estudiantes">Estudiantes</router-link></li>
      <li><router-link id="i" to="/areas">Áreas</router-link></li>
      <li><router-link id="i" to="/subareas">Subáreas</router-link></li>
      <li><router-link id="i" to="/evaluacion">Evaluación</router-link></li>
      <li><router-link id="i" to="/preguntas">Preguntas</router-link></li>
      <li><router-link id="i" to="/login">Login</router-link></li>
      <li><router-link id="i" to="/registro">Registro</router-link></li>
      </ul>
        
      </nav>
      </header>
        
      </section>

    </div>
    <router-view/>
  </div>
</template>

<style>

*{text-decoration:none; list-style:none; margin:0px; padding:0px;  outline:none;} 
body{margin:0px; padding:0px; font-family: 'Open Sans', sans-serif;}
section{width:100%;  max-width:1400px;  display:table; position:relative;}
/* h1{margin:0px auto; display:table; font-size:26px; padding:40px 0px; color:#002e5b; text-align:center;}
h1 span{font-weight:500;} */

header{width:100%; display:table; background-color:rgb(13, 65, 47); margin-bottom:20px;}

nav{width:auto; float:right;}
nav ul{display:table; float:right;}
nav ul li{ float:left;}
nav ul li:last-child{padding-right:0px;}
nav ul li a{color: rgb(167, 241, 215); font-size:16px; padding: 18px 20px; display:inline-block; transition: all 0.5s ease 0s;}
nav ul li a:hover{background-color: rgb(167, 241, 215); color:rgb(13, 65, 47); transition: all 0.5s ease 0s;}
nav ul li a:hover i{color:#fde428; transition: all 0.5s ease 0s;}

#i{
  text-decoration: none;
}
</style>





 



<style lang="scss">
  #nav {
   padding: 0px;
   height: 60px;
   
  

   a {
     font-weight: bold;
     

     &.router-link-exact-active {
       color:#5379fa;
       
     }
   }
 }
</style>
