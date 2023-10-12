<template>
  <div>
    <nav class="navbar navbar-expand-sm ">
  <div class="container-fluid px-md-5">
    <div class="row align-items-center">
      <div class="col-10">
         <a class="navbar-brand" href="#"><img src="@/assets/logo.png" class="w-75" alt=""></a>
      </div>
      <div class="col">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
      </div>
    </div>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Serviços</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Portifólio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link " >Contatos</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
 </div>
</template>
<script>
export default {
  name: 'HeaderCabecalho'
}
</script>

<style scoped>
  .nav-link{
    color: #000000;
    font-size: 20px;
    font-weight: bold;
  }
  .nav-link:hover{
    color: #7B70FC;
  }
</style>
