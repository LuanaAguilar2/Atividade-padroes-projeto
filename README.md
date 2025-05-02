# Atividade padrões projeto
Nesta atividade deveriamos desenvolver uma pesquisa sobre padrões de projeto utilizados para desenvolvimento de API REST com Node JS. Desenvolver uma Ficha-Resumo sobre o resultado da pesquisa, escolhendo um padrão de projeto de exemplo.
Aplique este padrão de projetos, na construção de uma API, baseada na API que construímos em aula. Onde terão rotas (end points) para produto e cliente.

Ficha resumo- Padrões de projeto em API Rest com node.js 

* Tema da pesquisa: 
    Padrões de Projeto no Desenvolvimento de API REST com Node.js 

* O que são padrões de projeto:  
    Padrões de projeto são soluções reutilizáveis e bem definidas para problemas comuns que surgem durante o desenvolvimento de software. 

* Objetivo:  
     e compreender como os padrões de projeto contribuem para a organização, escalabilidade e manutenibilidade de APIs desenvolvidas com Node.js. 

* Padrões pesquisados: 
    MVC (Model-View-Controller) 
        O MVC é separado em 3 camadas muito bem definidas, model, view e controller, é frequentemente usado em projetos devido à sua arquitetura, que permite a separação do projeto em camadas, cada uma delas executa apenas o que lhe é determinado. 
        Model:  Trata os dados 
        Controller: Possui a lógica de negócios  
        Router(substitui o view): Estabelece os endpoints e aciona os controladores. 

    Repository Pattern  
        O Repository Pattern encapsula a lógica de acesso a dados, facilitando a injeção de dependência e promovendo uma abordagem orientada a objetos. Ele permite aplicar o princípio da persistência ignorante, mantendo as entidades da regra de negócio independentes da forma como os dados são armazenados. 

    DTO (Data Transfer Object) 
        DTO é um padrão de projeto usada para mover dados de um ponto a outro na solução. Frequentemente, esse transporte acontece fora do processo da aplicação, interagindo com servidor e cliente, entre servidores ou até mesmo com outras partes da solução. Mas nada impede que possa acontecer dentro do processo. ele é apenas um objeto de dados, logo, não costuma apresentar comportamento próprio. 

* Padão escolhido:  
    MVC 
* Vantagens do MVC  
    Pode ser usada em várias linguagens e frameworks  
    Atualização rápida da interface do aplicativo;  
    Manutenção simples do código; 
    Facilidade na aplicação de níveis de proteção;  
    Unificação de grupos de programadores. 

* Conclusão:  
    O padrão MVC é amplamente utilizado em APIs com Node.js por organizar a aplicação de forma clara e eficiente. Ele facilita o trabalho em equipe, melhora a legibilidade do código e separa responsabilidades entre os componentes da aplicação. 


* Sites utilizados:  

    https://www.alura.com.br/artigos/design-patterns-introducao-padroes-projeto 

    https://www.devmedia.com.br/introducao-ao-padrao-mvc/29308 

    https://renicius-pagotto.medium.com/entendendo-o-repository-pattern-fcdd0c36b63b 

    https://pt.stackoverflow.com/questions/31362/o-que-%C3%A9-um-dto#:~:text=DTO%20%C3%A9%20um%20padr%C3%A3o%20de,que%20ocorra%20dentro%20do%20processo. 

    https://coodesh.com/blog/dicionario/o-que-e-arquitetura-mvc/ 


