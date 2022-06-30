<template>
    <div class="container">
        <div class="sub-container">
            <img src="../assets/image-jeremy.png" alt="perfil" id="imagem">
            <p id="report">Report for</p> 
            <h3> Jeremy Robson</h3>
        </div>
        <div class="nav-bar"> 
            <p>Daily</p>
            <p>Weekly</p>
            <p>Monthly</p></div>
        </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,100&family=Rubik:wght@300;400;500&display=swap');
.container{
    width: 150px;
    height: 320px;
    background-color: hsl(235, 46%, 20%);
    border-radius: 4%;
    font-family: 'Rubik', sans-serif;
    font-size: 12px;
    color: whitesmoke;
    font-weight: 100;
   }
   .nav-bar{
    color: #A9A9A9
   }
.nav-bar p:hover{
    color: white;
    cursor: pointer;
}
#report{
    margin-top: 30px;
    margin-left: 15px;
    font-size: 10px;
    color: 	#C0C0C0;
    margin-bottom: 0px;
   
    
}
h3{
    font-size: 22px;
    font-weight: 200;
    margin-left: 15px;
    margin-top: 0px;
}
p{
    margin-left: 15px;
}
.sub-container{
    width: 150px;
    height: 220px;
    background-color:hsl(246, 80%, 60%);
    border-radius: 4%;
   
}
#imagem{
   height: 40px;
   border-radius: 50%;
   border: 2px solid white;
   margin-top: 15px;
   margin-left: 15px;
}
@media(max-width: 800px){
    .container{
        width: 85%;
        margin-top: 13%;
        height: 172px;
        }
    .sub-container{
        width: 100%;
        height: 120px;
        display: flex;
    }
  #report{
    
    font-size: 10px;
    color: 	#C0C0C0;
    margin-top: 40px;
  
  }
  h3{
     margin-top: 50px;
     margin-left: -45px;
     
     
  }
  #imagem{
   height: 50px;
   border-radius: 50%;
   border: 2px solid white;
   margin-top: 25px;
   margin-left: 15px;
  }
  .nav-bar{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-top: 8px;
    font-size: 13px;
    color: 	#A9A9A9;
    font-weight: 500;
  }
  .nav-bar p:hover{
    color: white;
  }
  
}
</style>
