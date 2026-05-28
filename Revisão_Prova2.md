# DIAGRAMA DE ATIVIDADE
- diagrama comportamental -> fluxo de controle de uma atividade p/ outra
- descrições de ações passo-a-passo
- sequência controla temporal de ações -> fluxograma com suporte a paralelismp e sincronismo
- Atividade: descreve a implementação de um caso de uso
- Ação: passo individual dentro de uma atividade.
- serve para captura de trabalhos que vão ser executados quando uma operação específica do sistema é disparada (ação)
- serve para modelagem de fluxo de trabalho e processos
- elementos:
  - nó inicial: ponto de inicio
  - fluxo/aresta: sequencia de atividades
  - decisão: um fluxo de entrada e vários de saída com uma sentina ou guarda
  - intercalação: varios fluxos de entrada e uma unica saida
  - fork: duas ou mais atividades sao realizadas em paralelo
  - join: duas ou mais atividades se unem para realizar uma nova tarefa
  - nó final: término da modelagem
  - partições/swimlanes: quem realiza cada ação
  - sinais/flags: mensagens
  - final de fluxo: parte da atividade que termina, mas a modelagem prossegue
- ATENÇÃO:
  - *a cada nó branch deve corresponder a um ní merge*
  - *cada nó fork deve corresponder a um nó join*
  - só existe um nó inicial e um nó final
  - 
  <img width="939" height="591" alt="image" src="https://github.com/user-attachments/assets/3627818e-8731-495a-bf44-cef09a15ec3f" />

# DIAGRAMA DE MÁQUINA DE ESTADO
- diagrama comportamental -> descrebe como um sistema se comporta quando um evento ocorre
- estado que um objeto pode se encontrar dentro de uma execução dos processos de um sistema
- representar o ciclo de vida de um objeto
- modelar sistemas reativos
- ajuda na detecção de falhas lógicas
- documentar regras de negócio
- completa outros diagramas UML
- elementos:
  - estado simples: retangulo
  - estado inicial
  - estado final
  - transição: seta
    - trigger: sem isto, a transição não ocorre; dispara a transição de um estado para outro
    - condição de guarda: valor lógico que deve ser verdadeira para que a transição ocorra após o triger
    - action: atividade executada após a transição
  - Estado: entry/, do/, exit/.
  - decisão
  - junção: conecta transições
  - fork: divisão de uma transição em fluxos simultaneos
  - join: sincronização de multiplas transições concorrentes em um unico estado

-
<img width="788" height="314" alt="image" src="https://github.com/user-attachments/assets/9988c785-8f89-4638-aaa8-6d2da352827f" />

# MODELO DE CASO DE USO
- modelo de análise que representa um refinamento dos requisitos funcionais do sistema em desenvolvimento
- relacionamentos
  - comunicação: a qual caso e uso o ator está relacionado
  - inclusão: descreve cenários que são compartilhados entre diferentes casos de uso
  - extensão: modelar situações em que diferentes sequências de interações podem ser inseridas em um mesmo caso de uso
  - extensão: usado quando um comportamento eventual de um caso de uso tiver de ser descrito
  - generalização: dois ou mais casos de usos ou dois atores;
- Modelos de casos de uso: **DIAGRAMA DE CASO DE USO**
- representa cenários que o sistema interage com pessoas
- metas a atingir
- escopo do sistema
  - elementos:
    - balao: caso de uso
    - pessoa: ator
    - caixa: limite do sistema (cenário)
  - relações
    - associação: linha entre atoress e casos de uso
    - generalização: seta entre atores ou casos de uso
    - inclusão: sequencia de iterações obrigatorias entre casos de uso (seta traçada lado direito)
    - extensão: sequencia de iterações opcionais entre casos de uso (seta traçada lado esquerdo)
  - Usado para compelemnatr um caso de uso descrito em texto
  - representa metas de iterações entre sistemas e usuarios
  - define e organiza requisitps funcionais no sistema
  - modela o fluxo básico de eventos
 -
 <img width="926" height="622" alt="image" src="https://github.com/user-attachments/assets/c0ce1f5c-b04e-456c-8777-236f0c33096e" />
-
<img width="601" height="813" alt="image" src="https://github.com/user-attachments/assets/60f93438-7ca2-446a-8888-28b851da78c5" />

