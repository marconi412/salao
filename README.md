<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salão Beleza & Escola - Senac</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Salão Beleza & Escola</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="servicos.html">Serviços</a></li>
                    <li><a href="cursos.html">Cursos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Transforme sua Beleza e seu Futuro com a Nossa Escola</h2>
            <p>Aprenda com os melhores profissionais e obtenha certificação reconhecida pelo Senac.</p>
            <a href="cursos.html" class="btn">Saiba mais</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>Sobre Nós</h2>
            <p>Combinamos estilo e aprendizado em um espaço dedicado à beleza e ao desenvolvimento profissional. Nossa parceria com o Senac oferece cursos certificados para quem deseja ingressar no mundo da beleza com conhecimento e prática.</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Salão Beleza & Escola. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>









<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nossos Serviços - Salão Beleza & Escola</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Salão Beleza & Escola</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="servicos.html">Serviços</a></li>
                    <li><a href="cursos.html">Cursos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="services">
        <div class="container">
            <h2>Nossos Serviços</h2>
            <ul>
                <li>Corte de cabelo</li>
                <li>Penteados</li>
                <li>Coloração</li>
                <li>Maquiagem profissional</li>
                <li>Tratamento capilar</li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Salão Beleza & Escola. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>









<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cursos - Salão Beleza & Escola</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Salão Beleza & Escola</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="servicos.html">Serviços</a></li>
                    <li><a href="cursos.html">Cursos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="courses">
        <div class="container">
            <h2>Cursos Oferecidos</h2>
            <ul>
                <li>Curso de Cabeleireiro</li>
                <li>Curso de Maquiagem</li>
                <li>Curso de Colorimetria</li>
                <li>Curso de Design de Sobrancelhas</li>
            </ul>
            <a href="contato.html" class="btn">Inscreva-se agora</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Salão Beleza & Escola. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>









<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato - Salão Beleza & Escola</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>Salão Beleza & Escola</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="servicos.html">Serviços</a></li>
                    <li><a href="cursos.html">Cursos</a></li>
                    <li><a href="contato.html">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="contact">
        <div class="container">
            <h2>Entre em Contato</h2>
            <form action="#" method="post">
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensagem:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit" class="btn">Enviar Mensagem</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Salão Beleza & Escola. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>









* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

header {
    background-color: #f5913f;
    padding: 20px 0;
}

header .logo h1 {
    color: #fff;
    text-align: center;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    margin: 10px 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: 21, 127, 214;
    text-decoration: none;
    font-weight: bold;
    padding: 10px;
    transition: background 0.3s ease;
}

nav ul li a:hover {
    background-color: rgba(255, 255, 255, 0.2);
    border-radius: 5px;
}

#hero {
    background: url('background-image.jpg') no-repeat center center/cover;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: rgb(21, 127, 214);
    text-align: center;
}

#hero h
