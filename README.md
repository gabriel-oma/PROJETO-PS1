# Aplicativo de realização de atividades sustentáveis

O projeto é um sistema de gamificação que incentiva a prática de atividades sustentáveis, recompensando os usuários com pontos que podem ser trocados por prêmios.

## Funcionalidades

- **Cadastro de Usuários**: Registro de novos usuários com verificação via código de confirmação.
- **Registro de Atividades Sustentáveis**: Os usuários podem registrar suas ações sustentáveis e acumular pontos.
- **Exclusão de Dados**: Possibilidade de excluir usuários e atividades registradas.
- **Listagem de Dados**: Consulta de usuários e atividades cadastradas.
- **Ranking de Usuários**: Exibição dos usuários com maior pontuação.
- **Sistema de Recompensas**: Troca de pontos acumulados por prêmios.
- **Notificações Automáticas**: Envio de alertas para usuários ao atingirem novos níveis ou desbloquearem recompensas.
- **Ajuda**: Exibe informações sobre o sistema e como utilizá-lo.

## Como Utilizar

### Executar o Programa
O sistema é executado diretamente pelo terminal. Para iniciá-lo, basta rodar o script Python correspondente.

### Cadastro de um Novo Usuário
1. Escolha a opção **"Cadastrar novo usuário"**.
2. Insira um nome de usuário e email.
3. Defina uma senha que contenha pelo menos:
   - 4 caracteres,
   - 3 letras/números,
   - 1 caractere especial.
4. Confirme o código de verificação enviado ao email.

### Registro de Atividades Sustentáveis
1. Escolha a opção **"Registrar atividades sustentáveis"**.
2. Selecione uma atividade predefinida ou insira uma nova.
3. Informe quantas vezes a atividade foi realizada.
4. Os pontos são atribuídos de acordo com a atividade e a quantidade realizada.

### Consulta de Usuários e Atividades
- **Lista de Usuários**: Exibe todos os usuários cadastrados e seus respectivos pontos.
- **Lista de Atividades**: Mostra todas as atividades registradas pelos usuários.

### Consulta do Ranking de Usuários
- A opção **"Ranking de usuários"** exibe a classificação dos usuários ordenados por pontuação acumulada.

### Resgate de Recompensas
- A opção **"Resgatar recompensa"** permite trocar os pontos acumulados por prêmios disponíveis no sistema.

### Encerramento do Programa
- Selecionando **"Sair"**, a execução do sistema é finalizada.

## Estrutura do Código
O sistema é estruturado em diferentes funções para garantir modularidade e facilidade de manutenção:

- `cadastrar_usuario()`: Registra novos usuários e gerencia a verificação por código.
- `registrar_atividade()`: Permite aos usuários cadastrarem atividades sustentáveis e acumularem pontos.
- `listar_usuarios()`: Exibe a lista de usuários cadastrados com suas respectivas pontuações.
- `listar_atividades()`: Exibe todas as atividades registradas no sistema.
- `ranking()`: Ordena e exibe os usuários de acordo com sua pontuação.
- `resgatar_recompensa()`: Permite a troca de pontos por recompensas.
- `ajuda()`: Ajuda os novos usuários a utilizarem de maneira certa o sitema
- `menu()`: Controla a interação do usuário por meio de um menu interativo no terminal.

