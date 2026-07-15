<!DOCTYPE html>

<html lang="pt-br">
<head>
    <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
    <title>Tela de login!</title>
    
    <style>
       * {
           margin: 0;
           padding: 0;
           box-sizing: border-box;
           font-family: 'Poppins', sans-serif;
       }
       body {
           display: flex;
           justify-content: center;
           align-items: center;
           min-height: 100vh;
           
           background-image: url('https://server.wallpaperalchemy.com/storage/wallpapers/1719/minecraft-enchanted-forest-treehouse-village-wallpaper-card.jpg');
           background-size: cover;
           background-position: center;
       }
       .container {
           width: 420px;
           background-color: transparent;
           border: 2px solid rgba(255,255,255,.2);
           border-radius: 10px; /*É aquela bordinha bonitinha*/
           color: #fff;
           padding: 25px 25px;
           box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
           backdrop-filter: blur(1.8px); /*MUUIITO IMPORTANTE!! Serve pra deixar o container meu opaco (e dá pra deixar + ou - pra controlar a quantidade de opaco)*/
       }
       .container h1 {
           font-size: 48px;
           text-align: center;
       }
       .input-box {
           position: relative;
           width: 100%;
           height: 50px; /*Aqui ó, 50 pixels*/
           margin: 25px 0;
       }
       .input-box input {
           width: 100%;
           height: 100%; /*Como tá na classe do input-box vai ocupar a altura máxima que tava antes, que é 50px (pixels)*/
           background-color: transparent;
           border-radius: 40px; /*Arredondooouu*/
           border: 2px solid rgba(255,255,255,.2);
           outline: none; /*Sem aquela linha azul que fica envolta do campo de texto quando tá escrevendo*/
           font-size: 16px;
           color: #fff; /*A cor do texto dentro do campo de texto fica branco*/
           padding: 20px 45px 20px 20px; /*Em cima, direita, baixo, esquerda*/
       }
       .input-box input::placeholder { /*É pra editar aquele texto de dentro no placeholder*/
           color: #fff;
       }
       .input-box i { /*Serve pra ajustar o ícone*/
           position: absolute;
           right: 20px; /*Arrasta 20px pra direita*/
           top: 50%; 
           transform: translateY(-50%);/*Ajuste do ícone de novo*/
           font-size: 20px; /*Tamanho do ícone*/
       }
       .remember-forgot {
           display: flex;
           justify-content: space-between; /*Joga cada texto pra um lado*/
           margin: -15px 0 15px;
       }
    /*
        Margin & pagging:
    
        1 valor – margin: 20px = Todos os lados.
        2 valores – margin: 20px 30px = Em cima e embaixo, dos lados.
        3 valores – margin: 20px 30px 40px = Em cima, dos lados,embaixo.
        4 valores – margin: 20px 30px 40px 50px = Em cima, direita, embaixo, esquerda (igual um relógio).
    */
       .remember-forgot label input {
           margin-right: 5px;
       }
       .remember-forgot a { /* Serve para editar o <a> (link) */
           text-decoration: none; /* Remove a linha abaixo do texto */
           color: #fff;
           font-weight: bold;
       }
       .remember-forgot a:hover { /* Quando passar o mouse sobre o link */
           text-decoration: underline; /* Adiciona a linha abaixo */
       }
       .login {
           width: 100%;
           height: 50px;
           background-color: #fff;
           border: none;
           border-radius: 40px;
           cursor: pointer; /*Serve para usuários de pc quando clicar/passar por cima do botão invés de uma seta uma mãozinha*/
           font-size: 18px;
           color: #333;
           font-weight: 600;
           box-shadow: 0 0 10px rgba(0,0,0,.1);
       }
       .login:hover {
           background-color: #333;
           color: #fff;  
           transition: 0.5s; /*Mudar de cor um pouco mais devagar*/          
       }
       .register-link {
           font-size: 16px;
           text-align: center;
           margin: 20px 0 15px;
       }
       .register-link a {
           text-decoration: none;
           color: #fff;
           font-weight: 600;
       }
       .register-link a:hover {
           text-decoration: underline;
       }
       .gif img {
           display: block;
           margin-left: auto;
           margin-right: auto;
       }
    </style>
</head>
<body>
    <main class="container"> <!--A página toda-->
        <form action="project_home.html">
            <h1>Tela de login</h1>

        <div class="input-box">
            <input required placeholder="Usuário" type="email" maxlength="40" oninvalid="this.setCustomValidity('TEM QUE BOTAR A BUDEGA DO E-MAIL!')" oninput="this.setCustomValidity('')">
                <i class="bx bxs-user"></i>
        </div>
        <div class="input-box">
           <input required placeholder="Senha" type="password" maxlength="20" oninvalid="this.setCustomValidity('AAAAAA DA PRÓXIMA VEZ EU TE COBRO A SENHA DO BOLSA-FAMÍLIA!!')" oninput="this.setCustomValidity('')">
                <i class="bx bxs-lock-alt"></i>
        </div>
        <div class="remember-forgot">
            <label>
                <input type="checkbox">
                Lembrar minha senha!
            </label>
            <a href="#">Esqueci minha senha!</a>
        </div>
    <button type="submit" class="login">Login</button>
        <div class="register-link">
            <p>Opa! Não tem conta? <a href="#">Cadastre-se!</a></p>
        </div>
        </form>
         <section class="gif">
            <img src="https://media.tenor.com/9_m7XWZP0XwAAAAi/minecraft.gif" alt="gif pikachu picareta">
         </section>
    </main>
</body>
</html>
