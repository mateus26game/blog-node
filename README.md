# How to Build a Blog with Node.js, Express & MongoDB

Este projeto é uma implementação de um blog simples utilizando Node.js, Express e MongoDB. A ideia original do projeto foi inspirada no tutorial "How to Build a Blog with Node.js, Express & MongoDB".

Descrição do Projeto
--
O blog permite que usuários criem, leiam, atualizem e excluam posts. As funcionalidades principais incluem:

* Autenticação de Usuários: Utiliza JSON Web Tokens (JWT) para gerenciar sessões de usuários.

* CRUD de Posts: Permite que administradores adicionem, editem e excluam posts do blog.

* Paginação: Os posts são paginados, permitindo uma melhor navegação.

Modificações Realizadas
--
Utilizei este projeto como base e fiz várias modificações para atender às exigências do meu trabalho de back-end na faculdade. As principais alterações incluem:

* Estrutura do Código: Organizei o código em módulos para melhorar a manutenção e a legibilidade.

* Autenticação: Implementei uma lógica de autenticação robusta utilizando o bcrypt para hash de senhas e JWT para gerenciamento de sessões.

* Interface de Administração: Criei uma interface de administração onde os usuários podem fazer login e gerenciar os posts do blog.

* Validação de Dados: Adicionei validações para garantir que os campos obrigatórios fossem preenchidos e que as entradas fossem seguras.
