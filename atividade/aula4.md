Objetivo Criar uma pagina usando HTML e CSS semantico.

1✅ Descrição do desafio

Monte uma página pessoal básica com as seguintes características:

💚 Dica para quem vai fazer

    Foque em usar tags semânticas corretas. Evite usar apenas <div> para tudo. Teste no navegador para ver a estrutura!

1️⃣ Estrutura HTML (semântica!)

    Use tags semânticas do HTML5: <header>, <nav>, <main>, <section>, <footer>.

    Um cabeçalho com o nome do site ou seu nome.

    Um menu de navegação (nav) com pelo menos 2 links fictícios.

    Um conteúdo principal (main) com:

        Um parágrafo de apresentação sobre você ou sobre o tema da página.

        Uma section com uma lista (ol ou ul) de pelo menos 3 itens.

    Um rodapé com seu email ou direitos autorais.

    2️⃣ Estilo com CSS

    Defina uma cor de fundo para a página.

    Altere a cor dos títulos e links.

    Aplique margens ou padding nos parágrafos e seções.

    Use uma fonte personalizada (Google Fonts opcional).

    Destaque visualmente o rodapé.

    ✅ Extra (opcional)

Se quiser, adicione:

    Uma imagem com a tag <img>.

    Um botão estilizado.

    Links reais para redes sociais ou email.

    🟢 Exemplo de estrutura sugerida
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <title>Minha Página Semântica</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>Bem-vindo ao meu site!</h1>
      <nav>
        <ul>
          <li><a href="#">Início</a></li>
          <li><a href="#">Sobre</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section>
        <h2>Sobre mim</h2>
        <p>Olá! Meu nome é [Seu Nome]. Esta é minha página feita em HTML5 semântico e CSS puro.</p>
      </section>

      <section>
        <h2>Meus tópicos favoritos</h2>
        <ul>
          <li>HTML & CSS</li>
          <li>JavaScript</li>
          <li>Acessibilidade Web</li>
        </ul>
      </section>
    </main>

    <footer>
      <p>© 2025 Seu Nome - Todos os direitos reservados | Contato: email@exemplo.com</p>
    </footer>
  </body>
</html>




