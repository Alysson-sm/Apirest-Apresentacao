/*Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. */ <=> buscar entender isso

REST é um termo definido para "Transferência de Estado Representacional"
(Representational State Transfer), foi criado em 2000 por Roy FIelding durante sua tese de doutorado, no qual ele escreveu uma design de arquitetura de software construido para servir  aplicaçoes em rede. 


Agora que sabemos o que é uma API vamos falar de API rest e consequentemente RESTful.

API REST, também chamada de API RESTful é uma API que está em conformidade com as instruções de  construção da arquitetura REST. A duvida que tive durante a construção desse trabalho e acredito que voce que esta lendo tambem ira ter, existe diferença entre REST e RESTful ? 

REST: representa um conjunto de principios de arquitetura, o desenvolvedor pode implementar as instruçoes que acredita trazer beneficios a sua Api. 


RESTful: representa a condição de um sistema específico em aplicar os conceitos de REST, se o serviço o qual a API esta se comunicando tem condiçoes de atender o que esta sendo pedido. Caso tenha tem um cenario que atenda essas condiçoes a API recebe o titulo de RESTful.

Agora que ja temos uma ideia do que é cada termo, o que minha API precisa atender pra se torna REST ?

    * Ter uma arquitetura cliente/servidor formada por clientes, servidores e recursos, com solicitações gerenciadas por meio de HTTP.

    * Estabelecer uma comunicação stateless entre cliente e servidor. Isso significa que nenhuma informação do cliente é armazenada entre solicitações GET e toda as solicitações são separadas e desconectadas.

    * Armazenar dados em cache para otimizar as interações entre cliente e servidor.

    * Ter uma interface uniforme entre os componentes para que as informações sejam transferidas em um formato padronizado. Para tanto, é necessário que

        => os recursos solicitados sejam identificáveis e estejam separados das representações enviadas ao cliente.
        => os recursos possam ser manipulados pelo cliente por meio da representação recebida com informações suficientes para tais ações;
        =>as mensagens autodescritivas retornadas ao cliente contenham informações suficientes para descrever como processá-las;
        => hipertexto e hipermídia estão disponíveis. Isso significa que após acessar um recurso, o cliente pode usar hiperlinks para encontrar todas as demais ações disponíveis para ele no momento.
    
    * Ter um sistema em camadas que organiza os tipos de servidores (responsáveis pela segurança, pelo carregamento de carga e assim por diante) envolvidos na recuperação das informações solicitadas em hierarquias que o cliente não pode ver.
    
    * Possibilitar código sob demanda (opcional): a capacidade de enviar um código executável do servidor para o cliente quando solicitado para ampliar a funcionalidade disponível ao cliente. 

