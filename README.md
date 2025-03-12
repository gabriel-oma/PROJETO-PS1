# Green Money

**Green Money** é um sistema de gamificação que incentiva práticas sustentáveis, recompensando os usuários com pontos que podem ser trocados por prêmios.

## Funcionalidades

- Cadastro de usuários com verificação por código.
- Registro de atividades sustentáveis e acúmulo de pontos.
- Exclusão de usuários e atividades.
- Listagem de usuários e atividades cadastradas.
- Ranking de usuários baseado nos pontos acumulados.
- Sistema de recompensas baseado na quantidade de pontos.
- Notificações automáticas para usuários ao atingirem novos níveis ou desbloquearem recompensas.
- Verificação e validação de email e senha durante o cadastro.
- Ajuda integrada para usuários.

## Como Utilizar

### Executar o programa
O sistema é executado no terminal. Basta rodar o script Python para iniciar o menu interativo.

### Cadastrar um novo usuário
1. Escolha a opção **1. Cadastrar novo usuário**.
2. Insira um nome de usuário e email.
3. Defina uma senha com pelo menos 4 caracteres, 3 letras/números e 1 caractere especial.
4. Confirme o código de verificação enviado ao email.

### Registrar atividades sustentáveis
1. Escolha a opção **2. Registrar atividades sustentáveis**.
2. Selecione uma atividade predefinida ou insira uma nova.
3. Informe quantas vezes a atividade foi realizada.
4. O usuário recebe pontos de acordo com a atividade e quantidade realizada.

### Consultar usuários e atividades
- **Lista de usuários** exibe todos os usuários cadastrados e seus pontos.
- **Lista de atividades** exibe todas as atividades registradas.

### Consultar ranking de usuários
- **Ranking de usuários** exibe os usuários ordenados por pontuação.

### Resgatar recompensas
- Escolha a opção **9. Resgatar recompensa** para trocar pontos acumulados por prêmios disponíveis.

### Excluir usuários e atividades
- Escolha a opção **3. Excluir usuário** para remover um usuário do sistema.
- Escolha a opção **4. Excluir atividade** para remover atividades registradas.

### Ajuda
- Escolha a opção **8. Ajuda** para visualizar informações sobre o funcionamento do sistema.

### Sair do programa
- Escolha a opção **10. Sair** para encerrar a execução do sistema.

## Estrutura do Código

O sistema está estruturado em diferentes funções para modularidade e facilidade de manutenção:

- `cadastrar_usuario()`: Cadastra novos usuários com validação de email e senha.
- `registrar_atividade()`: Registra atividades sustentáveis.
- `listar_usuarios()`: Exibe a lista de usuários cadastrados.
- `listar_atividades()`: Exibe a lista de atividades registradas.
- `ranking()`: Exibe o ranking de usuários.
- `resgatar_recompensa()`: Permite a troca de pontos por recompensas.
- `excluir_usuario()`: Remove um usuário do sistema.
- `excluir_atividade()`: Remove atividades registradas.
- `ajuda()`: Exibe informações sobre o uso do sistema.
- `menu()`: Controla a interação do usuário no terminal.

## Regras de Validação

- **Senhas** devem ter entre 4 e 15 caracteres, conter pelo menos 3 letras/números e 1 caractere especial.
- **Emails** devem estar no formato válido (exemplo: user@example.com).
- **Usuários** não podem ter o mesmo email ou username já cadastrado.
- **Atividades** só podem ser registradas por usuários já cadastrados.
- **Pontos e recompensas** são concedidos de acordo com os níveis estabelecidos.

## Notificações

O sistema notifica automaticamente os usuários quando:
- Eles atingem um novo nível de pontuação.
- Eles acumulam pontos suficientes para resgatar uma recompensa.

## Recompensas e Níveis

O sistema oferece recompensas conforme os pontos acumulados:

100 pontos: Desconto em lojas sustentáveis ou cashback de R$ 10,00 |
250 pontos: Toucher de alimentação saudável ou R$ 30,00 |
350 pontos: Garrafa térmica ecológica ou R$ 50,00 |
500 pontos: Kit de reciclagem ou R$ 70,00 |
700 pontos: Kit de produtos sustentáveis ou R$ 100,00 |
1000 pontos: Gift Card de R$ 150,00 ou assinatura em serviços ecológicos |

Os níveis de pontuação que garantem notificações são **100, 250, 500 e 1000 pontos**.
