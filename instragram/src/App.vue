
<template>
  
  <div class="header">
      
      <div class="logo">
    <p>Instagram</p>
      </div>
     
     <div class="iconos">
       <img src="./assets/agregar.png">
       <img src="./assets/me-gusta.png">
       <img src="./assets/Mensaje.png">
     </div>
  </div>

<div class="estados">

  <div class="estado-1">
    <img src="./assets/Luffy.jpg"> 
    <span>Tu Historia</span>
 </div> 
     <div class="agregar">
       <img src="./assets/Estado.png"> 
      </div>


<div class="estado-2">
    <img src="./assets/Zoro.jpg"> 
    <span>Zoro</span>
 </div> 

<div class="estado-3">
    <img src="./assets/Sanji.jpg"> 
    <span>Sanji</span>
 </div> 

<div class="estado-4">
    <img src="./assets/Chopper.jpg"> 
    <span>Chopper</span>
 </div> 

<div class="estado-5">
    <img src="./assets/Nami.jpg"> 
    <span>Nami</span>
 </div> 
</div>

<div class="Cards">
   
  <div class="card-1">
     <div class="header-card-1">
       <img src="./assets/Law.jpg">
       <span>Trafalgar_D_Law</span>
    </div>
     <div class="body-card-1">
        <img src="./assets/Fondo.jpg">
     </div>
     <div class="interacion-card-1">
        <img src="./assets/me-gusta.png">
        <img src="./assets/Comentario.png">
        <img src="./assets/Compartir.png">
     </div>
     <div class="guardar-card-1">
        <img src="./assets/Guardar.png">
     </div>
     <div class="menu-card-1">
        <img src="./assets/menu.png">
     </div>
    <div class="footer-letter-card-1">
      <span>5,000 likes</span>
    </div>
    <div class="footer-card-1">
      <img src="./assets/Luffy.jpg">
      <p>Add a Commet...</p>
    </div>
  </div> 

   
    <div class="card-2">
     <div class="header-card-2">
       <img src="./assets/Shanks.jpg">
       <span>Akagami_No_Shanks</span>
    </div>
     <div class="body-card-2">
        <img src="./assets/shanks-fondo.jpg">
     </div>
     <div class="interacion-card-2">
        <img src="./assets/me-gusta.png">
        <img src="./assets/Comentario.png">
        <img src="./assets/Compartir.png">
     </div>
     <div class="guardar-card-2">
        <img src="./assets/Guardar.png">
     </div>
     <div class="menu-card-2">
        <img src="./assets/menu.png">
     </div>
    <div class="footer-letter-card-1">
      <span>6,000 likes</span>
    </div>
    <div class="footer-card-2">
      <img src="./assets/Luffy.jpg">
      <p>Add a Commet...</p>
    </div>
  </div> 


<div class="card-3">
     <div class="header-card-3">
       <img src="./assets/Doffy.jpg">
       <span>Donquixote_Doflamingo</span>
    </div>
     <div class="body-card-3">
        <img src="./assets/doffy-fondo.jpg">
     </div>
     <div class="interacion-card-3">
        <img src="./assets/me-gusta.png">
        <img src="./assets/Comentario.png">
        <img src="./assets/Compartir.png">
     </div>
     <div class="guardar-card-3">
        <img src="./assets/Guardar.png">
     </div>
     <div class="menu-card-3">
        <img src="./assets/menu.png">
     </div>
    <div class="footer-letter-card-3">
      <span>9,000 likes</span>
    </div>
    <div class="footer-card-3">
      <img src="./assets/Luffy.jpg">
      <p>Add a Commet...</p>
    </div>
  </div> 

</div>


</template>

<script>
export default {
    
}
</script>

<style>

*
{
  margin:  0;
  padding: 0;
  font-family: 'Fredoka', sans-serif;
  background-color: black;
  color: white;
}


/*Header Configuration*/
@import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Inter&family=Open+Sans:wght@300;400&family=Roboto:wght@300&display=swap');
.header
{
  width:  100%;
  height: 60px;
  background-color: black;
  position: fixed;
  z-index: 300;
}

.logo p
{
  color: wheat;
  font-family: 'Fredoka', sans-serif;
  font-size: 25px;
}

.logo
{
  
  width: 20%;
  position: fixed;
  top:  15px;
  left: 10px;
}

.iconos
{
   width:  140px;
   position: absolute;
   left: 63%;
   top: 15px;
}

.iconos img
{
  width:  30px;
  height: 30px;
  margin-left: 15px;
}


/*Estados Configuration*/

.estados
{
  width:  100%;
  height: 160px;
  background-color: black;
  position: absolute;
  top: 5px;
  z-index: -1;
  border-bottom: 3px solid rgb(99, 99, 99); 
  overflow-y: auto;
}

.estado-1 img
{
  width:  70px;
  height: 70px;
  border-radius: 50%;
  position: absolute;
  top: 68px;
  left: 5px;
}

.estado-1 span
{
  font-size: 12px;
  color: white;
  position: relative;
  top: 137px;
  left: 13px;
}

.agregar img
{
  width:  20px;
  height: 20px;
  border-radius: 50%;
  border: solid 3px black;
  position: relative;
  top: 95px;
  left: 50px;
}

/*estado 2*/

.estado-2 img
{
  width:  70px;
  height: 70px;
  border-radius: 50%;
  border: solid 3px rgb(18, 204, 43);
  position: absolute;
  top: 66px;
  left: 90px;
}

.estado-2 span
{
  font-size: 12px;
  color: white;
  position: relative;
  top: 89px;
  left: 115px;
}

/*estado 3*/

.estado-3 img
{
  width:  70px;
  height: 70px;
  border-radius: 50%;
  border: solid 3px rgb(18, 204, 43);
  position: absolute;
  top: 66px;
  left: 180px;
}

.estado-3 span
{
  font-size: 12px;
  color: white;
  position: relative;
  top: 70px;
  left: 203px;
}


/*estado 4*/

.estado-4 img
{
  width:  70px;
  height: 70px;
  border-radius: 50%;
  border: solid 3px rgb(18, 204, 43);
  position: absolute;
  top: 66px;
  left: 270px;
}

.estado-4 span
{
  font-size: 12px;
  color: white;
  position: relative;
  top: 50px;
  left: 285px;
}


/*estado 5*/

.estado-5 img
{
  width:  70px;
  height: 70px;
  border-radius: 50%;
  border: solid 3px rgb(18, 204, 43);
  position: absolute;
  top: 66px;
  left: 355px;
}

.estado-5 span
{
  font-size: 12px;
  color: white;
  position: relative;
  top: 31px;
  left: 380px;
}


/*Publicaciones*/

/*Card-1*/

.card-1
{
  width: 100%;
  height: 300px;
  background-color: aqua;
  position: absolute;
  top: 173px;
}

.header-card-1
{
  width: 100%;
  height: 60px; 
  position: absolute;
  top: 0px;
}

.header-card-1 img 
{
  width:  40px;
  height: 40px;
  margin-left: 3px;
  margin-top: 13px;
  border-radius: 50%;
  cursor: pointer;
}

.header-card-1 span 
{
  position: absolute;
  top: 30px;
  left: 46px;
  cursor: pointer;
}

.body-card-1
{
  width: 100%;
  height: 100%;
  background-color: brown;
}

.body-card-1 img
{
   width:  100%;
   height: 100%;
}

.interacion-card-1
{
  width: 100%;
  height: 20px;
}

.interacion-card-1 img 
{
  width: 25px;
  margin-left: 5px;
  margin-top: 5px;
  cursor: pointer;
}

.guardar-card-1 
{
  width: 100%;
  height: 15px;
}

.guardar-card-1 img 
{
  width: 25px;
  position: absolute;
  left: 92%;
  top: 305px;
  cursor: pointer;
}

.menu-card-1
{
  width: 100px;
  height: 25px;
  position: absolute;
  top: 30px;
  left: 68%;
}

.menu-card-1 img 
{
  width: 25px;
  position: absolute;
  left: 90%;
  top: -5px;
  cursor: pointer;
}

.footer-letter-card-1
{
  width: 100px;
  height: 25px;
  margin-left: 6px;
  font-size: 18px;
}

.footer-card-1 img
{
  width:  33px;
  height: 33px;
  border-radius: 50%;
  position: absolute;
  left: 2px;
  top: 370px;
}

.footer-letter-card-1 span 
{
  cursor: pointer;
}


.footer-card-1 p 
{
  position: absolute;
  left: 41px;
  top: 380px;
  font-size: 19px;
  opacity: 50%;
  color: rgb(150, 150, 150);
  font-family: 'Inter', sans-serif;
  cursor:text;
}


/*card-2*/

.card-2
{
  width: 100%;
  height: 300px;
  background-color: aqua;
  position: absolute;
  top: 590px;
}

.header-card-2
{
  width: 100%;
  height: 60px; 
  position: absolute;
  top: 0px;
}

.header-card-2 img 
{
  width:  40px;
  height: 40px;
  margin-left: 4px;
  margin-top: 13px;
  border-radius: 50%;
  cursor: pointer;
}

.header-card-2 span 
{
  position: absolute;
  top: 30px;
  left: 46px;
  cursor: pointer;
}

.body-card-2
{
  width: 100%;
  height: 100%;
  background-color: brown;
}

.body-card-2 img
{
   width:  100%;
   height: 100%;
}

.interacion-card-2
{
  width: 100%;
  height: 20px;
}

.interacion-card-2 img 
{
  width: 25px;
  margin-left: 5px;
  margin-top: 5px;
  cursor: pointer;
}

.guardar-card-2 
{
  width: 100%;
  height: 15px;
}

.guardar-card-2 img 
{
  width: 25px;
  position: absolute;
  left: 92%;
  top: 305px;
  cursor: pointer;
}

.menu-card-2
{
  width: 100px;
  height: 25px;
  position: absolute;
  top: 30px;
  left: 68%;
}

.menu-card-2 img 
{
  width: 25px;
  position: absolute;
  left: 90%;
  top: -5px;
  cursor: pointer;
}

.footer-letter-card-2
{
  width: 100px;
  height: 25px;
  margin-left: 6px;
  font-size: 18px;
}

.footer-card-2 img
{
  width:  33px;
  height: 33px;
  border-radius: 50%;
  position: absolute;
  left: 2px;
  top: 370px;
  cursor: pointer;
}

.footer-letter-card-2 span 
{
  cursor: pointer;
}


.footer-card-2 p 
{
  position: absolute;
  left: 41px;
  top: 380px;
  font-size: 19px;
  opacity: 50%;
  color: rgb(150, 150, 150);
  font-family: 'Inter', sans-serif;
  cursor:text;
}


/*card-3*/

.card-3
{
  width: 100%;
  height: 300px;
  background-color: aqua;
  position: absolute;
  top: 1010px;
}

.header-card-3
{
  width: 100%;
  height: 60px; 
  position: absolute;
  top: 0px;
}

.header-card-3 img 
{
  width:  40px;
  height: 40px;
  margin-left: 4px;
  margin-top: 13px;
  border-radius: 50%;
  cursor: pointer;
}

.header-card-3 span 
{
  position: absolute;
  top: 30px;
  left: 46px;
  cursor: pointer;
}

.body-card-3
{
  width: 100%;
  height: 100%;
  background-color: brown;
}

.body-card-3 img
{
   width:  100%;
   height: 100%;
}

.interacion-card-3
{
  width: 100%;
  height: 20px;
}

.interacion-card-3 img 
{
  width: 25px;
  margin-left: 5px;
  margin-top: 5px;
  cursor: pointer;
}

.guardar-card-3
{
  width: 100%;
  height: 15px;
}

.guardar-card-3 img 
{
  width: 25px;
  position: absolute;
  left: 92%;
  top: 305px;
  cursor: pointer;
}

.menu-card-3
{
  width: 100px;
  height: 25px;
  position: absolute;
  top: 30px;
  left: 68%;
}

.menu-card-3 img 
{
  width: 25px;
  position: absolute;
  left: 90%;
  top: -5px;
  cursor: pointer;
}

.footer-letter-card-3
{
  width: 100px;
  height: 25px;
  margin-left: 6px;
  font-size: 18px;
}

.footer-card-3 img
{
  width:  33px;
  height: 33px;
  border-radius: 50%;
  position: absolute;
  left: 2px;
  top: 370px;
  cursor: pointer;
}

.footer-letter-card-3 span 
{
  cursor: pointer;
}


.footer-card-3 p 
{
  position: absolute;
  left: 41px;
  top: 380px;
  font-size: 19px;
  opacity: 50%;
  color: rgb(150, 150, 150);
  font-family: 'Inter', sans-serif;
  cursor:text;
}


</style>