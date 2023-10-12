<template>
    <div class="container-fluid my-5">
        <div class="row align-items-center justify-content-center">
            <div class="col-12 col-md-6 col-lg-5 ps-md-5 text-center text-sm-start">
                <h1 id="title-h1"><strong id="title-h1-purple">Design Inteligente:</strong>
                    <br>
                    Criatividade Impulsionada
                    pela IA
                </h1>
                <p id="text-section">
                    Faça parte da revolução do design impulsionada pela IA e conecte-se com milhões de brasileiros. Na
                    Designight, oferecemos uma plataforma inovadora que
                    combina a criatividade humana com o poder da Inteligência Artificial.
                </p>
                  <button class="btn btn-purple">Saiba mais</button>
            </div>
            <div class="col-12 col-md-6 col-lg-6  text-center text-sm-start d-none d-md-block">
                <img src="@/assets/Tablet.png" class="img-fluid" alt="">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'PrimeiraSection'
}
</script>
  
<style scoped>
#title-h1{
    font-size: 40px;
    color:  #000000;
    font-weight: bold;
}
#title-h1-purple{
    font-size: 35px;
    color:  #7B70FC;
}
#text-section{
    font-size: 17px;
}
.btn-purple{
    background-color: #7B70FC;
    color: #ffffff;
    font-weight: bold;
    padding-left: 65px;
    padding-right: 65px;
    border-radius: 10px;
}
</style>
  