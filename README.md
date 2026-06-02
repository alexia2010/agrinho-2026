# agrinho-2026
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inteligência Artificial no Campo - AgroFuturo 2026</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Caixa flutuante de acessibilidade -->
    <div class="acessibilidade">
        <button id="aumentarFonte">A+</button>
        <button id="diminuirFonte">A-</button>
        <button id="modoEscuro">🌙/☀️</button>
        <button id="lerTexto">🔊</button>
        <button id="pararLeitura">⏹️</button>
    </div>

    <!-- HERO SECTION -->
    <header class="hero">
        <div class="hero-content">
            <h1>Tecnologia agrícola reforça papel do Brasil</h1>
            <p>Inovação digital e inteligência artificial transformando o campo sustentável.</p>
            <a href="#seminario" class="btn-acao">Inscreva-se no Seminário</a>
        </div>
    </header>

    <!-- SEÇÃO DE CONTEÚDO -->
    <main>
        <section class="conteudo">
            <div class="cards">
                <div class="card">
                    <h2>O Futuro da Agricultura</h2>
                    <p>A agricultura sustentável ganha espaço no debate global, unindo produtividade e inovação.</p>
                    <div class="imagem"><img src="Foto1.png" alt="Tecnologia agrícola"></div>
                </div>

                <div class="card">
                    <h2>Benefícios da IA no Campo</h2>
                    <div class="accordion">
                        <button class="accordion-btn">1. Otimização de Recursos</button>
                        <div class="accordion-content">
                            <p>Sistemas de irrigação inteligentes e sensores monitoram solo e plantas, reduzindo desperdício de água e melhorando a produtividade.</p>
                        </div>

                        <button class="accordion-btn">2. Monitoramento de Culturas</button>
                        <div class="accordion-content">
                            <p>Drones e sensores capturam imagens que são analisadas por IA, permitindo detecção de doenças e planejamento estratégico.</p>
                        </div>

                        <button class="accordion-btn">3. Previsibilidade e Gestão de Riscos</button>
                        <div class="accordion-content">
                            <p>Análise de dados climáticos e históricos de produção permite prever colheitas e otimizar logística.</p>
                        </div>

                        <button class="accordion-btn">4. Automação</button>
                        <div class="accordion-content">
                            <p>Tratores e máquinas autônomas realizam tarefas com precisão, aumentando eficiência e reduzindo mão de obra.</p>
                        </div>

                        <button class="accordion-btn">5. Qualidade e Sustentabilidade</button>
                        <div class="accordion-content">
                            <p>IA possibilita rastreabilidade, controle de insumos e redução de desperdícios, promovendo alimentos de alta qualidade e sustentabilidade.</p>
                        </div>
                    </div>
                    <div class="imagem"><img src="Foto2.png" alt="IA no campo"></div>
                </div>

                <div class="card">
                    <h2>Reconhecimento Internacional</h2>
                    <p>O trabalho inovador do Brasil no uso de microrganismos nas lavouras ganhou destaque mundial, reforçando seu protagonismo tecnológico.</p>
                    <div class="imagem"><img src="Foto3.png" alt="Inovação agrícola"></div>
                </div>
            </div>
        </section>

        <!-- FORMULÁRIO -->
        <aside class="formulario" id="seminario">
            <h2>Venha conhecer melhor como a IA pode ser uma aliada do Campo</h2>
            <p>Inscreva-se no nosso seminário on-line:</p>
            <form>
                <input type="text" placeholder="Nome" required>
                <input type="email" placeholder="E-mail" required>
                <input type="text" placeholder="Cidade">
                <input type="text" placeholder="Estado">
                <input type="text" placeholder="País">
                <button type="submit">Inscrever-se</button>
            </form>
        </aside>

        <!-- INTERAÇÃO COM O LEITOR -->
        <section class="comentarios">
            <h2>Comentários</h2>
            <textarea placeholder="Deixe sua mensagem..."></textarea>
            <button type="button" id="enviarComentario">Enviar</button>
        </section>
    </main>

    <!-- RODAPÉ -->
    <footer>
        <p>Referências: <a href="https://www.bemagro.com/beneficios-inteligencia-artificial-no-campo/" target="_blank">BemAgro</a> | <a href="https://www.agrolink.com.br/noticias/o-campo-conectado--como-a-ia-vem-transformando-o-agro_514351.html" target="_blank">Agrolink</a></p>
        <p>AgroFuturo 2026 ° Conectando a inteligência tecnologia à terra de forma sustentável</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>