# 4.A---Checkpoint-3---SOLID-e-Clean-Code-em-C-
Você foi contratado para desenvolver um sistema simples de gerenciamento de biblioteca que precisa:
Identificação de Violações

Princípio da Responsabilidade Única (SRP):
Classe:GerenciadorBiblioteca
Descrição: A classe GerenciadorBiblioteca faz várias tarefas diferentes,cadastro de livros,usuários,empréstimos e devoluções,cálculo de multa e notificação. 
Uma classe devia ter apenas uma responsabilidade.

Princípio Aberto/Fechado (OCP):
Classe: GerenciadorBiblioteca
Descrição:Precisa modificar os métodos existentes se eu quiser adicionar um novo tipo de notificação.
O código deveria estar aberto para extensão, mas fechado para modificação.

Princípio da Inversão de Dependência (DIP)
Classe:GerenciadorBiblioteca
Descrição: A classe depende de implementações concretas de envio de notificações, em vez de depender de abstrações (interfaces). Isso dificulta a reutilização e testes.

Clean Code - Métodos longos com muitas responsabilidades
Métodos: RealizarEmprestimo, RealizarDevolucao
Descrição: Métodos realizam várias operações. 
O ideal é que cada método tenha uma única responsabilidade.

Clean Code - Nomes genéricos
Classe: GerenciadorBiblioteca
O nome da classe é genérico, centraliza diversas responsabilidades que deveriam estar em outras classes
