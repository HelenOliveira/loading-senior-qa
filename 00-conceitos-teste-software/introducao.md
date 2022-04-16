# **Fundamentos de Teste**

## **1. O que é Teste de Software?** 

Os sistemas de software fazem parte da vida diária do ser humano. Com certeza em algum momento da vida, vários individuos precisaram de um software que teve um mal funcionamento. Um sistema com mal funcionamento pode acarretar em muitos problemas como perda de tempo, dinheiro e até a morte.
Segundo **ISTQB** (*Certified Tester Foundation Level Syllabus*) teste de software é uma forma de analisar a qualidade do software e reduzir riscos de 
falha do mesmo em uma operação.
Testar um software consiste não somente em executa lo mas também verificar e analisar os resultados. 

## **2. Por que o Teste de Software é necessário?** 

Todo software precisa ser testado, além de existirem requisitos e padroẽs como documentações específicas do setor, existem testes rigorosos de componentes e sistemas  que podem diminuir riscos e falhas durante a execução. 
Quando um  software é testado antes, é possível identificar  os riscos e falhas podendo reduzir os gastos e melhorar a qualidade do software.

## **3. Os sete princípios de teste.** 

Nos úlitmos 50 anos foram sugeridos princípios de testes oferecendo orientações gerais para todos os testes como:

**1. O teste mostra a mostra a presença de defeitos e não  a sua ausencia:** Mesmo com defeitos um software pode funcionar normalmente, enquanto o erro não for encontrado.

**2. Testes exaustivos são impossíveis:** É importante testar o trivial, em vez de testar tudo em todas as combinações, por causa dos riscos em afetar algum componente.

**3. O teste inicial economiza tempo e dinheiro:** Quanto mais cedo se inicia o teste melhor é, isto ajuda a reduzir as alterações custosas.

 **4. Defeitos se agrupam:** Normalmente um pequeno número de defeitos tendem a serem descobertos durante o pré lançamentos dos testes. São  entradas importantes em uma análise  o agrupamento de defeitos previstos  e o agrupamento de defeitos observados reais em teste de produção.

**5. Cuidado com o paradoxo de pesticida:** Os  mesmos testes sendo feitos repetidamente não encontrarão novos defeitos. Para encontrar novos defeitos é necessário serem alterados e serem gravados.

**6. O teste depende do contexto:** Para cada tipo de software é  feito testes diferentes. O mesmo teste pode ser usado de forma diferente em diferentes âmbitos.

 **7. Ausencia de erros é uma ilusão:** É impossível encontrar todos os defeitos  possíveis em um software, embora muitas organizações esperam isto dos testadores. Os principios 2 e 1 provam que isto é um erro.

## **4. Processos de teste.**

O conjunto de práticas  comuns que garantem a menor chance de atingirem seus objetivos é denominado processos de testes. Embora não exista uma fórmula universal para testar os softwares,  esse conjunto de práticas auxilia nas atividades de testes.

Alguns fatores contribuem para o processo de teste de uma organização:

   * Modelo de ciclo de vida
   * Níveis de testes e tipos 
   * Riscos de produtos e Projeto
   * Domínio do Negócio
   * Restrições Operacionais como:  escala de tempo, complexibilidade.
   * Práticas Organizacionais
   * Normas Internas e externas necessárias.

## **5. A psicologia do teste**

O desenvolvimento de software, e os testes de software é feita por humanos testando os softwares, e a pscologia humana auxilia de forma significativa nos testes de software.


### **Teste Durante o Ciclo de Vida de Desenvolvimento de Software:**

**1.Modelos de ciclo de vida de desenvolvimento de software.**

O cliclo de vida de um teste especifica todo trabalho feito em cada estágio do desenvolvimento do proejto de desenvolvimento de software.
Existem vários de ciclo de vida no desenvolvimento de um software e cada um aborda um tratamento diferente.

   **1.1 Dessenvolvimento de software e teste de software**

   Nessa parte é bom que o testador esteja acostumado com o modelos mais simples de ciclo de vida de desenvolvimento de software para que possam acontecer as atividades  apropriadas de testes.

   Existem várias caracteristicas para um bom teste:

   * Para cada atividade de desenvolvimento de  software há vários tipos de teste equivalentes.

   * Cada ponto do teste possui objetivos diferentes.

   * A análise e a modelagem de teste para um tipo de nível de teste começa no decorrer da atividade de desenvolvimento similar.

   * Para determinar e refinar  os requisitos e a modelagem dos testes os testadores discutem  e ficam envolvidos na revisão do produto.

   Os modelos de ciclo de vida de desenvolvimento de software mais comuns se dividem em duas categorias:    

   * **Modelos de desenvolvimento sequencial:** O modelo de ciclo de desenvolvimento de software  sequencial segue um fluxo de atividades sequencial e linear. Ou seja, uma fase do projeto só se inicia quando a outra tiver termninado  e pode levar muito tempo para serem entregues aos steakeholders e aos usuários.

   * **Modelos de desenolvimento iterativo e incremental:** Já no teste interativo ocorre divididos em grupos, construídos e testados juntos por ciclos e podem incluir iterações anteriores e possuem duração fixa.

   **1.2 Modelos de ciclos de vida de desenvolvimento de software em contexto**
    
   Modelos de ciclo de vida de desenvolvimento de software são baseados de acordo com a necessidade do projeto e do produto, adapatando com base na meta para o projeto. Conforme o contexto do projeto pode ser essencial que  seja reorganizado os níveis ou as atividades de teste.
   A razão pela qual os modelos de desenvolvimento de software devem ser reogarnizados ou adaptados ao contexto das caracteristicas do projeto e do produto devem ser:

   * Sistema com diferentes riscos de produto.
   * Um progama que contenha muitas unidades de negócios que fazem parte de um mesmo projeto
   * Tempo curto para entrega do produto ao mercado


**2.Níveis de Teste.**

Cada nível de teste é uma categoria do processo de teste que consiste nas atividades e são gerenciados juntos. Desde  os teste de componentes até outras atividades dentro do ciclo de vida de desenvoliemnto de software. 
As características em comum dos testes são:

   * Objetivos especificos
   * Base de teste
   * Objetos de testes
   * Defeitos e falhas típicas
   * Abordagens e responsabilidades

O necessário para cada nível de teste é que se tenha o um ambiente apropriado.

   * **Teste de componente:** 

   **Objetivos:** 
   * Reduzir riscos
   * Averiguar o comportamento funcional ou não funcional.
   * Verificar e  achar defeitos nos componentes.
   * Evitar que os defeitos se espalhem. 

   **Base de teste:**

   * Projeto detalhado
   * Código
   * Especificações de componentes 


   **Objetos de teste**

   * Componentes, unidades ou módulos
   * Estruturas de código e dados
   * Classes
   * Módulos de de banco de dados

   **Defeitos e falhas:**

   * Problemas no fluxo de dados
   * Códigos e lógica incorretos
   * Funcionalidade incorreta 


**Abordagens e responsabilidades**

Normalmente o código de componente é executado pelo desenvolvedor criador do código. 
 

   * **Teste de integração:** 

**Objetivos:**

* Reduzir risco
* Averiguar se os comportamentos funcionais e não funcionais das interfaces 
* Produzir confiança na qualidade das interfaces
* Achar  defeitos que indicam que estejam na interface
* Evitar que os defeitos espalhem para níveis mais altos de teste. 

**Base de teste**

* Software e modelagem do sistema
* Diagramas de sequência
* Especificações de interface e protocolo de comunicação
* Casos de uso
* Arquitetura no nível de componente ou sistema
* Fluxos de trabalho;
* Definições de interface externa 

**Objetos de teste**

* Subsistemas
* Banco de dados
* Infraestrutura
* Interface
* APIs
* Micros serviços


**Defeitos e falhas típicas**

* Dados incorretos
* Sequenciamento ou temporização incorretos de chamadas de interface
* Incompatibilidade de interface
* Falhas na comunicação entre componentes
* Falha de comunicação não manipulada ou tratada de forma errada entre componentes
* Suposições incorretas sobre o significado, as unidades ou limites dos dados que estão sendo transmitidos entre os componentes.


**Abordagens e responsabilidades**

Os testes de integração de componentes e os testes de integração de sistemas devem ser focalizados na própria integração. Normalmente os teste de integração de componentes é responsabilidade do desenvolvedor e o teste de integração dos sistema ficam incubidos aos testadores.


 * **Teste de sistema:** 

 **Objetivos:**
   
   * Reduzir riscos
   * Averiguar o comportamento funcional ou não funcional
   * Validar se o sistema esta completo
   * Desenvolver confiança na aqualidade do sistema como um todo
   * Achar defeitos 

**Base de teste:**

* Especificações de requisitos de sistema e software
* Relatórios de análise de risco
* Casos de uso
* Épicos e histórias de usuários
* Modelos de comportamento do sistema
* Diagramas de estado;
* Sistema e manuais do usuário 

**Objetos de teste**
* Aplicações
* Sistemas de hardware e software
* Sistemas operacionais
* Sistemas sob teste
* Configuração do sistema e dados de configuração

**Defeitos e falhas típicas:** 

* Cálculos incorretos;
* Comportamento funcional ou não funcional do sistema incorreto ou inesperado
* Controle ou fluxos de dados dentro do sistema incorretos
* Falha na execução correta e completa de tarefas funcionais de ponta a ponta /n
* Falha na execução do sistema
* Falha no funicinamento descrito nos manuais do sistema e usuário

**Abordagens e responsabilidades**

O teste do sistema se concentra no comportamento geral do sistema como um todo. Normalmente fica na responsabilidade dos testadores independentes fazer os testes no sistema.

   * **Teste de aceite:** 

 **Objetivos:**

   * Criar confiança na qualidade do sistema
   * Validar o sistema completo


**Base de teste**

* Processos de negócios;
* Requisitos do usuário ou de negócios;
* Regulamentos, contratos legais e normas;
* Casos de uso;
* Requisitos de sistema;
* Documentação do sistema ou usuário;
* Procedimentos de instalação;
* Relatórios de análise de risco.


**Defeitos e falhas típicas**

* Fluxos de trabalho do sistema não atendem aos requisitos do negócio ou do usuário;
* Regras de negócios não são implementadas corretamente;
* O sistema não atende os requisitos contratuais ou regulatórios;
* Falhas não funcionais, como vulnerabilidades de segurança, eficiência de performance inadequada sob altas cargas ou operação inadequada em uma plataforma suportada.

**Abordagens e responsabilidades**

Normalmente os testes de aceite são efetuados pelos clientes, usuário de negócios, proprietários do produto ou operadores de um sistema assim como stakeholders podem esta no projeto.



**3. Tipos de Teste.**

Os testes podem ser divididos da seguinte forma:

Funcionais e não  funcionais:
   * **Funcionais:**  testes funcionais examinam  as especificações de requisitos, épicos, história de usuários, especificações, ou seja o que o sistema deve fazer. Com o teste funcional pode se observar o comportamento do software.

   * **Não funcionais:**  testes não funcionais examinam as caracteristicas do software, como a usabilidade, a perfomace e a segurança. Testes não funcionais ajudam a avaliar o quao bom o sistema está. Ele pode ser usado em todos os níveis de teste.

   * **Testes caixa-branca:**: teste caixa-branca verifica a parte interna do software, como códigos, arquitetura, fluxos de trabalho e fluxos de dados. Sua eficácia pode ser medida pela cobertura estrutural que é a extensão em  algum tipo de elemento estrutural. Para seu uso é necessário possuir habilidades mais avançadas, 'observando como o código foi construido.


**4. Teste de manutenção.**

Depois de todo processo de implatação do sistema, o software precisa ser mantido, pois no momento de entrega do sistema, são encontrados muitos erros pelo usuário. Nesse período é onde os defeitos apareceram e as mudanças são necessárias para manter a melhoria de qualidade do software. Os testes de manutenção precisam ser realizados para qualificar o funcionamento do software e garantir o seu sucesso com as alterações feitas.

No teste de manutenção, podem ser usado vários escopos e eles dependem do:
   * Nível de risco da mudança e o quanto isso  afeta o sistema e não atingi os outros componentes.
   * Dimensão  do sistema
   * Grandeza da mudança


**Teste estático**

**1. Noções básicas sobre testes estáticos.**
Ao contrário do teste dinãmico, os testes estáticos por sua vez depende da execução do software a ser testado. Ele necessita do exame manual dos produtos de trabalho, ou seja, as revisões ou da análise feita por ferramentas de códigos. A análise estática tem se tornado muito significativa para os sistemas críticos de segurança. E está sendo usada em muitos sistemas automatizados.
E seu benefício é que quando usado no início de ciclo de vida do desenvolvimento de software, possibilita a detecção prévia dos defeitos. 


**2. Processo de revisão**

Este processos pode ser dividido em dois tipos: formal e informal. 
* **Informais:** tem como característica por não preservar um processo estabelecido e não ser documentado.
* **Formais:**  tem como característica a participação da equipe, processos são documentados e esta relacionado a causas como modelo de ciclo de vida do desenvolvimento do software.

O processo de revisão pode ser dividido em etapas, são elas:

   * Planejamento
   * Revisão individual
   * Analisar e comunicar
   * Corrigir e reportar

Os resultados da revisão podem sofrer alterações depedendendo de sua formalidade.


**Técnicas de Teste**

**1. Categorias de técnicas de teste**

A técnica de teste tem como objetivo auxiliar na identificação das condições de teste, os casos e os dados dos testes. Na escolha da técnica, pode depender de alguns fatores como:

* Dificuldade do componente ou do sistema;
* Normas regulatórias;
* Quesitos contratuais ou do cliente;
* Grau  e tipos de risco;
* Documentação disponível;
* Conhecimento e habilidades do testador;
* Ferramentas disponíveis;
* Tempo e orçamento;
* Modelo de ciclo de vida de desenvolvimento de software.
* Tipos de defeitos esperados no componente ou sistema

Das técnicas citadas algumas são usadas em todos os níveis do teste, outras são aplicadas em alguns níveis.
A usabilidade das técnicas podem variar entre formal e  muito informal, isso irá depender circunstância e maturidade dos processos de teste.


**2. Técnicas de teste caixa preta**

Particionamento ou equivalência:

Nesta técnica divide se os dados em partições que são comumentes chamadas de classes de equivalência, de forma que todos os membros de uma certa partição deve ser processado da mesma forma. Há  partições de equivalência para valores válidos e não válidos e são elas:

 * **Valores válidos:** que devem ser aceitos pelo componente ou sistema.
 * **Valores invalidos:** que  devem ser rejeitados pelo componente ou sistema.

Para cobertura 100% dessa técnica, os casos de teste teem que cobrir as partiçoes identificadsas, inclusive as não válidas, utilizando o mínimo de cada valor das partições. A forma de  medir sua cobertura é o número de partições de equivalência testatas dividida pelo numero e partições de equivalência identificadas, expresso por porcentagem.


**Analise de valor e limite:**

A análise de valor de limite é uma amplificação do particionamento de equivalência, porém ela só pode ser utilizada se a partição é ordenada, contendo dados númericos ou sequenciais.
Vale lembrar que o comportamento nos limites das partições de equivalência é mais provável que seja incorreto do que o comportamento dentro das partições. 

Sua cobertura pode ser medida pelo número de valores limeites testados dividido pelo número total de valores de teste.


**Teste de tabela de decisão:**

Para testar a implementação de requisitos do sistema são utilizados técnicas combinatórias. Ao criar tabelas de decisão o testador.  Uma boa maneira de registrar regras de negócio complexas são as tabelas de decisão. Criando as tabelas de decisão o testador consegue identificar as entradas e saídas do sistema.
E os valores apresentados normalmente são  boleanos ou seja, 0 ou 1.

Notações mais usadas na tabela de decisão:
Para decisões:

"S"  quando a condição for verdadeira 
"N" quando a condição for falsa
"-"  quando o valor da transição não importa.

Para ações:

"X" quando ação deve ocorrer.
Em branco quando a ação não deve ocorrer. 

A tabela de transição auxilia na identificação de todas as combinações importantes.
 

**Teste de transição de estado:**

Dependendo das condições atuais ou histórico dos componentes ou do sistema eles podem responder de maneira diferente.
Através de um diagrama pode se observar a forma como se encontra  o estado do software.
Quando iniciada essa transição por um evento esse evento gera a transição e essa mudança de estado pode fazer o software executar uma ação.
Todas as transições válidas e inválidas entre estados assim como os eventos, condições de proteção e as ações resultantes para transições válidas.

Os testes de transição são comumentes usados em  software que possuem menus, como indústrias de prateleira de software.
Sua cobertura normalmente é  medida pelo número de estados  identificados, dividido pelo número de de transições identificados pelo estado de teste.

**Teste de caso de uso:**

Uma maneira específica que podem projetar interações com itens de software pode ser derivada de casos de uso.
O caso de uso está ligado a atores que são representados pelos usuários, humanos, hardware, componentes do sistema,  dentre outros.
Pode se descrever o caso de uso como interações e atividades assim como condições prévias  e pós condições linguagen natural quando adequado.
Um caso de uso pode sofrer alterações em em seu comportamento básico,incluindo o comportamento excepcionalmente no tratamento de erros.
Pode se medir sua cobertura em porcentagem.

**3.Técnicas de teste caixa-branca.**

Na estrutura interna do objeto de teste é funfadamentado o teste caixa-branca.Este teste pode ser utilizado em todos os níveis de testes, porém duas técnicas avançadas  referentes a código que são muito utillizadas no nível de teste de componentes,  e são elas:
   * **Teste de cobertura de instruções:** Onde as intruções executávies do código são testada. Para medir a cobertura é necessário dividir o numero de intruções executadas pelo testes pelo numero total de instruções executáveis existentes. 
   * **Teste de decisão e cobeertura:** Onde se testa as decisões existentes no código e o código executado com base nos resultados. Para calcular a cobertura é dividir o número de resultados de decisão pelo numero total de resultados de decisão no objeto de teste.

**4. Técnicas de teste baseado na experiência.**

Técnicas de expriência são fundamentadas na intuição do testador. Também são udados aplicativos e sistemas conhecidos do testador. O testador ao utilizar essas técnicas podem melhorar a eficiência do sistema e auxliar na detecção dos defeitos previamente.

As técnicas mais comuns usadas são:
* **Suposição de erro:** usada como prevenção de erros, falhas e defeitos com base no conhecimento do testador inclui:
   * Como aplicativo funcionou antes
   * Quais erros tendem acontecer
   * Erros ocorridos em outros aplicativos
   
* **Teste exploratório:** No teste exploratŕio são usados testes informais  modelados dinamicamente e o resultados destes testes são utiizados para executar testes em outras áreas.
Esse teste é muito válido para quando existem poucas ou inadequadas especificações ou pressão de tempo significativa nos testes além ser útil para completar outras técnicas de testes formais.

* **Teste Baseado em checklist:** Neste teste é feito uma listagem onde os testadores modelam, implementam e executam testes implementados em lista. Esse cheklist é produzido como base na experiência e conhecimento para a avaliar o que é  mais importante para o usuário.
Eles podem ser gerados para dar suporte a vários tipos de testes, inclusive os funcionais e os não funcionais.

**5. Gerenciamento de teste**

Consiste em gerenciar os defeitos de teste. Relatório de defeitos de teste, critérios de entrada e saída de teste, risco do produto e do projeto.Baseado em risco, abordagem e controle do teste,estimativa e estratégia do teste, monitoramento do teste, plano e planejamento do teste.Relatório de progresso e de resumo do teste. Testador.

Organização do teste

 * **Teste independente** *:  Em teste independente normalmente pode ser testado por pessoas em papeis diferentes como por exemplo o cliente.  Em alguns casos o grau de independencia, o testator geralmente se torna mais eficaz em encontrar erros, isto devido a diferenças entre autor e testador.

 Pode se classsificar os graus de independência nos testes como baixo nivel e alto nível de independência

   * Quando não se tem testadores a unica forma de teste são os prórios testadores.
   * Desenvolvedores independentes e testadores fazendo os testes dos produtos da própria equipe.
   * A equipe de teste idenpendentes que fazem parte do mesma organização inputando ao gerenciamento de projetos.
   * Testadores independentes da organização empresarial ou da comunidade de usuários ou especializados em tipos de testes específicos, como usabilidade.segurança,    performance, regulamentação, conformidade ou portabilidade.
   * Testadores independentes que não fazem parte da organização.

Geralmente, para a maioria dos projetos é melhor se ter vários níveis de teste com alguns desses níveis gerenciados por testadores independentes. Para exercer maior controle sobre a qualidade de seu próprio trabalho, os desenvolvedores precisam participar dos testes.

A independência dos testes varia de acordo como eles são implementados, depedendo do modelo de ciclo de vida de desenvolviemento de software. Algumas organizações utilizam métodos agéis para  e seus testadores podem fazer parte de uma equipe de desenvolviemento. E em alguns casos pode se usar testes de aceite para validar as histŕias de usuários ao final de cada iteração.

**Vantagens da independência do teste incluem:**

   * Provavelmente os testadores independentes reconhecerão diferentes tipos de falhas se comparado aos desenvolvedores, isto se dá por diferentes históricos, técnicas e vieses.
   * Durante a especificação e a implementação do sistema, um testador inpedendente pode averiguar, desafiar ou contestar as suposições feitas pelos _stakeholders_.
   * O isolamento da equipe de desenvolvimento pode acarretar em atrasos no fornecimento de feedback para equipe de desenvolvimento.
   * O senso de resposabilidade pela qualidade pode ser perdida pelos desenvolvedores.
   * Testadores independentes podem ser visto como impecílio ou culpados por atrasos na liberação.
   * Testadores independente podem não possuir informações importantes como por exemplo o objeto de teste.

Os beneficios da indepedência do teste em muitas organizações são alcançadas com sucesso evitando todas desvantgens.

## **5.1 Funções de um gerente de teste e do testador**

Os testadores e os gerentes de teste são dois papeis cobertos neste syllabus e suas tarefas desenvolvidas por estes dois papeis dependem doo cenário do projetoe do produto, assim como as aptidoes das pessoas em suas organizações.

A liderança das atividades bem sucedidas de testes e o processo geral de teste são de responsabilidade do gerente de teste.

Tarefas comuns de gerente de de teste são:

   * Criar ou revisar um coneito de teste e um metodo de teste para organização.
   * Projetar as tarefas considerando o contexto e entendendo os objetivos e riscos do teste. Pode ser incluído abordagens de teste, o tempo, o esforço, o custo, aquisição de recursos, o planejamento e o conceito de níveis e ciclos de testes.
   * Escrever e atualizar os planos de testes.
   * Organizar os planos de teste com outras tarefas do projeto, como   planejamento da integração.
   * Dar início a analise do projeto e a implementação e a execução dos testes, supervisionando os resultados alcançados, observando o status dos critérios de saída.
   * Com base nas informações coletadas, preparar e entregar os relatórios de progresso do tese e resumo.
   * Para o controle de testes, juntar as ações importantes, adaptando como base nos resultados e no progresso.
   * suporte para ajustar o sistema de gerenciamento de defeitos e o gerenciamento de ajuste adequado do testware.
   * Para medir o progresso do teste e avaliar a qualidade do teste e do produto adotar métricas adequadas.
   Decidir sobre a implementação dos ambientes de testes.
   * Dentro da organização promover e defender os tatadores, a equipe e a profissão.
   * Ampliar as  competências e carreiras dos testadores (Treinamentos).
O ciclo de vida de desenvolvimento de software varia de acordo com jeito que a função  de gerente de teste é  feito. Um exemplo, no desenvolvimento ágil algumas incumbências citadas acima são tratados pela equipe Ágil da organização, principalmente aquelas  relacionadas ao teste diário realizado dentro da equipe. Normalmente o testador faz parte da equipe. 

 Quando algumas tarefas envolvem mais equipes ou envolve toda a  organização, podem ser testados por gerentes de teste  de fora da equipe de desenvolvimento. Para maiores informações de como gerenciar uma equipe de teste veja black (2009). 

Tarefas comuns de um testador: 

   * Revisar e colaborar para os planos de teste.
   * Examinar, revisar e  analisar os quesitos, as histárias de usuários e os critérios de aceite, as especificações e modelos da testabiliadade.
   * Reconhecer e documentar as condições de teste e capturar a restreabilidade entre os casos de teste, as conidções de teste e a base de teste.
   * Arquitetar, ajustar e verificar os ambientes de teste.
   * Arquitetar e implementar e casos de teste e procedimentos de teste.
   * Fazer e obter dados de teste.
   *  Realizar os testes, analisar os resultados e documentar os desvios dos resultados esperados.
   * Utilizar ferramentas compatíveis para simplificar o prcesso de teste.
   * Automatizar os testes de acordo com a necessidade.
   * Analisar as especificações não funcionais, como eficiência de performance, confiança, usabilidade, segurança, compatibilidade e portabilidade.
   * Revisar os testes desenvovidos por outros.

A pessoa que pode ser especialista nessas funções normalmente  trabalham em analise de teste, projeto de teste, automação de testes. Pessoas diferentes   podem exercer o papel de testador em níveis  de testes diferentes níveis de testes, dependendo dos riscos relacionados ao produto e ao projeto e o modelo de ciclo de vida de desenvolvimento do software. 

## **5.2 Planejamento e estimativa de testes**

**5.2.1 Objetivo e conteúdo de um plano de teste**

A politica de teste e a estratégia de teste da organização influenciam o planejamento por seus ciclos de vida e métodos de desenvolvimento utilizados pelos escopo dos teses, objetivos, riscos retrições, criticidae,testablilidade e dsiponibilidade dos recuros.

Mais informações e ficam a dispoção conforme o andamento do projeto e do planejamento do teste, além de mais detalhes que podem ser incluídos no plano de teste. O planejamento de teste é uma tarefa contínua e é feito durante todo o ciclo de vida do produto. O feedback das tarefas e teste deve ser utilizado para reconhecer a alteração de reiscos para que o planejamento seja acertado.

É possível que o planejamento seja documentado em plano de teste principal e em palneos de tese separados para cada nível de teste, como testes de sistema e teses de aceite ou para cada tipo de teste como teste de usablidade e teste de perfomance.

A tarefas de planejamento do teste  podem ser documentadas em um  plano de tese e englobam:

   * Definri o escopo, os obejtivo e os riscos do teste.
   * Determinar a abordagem geral do teste.
   * Agregar e coordenar as tarefas de teste nas atividades do ciclo de vida do software.
   * Decidir o que testar, pessoas e outros recursos fundamentais para realizar várias tarefas de teste e como elas serão realizadas.
   * Planejar as tarefas de análise,projeto implementação, execução e avaliação de testes, em datas específicas.
   * Escolher as métricas para monitoramento e controle dos testes
   * Orçar as atividades do teste.
   * Apontar o nível de detalhes e a estrutura da documentação de teste.

O material dos planos de teste varia e pode se estender além dos tópicos mostrados acima e pode ser encontrado no padrão [ISO29119-3].

**5.2.2 Estratégia de teste e abordagem de teste**

Uma estratégia de teste oferece uma definição geral do processo de teste, mais comum no nível do produto ou organizacional. Categorias comuns de estratégias de teste incluem:

* **Análitica:** tal qualidade de estratégia de teste é embasado em uma análise de algum fator, como por exemplo exigencia ou risco. O testes por exemplo são projetados e priorizados com base no nível de risco.

* **Baseada em modelo:** este tipo de estratégia de teste é baseado em algum modelo de teste de alguma caracteristica  do produto, como uma função, um preocesso empresarial, uma estrutura  interna ou um atributo não funcional, como exemplo a confiabilidade.

* **Metódica:** tal qualidade de estratégia de teste precisa do uso sistemático de um conjunto determinados de testes  ou condições de testes, como uma classificação de tipos básicos ou de possíveis falhas, uma lista de aspectos importantes, ou padrões de aparência e comportamento de aplicativos móveis ou páginas da web da empresa.

* **Compátivel como processo:** Baseado em regras e padrões externos, este tipo de estratégia de testes envolve análise e implementação do teste, como alguns que são definidos por padrões específicos do setor, pela documentção do processo, pela identificação e uso da base de teste, por qualquer processo ou padrão colocado pela empresa.

* **Dirigida:** é orientado principalmente pelo aconselhamento, orientação ou instrução dos *stakeholders*,especialistas no domínio do negócio ou escpecialista em tecnolgia tal estratégia de teste. Eles podem ou não esta fora da equipe de teste ou fora da própria empresa.

* **Contra Regressão:** é estimulado pelo desejo de evitar a regressão de recursos exstentes esse tipo de estratégia. Ainda inclui a reutilização extensiva de testes de regressão e de conjuntos de teste tal estratégia de testes.

* **Reativa:** O teste é reativo ao componente ou ao sistema que esta sendo testado  e aos acontecimentos que ocorrem durante a execução do teste. Os testes ocorrem durante a execução. Os testes podem ser planejados e feitos imediatamente executados em resposta ao conhecimento adquirido em resultados de testes anteriores. O texte exploratórios, se complementando e podendo alcançar  testes mais eficazes quando usados juntos.

Uma estratégia de teste adequadaconstantemente criada pela combinação de vários dessas qualidades de estratégias de teste. Como exemplo: testes baseados em risco, podem ser combinados com testes exploratários, se complementados podem alcançar testes mais eficientes quando  utilizados juntos.

Apesar da estratégia de teste fornecer uma definição geral do processo de teste. a abordagem de teste familiariza a estratégia de teste para um projeto ou lançamento específico. O ponto de partida para selecionar as técnicas de teste. os níveis de teste e os tipos de teste, e para definir os critérios de entrada e saída é a abordagem de teste.  A abordagem escolhida depende da circunstancia e pode considerar fatores como riscos, segurança, recursos e habilidades disponíveis, tecnologia,natureza do sistema, obejtivos de teste e regulamentos.

**5.2.3 Critérios de entrada e saída (definição de "pronto" e "feito"**

Para se ter o controle eficaz sobre a qualidade do software e dos testes é aconselhável ter parametros que definam quando uma determinada atividade de teste deve começar e quando a atividade termina. Os parametros de entrada que são chamados de "pronto" no desenvolvimento ágil, determinam condições prévias para realização de uma determinada atividade de teste. Se os parametros de entrada não forem feitos, é possível que a atividade se mostre mais difçil, mais lenta, custo mais alto e mais ariscada. Os parametros de saída, chamados de "feito" no desenvolvimento ágil, determinam quais as condições devem ser obtidasde para informar que um nével de teste ou um conjunto de testes foram feitos. Os parâmetros de entrada e saída devem ser estabelecidos para cada nível e qualidade de teste e serão diferentes com base nos objetivos do teste.

Parâmetros típicos de entrada incluem:

   

FONTE: https://bstqb.org.br/b9/doc/syllabus_ctfl_2018br.pdf 

