<html>

<img src="https://i.imgur.com/VC44zJJ.png">


<div class="container-login">

  <div class="login h2">
    <h2 style="color: #A6A65A;">Bem vindo de volta!</h2>
  </div>

  <div class="texto-login">
    <p>Faça login para continuar</p>
  </div>

  <h2>E-mail</h2>

  <div class="email">
    <input type="email" placeholder="Digite seu email">
  </div>
  
  <h2>Senha</h2>

  <input type="password" placeholder="Digite sua senha">

  <div class="esqueci">
    <p>esqueci minha senha</p>
  </div>
    
  <button class="entrar">Entrar</button>

  <p>ou</p>

  <button class="google">Continuar com o google</button>
  
  <p>Não tem uma conta </p>
  
  <button class="conta">Criar conta</button>

</div>

<style> 
  body {
    background-color: #f8f4ef;
    display: flex;
    flex-direction: column;
    align-items: center;      
    justify-content: center;   
    min-height: 100vh;        
    margin: 0;
    font-family: sans-serif;
  }

  .container-login {
    width: 100%;
    max-width: 400px;         
    display: flex;
    flex-direction: column;   /
  }

 
  .login h2{
     background-color: #f8f4ef
  } 

  .email{
    width: 100%;
    max-width: 400px;           
    height: 45px;        
    font-size: 16px;        
    border-radius: 8px;     
    border: 1px solid #cccccc00; 
    box-sizing: border-box; 
  }

  .esqueci p {
    color: #c0715d
  }

  .entrar {
    border: solid 1px rgba(255, 255, 255, 0);
    background-color: #c0715d;
    color: #FFFFFF;
    padding: 15px 30px; 
    font-size: 18px;
    border-radius: 8px;
  }

  .conta{
    border: solid 1px rgba(255, 255, 255, 0);
    background-color: #f8f4ef;
    color: #c0715d;
  }
    
  .google{
    padding: 15px 30px; 
    font-size: 18px;
  }
</style>
</html>
