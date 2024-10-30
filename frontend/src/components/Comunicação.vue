<template>
    <div class="wrapper">
      <div class="img-section">
        <img src="../Imagens/comunicação.png" alt="comunicação" class="comunicação">
      </div>
      <div class="text-section">
        <h2>Descubra o melhor<br>prestador para você</h2>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Comunicação"
  };
  </script>
  
  
<style scoped>
.wrapper {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  background-color: #f9f9f9;
}

.img-section {
  max-width: 50%;
  text-align: center;
}

.clienteImg {
  width: 100%;
  max-width: 400px;
  object-fit: contain;
}

.text-section {
  max-width: 45%;
}

.text-section h2 {
  font-size: 28px;
  color: #458FF6;
  margin-bottom: 10px;
  line-height: 1.3;
}

</style>