#  **Linguagens Naturais: O BDD e a Sintaxe *Gherkin*** 
 
Para garantir uma boa qualidade do projeto em processo de testes é interessante entender como as linguagens naturais como **BDD** e  da **Sintaxe *Gherkin*** são importantes. 

 A medida que a tecnologia avança trazendo novas ferramentas e alcançando  o conhecimento dos usuários comuns que muitas vezes  nem são estudantes da tecnologia para sua formação profissional, apenas consumidores no seu trabalho. 

Os grandes players têm aprendido com a tecnologia que é exatamente esses usuários que serão alvo de seus serviços, onde os intermediários serão eliminados em um meio lógico e lucrativo, através de processos heurísticos desenvolvendo a cada dia ferramentas de criação  “user friendly” para que isso seja realidade em algum momento, relegando os desenvolvedores a cargos bem mais especializados e mais alto nível. 

Estas linguagens são chamadas de linguagens naturais como o YAML e o Python, que estão quase lá porem ainda necessitam um pouco de conhecimento em codificação. 

Porém existem métodos linguísticos e semânticos que buscam produzir uma emulação do comportamento do usuário numa linguagem simples, sendo a sua endentação a principal chave para o funcionamento como por exemplo o **BDD**  e a **sintaxe *Gherkin.***  

## **O que é BDD?**

**BDD** (*Beauvoir Driven Development*) é uma técnica de desenvolvimento ágil que visa colaboração dos desenvolvedores na melhoria de qualidade, unindo tanto áreas técnicas como não técnicas para criar métodos de validação em testes de sistemas, onde tenha mais colaborações entres as visões, assegurando a qualidade do projeto. 

O **BDD**  é utilizado para criar casos de testes onde sua lógica facilita um entendimento simples para todos. Normalmente nesse processo é utilizado como base a Sintaxe Gherkin, que é um tipo de sintaxe que auxilia essa lógica de escrita e aplicação do processo **BDD** . 

Esse processo é muito útil pois auxilia na compreensão dos testes que serão gerados e podem ser feitos como processos manuais e serem facilmente automatizados sem gerar conflitos de falta de conhecimento, uma vez que pretende eliminar a “torre de babel” muito comum nas áreas incluídas 

Os cenários em **BDD** são criados através da “quebra” de um requisito dentro de uma situação e necessidade para gerar cenários de teste que gerarão o resultado aguardado. A identação usada para tal cenário são a palavras Dado que, Quando,  Entao e vez ou outra Deve par dentro de contexto gerar um cenário. 

## **Mapa para gerar identação no uso da Sintaxe como *Gherkin*** 

 Estrutura Básica de Sintaxe par o  ***Gherkin***  para o **BDD** 

* **Dado** (contexto) 

* **Quando** (evento) 

* **Então** (saída) 

**Palavras chaves auxiliares** 

* **Mas** 

* **E** 

* **#** Comentário durante a escrita 



É possível perceber que a forma de escrita é como escrever um roteiro de filme ou uma história, separando o cenário da cena, os atores e as situações usando os processos da linguística sem precisar saber programação. Há várias ferramentas que podem traduzir esse roteiro para linguagem de programação incluído num plano de testes e é de suma importância para testes automatizados, onde neste caso, se envolve a programação que pode variar de acordo com a dificuldade do cenário. 

 
**Exemplo:** controle de carros de aluguel 

## **Cenário para teste de retirada do carro do pátio** 

*  **Cenário A:** Carros que podem ser alugados  

*  **Dado que** um cliente aluga um carro 

*  **E**tenho que cinco carros no pátio disponíveis no pátio 

*  **Quando** ele aluga o carro 

* **Então** eu devo ter 4 carros disponíveis no pátio 

 
## **Cenário para devolução e carro alugado**

* **Cenário B:** Carros alugados devem voltar ao pátio 

* **Dado** que um carro está alugado e eu tenho cinco carros 

* **E** o cliente de devolver o carro alugado 

* **Quando** ele devolve o carro 

* **Então** eu devo ter cinco carros disponíveis no pátio 

Claramente os cenários acima expostos são simples, porém auxiliam com processo de descrição com intuito simples para o entendimento até de quem não entende de programação. Isso é muito importante para os profissionais de testes, principalmente para os P.Os e até mesmo para usuários de comuns de quaisquer negócios, que podem envolver se em todo processo de testes com seu ponto de vistas e conhecimento, agregando mais qualidade no que está sendo feito.
