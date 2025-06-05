# Atividade - Inteligência Artifical: Implementando Agente Inteligente com Máquina de Estados em Python

Este repositório contém um jogo de adivinhação em Python com uma interface interativa via terminal e visualização gráfica das tentativas do jogador. Realizei algumas melhorias no jogo como níveis de dificuldade; 
ajustes no gráfico e histórico de tentativas.

## Descrição

O programa escolhe aleatoriamente um número entre 1 e 100, e o jogador deve tentar adivinhar esse número. O jogo possui três níveis de dificuldade:

- **Fácil**: 7 tentativas  
- **Médio**: 5 tentativas  
- **Difícil**: 3 tentativas

Durante o jogo, dicas se o número é maior ou menor surgirão para o jogador e, ao final, o histórico de tentativas do jogador é armazenado e é exibido um gráfico com a evolução dos palpites em relação ao número 
secreto.

### Melhorias adicionadas por mim:
- Inclusão dos níveis de dificuldade (fácil, médio e difícil);
- Armazenamento e exibição do **histórico de tentativas**;
- Ajustes no gráfico para melhor visualização das tentativas e do número secreto.

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/lucasxavila/atividade-smartAgentStateMachine.git
3. Navegue até o diretório do projeto:
   ```bash
   cd atividade-smartAgentStateMachine
4. Instale as dependências necessárias:
   ```bash
   pip install matplotlib mplcursors
5. Execute o jogo:
   ```bash
   python jogo_adivinhacao.py
