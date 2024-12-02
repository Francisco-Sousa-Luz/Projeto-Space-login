🎉 Novo Projeto Concluído: Space Login 🎉
Estou muito animado em compartilhar com vocês meu mais recente projeto de desenvolvimento web, o Space Login! 🚀

#Sobre o Projeto:
O Space Login é uma interface de login estilizada que combina funcionalidade e design moderno. Este projeto foi desenvolvido utilizando HTML e CSS, focando na criação de uma experiência de usuário envolvente e visualmente atraente.

#Principais Funcionalidades:
Tela de login com campos para usuário e senha.

Efeitos de foco suaves e transições para uma melhor experiência de usuário.

Opção para lembrar a senha e link para recuperação.

Design responsivo e elegante com fundo temático espacial.

#Tecnologias Utilizadas:
HTML5: Estrutura semântica clara e organizada.

CSS3: Estilização avançada com efeitos visuais como sombras, desfoque de fundo (backdrop-filter) e transições suaves.

#Destaques do Design:
Fundo com imagem temática espacial: para um visual imersivo, criado por mim através da plataforma Leonardoai.

Campos de entrada estilizados com ícones: para melhor usabilidade.

Botão de login com animações interativas: para feedback visual dinâmico.

# Estrutura do Código
HTML:

<main class="Container">
    <form>
        <h1>Space login</h1>
        <div class="input-box">
            <input placeholder="Usuário" type="email">    
            <i class="bx bxs-user"></i>
        </div>

        <div class="input-box">
            <input placeholder="Senha" type="password">    
            <i class="bx bxs-lock-alt"></i>
        </div>

        <div class="remember-forgot">
            <label>
                <input type="checkbox">
                Lembrar senha
            </label>
            <a href="#">Esqueci a senha</a>
        </div>

        <button type="submit" class="login">Login</button>

        <div class="register-link">
            <p>Não tem uma conta? <a href="#">Registre-se</a></p>
        </div>
    </form>
</main>

# CSS:

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: url(./img/alchemyrefiner_alchemymagic_0_d54bd61f-bdc2-4cfd-be1f-589c56c85f16_0.jpg) no-repeat center center fixed;
    background-size: cover;
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
}

.Container {
    background: rgba(255, 255, 255, 0.1);
    width: 400px;
    padding: 30px 40px;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    color: #fff;
}

.Container h1 {
    font-size: 36px;
    text-align: center;
    margin-bottom: 20px;
    font-weight: 700;
}

.input-box {
    position: relative;
    width: 100%;
    margin: 20px 0;
}

.input-box input {
    width: 100%;
    height: 50px;
    padding: 10px 20px;
    padding-right: 40px;
    border: none;
    border-radius: 25px;
    background: rgba(255, 255, 255, 0.2);
    color: #fff;
    outline: none;
    font-size: 16px;
}

.input-box input::placeholder {
    color: #ddd;
}

.input-box i {
    position: absolute;
    right: 15px;
    top: 50%;
    transform: translateY(-50%);
    color: #ddd;
}

.input-box input:focus {
    background: rgba(255, 255, 255, 0.4);
    border: 1px solid rgba(255, 255, 255, 0.5);
}

.remember-forgot {
    display: flex;
    justify-content: space-between;
    margin: 15px 0;
}

.remember-forgot label {
    display: flex;
    align-items: center;
}

.remember-forgot label input {
    margin-right: 5px;
    accent-color: #fff;
}

.remember-forgot a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}

.remember-forgot a:hover {
    color: #ddd;
}

.login {
    width: 100%;
    height: 50px;
    background-color: #fff;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    font-size: 18px;
    color: #333;
    font-weight: 600;
    margin-top: 20px;
    
}

.login:hover {
    background-color: transparent;
    border: 1px solid #fff;
    color: #fff;
    transform: scale(1.05);
}

.register-link {
    text-align: center;
    margin: 20px 0 0;
    font-size: 14px;
}

.register-link a {
    color: #fff;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s;
}

.register-link a:hover {
    color: #ddd;
}


# Como Usar:
Copie o código HTML e CSS acima.

Cole o código nos arquivos HTML e CSS do seu projeto.

Faça ajustes conforme necessário para integrar com sua lógica de backend.

# Estilo e Ícones:
Este projeto utiliza os ícones da biblioteca Boxicons. Certifique-se de incluir o CDN da Boxicons no seu projeto:
<link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>

# Contribuição:
Sinta-se à vontade para contribuir com melhorias para este projeto. Para isso, siga os passos abaixo:

Faça um fork deste repositório.

Crie uma nova branch: git checkout -b minha-nova-funcionalidade

Faça suas modificações e commit: git commit -m 'Adiciona nova funcionalidade'

Envie suas alterações: git push origin minha-nova-funcionalidade

Abra um pull request.

# Licença:
Este projeto é licenciado sob a MIT License.
