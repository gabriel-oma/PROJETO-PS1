Green Money é um sistema de gamificação que incentiva a prática de atividades sustentáveis, recompensando os usuários com pontos que podem ser trocados por prêmios.

Funcionalidades

Cadastro de usuários com verificação por código.

Registro de atividades sustentáveis e acúmulo de pontos.

Exclusão de usuários e atividades.

Listagem de usuários e atividades cadastradas.

Ranking de usuários baseado nos pontos acumulados.

Sistema de recompensas baseado na quantidade de pontos.

Notificações automáticas para usuários ao atingirem novos níveis ou desbloquearem recompensas.

Como Utilizar

Executar o programa

O sistema é executado no terminal. Basta rodar o script Python para iniciar o menu interativo.

Cadastrar um novo usuário

Escolha a opção 1. Cadastrar novo usuário.

Insira um nome de usuário e email.

Defina uma senha com pelo menos 4 caracteres, 3 letras/números e 1 caractere especial.

Confirme o código de verificação enviado ao email.

Registrar atividades sustentáveis

Escolha a opção 2. Registrar atividades sustentáveis.

Selecione uma atividade predefinida ou insira uma nova.

Informe quantas vezes a atividade foi realizada.

O usuário recebe pontos de acordo com a atividade e quantidade realizada.

Consultar usuários e atividades

5. Lista de usuários exibe todos os usuários cadastrados e seus pontos.

6. Lista de atividades exibe todas as atividades registradas.

Consultar ranking de usuários

7. Ranking de usuários exibe os usuários ordenados por pontuação.

Resgatar recompensas

9. Resgatar recompensa permite trocar pontos acumulados por prêmios.

Sair do programa

10. Sair encerra a execução do sistema.

Estrutura do Código

O sistema está estruturado em diferentes funções para modularidade e facilidade de manutenção:

cadastrar_usuario(): Cadastra novos usuários.

registrar_atividade(): Registra atividades sustentáveis.

listar_usuarios(): Exibe a lista de usuários cadastrados.

listar_atividades(): Exibe a lista de atividades registradas.

ranking(): Exibe o ranking de usuários.

resgatar_recompensa(): Permite a troca de pontos por recompensas.

menu(): Controla a interação do usuário no terminal.

Requisitos

Python 3.x
