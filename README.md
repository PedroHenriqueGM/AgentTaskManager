Agent Task Manager – Assistente de Gerenciamento de Tarefas

Sobre o projeto:

O Agent Task Manager é um agente de inteligência artificial desenvolvido em Python, utilizando Google ADK e Gemini, com integração à API do Trello para gerenciamento de tarefas.

O objetivo do projeto é permitir que o usuário organize suas atividades por meio de conversas em linguagem natural, sem precisar acessar manualmente o quadro do Trello para realizar cada operação.

O agente interpreta as solicitações do usuário e utiliza ferramentas Python para executar ações diretamente no Trello.

Funcionalidades:

- Adicionar tarefas: cria cartões no Trello com nome, descrição e data de vencimento.

- Listar tarefas: consulta as atividades cadastradas e permite filtrá-las por status.

- Alterar status: movimenta cartões entre listas, como "A Fazer", "Em Andamento" e "Concluído".

- Remover tarefas: localiza cartões pelo nome e permite excluí-los mediante confirmação do usuário.

- Contexto temporal: utiliza a data e o horário atuais para auxiliar na organização das atividades.

Tecnologias utilizadas:

- Python

- Google ADK (Agent Development Kit)

- Google Gemini API

- Trello API

- Py-Trello

- Python Dotenv

Como funciona:

O Google ADK é responsável pela estrutura e coordenação do agente, enquanto o Gemini interpreta as mensagens enviadas pelo usuário e identifica quais ferramentas precisam ser utilizadas.

As ferramentas são implementadas em Python e realizam as operações necessárias por meio da API do Trello, permitindo que o agente consulte, crie, atualize e remova cartões.

Configuração e execução:

1. Clone o repositório.

2. Crie e ative um ambiente virtual Python.

3. Instale as dependências do projeto.

4. Configure as variáveis de ambiente em um arquivo .env.

5. Execute o agente utilizando o Google ADK.

6. Variáveis de ambiente

Configure as seguintes credenciais no arquivo .env:

GOOGLE_API_KEY=sua_chave_gemini
TRELLO_API_KEY=sua_chave_trello
TRELLO_API_SECRET=seu_secret_trello
TRELLO_TOKEN=seu_token_trello

Importante: não compartilhe ou publique suas credenciais. O arquivo .env deve estar incluído no .gitignore.

Aprendizados e melhorias:

O desenvolvimento proporcionou experiência prática com agentes de inteligência artificial, integração de APIs externas, criação de ferramentas em Python e utilização de modelos Gemini para interpretação de solicitações em linguagem natural.

A partir da estrutura disponibilizada no bootcamp IA do Zero ao Primeiro Agente, foram realizadas adaptações e melhorias, incluindo a implementação de uma ferramenta de exclusão de tarefas no Trello.
