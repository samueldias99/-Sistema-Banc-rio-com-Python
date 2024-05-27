Sistema Bancário
Este é um sistema bancário simples desenvolvido em Python. Ele permite que os usuários realizem operações bancárias básicas como depósitos, saques, criação de contas e exibição de extratos. O sistema é operado via um menu de terminal.

Funcionalidades
Depositar: Permite ao usuário depositar uma quantia em sua conta.
Sacar: Permite ao usuário sacar uma quantia de sua conta, respeitando o limite diário e o número máximo de saques.
Extrato: Exibe o extrato da conta do usuário.
Nova conta: Cria uma nova conta para um usuário existente.
Listar contas: Lista todas as contas criadas.
Novo usuário: Cria um novo usuário no sistema.
Sair: Encerra o sistema.
Requisitos
Python 3.x
Como usar
Clone o repositório para a sua máquina local.
bash
Copiar código
git clone <https://github.com/samueldias99/-Sistema-Banc-rio-com-Python>
Navegue até o diretório do projeto.
bash
Copiar código
cd nome-do-repositorio
Execute o script Python.
bash
Copiar código
python nome_do_script.py
Detalhes das Funções
menu()
Exibe o menu de opções e captura a escolha do usuário.

depositar(saldo, valor, extrato)
Realiza um depósito na conta do usuário.

sacar(saldo, valor, extrato, limite, numero_saques, limite_saques)
Realiza um saque na conta do usuário, respeitando limites e número máximo de saques.

exibir_extrato(saldo, extrato)
Exibe o extrato da conta do usuário.

criar_usuario(usuarios)
Cria um novo usuário no sistema.

filtrar_usuario(cpf, usuarios)
Busca um usuário pelo CPF.

criar_conta(agencia, numero_conta, usuarios)
Cria uma nova conta associada a um usuário existente.

listar_contas(contas)
Lista todas as contas cadastradas no sistema.

main()
Função principal que executa o loop do menu e chama as outras funções conforme a escolha do usuário.

Exemplo de Uso
Após iniciar o script, o usuário verá o menu principal e poderá escolher uma das opções para realizar as operações desejadas. Abaixo está um exemplo de interação:

csharp
Copiar código
================ MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> d
Informe o valor do depósito: 1000
=== Depósito realizado com sucesso! ===


Esse README deve fornecer uma visão geral clara e útil do seu projeto, ajudando outros desenvolvedores a entenderem e utilizarem seu sistema bancário. Se precisar de mais alguma coisa, sinta-se à vontade para perguntar!
