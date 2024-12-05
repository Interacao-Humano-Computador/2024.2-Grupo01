### Introdução

Seguindo a Engenharia de Usabilidade de Mayhew, processo de design escolhido para este projeto, é necessário a identificação das características, capacidades e restrições da plataforma na fase de análise de requisitos. Tais capacidades e restrições delimitam as possibilidades para uma interface de usuário e devem ser levadas em consideração em uma proposta de solução.
### Objetivo

O objetivo é identificar e definir características, capacidades e restrições impostas por hardware e software à plataforma objeto de estudo deste projeto. Assim, entendendo as opções disponíveis para a solução de design antes da fase de design, avaliação e desenvolvimento sugerida por Mayhew. Além das possibilidades, também procura-se levar a saber quais opções de projeto são desvantajosas, apesar de viáveis, e quais são facilitadas pelas características da plataforma.

### Metodologia

Tomando como base o procedimento proposto por Mayhew(1999), foram efetuadas as seguintes etapas:
- Identificar os aspectos relevantes das plataformas em que o sistema está presente
- Analisar materiais sobre a plataforma
- Documentar as características, capacidades e restrições das plataformas

### Características da plataforma

O Bluesky é uma rede social de microblogs descentralizada, ou seja, é uma plataforma que permite aos seus usuários interagir entre si por meio de breves publicações e mensagens diretas. Ele pode ser acessado por um dispositivo com acesso à internet, como desktops, notebooks, celulares e tablets, com a possibilidade de uso de navegadores de internet modernos, como Google Chrome, Mozilla Firefox, Safari, Microsoft Edge, entre outros.
Essa rede social oferece funcionalidades que merecem ser pontuadas, sendo elas:

- Criação de publicações contendo textos, imagens, vídeos ou links
- Interagir com publicações por meio de comentários, curtidas e repostagens
- Seguir perfis
- Buscar e explorar publicações ou perfis de usuários
- Enviar mensagens privadas
- Salvar feeds 
- Criar listas de usuários de interesse
- Criar listas de moderação
- Editar perfil
- Configurar conta

#### Tecnologias utilizadas

As principais tecnologias utilizadas na construção do sistema são:

- Typescript (Javascript)
- HTML
- CSS
- React+Expo
- Go
- ScyllaDB
- SQLite

#### Capacidades e Restrições

- Requer acesso à internet
- Input é feito por teclado e mouse ou tela touchscreen a depender do aparelho
- Os navegadores utilizados para acessar o site devem ser compatíveis com padrões web como HTML5, CSS3 e Javascript
- As publicações podem ter até 300 caracteres
- Não é possível enviar vídeos ou imagens em mensagens diretas
- A tradução de publicações leva a uma nova aba com a tradução do Google Tradutor
- Publicações não são editáveis após postagem
- É possível utilizar de listas de usuários e de moderação feitas por outras pessoas
- É possível modificar o tema do site
- É possível escolher a fonte do site, entre padrão e do sistema, bem como alterar o tamanho da fonte
- É possível adicionar textos alternativos em publicações com imagens

## Referência bibliográfica
> 1. Mayhew, D. J. The Usability Engineering Lifecycle: A Practitioner's Handbook for User Interface Design. Morgan Kaufmann, 5 abr. 1999.

## Bibliografia

> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.
> 2. Bluesky. bluesky-social. Github, 2024. Disponível em; https://github.com/bluesky-social. Acesso em: 02 dez. 2024.

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
            <td>03/12</td>
            <td>1.0</td>
            <td>Criação do documento.</td>
            <td><a href="https://github.com/Joa0V">João Ribeiro</a></td>
            <td>01/12</td>
            <td><a href="https://github.com/ccarlaa">Carla</a></td>
        </tr>
    </table>
</div>