# The Resistance

## Visão geral

The Resistance é um jogo de tabuleiro de dedução social para 5 a 10 jogadores, em que alguns participantes são membros da resistência e outros são espiões infiltrados.

O objetivo dos membros da resistência é completar missões secretas com sucesso, enquanto os espiões tentam sabotar as missões e enganar os outros jogadores. O jogo é dividido em rodadas de missões, e em cada uma os jogadores votam para propor uma equipe que irá realizar a missão.

Cada missão exige um número específico de jogadores, e o grupo escolhido precisa decidir se vai aceitar ou rejeitar a proposta. Se a missão for aprovada, os participantes escolhidos realizam uma ação secreta que pode ser "sucesso" ou "fracasso". Os espiões escondem o fracasso, enquanto os membros da resistência sempre ajudam a missão a dar certo.

Ao longo do jogo, os jogadores discutem, fazem acusações, tentam identificar os espiões e usam a lógica para descobrir quem mente. A tensão vem do fato de que as ações são secretas e as informações são limitadas, então qualquer jogador pode parecer confiável ou suspeito.

O jogo tem um estilo muito parecido com bluffing e psicologia social. Ele exige leitura de comportamento, persuasão, memória e boa capacidade de dedução. A resistência vence se conseguir completar um número suficiente de missões, e os espiões vencem se conseguirem sabotar o suficiente para impedir esse objetivo.

Em resumo, The Resistance é um jogo de estratégia, blefe e dedução em que a confiança entre os jogadores é tão importante quanto a capacidade de esconder a própria identidade.

## Engenharia reversa - análise do sistema de jogo

Uma análise de engenharia reversa de The Resistance revela os seguintes componentes-chave:

### Elementos estruturais

- Sistema de papéis: dois estados opostos (resistência vs. espiões) que definem comportamentos e objetivos conflitantes
- Mecânica de votação: coleta de informações através das escolhas dos jogadores
- Ações secretas: mecanismo de ocultação de informações que cria assimetria de conhecimento
- Rodadas de missões: iterações repetitivas que geram dados de padrão comportamental

### Dinâmica de informação

- As falhas ocorrem apenas se um espião escolhe "fracasso", enquanto sucessos ocorrem quando toda a equipe coopera
- A informação revelada é binária (sucesso/fracasso), mas a causa é oculta
- Discussões entre jogadores funcionam como tentativas de inferência através de pistas comportamentais

### Padrões dedutivos

Os jogadores usam lógica dedutiva para identificar espiões através de: histórico de missões aprovadas/rejeitadas, padrões de votação, linguagem corporal, hesitações e consistência nas narrativas.

### Pontos de falha do sistema

- Espiões podem ser descobertos através de análise estatística de suas ações
- Padrões de fala e comportamento repetitivo expõem inconsistências
- Alianças identificáveis reduzem o espaço de possibilidades lógicas
- A memória coletiva dos eventos cria um histórico rastreável

## Jogos similares em mecânica

### Avalon

Evolução direta de The Resistance com mecânicas aprimoradas. Adiciona personagens especiais como Merlin e Assassino, permitindo diferentes níveis de informação assimétrica e criando dinâmicas mais complexas.

### Mafia / Werewolf

Progenitor da categoria de dedução social. Estrutura dia/noite onde a mafia mata à noite e a cidade vota durante o dia. Base para muitos jogos modernos de esconder identidades e identificar infiltrados.

### One Night Ultimate Werewolf

Versão condensada e rápida de Mafia com múltiplos papéis e ações noturnas simultâneas, mantendo o foco em leitura comportamental em sessões curtas.

### Two Rooms and a Boom

Mecânica de divisão de espaço físico onde dois times separados devem alcançar um objetivo, com comunicação limitada e papéis secretos que alteram objetivos individuais.

### Coup

Dedução social minimalista com eliminação de personagens e ações secretas. Foco em blefe e lógica dedutiva em rodadas rápidas, sem discussão prolongada.

### Secret Hitler

Incorpora votação secreta e discussão política. Liberais vs. Fascistas tentam identificar uns aos outros enquanto votam em propostas legislativas, combinando mecânicas de votação com traição oculta.

## Inspirações conceituais

### Psicologia social

- Teoria de Jogo: dinâmicas de cooperação vs. competição
- Lógica Proposicional: dedução através de premissas incompletas
- Teorema de Bayes: análise probabilística de identidades baseada em comportamento observado

### Literatura e cinema

- Motivos de espionagem (Le Carré, Fleming)
- Estruturas de mistério e investigação
- Dinâmicas de confiança e traição

### Teoria da informação

- Assimetria de conhecimento como core mechanic
- Comunicação imperfeita sob restrição
- Padrões estatísticos emergentes do comportamento


