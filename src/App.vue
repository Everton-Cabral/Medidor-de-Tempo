<template>
  <div id="app">
  <appMenu></appMenu>
  <div class="blocos"> 
    <appWork></appWork>
    <appPlay></appPlay>
    <appStudy></appStudy>
    <appExercise></appExercise>
    <appSocial></appSocial>
    <appSelfCare></appSelfCare>
    
  </div>
  
  
  </div>
  
</template>

<script>
 import appMenu from '@/components/menu';
 import appWork from '@/components/work';
 import appPlay from '@/components/play';
 import appStudy from '@/components/study';
 import appExercise from '@/components/exercise';
 import appSocial from '@/components/social';
 import appSelfCare from '@/components/selfCare';
 
export default {
 components:{ appMenu, appWork, appPlay, appStudy, appExercise, appSocial, appSelfCare}
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,100&family=Rubik:wght@300;400;500&display=swap');
body{
  margin: 0px 0px 800px 0px;
  background-color: hsl(226, 43%, 10%);
  
}
#app{ 
  background-color: hsl(226, 43%, 10%);
 height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: center;
 

  
  }
  .blocos{
    height: 339px;
    width: 500px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    margin-left:15px;
    
    
  }
  .bloco-container{
      width: 150px;
      height: 150px;
      margin-right: 15px;
      margin-top: 10px;
      border-radius: 5%;
      display: flex;
      justify-content: flex-end;
      align-items: flex-end;
     
      
  }
  .icone{
    height: 45px;
    margin-left: -8px;
    margin-top: -105px;
    position: absolute;
     
    
  }
    .bloco-subcontainer{
    width: 100%;
    height: 75%;
    border-radius: 5%;
    position: relative;
    background-color: hsl(235, 46%, 20%);  
  }

  .bloco-subcontainer:hover{
   background-color: hsl(235, 45%, 61%);
   cursor: pointer;
  }
.bloco-titulo{
  font-family: 'Rubik', sans-serif;
  color: whitesmoke;
  font-size: 13px;
  margin-top:20px;
  margin-left: 20px;
}
#pontos{
  height: 4px;
}
.bloco-corpo{
  color: whitesmoke;
   font-family: 'Rubik', sans-serif;
   font-weight: 100;
   font-size: 30px;
   margin-left: 20px;
   margin-top: 18px;
}
#subhora{
  margin-top: 0px;
  font-size: 9px;
  color:#C0C0C0;
  margin-left:0px;    
  font-weight: 500;
}

@media(max-width:800px){
  
  #app{
    display: flex;
    flex-wrap: wrap;
    height: auto;
  }
  .blocos{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .bloco-container{
    width: 85%;
     overflow: auto;
      margin-top: 8%;
  }
 
.bloco-titulo{
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-right: 5%;
  margin-left: 5%;
}
 .bloco-corpo{
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-right: 5%;
 }

}
</style>
