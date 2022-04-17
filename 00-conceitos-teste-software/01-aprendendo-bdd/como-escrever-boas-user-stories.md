**Como escrever boas user stories** 

**O que é BDD?**

O BDD (*behaviour driven development*) é uma técnica é uma muito usada no desenvolvimento ágil que se originou do TDD (*Test Driven Development*), ela foi criada com intenção de estimular os membros da equipe entre si. A sua função é descrever o comportamento do programa que será produzido. 

Tal estimulo não esta presente somente no BDD mas também em outros métodos ágeis como SCRUM por exemplo. 

Independentemente do tipo de programa que será feito como desktop, apps, móbile e web,  essa técnica pode ser utilizada. 

Existe a colaboração de especialistas várias áreas: qa’s (testadores), *product owners* (gerente de produto) *business analysts* (analistas de negócios ao definir o comportamento do programa que será produzido. Tal colaboração é entendia como *Three* amigos. Tal associação não esta presente somente no BDD mas também em outros métodos ágeis como SCRUM por exemplo. 

No momento de testar o software o foco esta em testa lo sob o ponto de vista do seu comportamento, ou seja, ao desenvolver casos de teste o alvo é no comportamento do software de forma mais vasta, ao contrário do que se faz nos teste de software clássico. 

Lembrando que o BDD não é somente uma técnica par automatizar testes mas sim para uma Técnica de desenvolvimento que auxilia na construção  melhores testes. 

Portanto ao se os testes forem escritos somente após o software estar pronto, o BDD não está sendo aplicado de forma correta, pois os testes não estão sendo conduzindo o desenvolvimento. 

Desse modo de realizar testes, também é plausível que exerçam o fluxo inteiro em certa função (*end to end testing*) e não somente uma função específica. 

**Por que usar BDD?**

Ao utilizar BDD auxilia a qualidade do produto de uma forma genérica pois estimula a cooperação da equipe desde o principio, permitindo o alinhamento desde o inicio. 

É importante detalhar o funcionamento do software nesse modelo pois várias ferramentas de teste são eficazes para executar esses eventos de usuário. Isso auxilia a desenvolver casos de teste mais rápido. 

Alem do mais utilizar BDD facilita a comunicação e a compreensão entre as equipes, auxiliando na legibilidade e desprende a descrição das funções do software das questões técnicas das execuções dos testes. 

O *cucumber* é um exemplo de ferramenta muito conhecida que oferece um apoio para várias linguagens como Java, Ruby. 

**Como escrever boas histórias e bons cenários de BDD**

Os cenários são redigidos utilizando o padrão composto por palavras chave: 

    **As-want-so** (como eu quero-para) 

        **Given-when-then** (dado-quando-então) 

Cada uma dessas palavras chave é utilizada da seguinte  maneira: 

    **Como**

        Papel que executa alguma ação no produto sobre teste 

**Eu quero** 

    Fazer alguma atividade no produto sobre teste 

**Para**  

    Algum efeito específico ou algo seja feito 

    **Cenário 1**

    **Dado** 

        Pré requisitos para meu teste 

    **Então**  

        Deve acontecer alguma coisa (o que eu quero que aconteça no meu teste) 

    **Cenário 2** 

    **Dado**

    ... 

 	**Quando** 

    ... 

    **Então** 

    ... 


**Exemplo de história de usuário com cenários** 

 

**Como:** tenho  uma conta no banco e tem aplicativo do banco  instalado no meu celular 

**Eu quero:** ser pato a controlara administrar a minha conta corrente através do aplicativo do banco. 

**Para:** melhorar o controle do meu dinheiro 

    **Cenário 1 : Realizar transferências da conta corrente** 

    **Dado:** eu devo esta logado na minha conta do banco. 

    **E:** tenha um limite maior que 0; 

    **E:**  menor que o limite de transferência permitido pelo aplicativo 

    **E:** menor que o limite da mina conta. 

    **Então:** o banco deverá permitir e realizar a transferência do dinheiro. 

    **E:** eu tenho que receber um SMS de confirmação da transação bancária. 
 
 **Cuidado com Ambigüidades** 

É relevante prestar atenção e usar a cautela ao escrever as histórias de usuários e os exemplos com ambigüidades, embora a toda língua não seja formal é cheia de ambigüidades. 

No português isto é fácil de acontecer, algo que seja claro para alguns da equipe e para outros não.  

Uma boa prática de procurar por ambigüidades é retirar cada palavra em uma frase em busca de sentidos que elas podem ter. Uma prática que ajuda evitar as informações confusas é escrever histórias nas reuniões de refinamento de backlog. 

**Concluindo** 

O que importa mesmo no momento de escrever boas histórias no formato BDD é concentrar se no comportamento.

Fonte: https://bit.ly/3HPsRks