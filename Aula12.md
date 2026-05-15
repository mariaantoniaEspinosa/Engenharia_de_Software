# Diagrama de Atividade
- Permite a modelação de fluxos e processos.
- UML
- elementos básicos:
  - **nó inicial** (ponto preto sólido)
  - **nó final** (ponto branco com ponto preto)
  - **ação** (quadrado com palavras descritivas - verbo)
  - **aresta/fluxo** (linha com uma seta)
  - **decisão** (formato de diamante em que entra uma seta e saí no minímo duas) - condição de guarda (o que faz eu decidir um ou outro; escolha de um caminho específico)
  - **intercalação** (junção de dois fluxos) (entram duas setas no diamante e saí uma)
  - **fork** - divergência (travessão com uma seta entrando e várias saindo) - dupla da join; representam o paralelismo; escolha de vários caminhos; fluxo só continua depois que tudo dentro dos travessões foi realizado.
  - **join** - convergência (travessão com várias setas entrando e uma saindo) - dupla da fork; representam o paralelismo; escolha de vários caminhos; fluxo só continua depois que tudo dentro dos travessões foi realizado.
  - **fim de fluxo** (bolinha branca com X) - encerramento de fluxo que impediu o objetivo final
  - **timer** (X com traços em cima e embaixo) - tempo de intervalo/limite para alguma ação.
  - **lane** (autor) - diz quem que faz determinada ação
  - **envio de mensagem** (post it triangular na ponta final)
  - **recebe mensagem** (post it com triangulo na ponta incial)
  - **processo** (flanelinha, outro diagrama inteiro abreviado)
- sempre é necessário sair de um ponto inicial e terminar em um ponto final
- não há mais de um ponto final ou inicial; só há ponto final duplo em diagramas feios.
## Exemplo de diagrama feito no Astah
### Prática Veículo
<img width="939" height="591" alt="image" src="https://github.com/user-attachments/assets/d1a90170-cecf-4eb4-9004-db9a904f9eaf" />

*Prova II: diagrama de (classe, de domínio), de caso de Uso, de Atividades, de Máquina*

# Diagrama de Estado de Máquina ou de Transição de Estados
- como um sistema se comporta quando um evento ocorre
- representa o ciclo de vida de um objeto
- exemplo: (criado->confirmado->enviado->entregue->finalizado)
- ajuda em falhas lógicas no sistema
- elementos de um diagrama de estados:
  - **estado inicial**
  - **estado final**
  - **estado**
  - **decisão**
  - **junção**
  - **transição** (gatilho/evento *obrigatório - guarda - ação)
  - estado (entry/ - do/ - exit/)
    - sub estado
  - decisão
  - junção
  - entry point
  - exit point
  - estado de histórico (não cai em prova)
  - fork - divisão
  - join - junção
## Exemplo de diagrama feito no Astah
### Prática Joguinho de Parkur
<img width="788" height="314" alt="image" src="https://github.com/user-attachments/assets/3e3fbe43-2562-479a-8fd2-aa411cfb95cb" />

