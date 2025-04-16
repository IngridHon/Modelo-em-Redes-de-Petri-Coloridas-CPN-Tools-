# Modelo-em-Redes-de-Petri-Coloridas-CPN-Tools-
# Projeto SED - Modelo em Redes de Petri Coloridas (CPN Tools)

Este repositório contém um modelo de simulação desenvolvido em **CPN Tools**, utilizando **Redes de Petri Coloridas (Colored Petri Nets)**, como parte do Projeto SED (Sistema Embarcado Digital).

## Objetivo

O objetivo deste projeto é modelar e simular o comportamento de um sistema digital embarcado com diferentes prioridades de eventos, utilizando a formalização das redes de Petri para análise de desempenho, concorrência e controle de fluxo.

## Ferramentas Utilizadas

- **CPN Tools 4.0.1**: ambiente gráfico para modelagem e simulação de redes de Petri coloridas.
- **CPN ML**: linguagem baseada em Standard ML usada para definir funções, variáveis e comportamentos dentro do modelo.

## Estrutura do Projeto

O arquivo principal do projeto é:

- `ProjetoSED_Final.cpn`: modelo em XML exportado pelo CPN Tools.

### Elementos Importantes

- **Prioridades definidas**:
  - `P_HIGH = 100`
  - `P_NORMAL = 1000`
  - `P_LOW = 10000`
  
- **Tipos de cores (colsets)** definidos:
  - `unit` (sem dados)
  - `bool` (booleano)

- **Múltiplos blocos e transições** que compõem o sistema modelado.

## Como Abrir e Executar

1. Instale o [CPN Tools](http://cpntools.org/download).
2. Abra o programa e carregue o arquivo `ProjetoSED_Final.cpn`.
3. Clique com o botão direito nas transições e selecione **Run** para simular.
4. Utilize os monitores e breakpoints, se necessário, para analisar o comportamento do sistema.

## Referências

- [Site Oficial do CPN Tools](http://cpntools.org)
- [Colored Petri Nets: Theory and Practice](https://cs.au.dk/~cpnbook/)

---
Autor: Ingrid Honório da Silva - 119210830 Guilherme Santos da Silveira - 124212387

---- Vídeo de demonstração no youtube
---

> Projeto desenvolvido como parte das atividades da disciplina/projeto de Sistemas Embarcados Digitais.

