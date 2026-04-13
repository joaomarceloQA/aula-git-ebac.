API Test Automation - ServeRest 🚀
Este projeto demonstra a implementação de uma arquitetura robusta para testes automatizados de API, utilizando o framework Cypress. O foco principal é a validação da funcionalidade de gerenciamento de usuários, garantindo a integridade dos dados e a confiabilidade dos endpoints.

🛠️ Stack Tecnológica
Framework: Cypress

Linguagem: JavaScript (ES6+)

Relatórios: Mochawesome Reports

CI/CD: GitHub Actions (Automação de Workflow)

API de Teste: ServeRest (Local & Online)

📌 Funcionalidades Implementadas
Arquitetura BaseUrl: Configuração centralizada para facilitar a transição entre ambientes (Local, Staging, Produção).

Testes de Contrato & Funcionais: Validação de Status Codes, JSON Schema e mensagens de erro do sistema.

Massa de Dados Dinâmica: Utilização de lógicas para geração de e-mails e nomes únicos, evitando conflitos em execuções repetitivas.

Pipeline de Integração Contínua: Workflow automatizado que executa toda a suíte de testes a cada novo commit.

⚙️ Configuração da Pipeline (CI)
O projeto conta com um workflow no GitHub Actions que automatiza os seguintes passos:

Provisionamento de ambiente Ubuntu.

Instalação de dependências do Node.js.

Inicialização automática da API ServeRest em segundo plano.

Execução dos testes em modo headless.

Geração e armazenamento dos artefatos de teste (Relatórios).
