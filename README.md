<!DOCTYPE html>

<html lang="pt-br">
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
