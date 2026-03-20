# Revisão última aula
## Desenvolvimento Ágil
- Prescritivos: seguem-se as etapas e o produto só é visto no final.
- Ágil: etapas são revistas durante o processo havendo mudanças; redução na quantidade de artefatos gerados; etepas são achatadas;
- *Artefato*: algum documento, ou executável de software.
- Extreme programming;
- TDD: construção de testes de software (1), protótipo/cód. (2), refatoração (3);
- Scrum: scrum master, p.o, dev team;
- 
  <img width="320" height="320" alt="image" src="https://github.com/user-attachments/assets/451452a2-d7d8-47ad-8dfa-0794020db750" />

# Aula 05

## Método de Desenvolvimento de Sistemas Dinâmicos 

- software ágil que “oferece uma metodologia para construir e manter sistemas que atendem restrições de prazo apertado através do uso da prototipagem incremental em um ambiente de projeto controlado.
- Ciclo de vida DSDM:
- <img width="601" height="466" alt="image" src="https://github.com/user-attachments/assets/152f578d-f619-4577-b6f1-eb8a042f8cc1" />

- Estudo da viabilidade: estabelece os requisitos básicos de negócio e restrições associados à aplicação a ser construída 
- Estudo do negócio: estabelece os requisitos funcionais e de informação que permitirão à aplicação agregar valor de negócio
- Iteração de modelos funcionais:  produz um conjunto de protótipos incrementais que demonstram funcionalidade para o cliente
- Iteração de projeto e desenvolvimento: revisita protótipos desenvolvidos durante a iteração de modelos funcionais para assegurar-se de que cada um tenha passado por um processo de engenharia para capacitá-los a oferecer, aos usuários finais, valor de negócio em termos operacionais
- Implementação:  aloca a última versão do incremento de software no ambiente operacional.

## FDD - Feature Drivem Development

- <img width="873" height="405" alt="image" src="https://github.com/user-attachments/assets/8133d4ca-b0fe-4341-b874-f477b33a3b9a" />
-  funcionalidade é uma função valorizada pelo cliente passível de ser implementada em duas semanas ou menos.
-  As funcionalidades podem ser organizadas em um agrupamento hierárquico relacionado com o negócio.
-  uma funcionalidade é o incremento de software do FDD que pode ser entregue
-  o bloco de funcionalidades ser pequeno, seus projeto e representações de código são mais fáceis de inspecionar efetivamente.
-  O planejamento, cronograma e acompanhamento do projeto são guiados pela hierarquia de funcionalidades
-  requisito: <ação> o <resultado> <por|para quem| de | para que> um <objeto>

## DevOps
- <img width="601" height="398" alt="image" src="https://github.com/user-attachments/assets/8b9c66a7-c100-4154-82c5-ea5b80cef129" />
- mais recente metodologia.
- divide o desenvolvimeto do produto em duas parcelas iguais, esquerda: desenvolvimento, direita: operações.
- aplica os princípios do desenvolvimento ágil e do enxuto a toda a cadeia logística de software.
- 
- Plan: definido os objetivos do negócio, os requisitos do projeto e as funcionalidades a serem desenvolvidas
- Build: código-fonte escrito é compilado e empacotado em um artefato executável (um "build")
- Code: Os desenvolvedores escrevem o código-fonte da aplicação com base no que foi planejado
- Test: série de testes automatizados (testes unitários, de integração, de desempenho, etc.) para garantir a qualidade e identificar falhas o mais cedo possível
- Release: o artefato é preparado e versionado para a implantação
- Deploy: pacote da nova versão é implantado (instalado) no ambiente de produção
- Operate:equipe de operações gerencia a infraestrutura e garante que o software funcione de maneira estável e eficiente para o usuário final
- Monitor:  aplicação e a infraestrutura são monitoradas continuamente para coletar dados sobre desempenho, uso e possíveis erros

## Kanban
- todas as metodologias usam KanBan como quadro de controle de tarefas
- <img width="823" height="425" alt="image" src="https://github.com/user-attachments/assets/49b61acc-911f-4d75-8c53-680709f72b74" />
- técnica visual usada para gerenciar fluxos de trabalho e tarefas em processos de desenvolvimento
- Backlog: Representa o trabalho que ainda está aguardando para ser iniciado
- Workflow:  é dividido em colunas que representam diferentes estágios do processo, como "Análise", "Desenvolvimento", "Testes", e "Feito
- WIP: Limita o número de tarefas que podem estar em progresso em cada estágio
- Faixa Urgente: área especial no quadro para priorizar tarefas
- Cartões de Tarefas: Cada tarefa é representada por um cartão que se move através das colunas do quadro conforme seu progresso.
