# RF04 - Visualizar Animal

## Atores:

**Usuário Registrado** - Qualquer usuário que tenha criado uma conta no site para visualizar os animais disponíveis para adoção.

**Usuário Anônimo** - Qualquer usuário que esteja utilizando o site sem ter uma conta criada ou que não esteja logado.

### Descrição Sucinta:

Exibe informações detalhadas sobre gatos disponíveis para adoção no site. Os gatos são exibidos com fotos e descrições para ajudar os interessados a tomar uma decisão informada sobre a adoção.

### Pré-Condição:

Os atores devem ter selecionado um animal para visualizar suas informações.

### Fluxo Principal:


1. O ator ao acessar a tela de listagem de todos os animais disponíveis para adoção seleciona um dos animais para visualizar;
2. O sistema verifica se o animal existe no banco de dados:
    1. Se sim, o sistema vai para o passo 3.
    2. Senão o sistema exibe a mensagem "Erro ao exibir o animal selecionado", verifique se o animal ainda está disponível para adoção e tente novamente’.
3. O sistema verifica se o ator possui cadastro no banco de dados e o seu nível de permissões e:
    1. Se sim, o sistema exibe o botão com a mensagem "Tenho Interesse!" e vai para o passo 4.
    2. Senão, o sistema exibe o botão com a mensagem "Entrar".
4. O sistema apresenta a caixa de confirmação se o ator se encaixa no perfil do animal selecionado.

### Opções dos Usuários:

| Opção | Descrição | Atalho |
| --- | --- | --- |
| Tenho Interesse! | Exibe ao ator a solicitação de confirmação se o ator se encaixa no perfil do animal selecionado |  |


### Relatório do Usuário:

| Campo | Descrição | Formato |
| --- | --- | --- |
|  |  |  |
|  |  |  |

### Fluxo Alternativo:

**FA01 -** Botão de entrar:

1. O ator ao acessar a tela de listagem de todos os animais disponíveis para adoção seleciona um dos animais para visualizar;
2. O sistema verifica se o animal existe no banco de dados:
    1. Se sim, o sistema vai para o passo 3.
    2. Senão o sistema exibe a mensagem "Erro ao exibir o animal selecionado", verifique se o animal ainda está disponível para adoção e tente novamente’.
3. O sistema verifica se o ator possui cadastro no banco de dados e o seu nível de permissões e o ator que ainda não autenticou-se no sistema seleciona a opção de entrar;
4. O sistema exibe na tela o formulário de login .

![Protótipo de tela de visualização do animal selecionado](https://i.imgur.com/M9IBAUs.png)
