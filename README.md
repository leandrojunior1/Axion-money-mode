# Axion (InvestAI)

Repositório oficial do Axion, uma aplicação web voltada para análise de investimentos, gestão de dados financeiros e integração com serviços de automação e pagamento.

## Sobre o Projeto
O Axion nasceu como um projeto de exploração avançada em desenvolvimento web, integrando JavaScript, TypeScript, HTML e CSS. A proposta do sistema é simular um ambiente corporativo voltado para membros da InvestAI, oferecendo um painel interativo para tomada de decisões, visualização de dados de mercado e automação de fluxos operacionais.

Como um projeto orientado a produto, sua concepção focou na experiência do usuário, modularidade e escalabilidade dos componentes.

## Arquitetura e Recursos
* Painel de Controle (Dashboard): Interface voltada para visualização de dados financeiros e métricas em tempo real.
* Arquitetura Modular: Organização de código limpa para facilitar manutenção, testes e futuras expansões de funcionalidades.
* Integrações e Pagamentos: Estrutura preparada para conexão com APIs externas e gateways de pagamento (como Stripe).
* Automação e Inteligência: Implementação de lógicas voltadas a agentes e gerenciamento de estados.

## Problemas Encontrados
Durante o desenvolvimento do projeto, os principais desafios enfrentados foram:
* Transição de Complexidade: Salto na complexidade estrutural e de organização de código em comparação com o desenvolvimento tradicional em HTML vanilla.
* Integração de Banco de Dados: Dificuldades iniciais para conectar e estruturar o banco de dados (Supabase) de forma funcional e fluida com a aplicação.
* Sincronização de Dados: Complexidade em gerenciar o fluxo de dados assíncronos entre as telas e as requisições do sistema.

## Soluções Aplicadas e Apoio Tecnológico
Para superar os obstáculos técnicos e garantir a evolução do software, foram adotadas as seguintes medidas:
* Modularização do Código: Separação gradual das responsabilidades em componentes menores para mitigar a complexidade em relação ao HTML vanilla.
* Padronização de Consultas: Refatoração das chamadas e estruturação correta do fluxo de conexão com o banco de dados, garantindo estabilidade e persistência funcional.
* Uso de IA no Processo de Desenvolvimento: Apoio do Gemini para debugar trechos complexos, estruturar lógicas iniciais de integração com o banco de dados e acelerar a resolução de bugs durante a construção das telas.

## Tecnologias Utilizadas
* Linguagens: JavaScript, TypeScript, HTML5, CSS3
* Ferramentas de Apoio: Git, Supabase (banco de dados/autenticação), prototipagem e controle de fluxo.

## Estrutura do Repositório
```text
Axion/
├── .agents/        # Configurações e estruturas de agentes e automações
├── src/            # Código-fonte principal da aplicação
└── README.md       # Documentação do projeto
