Studenty

Sistema web de gerenciamento de chamados acadêmicos desenvolvido em Python, utilizando Flask e SQLite, com foco na comunicação entre alunos e professores por meio de uma plataforma simples, organizada e intuitiva.

Sobre o Projeto

O Studenty foi desenvolvido com o objetivo de centralizar o gerenciamento de solicitações acadêmicas entre alunos e professores. A aplicação permite registrar, acompanhar e responder chamados relacionados às disciplinas, proporcionando uma comunicação mais eficiente dentro do ambiente escolar.

O projeto simula um cenário real de uma instituição de ensino, implementando diferentes perfis de usuários, controle de permissões, autenticação, notificações e registro das principais ações realizadas no sistema.

Objetivos

Este projeto foi desenvolvido para aplicar conceitos de desenvolvimento web, banco de dados e engenharia de software, abordando temas como:

Desenvolvimento Back-end com Python e Flask;
Modelagem de banco de dados relacional;
Controle de acesso por níveis de usuário;
Autenticação com armazenamento seguro de senhas;
Organização da aplicação utilizando Blueprints;
Comunicação entre usuários por meio de chamados;
Registro de notificações e auditoria.
Funcionalidades
Aluno
Login na plataforma;
Matrícula em disciplinas;
Abertura de chamados;
Acompanhamento do status das solicitações;
Histórico de chamados;
Troca de mensagens com o professor;
Recebimento de notificações.
Professor
Visualização dos chamados das disciplinas sob sua responsabilidade;
Resposta aos chamados;
Atualização do status das solicitações;
Envio de retorno técnico;
Gerenciamento de disciplinas;
Visualização de estatísticas dos atendimentos.
Administrador
Gerenciamento de usuários;
Promoção de alunos para professores;
Visualização dos registros de auditoria;
Acompanhamento geral do sistema.
Controle de Acesso

O sistema possui três níveis de permissão:

Aluno
Professor
Administrador

Cada perfil possui acesso apenas às funcionalidades compatíveis com sua função.

Sistema de Chamados

Cada chamado contém:

Título;
Descrição do problema;
Disciplina relacionada;
Professor responsável;
Histórico de mensagens;
Retorno técnico;
Data de criação;
Status.

Os estados possíveis de um chamado são:

Aberto;
Em andamento;
Aguardando;
Finalizado.
Tecnologias Utilizadas
Python
Flask
SQLite
HTML5
CSS3
Jinja2
Werkzeug
Estrutura do Projeto
studenty/
│
├── static/
├── templates/
├── cadastro/
├── app.py
├── studenty.db
└── requirements.txt
Como Executar

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

A aplicação estará disponível em:

http://127.0.0.1:5000

Autor

Hebert Rocha

Projeto desenvolvido com o objetivo de consolidar conhecimentos em desenvolvimento web utilizando Python, Flask e SQLite, simulando um sistema de gerenciamento de chamados aplicado ao contexto acadêmico.
