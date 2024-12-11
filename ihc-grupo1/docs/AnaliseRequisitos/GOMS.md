
## Introdução
O GOMS (Goals, Operators, Methods, Selection Rules) é uma técnica que consiste basicamente em analisar o comportamento do usuário na execução de uma tarefa, e assim prevermos soluções de maior desempenho na usabilidade. 

## Metodologia

Ao abordamos o GOMS temos algumas convenções a serem utilizadas no prcoesso de análise de tarefas, isto é, ter em vista os elementos que o mesmo é feito. 

 **Elemento**        | **Descrição**                                                                                                                                                   |
|---------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Goals (Objetivos)**      | Representam as metas que o usuário busca alcançar ao executar uma tarefa, como "abrir um arquivo", "imprimir um documento" ou "enviar um e-mail". |
| **Operators (Operadores)** | São as ações físicas e mentais realizadas para atingir os objetivos, incluindo ações cognitivas, como lembrar informações, e físicas, como clicar ou digitar.      |
| **Methods (Métodos)**      | São a sequência organizada de operadores utilizados para atingir um objetivo. Descrevem o plano ou estratégia que o usuário segue para concluir a tarefa.              |
| **Selection rules (Regras de seleção)** | Diretrizes que orientam o usuário na escolha de métodos e operadores, determinando a melhor abordagem para alcançar o objetivo desejado.        |

<p align="center"><b>Referência:</b> <a href="#referencia-bibliografica">Barbosa e Silva[¹]</a></p>


## Análise de Tarefas.

### Tarefa 1: Salvar post em itens salvos.

Nesta tarefa o usuário deseja salvar em sua aba itens salvos um post de interesse. 

```
GOAL 0: Fazer login na página para acessar o item 
    OP 0.1: Digitar o e-mail no campo de login 
    OP 0.2: Digitar a senha no campo correspondente 
    OP 0.3: Clicar no botão de login

GOAL 1: Identificar o item que deseja salvar 
    OP 1.1: Navegar pela timeline ou buscar o item desejado 
    OP 1.2: Parar a navegação ao encontrar o item

GOAL 2: Abrir o menu de opções do item 
    OP 2.1: Guiar o mouse ou tocar no ícone de opções (três pontos) 
    OP 2.2: Clicar ou tocar no ícone para abrir o menu

GOAL 3: Selecionar a opção de salvar o item 
    (Sel. Rule: Se o item já estiver salvo, a opção exibida será "Remover de Itens Salvos" em vez de "Salvar".) 
    OP 3.1: Guiar o mouse ou tocar na opção "Salvar em Itens Salvos" 
    OP 3.2: Clicar ou tocar para confirmar o salvamento

GOAL 4: Confirmar que o item foi salvo 
    OP 4.1: Observar a notificação ou mudança visual no ícone indicando sucesso 
    OP 4.2: (Opcional) Navegar até a aba "Itens Salvos" para verificar a presença do item
```

### Tarefa 2: Publicar um post no Bluesky

Nesta tarefa o usuário deverá fazer uma publicação na plataforma. 

```
GOAL 0: Fazer login na conta do Bluesky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Acessar a área de criação de post
    OP 1.1: Guiar o mouse até o campo de criação de post (caixa de texto)

GOAL 2: Escrever o conteúdo do post
    OP 2.1: Digitar o conteúdo desejado no campo de texto
    OP 2.2: Revisar e corrigir o texto, se necessário

GOAL 3: Adicionar mídia ao post (opcional)
    OP 3.1: Guiar o mouse até o ícone de adicionar mídia (foto, vídeo, link)
    OP 3.2: Clicar ou tocar no ícone para abrir o seletor de arquivos
    OP 3.3: Selecionar o arquivo desejado e confirmar a adição

GOAL 4: Publicar o post
    OP 4.1: Guiar o mouse até o botão "Post"
    OP 4.2: Clicar ou tocar no botão para publicar o post

GOAL 5: Confirmar que o post foi publicado
    OP 5.1: Observar a atualização na timeline ou na página do perfil
    OP 5.2: (Opcional) Verificar a notificação de sucesso
```

### Tarefa 3: Editar Perfil no BLuesky

```
GOAL 0: Fazer login na conta do Bluesky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Acessar a página de perfil
    OP 1.1: Guiar o mouse até a aba "edit profile"

GOAL 2: Modificar informações do perfil
    OP 2.1: Guiar o mouse até o campo de texto que deseja alterar (nome, biografia, etc.)
    OP 2.2: Clicar ou tocar no campo de texto para editar
    OP 2.3: Digitar as novas informações no campo de texto

GOAL 3: Adicionar ou mudar a foto de perfil (opcional)
    OP 3.1: Guiar o mouse até a foto de perfil atual
    OP 3.2: Clicar ou tocar no ícone de foto
    OP 3.3: Selecionar ou tirar uma nova foto para o perfil

GOAL 4: Salvar as alterações feitas
    OP 4.1: Guiar o mouse até o botão "Salvar" ou "Concluir"
    OP 4.2: Clicar ou tocar no botão para salvar as alterações

GOAL 5: Confirmar que o perfil foi atualizado
    OP 5.1: Observar as mudanças na página de perfil
    OP 5.2: Verificar visualmente que as alterações foram salvas corretamente
```

### Tarefa 4: Bloquear um Perfil de usuário

```
GOAL 0: Fazer login na conta do Bluesky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Acessar o perfil que deseja bloquear
    OP 1.1: Navegar pela timeline ou buscar pelo nome de usuário
    OP 1.2: Clicar ou tocar no perfil desejado para abrir a página do usuário

GOAL 2: Abrir o menu de opções do perfil
    OP 2.1: Guiar o mouse até o ícone de opções (três pontos) no perfil
    OP 2.2: Clicar ou tocar no ícone para abrir o menu de opções

GOAL 3: Selecionar a opção "Bloquear" no menu
    OP 3.1: Guiar o mouse ou tocar na opção "Bloquear"
    OP 3.2: Clicar ou tocar para confirmar o bloqueio

GOAL 4: Confirmar que o perfil foi bloqueado
    OP 4.1: Observar a atualização visual na página do perfil (exibição de "Bloqueado")
    OP 4.2: (Opcional) Verificar notificação de bloqueio ou mudança na lista de seguidores
```

### Tarefa 5: Curtir uma postagem de um usuário

```
GOAL 0: Fazer login na conta do Bluesky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Navegar até o post no qual deseja dar like
    OP 1.1: Navegar pela timeline ou buscar pelo post desejado
    OP 1.2: Parar a navegação ao encontrar o post

GOAL 2: Localizar o ícone de "Like" no post
    OP 2.1: Guiar o mouse até o ícone de coração (like) abaixo do post
    OP 2.2: Verificar se o ícone de like está disponível para interação

GOAL 3: Dar like no post
    OP 3.1: Clicar ou tocar no ícone de coração (like)

GOAL 4: Confirmar que o like foi registrado
    OP 4.1: Observar a mudança visual no ícone (mudança de cor ou animação)
    OP 4.2: Verificar o aumento no contador de likes do post
```
### Tarefa 6: Envio de mensagens privadas

```
GOAL 0: Acessar a aba de chat
    OP 0.1: Localizar o ícone ou aba correspondente ao chat.
    OP 0.2: Clicar no ícone/aba.

GOAL 1: Selecionar conversa existente
    OP 1.1: Identificar a conversa na lista de chats.
    OP 1.2: Clicar na conversa para abri-la.

GOAL 2: Criar um novo chat
    OP 2.1: Localizar e clicar no botão para criar um novo chat.
    OP 2.2: Digitar o nome ou identificador do usuário no campo de busca.
    op 2.3: Selecionar o usuário desejado.

GOAL 3: Enviar mensagem
    OP 3.1: Digitar o texto no campo de input.
    OP 3.2 Enviar a mensagem clicando no botão ou pressionando "Enter".
```

### Tarefa 7: Criar lista de usuários

```
GOAL 0: Criar lista de perfis de interesse

	GOAL 1: Ir à tela de criação da lista
		OP 1.0: Clicar no botão 'Listas' na barra lateral
		OP 1.1: Clicar no botão 'Novo' na seção superior da tela

	GOAL 2: Definir informações iniciais da lista de usuários
		OP 2.0: Escrever o nome da lista
		OP 2.1: Escrever descrição da lista
		OP 2.2: Definir uma imagem de avatar para a lista
			OP 2.2.0: Carregar uma imagem do sistema ao site
		OP 2.3: Salvar informações iniciais da lista de usuários

	GOAL 3: Adicionar perfis à lista
		OP 3.0: Clicar no botão 'About' na seção superior da tela
		OP 3.1: Clicar no botão 'Adicionar'
		OP 3.2: Buscar por usuários
			OP 3.2.0: Escrever o nome ou parte do nome de um perfil de interesse
		OP 3.3: Clicar no botão 'adicionar' ao lado do perfil de interesse
		OP 3.4: Clicar no botão 'Feito'
```

### Tarefa 8: Compartilhar um post

```
GOAL 0: Fazer login na conta do BlueSky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Localizar o post que deseja compartilhar
    OP 1.1: Navegar pela timeline ou buscar o post desejado
    OP 1.2: Parar a navegação ao encontrar o post

GOAL 2: Acessar as opções de compartilhamento
    OP 2.1: Guiar o mouse até o ícone de compartilhamento (geralmente uma seta ou símbolo de retweet)
    OP 2.2: Clicar ou tocar no ícone de compartilhamento

GOAL 3: Escolher o método de compartilhamento
    OP 3.1: Selecionar "Repostar" para compartilhar diretamente na sua timeline
    OP 3.2: Selecionar "Citar post" para adicionar um comentário ao compartilhar

GOAL 4: Adicionar comentário (se "Citar post" foi selecionado)
    OP 4.1: Digitar o comentário no campo de texto
    OP 4.2: Revisar o comentário

GOAL 5: Confirmar o compartilhamento
    OP 5.1: Clicar no botão "Compartilhar" ou "Repostar"

GOAL 6: Verificar se o post foi compartilhado
    OP 6.1: Observar a atualização na sua timeline
    OP 6.2: Verificar a notificação de compartilhamento bem-sucedido
```

### Tarefa 9: Seguir um novo usuário

```
GOAL 0: Fazer login na conta do BlueSky
    OP 0.1: Digitar o e-mail no campo de login
    OP 0.2: Digitar a senha no campo correspondente
    OP 0.3: Clicar no botão de login

GOAL 1: Encontrar o usuário que deseja seguir
    OP 1.1: Usar a barra de pesquisa para buscar o nome do usuário
    OP 1.2: Navegar pelos resultados da pesquisa

GOAL 2: Acessar o perfil do usuário
    OP 2.1: Clicar no nome ou foto do usuário nos resultados da pesquisa

GOAL 3: Iniciar o processo de seguir
    OP 3.1: Localizar o botão "Seguir" no perfil do usuário
    OP 3.2: Clicar no botão "Seguir"

GOAL 4: Confirmar que está seguindo o usuário
    OP 4.1: Observar a mudança visual no botão (de "Seguir" para "Seguindo")
    OP 4.2: Verificar se os posts do usuário aparecem na sua timeline
```
### Tarefa 10: Criar um Pacote Inicial

Nesta tarefa, o usuário deseja criar um Pacote Inicial na plataforma Bluesky para organizar e compartilhar feeds e perfis favoritos com amigos.

```
GOAL 0: Fazer login na conta do Bluesky  
    OP 0.1: Digitar o e-mail no campo de login  
    OP 0.2: Digitar a senha no campo correspondente  
    OP 0.3: Clicar no botão de login  

GOAL 1: Acessar a aba "Pacotes Iniciais"  
    OP 1.1: Navegar até a aba "Pacotes Iniciais" no menu do perfil  
    OP 1.2: Clicar na aba para visualizar as opções de pacotes  

GOAL 2: Iniciar a criação de um novo pacote  
    OP 2.1: Clicar no botão "Criar" exibido na interface  
    (Sel. Rule: Se o usuário optar por "Faça um para mim", o sistema cria automaticamente um pacote com base em sugestões.)  

GOAL 3: Personalizar o pacote  
    OP 3.1: Digitar um nome para o pacote no campo correspondente  
    OP 3.2: Escrever uma descrição breve sobre o pacote  
    OP 3.3: Navegar pela lista de feeds e perfis disponíveis  
    OP 3.4: Selecionar os itens desejados para adicionar ao pacote  

GOAL 4: Confirmar a criação do pacote  
    OP 4.1: Clicar no botão "Salvar" ou "Finalizar" para concluir a criação  
    OP 4.2: Verificar a mensagem de confirmação de sucesso  

GOAL 5: Compartilhar o pacote com amigos (opcional)  
    OP 5.1: Clicar no botão "Compartilhar" exibido ao lado do pacote criado  
    OP 5.2: Escolher os contatos para enviar o pacote  
    OP 5.3: Confirmar o envio e observar a notificação de sucesso  

GOAL 6: Verificar o pacote criado  
    OP 6.1: Retornar à aba "Pacotes Iniciais" para confirmar a presença do novo pacote na lista  
    OP 6.2: Observar os itens adicionados no pacote para garantir que estão corretos  
```


## Bibliografia
> 1. Bilheteria Digital. Análise Hierárquica de Tarefas. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023.1. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/hta/.> Acesso em 01/12/2024 ás 14:41

> 2. Dominio Publico. Análise de Tarefas. Repositório do Grupo Dominio Público da disciplina de Interação Humano Computador da Universidade de brasília, 2023.2. Disponível em: <https://interacao-humano-computador.github.io/2023.2-Dominio-Publico/analise_de_requisitos/analise_de_tarefas/goms/> Acesso em 01/12/2024 ás 14:44

> 3. BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## :round_pushpin: Histórico de Versão 

<div align="center">
    <table>
        <tr>
            <th>Data</th>
            <th>Versão</th>
            <th>Descrição</th>
            <th>Autor</th>
            <th>Data da Revisão</th>
            <th>Revisor</th>
        </tr>
        <tr>
            <td>01/12</td>
            <td>1.0</td>
            <td>Criação do documento e de 5 tarefas. </td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
            <td>01/12</td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
        </tr>
        <tr>
            <td>01/12</td>
            <td>1.1</td>
            <td>Adiciona envio de mensagens privadas. </td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td>01/12</td>
            <td><a href="https://github.com/Jagaima">Davi Nobre</a></td>
        </tr>
        <tr>
            <td>02/12</td>
            <td>1.2</td>
            <td>Adicionando criação de lista de usuários</td>
            <td><a href="https://github.com/JoaoV">João Vitor</a></td>
            <td>03/12</td>
            <td><a href="https://github.com/GabrielSMonteiro">Gabriel Monteiro</a></td>
        </tr>
        <tr>
            <td>03/12</td>
            <td>1.3</td>
            <td>Adicionando compartilhar um post e seguir um novo usuário</td>
            <td><a href="https://github.com/GabrielSMonteiro">Gabriel Monteiro</a></td>
            <td>03/12</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
        </tr>
        <tr>
            <td>03/12</td>
            <td>1.4</td>
            <td>Adicionando criar pacotes</td>
            <td><a href="https://github.com/erteduarda">Eduarda Tavares</a></td>
            <td>03/12</td>
            <td><a href="https://github.com/GabrielSMonteiro">Gabriel Monteiro</a></td>
        </tr>
    </table>
</div>
