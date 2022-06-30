<template>
    <div class="bloco-container" id="selfCare">
        <img src="../assets/icon-self-care.svg" alt="" class="icone">
        <div class="bloco-subcontainer">
            <div class="bloco-titulo">
                SelfCare
                <img src="../assets/icon-ellipsis.svg" alt="" id="pontos-sel">
            </div>
           <div class="bloco-corpo">
             2hrs
            <p id="subhora">Last Week - 2hrs</p> 
           </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
#selfCare{
     background-color:hsl(43, 84%, 65%);
    }
    #pontos-sel{
        height: 4px;
        margin-left: 45px;
    }
</style>
