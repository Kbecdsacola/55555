# 55555
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Minha Página Web</title>
</head>
<body>
    <header>
        <h1>Bem-vindo à Minha Página</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Início</a></li>
            <li><a href="#">Sobre</a></li>
            <li><a href="#">Serviços</a></li>
            <li><a href="#">Contato</a></li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>Sobre Nós</h2>
            <p>Somos uma empresa dedicada a criar exemplos fictícios de páginas da web.</p>
        </section>
        <section>
            <h2>Nossos Serviços</h2>
            <ul>
                <li>Criação de Páginas da Web</li>
                <li>Design Responsivo</li>
                <li>Desenvolvimento Frontend e Backend</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Minha Página. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* Reset de Estilos */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Estilos Globais */
body {
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

nav {
    background-color: #444;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0.5rem 0;
}

nav a {
    text-decoration: none;
    color: #fff;
    margin: 0 1rem;
}

main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

footer {
    text-align: center;
    padding: 1rem 0;
    background-color: #444;
    color: #fff;
}
