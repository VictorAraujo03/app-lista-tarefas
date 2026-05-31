# App Lista de Tarefas

Aplicação web simples de lista de tarefas desenvolvida em PHP com PDO e MySQL. O projeto permite cadastrar, listar, atualizar, remover e marcar tarefas como concluídas. - Projeto desenvolvido através de um curso de Dev. Web na Udemy.

## Funcionalidades

- Cadastro de novas tarefas
- Listagem de tarefas
- Atualização de tarefas existentes
- Remoção de tarefas
- Marcação de tarefas como concluídas
- Filtro de tarefas pendentes

## Tecnologias utilizadas

- PHP
- PDO
- MySQL
- XAMPP
- HTML/CSS

## Estrutura do projeto

O projeto está organizado com foco na separação de responsabilidades:

- `tarefa.model.php`: model da entidade tarefa
- `tarefa.service.php`: regras de CRUD e consultas no banco
- `tarefa_controller.php`: controlador das ações da aplicação
- `conexao.php`: conexão com o banco de dados via PDO

## Como executar o projeto

1. Clone este repositório.
2. Coloque os arquivos do projeto na pasta do servidor local, como `htdocs` no XAMPP.
3. Crie um banco de dados MySQL.
4. Ajuste as credenciais de conexão no arquivo `conexao.php`, se necessário.
5. Crie as tabelas usadas pela aplicação.
6. Inicie o Apache e o MySQL no XAMPP.
7. Acesse o projeto pelo navegador.

## Configuração do banco

No estado atual, a conexão está configurada para:

- Host: `localhost`
- Banco: `php_com_pdo`
- Usuário: `root`
- Senha: vazia

Se o seu ambiente for diferente, edite o arquivo `conexao.php`.

## Objetivo do projeto

Este projeto foi desenvolvido com fins de estudo e prática de PHP com arquitetura simples baseada em model, controller e service, além do uso de PDO para integração com banco de dados.

## Melhorias futuras

- Validação de formulários
- Melhor organização de rotas e views
- Uso de arquivos de ambiente para configuração
- Paginação ou filtros mais completos
- Melhorias visuais na interface

## Autor

Victor Araujo
