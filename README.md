# P-gina-web-do-zero-primeira-intera-o

 
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Meu Blog Tech | Tecnologia e Programação</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f1f5f9;
            color: #183c63;
            line-height: 1.6;
        }

        /* CABEÇALHO */

        header {
            background: #183c63;
            color: white;
            padding: 25px 20px;
        }

        .container {
            max-width: 1100px;
            margin: auto;
        }

        .topo {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        header h1 {
            font-size: 28px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: #38bdf8;
        }

        /* APRESENTAÇÃO */

        .hero {
            text-align: center;
            padding: 65px 20px;
            background: linear-gradient(135deg, #183c63, #2563a6);
            color: white;
        }

        .hero h2 {
            font-size: 36px;
            margin-bottom: 15px;
        }

        .hero p {
            max-width: 650px;
            margin: auto;
            font-size: 17px;
        }

        /* CONTEÚDO */

        main {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .titulo-secao {
            margin-bottom: 25px;
            font-size: 26px;
        }

        /* ARTIGOS */

        .artigos {
            display: grid;
            grid-template-columns: repeat(
                auto-fit,
                minmax(280px, 1fr)
            );
            gap: 25px;
        }

        article {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            transition: transform 0.3s;
        }

        article:hover {
            transform: translateY(-5px);
        }

        article img {
            width: 100%;
            height: 190px;
            object-fit: cover;
        }

        .conteudo-artigo {
            padding: 20px;
        }

        .conteudo-artigo h3 {
            margin-bottom: 10px;
            font-size: 21px;
        }

        .artigo-autor {
            font-weight: bold;
            color: #64748b;
            font-size: 14px;
            margin-bottom: 12px;
        }

        .descricao {
            margin-bottom: 15px;
        }

        /* BOTÕES */

        .reacoes {
            display: flex;
            gap: 10px;
            margin-top: 15px;
        }

        button {
            border: none;
            padding: 9px 15px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            background: #e2e8f0;
            transition: 0.2s;
        }

        button:hover {
            background: #bae6fd;
            transform: scale(1.05);
        }

        button:active {
            transform: scale(0.95);
        }

        /* SOBRE */

        .sobre {
            background: white;
            margin-top: 40px;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        .sobre h2 {
            margin-bottom: 15px;
        }

        /* RODAPÉ */

        footer {
            background: #183c63;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 50px;
        }

        /* RESPONSIVIDADE */

        @media (max-width: 600px) {
            .topo {
                flex-direction: column;
                text-align: center;
            }

            nav a {
                margin: 0 8px;
                font-size: 14px;
            }

            .hero h2 {
                font-size: 27px;
            }

            .titulo-secao {
                font-size: 23px;
            }
        }
    </style>
</head>

<body>

    <!-- CABEÇALHO -->

    <header>
        <div class="container topo">
            <h1>💻 Meu Blog Tech</h1>

            <nav>
                <a href="#inicio">Início</a>
                <a href="#artigos">Artigos</a>
                <a href="#sobre">Sobre</a>
            </nav>
        </div>
    </header>

    <!-- APRESENTAÇÃO -->

    <section class="hero" id="inicio">
        <h2>Bem-vindo ao Meu Blog Tech!</h2>

        <p>
            Um espaço para compartilhar conhecimentos,
            dicas de programação, tecnologia e novidades
            do mundo digital.
        </p>
    </section>

    <!-- CONTEÚDO PRINCIPAL -->

    <main>

        <section id="artigos">

            <h2 class="titulo-secao">
                📚 Últimos artigos
            </h2>

            <div class="artigos">

                <!-- ARTIGO 1 -->

                <article>
                    <img
                        src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=800"
                        alt="Pessoa trabalhando com programação"
                    >

                    <div class="conteudo-artigo">

                        <h3>Meu primeiro post</h3>

                        <p class="artigo-autor">
                            Por: JOSEANE PONTES
                        </p>

                        <p class="descricao">
                            Boas-vindas ao meu novo blog!
                            Aqui vou compartilhar dicas de
                            programação e curiosidades da
                            área de tecnologia.
                        </p>

                        <div class="reacoes">
                            <button class="reacao">
                                ❤️ <span>0</span>
                            </button>

                            <button class="reacao">
                                😎 <span>0</span>
                            </button>
                        </div>

                    </div>
                </article>

                <!-- ARTIGO 2 -->

                <article>
                    <img
                        src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?w=800"
                        alt="Computador utilizado para programação"
                    >

                    <div class="conteudo-artigo">

                        <h3>Aprendendo HTML e CSS</h3>

                        <p class="artigo-autor">
                            Por: Gabriel Ribas
                        </p>

                        <p class="descricao">
                            Descubra como criar páginas web
                            utilizando HTML para estruturar
                            conteúdos e CSS para personalizar
                            o visual dos seus projetos.
                        </p>

                        <div class="reacoes">
                            <button class="reacao">
                                ❤️ <span>0</span>
                            </button>

                            <button class="reacao">
                                😎 <span>0</span>
                            </button>
                        </div>

                    </div>
                </article>

                <!-- ARTIGO 3 -->

                <article>
                    <img
                        src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=800"
                        alt="Código de programação na tela"
                    >

                    <div class="conteudo-artigo">

                        <h3>Primeiros passos com JavaScript</h3>

                        <p class="artigo-autor">
                            Por: JOSEANE PONTES
                        </p>

                        <p class="descricao">
                            Aprenda como utilizar JavaScript
                            para adicionar interatividade,
                            criar funções e desenvolver
                            aplicações web.
                        </p>

                        <div class="reacoes">
                            <button class="reacao">
                                ❤️ <span>0</span>
                            </button>

                            <button class="reacao">
                                😎 <span>0</span>
                            </button>
                        </div>

                    </div>
                </article>

            </div>
        </section>

        <!-- SOBRE -->

        <section class="sobre" id="sobre">

            <h2>👨‍💻 Sobre o blog</h2>

            <p>
                Meu Blog Tech é um projeto criado por
                JOSEANE PONTES com o objetivo de compartilhar
                conhecimentos sobre tecnologia,
                desenvolvimento web e programação.
            </p>

            <p>
                Aqui você encontrará conteúdos para
                aprender, evoluir e acompanhar o mundo
                da tecnologia.
            </p>

        </section>

    </main>

    <!-- RODAPÉ -->

    <footer>
        <p>
            © 2026 Meu Blog Tech.
            Desenvolvido por Gabriel Ribas.
        </p>

        <p>🚀 Tecnologia, conhecimento e inovação.</p>
    </footer>

    <!-- JAVASCRIPT -->

    <script>

        const botoes = document.querySelectorAll(".reacao");

        function botaoClicado(event) {

            const botao = event.currentTarget;

            const contador = botao.querySelector("span");

            contador.textContent =
                Number(contador.textContent) + 1;

        }

        botoes.forEach(function(botao) {

            botao.addEventListener(
                "click",
                botaoClicado
            );

        });

    </script>

</body>
</html>
