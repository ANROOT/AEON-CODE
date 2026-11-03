# AEON Code — Portfólio de sites

Projeto completo em HTML, CSS e JavaScript. Inclui a paleta azul profundo/ciano/violeta, logo da AEON, logo oficial da PrimeMKT e captura do site da Tribo da Periferia.

## Abrir no VS Code

1. Extraia este ZIP para uma pasta do seu computador.
2. No VS Code, clique em Arquivo > Abrir Pasta e escolha a pasta AEON_Code.
3. Para testar com um servidor local, instale a extensão Live Server (Ritwick Dey).
4. Clique com o botão direito em index.html e escolha Open with Live Server.
5. Edite, salve e acompanhe as alterações no navegador.

Não é necessário executar npm install nem fazer uma compilação.

Alternativa, caso você tenha Python: abra o terminal nessa pasta e execute:

    python -m http.server 5500

Depois abra http://localhost:5500 no navegador. No Windows, você também pode usar py -m http.server 5500.

## Onde editar

- index.html: capa, história da AEON, apresentação do trabalho e contatos.
- style.css: layout, tipografia, responsividade e paleta de cores. As variáveis --bg, --fg, --accent e --spectral controlam as cores da identidade.
- app.js: lista dos seis projetos, descrições, imagens, links e navegação.
- assets/: fontes locais, logos e imagens.

## Navegação

Use os botões de seta ou as teclas ← e → para trocar de tela. O botão Projetos abre o índice. R repete a animação; F alterna a tela cheia quando o navegador permite. No celular, deslize horizontalmente para trocar de tela e role verticalmente quando houver mais conteúdo.

## Publicar por conta própria

Esta é uma versão estática e portátil, sem exigência de login do ChatGPT no código. Publique o conteúdo desta pasta em uma hospedagem de sites estáticos. Para Vercel: use o preset Other, sem comando de build e com a pasta raiz como diretório de saída. O arquivo index.html deve ficar na raiz publicada.

As prévias ao vivo e os botões dos projetos acessam sites externos e precisam de internet. As imagens, logos e fontes estão incluídas no projeto. O Erike Beats é apresentado como piloto com checkout demonstrativo; o PrimeShow é uma apresentação de projeto.
