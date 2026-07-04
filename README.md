Studenty – Sistema de Chamados Acadêmicos

O Studenty é uma plataforma web desenvolvida com o objetivo de aproximar alunos e professores por meio de um sistema de chamados acadêmicos. A proposta é oferecer um ambiente simples, organizado e intuitivo para que dúvidas, problemas e solicitações relacionadas às disciplinas possam ser registradas, acompanhadas e resolvidas de forma eficiente.

Mais do que um sistema de abertura de chamados, o projeto busca simular um ambiente acadêmico real, no qual cada usuário possui responsabilidades e permissões específicas, tornando a experiência mais próxima de uma aplicação utilizada em instituições de ensino.

📌 Objetivos do Projeto

Este projeto foi desenvolvido como forma de aplicar conceitos de desenvolvimento web e banco de dados, integrando diferentes áreas da programação em uma única aplicação.

Durante o desenvolvimento foram explorados temas como:

Desenvolvimento Back-end com Python e Flask;
Banco de dados relacional utilizando SQLite;
Controle de acesso por níveis de usuário;
Autenticação com armazenamento seguro de senhas;
Organização de código utilizando Blueprints;
Comunicação entre usuários por meio de mensagens;
Registro de auditoria e notificações;
Modelagem de um sistema baseado em regras de negócio.
✨ Funcionalidades
👨‍🎓 Área do Aluno

O aluno possui acesso a um painel personalizado onde pode:

Visualizar suas disciplinas;
Realizar matrícula em novas matérias;
Abrir chamados para professores;
Acompanhar o andamento de cada solicitação;
Conversar com o professor através do próprio chamado;
Receber notificações sempre que houver atualizações.
👨‍🏫 Área do Professor

Cada professor possui acesso apenas aos chamados relacionados às disciplinas sob sua responsabilidade.

Entre suas funcionalidades estão:

Visualizar chamados recebidos;
Responder alunos;
Atualizar o status dos chamados;
Adicionar retornos técnicos;
Gerenciar disciplinas;
Acompanhar estatísticas dos atendimentos.
👨‍💼 Área Administrativa

O administrador é responsável pelo gerenciamento geral do sistema.

Seu painel permite:

Visualizar usuários cadastrados;
Promover alunos para professores;
Acompanhar registros de auditoria;
Monitorar informações gerais da aplicação.
🔒 Controle de Acesso

O sistema utiliza autenticação baseada em sessões e separa os usuários em três perfis distintos:

Aluno
Professor
Administrador

Cada perfil possui permissões específicas, garantindo que cada usuário visualize apenas as funcionalidades necessárias para sua função.

💬 Sistema de Chamados

Cada chamado reúne todas as informações relacionadas a uma solicitação acadêmica, incluindo:

título;
descrição do problema;
disciplina vinculada;
professor responsável;
histórico de mensagens;
retorno técnico;
data de criação;
situação atual.

Os chamados podem assumir os seguintes estados:

Aberto
Em andamento
Aguardando
Finalizado

Essa estrutura permite acompanhar todo o ciclo de atendimento desde sua abertura até sua conclusão.

🔔 Notificações

Sempre que um chamado sofre alguma atualização importante, como alteração de status ou resposta do professor, o aluno é informado por meio do sistema de notificações.

Essa funcionalidade mantém a comunicação organizada sem a necessidade de consultas constantes ao painel.

📋 Auditoria

As ações administrativas são registradas automaticamente, permitindo manter um histórico das alterações realizadas no sistema.

Esse recurso contribui para maior transparência e controle sobre operações importantes.

🛠 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

Python
Flask
SQLite
HTML5
CSS3
Jinja2
Werkzeug (Hash de Senhas)
🗂 Estrutura do Projeto
studenty/
│
├── static/
├── templates/
├── cadastro/
├── app.py
├── studenty.db
└── requirements.txt

A organização do projeto segue uma estrutura modular, facilitando futuras manutenções e expansões da aplicação.

🚀 Como Executar

Clone o repositório:

git clone https://github.com/seu-usuario/studenty.git

Acesse a pasta do projeto:

cd studenty

Crie um ambiente virtual (opcional):

python -m venv venv

Ative o ambiente virtual.

Windows

venv\Scripts\activate

Linux/macOS

source venv/bin/activate

Instale as dependências:

pip install -r requirements.txt

Execute a aplicação:

python app.py

Após a inicialização, o sistema estará disponível em:

http://127.0.0.1:5000
💡 Aprendizados

O desenvolvimento deste projeto permitiu consolidar conhecimentos em desenvolvimento web utilizando Python, além de proporcionar experiência prática com autenticação, arquitetura MVC, manipulação de banco de dados, organização de código, controle de permissões e construção de aplicações voltadas para problemas reais.

Também foi uma oportunidade para compreender como diferentes perfis de usuários interagem dentro de um mesmo sistema e como estruturar regras de negócio de forma clara e segura.

🔮 Melhorias Futuras

Entre as evoluções planejadas para o projeto estão:

Upload de arquivos nos chamados;
Envio de notificações por e-mail;
Dashboard com gráficos e indicadores;
Pesquisa e filtros avançados;
API REST para integração com outros sistemas;
Migração para PostgreSQL;
Interface totalmente responsiva;
Recuperação de senha;
Histórico completo de atividades dos usuários.
👨‍💻 Autor

Desenvolvido por Hebert Rocha como projeto acadêmico com foco na aplicação prática de conceitos de desenvolvimento web, banco de dados relacionais e engenharia de software.

O projeto representa a integração entre programação, organização de processos e boas práticas de desenvolvimento, buscando oferecer uma solução funcional para o gerenciamento de chamados no ambiente escolar.
