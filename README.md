pesquisa com texto,imagens e links de conteudo(videos/artigos)

## Conceito padrão MVC javascript
[MVC](https://blog.lewagon.com/pt-br/skills/o-que-e-padrao-mvc/)


Você já parou para pensar o que se passa por trás de uma tela de login de um software? Em frações de segundos a página é capaz de absorver as informações que foram digitadas no campo de email e senha, realizar a validação e entregar uma resposta positiva ou negativa. 
Esse processo só se torna possível quando existe um padrão de arquitetura de software adequado. Embora exista vários que podem ser utilizados, o MVC é o mais conhecido e empregado entre os desenvolvedores profissionais.
Se você quer saber como melhorar a usabilidade do seu software e otimizar o tempo de resposta entre o banco de dados e a interface de usuário, continue a leitura que vamos explicar todos os detalhes neste artigo. 
Afinal, o que é MVC?
Apesar de muitas pessoas considerarem essa sigla como um padrão de design de interface, na verdade ele é um padrão de arquitetura de software responsável por contribuir na otimização da velocidade entre as requisições feitas pelo comando dos usuários. 
Com quase 50 anos de formulação, a arquitetura MVC é dividida em três componentes essenciais: Model, Controller e View. 
Um dúvida muito recorrente na programação é se no processo de desenvolvimento pode ter apenas esses 3 componentes ou se é possível acrescentar mais alguns. A resposta é sim para a possibilidade de inserir uma camada extra. Essa sequência de códigos pode ser alterada conforme a necessidade do projeto. 
Mas um código com muitas camadas se torna muito confuso e por isso, o ideal é manter o padrão original. A seguir vamos explicar os conceitos e aplicações dos componentes que acompanham essa arquitetura de software.
Model ou Modelo 
Essa classe também é conhecida como Business Object Model (objeto modelo de negócio). Sua responsabilidade é gerenciar e controlar a forma como os dados se comportam por meio das funções, lógica e regras de negócios estabelecidas. 
Ele é o detentor dos dados que recebe as informações do Controller, válida se ela está correta ou não e envia a resposta mais adequada. 
Controller ou Controlador
A camada de controle é responsável por intermediar as requisições enviadas pelo View com as respostas fornecidas pelo Model, processando os dados que o usuário informou e repassando para outras camadas. 
Numa analogia bem simplista, o controller  operaria como o ‘’maestro de uma orquestra’’  que permite a comunicação entre o detentor dos dados e a pessoa com vários questionamentos no MVC. 
View ou Visão
Essa camada é responsável por apresentar as informações de forma visual ao usuário. Em seu desenvolvimento devem ser aplicados apenas recursos ligados a aparência como mensagens, botões ou telas. 
Seguindo nosso processo de comparação o View está na linha de frente da comunicação com usuário e é responsável transmitir questionamentos ao controller e entregar as respostas obtidas ao usuário. É a parte da interface que se comunica, disponibilizando e capturando todas as informação do usuário.
Como os componentes interagem?
Tudo começa com a interação do usuário na camada View. A partir daí o controlador pega essa informações e envia para o Model que fica responsável por avaliar aqueles dados e transmitir uma resposta. 
O controlador recebe essas respostas e envia uma notificação de validação daquela informação para a camada visão, fazendo com a mesma apresente o resultado de maneira gráfica e visual.
Todo esse processo leva em consideração as regras de negócio aplicadas na construção.



## Conceito Framework 

![framework](https://files.tecnoblog.net/wp-content/uploads/2021/11/o-que-e-framework-1-700x394.png)

Alguns exemplos de frameworks
A utilidade desse tipo de estrutura é bem variada. Há peças usadas para criar jogos, sites de internet, documentos, serviços, etc. Plataformas como a Flutter do Google e a Rails (duas opções de código aberto) são opções bastante usadas entre desenvolvedores, engenheiros e afins.

Algumas das ferramentas mais populares são:

AngularJS: Um framework JavaScript front-end desenvolvido pelo Google para aplicações para web;
Django: Uma ferramenta de código aberto para web escrita em Python;
Xamarin: Um dos frameworks mais populares para dispositivos móveis. Pertence a Microsoft;
React Native: Mais um exemplo de código aberto, esse framework é escrito em JavaScript e foi desenvolvido pelo Facebook.

//conceito da biblioteca


