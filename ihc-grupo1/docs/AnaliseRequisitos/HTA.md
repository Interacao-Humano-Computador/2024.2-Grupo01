## Introdução

A Análise Hierárquica de Tarefas (HTA - Hierarchical Task Analysis) é uma técnica amplamente utilizada para decompor sistemas ou processos complexos em subtarefas menores e mais gerenciáveis. Esse método é crucial em diversos campos, como engenharia de fatores humanos, design de experiência do usuário (UX) e gerenciamento de processos, pois permite uma visão detalhada de como tarefas são realizadas por usuários, ajudando na otimização de sistemas e fluxos de trabalho. A HTA é frequentemente aplicada no desenvolvimento de interfaces de usuário, onde a complexidade das interações precisa ser organizada de forma hierárquica, visando melhorar a usabilidade e a experiência do usuário final.

Neste trabalho, será explorada a aplicação da HTA no contexto do site do BlueSky. O objetivo é identificar, analisar e estruturar as tarefas necessárias para a criação de um sistema de comunicação eficiente e intuitivo, focado nas necessidades do usuário e nos fluxos de interação que garantem uma experiência fluida e intuitiva.

## Metodologia

A metodologia adotada para a realização deste trabalho segue os princípios da Análise Hierárquica de Tarefas, que envolvem a decomposição de tarefas em níveis hierárquicos e sua análise detalhada. O processo será dividido nas seguintes etapas:

**Definição do Sistema e Objetivo**: Primeiramente, será definido o sistema a ser analisado, que no caso é o site do Bluesky. O objetivo principal será estabelecer como o sistema é estruturado, considerando as principais funções e fluxos de interação.

**Identificação das Tarefas e Subtarefas**: As principais tarefas envolvidas no requisito que está sendo analisado serão identificadas e listadas.

**Criação da Hierarquia de Tarefas**: Uma vez identificadas, as tarefas serão organizadas hierarquicamente, com as tarefas principais no topo e as subtarefas que detalham ações específicas em níveis inferiores. Cada tarefa será subdividida de acordo com sua complexidade e relação com outras ações.

**Determinação das Dependências**: As dependências entre as tarefas serão analisadas, identificando quais tarefas precisam ser realizadas antes das outras e quais podem ocorrer simultaneamente. Isso permitirá entender o fluxo de trabalho e otimizar o processo.

**Validação e Ajustes**: Após a construção da hierarquia, será realizada uma revisão do modelo para garantir que ele esteja alinhado com as expectativas do usuário e as necessidades do sistema. Feedback de stakeholders pode ser incorporado para ajustar e refinar a análise.

## Desenvolvimento

A análise hirárquica de tarefas será representada por meio de diagramas nos quais serão representadas as seguintes representações gŕaficas:


<figure markdown="span">
  ![legenda](../assets/legenda.drawio.png){ width="400" align="center" }
  <figcaption>Imagem 1: Legenda dos Diagramas de HTA. Autor: Carla A. C. Ribeiro.</figcaption>
</figure>


### 1. Envio de Mensagens Privadas

Com base na metodologia de Análise Hierárquica de Tarefas, foi realizada a análise do fluxo de envio de uma mensagem privada entre os usuários do site BlueSky. O diagrama desenvolvido pode ser visto abaixo: 

<figure markdown="span">
  ![legenda](../assets/images/hta-chat.png){ width="400" align="center" }
  <figcaption>Imagem 1: Diagrama HTA - Envio de mensagens privadas. Autor: Carla A. C. Ribeiro.</figcaption>
</figure>

<div style='display: flex; align-items: center; flex-direction: column'>
<table>
<thead>
    <tr>
      <th>Objetivos / Operações</th>
      <th>Problemas e Recomendações</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0. Enviar mensagem privada</td>
      <td><strong>Plano:</strong> Enviar mensagem privada para outro usuário da plataforma.<br/><br/>
          <strong>Feedback:</strong> Garantir que os usuários consigam trocar mensagens.</td>
    </tr>
    <tr>
      <td>1. Acessar aba de chat</td>
      <td><strong>Plano:</strong> Acessar a página de chat.<br/>
          <strong>Feedback:</strong> Lista de conversas e a possibilidade da criação de novos chats.</td>
    </tr>
    <tr>
      <td>2. Selecionar conversa</td>
      <td><strong>Input:</strong> Selecionar conversa.<br/>
          <strong>Feedback:</strong> Visualizar mensagens trocadas entre os usuários.<br/>
          <strong>Recomendação:</strong> Melhorar o feedback para o usuário dos filtros selecionados.</td>
    </tr>
    <tr>
      <td>3. Criar novo chat</td>
      <td><strong>Input:</strong> Selecionar botão de criação de chat.</td>
    </tr>
    <tr>
      <td>3.2 Buscar usuário</td>
      <td><strong>Input:</strong> Selecionar usuário para a criação da conversa.</td>
    </tr>
    <tr>
      <td>2.1 e 3.1.1 Enviar mensagem</td>
      <td><strong>Input:</strong> Utilizar o input para enviar mensagens.</td>
    </tr>
  </tbody>
</table>

<p>
Tabela 1: Análise da HTA - Envio de mensagens privadas. Autor: Carla A. C. Ribeiro.
</p>
</div>

## Histórico de Versão 


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
            <td>Criação do documento e 1ª HTA.</td>
            <td><a href="https://github.com/ccarlaa">Carla Clementino</a></td>
            <td>**/12</td>
            <td><a href="https://github.com/"></a></td>
        </tr>
    </table>
</div>