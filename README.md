<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Axion - Documentação e Apresentação</title>
    <style>
        :root {
            --primary-color: #1e3a8a; /* Azul corporativo */
            --accent-color: #3b82f6;  /* Azul claro */
            --text-main: #1f2937;     /* Cinza escuro para texto */
            --text-muted: #4b5563;    /* Cinza médio */
            --bg-color: #f9fafb;      /* Fundo levemente acinzentado */
            --card-bg: #ffffff;       /* Fundo dos blocos */
            --border-color: #e5e7eb;  /* Cor de borda suave */
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 40px;
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
            border: 1px solid var(--border-color);
        }

        header {
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 {
            color: var(--primary-color);
            font-size: 2.25rem;
            margin: 0 0 10px 0;
        }

        .subtitle {
            color: var(--text-muted);
            font-size: 1.1rem;
            margin: 0;
        }

        h2 {
            color: var(--primary-color);
            font-size: 1.4rem;
            margin-top: 30px;
            margin-bottom: 15px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 5px;
        }

        p {
            margin-bottom: 15px;
            color: var(--text-main);
        }

        ul {
            margin: 0 0 20px 0;
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
            color: var(--text-muted);
        }

        li strong {
            color: var(--text-main);
        }

        pre {
            background-color: #111827;
            color: #f3f4f6;
            padding: 20px;
            border-radius: 6px;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
            font-size: 0.9rem;
            overflow-x: auto;
            margin: 20px 0;
        }

        footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid var(--border-color);
            text-align: center;
            font-size: 0.85rem;
            color: var(--text-muted);
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Axion (InvestAI)</h1>
            <p class="subtitle">Sistema de automação de processos, gerenciamento de dados e análise financeira.</p>
        </header>

        <section>
            <h2>Sobre o Projeto</h2>
            <p>O <strong>Axion</strong> nasceu como um projeto de exploração avançada em desenvolvimento web, integrando JavaScript, TypeScript, HTML e CSS. A proposta do sistema é simular um ambiente corporativo voltado para membros da InvestAI, oferecendo um painel interativo para tomada de decisões, visualização de dados de mercado e automação de fluxos operacionais.</p>
            <p>Como um projeto orientado a produto, sua concepção focou na experiência do usuário, modularidade e escalabilidade dos componentes.</p>
        </section>

        <section>
            <h2>Arquitetura e Recursos</h2>
            <ul>
                <li><strong>Painel de Controle (Dashboard):</strong> Interface voltada para visualização de dados financeiros e métricas em tempo real.</li>
                <li><strong>Arquitetura Modular:</strong> Organização de código limpa para facilitar manutenção, testes e futuras expansões de funcionalidades.</li>
                <li><strong>Integrações e Pagamentos:</strong> Estrutura preparada para conexão com APIs externas e gateways de pagamento (como Stripe).</li>
                <li><strong>Automação e Inteligência:</strong> Implementação de lógicas voltadas a agentes e gerenciamento de estados.</li>
            </ul>
        </section>

        <section>
            <h2>Tecnologias Utilizadas</h2>
            <ul>
                <li><strong>Linguagens:</strong> JavaScript, TypeScript, HTML5, CSS3</li>
                <li><strong>Ferramentas de Apoio:</strong> Git, Supabase (banco de dados/autenticação), prototipagem e controle de fluxo.</li>
            </ul>
        </section>

        <section>
            <h2>Estrutura do Repositório</h2>
            <pre>Axion/
├── .agents/        # Configurações e estruturas de agentes e automações
├── src/            # Código-fonte principal da aplicação
└── README.md       # Documentação do projeto</pre>
        </section>

        <footer>
            <p>Desenvolvido como projeto acadêmico e de portfólio para exploração de engenharia de software e gestão de produtos digitais.</p>
        </footer>
    </div>

</body>
</html>
