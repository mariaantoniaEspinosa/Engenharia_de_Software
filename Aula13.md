# Diagrama de Classe - Orientado a Objetos
- Etapas de modelagem:
  - comunicação
  - planejamento
  - *modelagem*
  - construção
  - emprego
- Diagramas **Estáticos**: estrutural
- Diagramas **Dinâmicos**: comportamental
- O que é *Orientação a Objetos*? coleção de objetos distintos, que incorporam estrutura de dados e comportamento.
- O que são *Objetos*? elemento que representa uma entidade (abstrata ou concreta)
- Exemplo1: Classe **carro** -> Objeto **marca**
- Exemplo2: Classe **pessoa** -> Atributos **Nome**, **Peso**, **Altura** e **Idade** -> Objeto **Maria**, **60kg**, **1,60** e **20**
- Parte comportamental da Classe -> *Métodos* **get**, **set**
## Visibilidade dos Atributos e Métodos
- +Público
- #Protegido (usado para Herança)
- -Privado
  
<img width="591" height="166" alt="image" src="https://github.com/user-attachments/assets/d0037c40-d7e9-4f28-a47a-e966d84e527a" />

### OBS: Diagrama de Dominío
- Representação de um diagrama de classe, onde as classes são as mesmas da entidade-relacionamento
- nome da classe e seus atributos são o foco principal
### Representação do Diagrama de Classe

<img width="1212" height="188" alt="image" src="https://github.com/user-attachments/assets/0797b9d3-62f6-4783-8145-e5ba3cb54ebe" />

- Uma classe é composta por: atributos e operações
  - atributos: descrição dos dados armazenados pelos objetos de uma classe
  - operações: descrição das ações que os objetos de uma classe sabem realizar
- Exemplo:
  - superior: Nome da classe **ContaBancaria**
  - central: atributos (características) **número**, **saldo**...
  - inferior: Operações ou métodos (comportamentos/funções) **criar()**, **bloquear**, ...

<img width="1170" height="293" alt="image" src="https://github.com/user-attachments/assets/2ef42bfe-2833-4daa-b2ef-0d64cbcb8282" />
  
### Associações
  - representação de relacionamentos entre objetos durante a execução de um sistema, por uma linha reta

### Multiplicidade (cardinalidade)
  - representação da informação dos limites inferior e superior da quantidade de objetos aos quais outro objeto pode estar associado (cliente 1--------0..*Pedido)

### Participação
- Obrigatória: se tiver 1 na cardinalidade miníma, é obrigatório
- Opcional: se tiver 0 na cardinalidade miníma, é opcional  

### Nome de associação, direção de leitura e papéis

<img width="1015" height="286" alt="image" src="https://github.com/user-attachments/assets/ad1c82eb-52e5-4e72-bfcc-8396a50fb97f" />

## Classe Associativas

<img width="984" height="311" alt="image" src="https://github.com/user-attachments/assets/9867daa5-61b7-40cc-9311-3382253364f5" />

- linha tacejada representa a associação
- não se deve nomear a linha da associação
- pode participar de outros relacionamentos
- muitos pra muitos, onde tem que guardar informação

### Associação ternária
  - Define-se o grau de uma associação como a quantidade de classes envolvidas na mesma
### Associações reflexivas
  - autoassociação
  - uma autoassociação indica que um objeto de uma classe se associa com outros objetos da mesma classe.
### Agregação e composição
LER SLIDES 
### Restrições sobre associações
- subset: indica objetos conectados por uma associação

  <img width="744" height="345" alt="image" src="https://github.com/user-attachments/assets/98bc8322-213f-4bfa-bd4b-a177331d9455" />

- xor: duas ou mais classes ligadas, precisam ter associações com uma classe em comum

  <img width="644" height="328" alt="image" src="https://github.com/user-attachments/assets/8a57884d-6b54-46d7-8e06-588e97c4ceb0" />

### Generalização e especializações (herança)
- dadas duas classes A e B, se A é uma generalização de B, então B é uma especialização de A
- termos:
  - subclasse e superclasse;
  - supertipo e subtipo;
  - classe base e classe herdeira;
  - ancestral e descendente.

<img width="1261" height="253" alt="image" src="https://github.com/user-attachments/assets/b4625346-8f4d-4c7b-91ce-228110899813" />

- a herança é representada na UML por uma flecha partindo da subclasse em direção à superclasse
- características:
  - transitividade:indica que uma classe em uma hierarquia herda tanto propriedades e relacionamentos de sua superclasse imediata quanto de suas não imediatas
  - Assimetria: se A for uma generalização de B, então B não pode ser uma generalização de A

<img width="547" height="540" alt="image" src="https://github.com/user-attachments/assets/de529c82-db8c-40c0-b7c0-b2f921a7bb60" />

  

