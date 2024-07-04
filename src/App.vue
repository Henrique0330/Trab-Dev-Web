<script setup></script>
<template>
  <div class="form">
    <form action="#">
      <div class="header">
        <div class="titulo">
          <h1>Cadastre-se</h1>
        </div>
        <div class="button-login">
          <button><a href="">Entrar</a></button>
        </div>
      </div>
      <div class="input-grupo">
        <div class="imput-box">
          <label for="Pnome">Primeiro Nome</label>
          <input id="Pnome" type="text" name="Pnome" placeholder="Digite Seu primeiro nome" required>
        </div>

        <div class="imput-box">
          <label for="sobrenome">Sobrenome</label>
          <input id="sobrenome" type="text" name="sobrenome" placeholder="Digite Seu Sobrenome" required>
        </div>

        <div class="imput-box">
          <label for="number">Celular</label>
          <input id="number" type="tel" name="number" placeholder="(xx) xxxx-xxxx" required>
        </div>

        <div class="imput-box">
          <label for="E-mail">E-mail</label>
          <input id="E-mail" type="text" name="E-mail" placeholder="Digite Seu E-mail" required>
        </div>

        <div class="imput-box">
          <label for="Senha">Senha</label>
          <input id="Senha" type="text" name="Senha" placeholder="Digite Seu Senha" required>
        </div>

        <div class="imput-box">
          <label for="Csenha">Confirme sua senha</label>
          <input id="Csenha" type="text" name="Csenha" placeholder="Confirme sua senha" required>
        </div>
      </div>
      <div class="Imput-genero">
        <div class="Imput-titulo">
          <h6>Gênero</h6>
        </div>
        <div class="genero-grupo">
          <div class="generos">
            <input type="radio" id="feminino" name="agente">
            <label for="feminino">Feminino</label>
          </div>

          <div class="generos">
            <input type="radio" id="feminino" name="agente">
            <label for="feminino">Feminino</label>
          </div>
          
          <div class="generos">
            <input type="radio" id="masculino" name="agente">
            <label for="masculino">Masculino</label>
          </div>

          <div class="generos">
            <input type="radio" id="outro" name="agente">
            <label for="outro">Outro</label>
          </div>

          <div class="generos">
            <input type="radio" id="nada" name="agente">
            <label for="nada">Prefiro não informar</label>
          </div>
        </div>
      </div>
    </form>
  </div>
</template>

<style scoped>

</style>
