# Levantamento de Requisitos - Jogo de Forca Online

## 1. Problema Apresentado

&nbsp;&nbsp;&nbsp;&nbsp;Foi proposta a elaboração de um jogo de forca online.

## 2. Proposta de Desenvolvimento

&nbsp;&nbsp;&nbsp;&nbsp;Propõe-se o desenvolvimento de um jogo de forca acessível tanto em computadores (via aplicação web) quanto em dispositivos móveis (app). O jogo oferecerá partidas multiplayer, incluindo salas temáticas, além da opção de enfrentar bots. Para tornar a experiência mais interativa, os jogadores poderão se comunicar por meio de um chat durante as partidas.

## 3. Requisitos Funcionais

&nbsp;&nbsp;&nbsp;&nbsp;Elaborou-se os seguintes requisitos funcionais, seguindo o modelo 5W2H, para o jogo de forca:

<div align="center">
<sub>Tabela 1 - Requisitos Funcionais</sub><br>

| ID    | Título                          | Descrição (5W2H)                                                                                              |
|-------|--------------------------------|-----------------------------------------------------------------------------------------------------------|
| RF001 | Partidas Multiplayer           | **What**: Permitir partidas entre vários jogadores. <br> **Why**: Para proporcionar interatividade entre usuários. <br> **Who**: Todos os jogadores. <br> **Where**: Na aplicação web e mobile. <br> **When**: Durante o uso do jogo. <br> **How**: Através da criação de salas privadas ou públicas. <br> **How Much**: Sem custo adicional. |
| RF002 | Modo Individual Contra Bot     | **What**: Permitir que um jogador jogue sozinho contra um bot. <br> **Why**: Para oferecer uma opção de jogo offline ou para praticar. <br> **Who**: Jogadores individuais. <br> **Where**: No jogo. <br> **When**: Quando não houver outros jogadores disponíveis ou quando o jogador quiser praticar. <br> **How**: O sistema controlará as respostas do bot. <br> **How Much**: Sem custo adicional. |
| RF003 | Geração Automática de Palavras  | **What**: Gerar palavras aleatórias para cada partida. <br> **Why**: Para evitar repetição e manter o jogo dinâmico. <br> **Who**: Todos os jogadores. <br> **Where**: No jogo. <br> **When**: No início de cada partida. <br> **How**: O sistema seleciona palavras de um banco de dados. <br> **How Much**: Sem custo adicional. |
| RF004 | Dicas Opcionais                 | **What**: Fornecer dicas para ajudar o jogador. <br> **Why**: Para facilitar o jogo para iniciantes. <br> **Who**: Todos os jogadores. <br> **Where**: No jogo. <br> **When**: Sempre que um jogador solicitar uma dica. <br> **How**: O sistema exibe uma pista relacionada à palavra. <br> **How Much**: Sem custo adicional. |
| RF005 | Cadastro e Login de Usuários    | **What**: Permitir que os jogadores criem contas e façam login. <br> **Why**: Para personalizar a experiência do usuário e salvar o progresso das partidas. <br> **Who**: Todos os jogadores. <br> **Where**: Na aplicação web e mobile. <br> **When**: No primeiro acesso ou ao iniciar sessão. <br> **How**: Por meio de um formulário com e-mail e senha. <br> **How Much**: Sem custo adicional. |
| RF006 | Personalização de Perfil        | **What**: Permitir que os usuários personalizem nome e avatar. <br> **Why**: Para tornar a experiência mais imersiva e interativa. <br> **Who**: Todos os jogadores cadastrados. <br> **Where**: No jogo. <br> **When**: Após o login. <br> **How**: Configuração disponível no perfil do usuário. <br> **How Much**: Custo adicional para a compra de alguns avatares. |
| RF007 | Histórico de Partidas           | **What**: Armazenar o histórico de partidas de cada jogador. <br> **Why**: Para permitir acompanhamento do desempenho. <br> **Who**: Todos os jogadores cadastrados. <br> **Where**: No jogo. <br> **When**: Após cada partida. <br> **How**: Banco de dados armazena resultados. <br> **How Much**: Sem custo adicional. |
| RF008 | Ranking de Jogadores            | **What**: Exibir um ranking de pontuação acumulada. <br> **Why**: Para incentivar a competitividade. <br> **Who**: Todos os jogadores cadastrados. <br> **Where**: No jogo. <br> **When**: Atualizado após cada partida. <br> **How**: O sistema calcula a pontuação baseada nos acertos. <br> **How Much**: Sem custo adicional. |
| RF009 | Modo História Temático           | **What**: Criar um modo história com temas variados e progressão de desafios. <br> **Why**: Para aumentar a imersão e engajamento dos jogadores. <br> **Who**: Todos os jogadores. <br> **Where**: No jogo. <br> **When**: Sempre que o usuário optar por esse modo. <br> **How**: O jogo apresenta uma narrativa interativa onde o jogador avança conforme acerta as palavras. <br> **How Much**: Sem custo adicional. |
| RF010 | Chat Durante as Partidas        | **What**: Permitir interação entre jogadores via chat. <br> **Why**: Para aumentar a imersão e comunicação. <br> **Who**: Todos os jogadores em partidas multiplayer. <br> **Where**: No jogo. <br> **When**: Durante as partidas. <br> **How**: Um chat será disponibilizado dentro das salas. <br> **How Much**: Sem custo adicional. |

<sup>Fonte: Material produzido pelo autor (2025) </sup>
</div>

## 4. Requisitos Não Funcionais

&nbsp;&nbsp;&nbsp;&nbsp;Elaborou-se os seguintes requisitos não funcionais, classificados por aspecto de qualidade e prioridade, para o jogo de forca:

<div align="center">
<sub>Tabela 2 - Requisitos Não Funcionais</sub><br>

| **RNF#**  | **Descrição**                                                                                      | **Aspecto de qualidade**      | **Prioridade**  |
|-----------|--------------------------------------------------------------------------------------------------|------------------------------|----------------|
| RNF001    | O sistema deve ser responsivo para desktop e mobile, garantindo acessibilidade.                  | Usabilidade                  | Alta           |
| RNF002    | O tempo de carregamento das telas deve ser inferior a 2 segundos para melhorar a experiência do usuário. | Eficiência de performance    | Alta           |
| RNF003    | O sistema deve suportar até 1000 jogadores simultaneamente para garantir escalabilidade.         | Confiabilidade               | Alta           |
| RNF004    | O sistema deve garantir segurança na autenticação por meio de criptografia de senhas.            | Segurança                    | Alta           |
| RNF005    | O sistema deve oferecer suporte aos idiomas português e inglês para ampliar o público-alvo.      | Usabilidade                  | Moderada       |
| RNF006    | O sistema deve utilizar inteligência artificial para gerar dicas dinâmicas e equilibradas.       | Funcionalidade               | Moderada       |

<sup>Fonte: Material produzido pelo autor (2025) </sup>
</div>