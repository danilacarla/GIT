O que é (VCS)?

Sistema de Controle de Versão, é uma ferramenta que permite o gerenciamento de alterações em um conjunto de arquivos ao longo do tempo. Ele registra todas as modificações feitas nos arquivos, permitindo que os desenvolvedores acompanhem as alterações, restaurem versões anteriores e trabalhem em conjunto de forma eficiente.

Principais recursos de um VCS Um VCS possui uma série de recursos que facilitam o gerenciamento de alterações em um projeto. Alguns dos principais recursos incluem:

Histórico de alterações; Ramificações (Branches); Mesclagem (Merge); Controle de acesso; Resolução de conflitos.

  + Conclusão
O Version Control System (VCS) é uma ferramenta essencial para o desenvolvimento de software. Ele permite o gerenciamento de alterações em um projeto, facilita a colaboração entre membros de uma equipe e oferece recursos poderosos para controlar e rastrear as modificações feitas nos arquivos. Com um VCS, os desenvolvedores podem trabalhar de forma mais eficiente, organizada e segura, garantindo a integridade do projeto ao longo do tempo.

  + Vantagens em utilizar o (VCS) :
Rastreamento e Reversão de Alterações; Colaboração Eficiente; Criação de Branches; Fusão de Branches.

  + Cite três exemplos populares de Sistemas de Controle de Versão (VCS):
Git: O Git é amplamente utilizado e conhecido por sua velocidade, flexibilidade e eficiência. Ele permite que os desenvolvedores criem branches, revertam alterações e colaborem em projetos de forma distribuída. Subversion (SVN): O SVN é um VCS centralizado que mantém um único repositório central. Ele é mais antigo que o Git e ainda é usado em alguns projetos legados. Mercurial: O Mercurial é semelhante ao Git em muitos aspectos, mas oferece uma abordagem mais simples e intuitiva para controle de versão

DESAFIO 2

1- Com suas palavras defina o que é programação orientada a objetos (POO) e cite seus pilares?
A Programação Orientada a Objetos (POO) é um paradigma fundamental no desenvolvimento de software, que se concentra na modelagem de sistemas através da interação entre "objetos" individuais. Cada objeto possui características próprias, representadas por seus atributos, e comportamentos definidos por seus métodos. Essa abordagem permite uma organização mais intuitiva e modular do código, promovendo a reutilização e facilitando a manutenção.
Um dos pilares da POO é a abstração, que simplifica a representação de entidades do mundo real em estruturas computacionais. Isso é alcançado ao identificar os aspectos essenciais de um objeto e ignorar detalhes menos relevantes para o contexto do sistema em desenvolvimento.
O encapsulamento garante que os detalhes internos de um objeto sejam ocultados do exterior, permitindo o controle sobre como os dados são acessados e modificados. Isso promove a segurança e a integridade do sistema, ao mesmo tempo em que facilita a manutenção e evolução do código ao longo do tempo.
A herança possibilita a criação de novas classes baseadas em classes existentes, permitindo a extensão e especialização do comportamento e dos atributos. Isso reduz a duplicação de código e estabelece uma hierarquia de classes que reflete a relação entre os objetos no mundo real.
O polimorfismo permite que objetos de diferentes classes respondam de maneira distinta a um mesmo método, de acordo com o contexto em que são utilizados. Isso aumenta a flexibilidade do código, permitindo tratamentos genéricos de objetos variados através de interfaces comuns.
2- Exemplifique e explique um cenário de abstração;
Um cenário prático de abstração na Programação Orientada a Objetos pode ser exemplificado através de um sistema de gerenciamento de biblioteca. Neste sistema, podemos considerar a abstração na modelagem das entidades principais, como Livro e Usuário.
3- Exemplifique e explique um cenário de encapsulamento;
Um cenário prático de encapsulamento na Programação Orientada a Objetos pode ser exemplificado através de um sistema de gestão de conta bancária. Neste contexto, a classe Conta Bancaria pode encapsular os dados sensíveis (como saldo) e controlar o acesso a eles através de métodos específicos.
4- Exemplifique e explique um cenário de herança;
Um cenário prático de herança na Programação Orientada a Objetos pode ser exemplificado através de um sistema de gerenciamento de funcionários de uma empresa, onde diferentes tipos de funcionários compartilham certas características comuns, mas também têm comportamentos específicos.
5- Exemplifique e explique um cenário de polimorfismo;
Um cenário prático de polimorfismo na Programação Orientada a Objetos pode ser exemplificado através de um sistema de gerenciamento de formas geométricas, onde diferentes formas (como círculos e retângulos) possuem métodos comuns para calcular área, mas cada forma implementa esses métodos de maneira específica.
6- Cite 5 vantagens da POO.
1.	Reutilização de Código: A POO promove a reutilização de código através de conceitos como herança e composição. Classes e objetos podem ser reutilizados em diferentes partes do programa ou em projetos diferentes, reduzindo a necessidade de escrever código redundante e facilitando a manutenção.
2.	Modularidade: A POO facilita a organização do código em módulos independentes (classes e objetos), o que promove uma estrutura mais limpa e organizada. Cada objeto é responsável por suas próprias funcionalidades, o que simplifica o desenvolvimento e a depuração.
3.	Facilidade de Manutenção: A estrutura modular da POO torna mais fácil a manutenção do código. Alterações ou correções podem ser feitas em uma parte específica do código sem afetar outras partes do sistema, desde que a interface pública dos objetos seja mantida.
4.	Flexibilidade e Extensibilidade: A POO permite que novas funcionalidades sejam adicionadas com relativa facilidade. Novas classes podem ser criadas a partir de classes existentes através da herança, adicionando novos comportamentos sem modificar o código já existente.
5.	Encapsulamento e Segurança: O encapsulamento na POO protege os dados internos de um objeto e restringe o acesso direto a eles fora da classe. Isso promove a segurança e a integridade do sistema, garantindo que apenas os métodos apropriados possam manipular os dados internos de um objeto.

DESAFIO 3

O que é protocolo de comunicação HTTP e como funciona:
O Protocolo de Transferência de Hipertexto (HTTP) é usado na web para comunicação entre clientes (como navegadores) e servidores. Funciona com requisições (como GET, POST) enviadas pelos clientes para obter recursos dos servidores, que respondem com dados (como HTML, imagens) e informações de status. É stateless, ou seja, não mantém estado entre requisições. HTTPS é uma versão segura com criptografia.
O que é REST, e qual sua relação com o protocolo de comunicação HTTP:
REST (Representational State Transfer) é um estilo arquitetural para sistemas distribuídos baseado em princípios simples e bem definidos. Ele utiliza o protocolo HTTP para definir operações sobre recursos através dos métodos padrões (GET, POST, PUT, DELETE). REST enfatiza a statelessness, onde cada requisição contém todas as informações necessárias, e utiliza URIs para identificar recursos e representações como JSON ou XML para transferência de dados.
O que é Web API, e qual é a sua relação com REST:
Uma Web API é uma interface que permite que aplicações se comuniquem pela internet usando padrões definidos. Ela especifica como os sistemas podem enviar e receber dados de forma padronizada. Muitas Web APIs seguem os princípios do REST, que define um estilo arquitetural para APIs web baseado em métodos HTTP (GET, POST, etc.), manipulação de recursos identificados por URIs, e a utilização de representações como JSON ou XML para transferência de dados.
Métodos de solicitações HTTP utilizados pelo padrão REST e suas respectivas finalidades:
Os principais métodos HTTP utilizados pelo padrão REST são:
GET: Recupera dados de um recurso específico. POST: Submete dados para processamento ou criação de um recurso. PUT: Atualiza um recurso existente com os dados fornecidos. DELETE: Remove um recurso identificado pelo URI. PATCH: Aplica modificações parciais a um recurso. HEAD: Obtém apenas os cabeçalhos de resposta, sem o corpo da mensagem. OPTIONS: Obtém informações sobre os métodos HTTP suportados pelo servidor para um recurso. Esses métodos permitem realizar operações de leitura, criação, atualização, remoção e verificação de recursos em APIs RESTful, seguindo os princípios de manipulação de recursos e statelessness.


DESAFIO 4

Em um sistema organizado em camadas de uma API, as responsabilidades das camadas geralmente são distribuídas da seguinte forma:
Entity (Entidade): Esta camada representa os objetos de dados principais do domínio da aplicação. Ela encapsula as estruturas de dados que são armazenadas e manipuladas no banco de dados ou em memória. Normalmente, as entidades mapeiam diretamente para tabelas de banco de dados ou são estruturas de dados que refletem conceitos importantes do domínio da aplicação.
Repository (Repositório): Responsável pelo acesso aos dados e pela persistência das entidades. Esta camada abstrai o banco de dados ou outra forma de armazenamento de dados subjacente. Ela encapsula todas as operações de leitura, escrita, atualização e remoção de dados do banco de dados, oferecendo uma interface de alto nível para que as outras camadas da aplicação possam interagir com os dados de forma independente da tecnologia de armazenamento utilizada.
Service (Serviço): Concentra a lógica de negócio da aplicação. Aqui ficam as regras de negócio que coordenam a interação entre as entidades e controlam os fluxos de dados. Os serviços orquestram chamadas aos repositórios, validam dados, executam operações complexas e garantem a consistência das operações realizadas pela API. Eles encapsulam a lógica que não pertence diretamente às entidades ou aos controladores.
Controller (Controlador): Responsável por receber requisições HTTP, interpretar parâmetros e delegar a execução para os serviços apropriados. Esta camada atua como um ponto de entrada para a API, expondo endpoints que são acessíveis externamente. Os controladores traduzem os dados da requisição para chamadas aos serviços e, em seguida, formatam as respostas retornadas pelos serviços em respostas HTTP adequadas para os clientes.
Em resumo, cada camada em uma arquitetura organizada em camadas de uma API tem uma responsabilidade clara: as entidades representam os dados principais, os repositórios gerenciam o acesso e a persistência dos dados, os serviços implementam a lógica de negócio e os controladores lidam com a interação com o mundo externo através de requisições HTTP. Essa separação de responsabilidades promove um design modular, facilitando a manutenção, a escalabilidade e a testabilidade do sistema.

Desafio 5

O que é um padrão de projeto e porque utilizamos:
Um padrão de projeto é uma solução reutilizável para problemas comuns que surgem no desenvolvimento de software. Ele fornece uma estrutura e diretrizes para abordar problemas específicos de forma eficiente, promovendo boas práticas e consistência no design. Utilizamos padrões de projeto para melhorar a modularidade, a escalabilidade e a manutenção do código, além de facilitar a comunicação entre desenvolvedores ao adotar soluções bem definidas. Ao aplicar padrões, evitamos reinventar a roda e podemos focar em aspectos mais criativos e específicos do projeto. Em suma, eles ajudam a criar sistemas mais robustos e de fácil entendimento.
Explique o conceito de arquitetura de solfware e seus propósitos:
A arquitetura de software refere-se à estrutura organizacional fundamental de um sistema de software, composta por seus componentes principais, suas interações e os princípios que orientam seu design e evolução. É um modelo que define como o sistema será estruturado e como os diferentes elementos interagirão para atingir os objetivos desejados.
Propósitos da arquitetura de software:
Visão Geral e Estrutura: Fornece uma visão clara da estrutura do sistema, facilitando a compreensão de como os diferentes componentes e módulos se inter-relacionam.
Facilita Decisões: Ajuda na tomada de decisões sobre tecnologias, design e outras escolhas importantes, baseando-se em requisitos técnicos e de negócios.
Escalabilidade e Manutenção: Garante que o sistema possa crescer e se adaptar a novas necessidades sem exigir grandes reescritas, promovendo a manutenção mais eficiente.
Qualidade e Desempenho: Estabelece as bases para garantir que o sistema atenda a requisitos de qualidade, como desempenho, segurança e confiabilidade.
Comunicação: Serve como um meio de comunicação entre as partes interessadas (desenvolvedores, clientes, etc.), alinhando expectativas e garantindo que todos compreendam a visão do sistema.
Em resumo, a arquitetura de software é essencial para criar sistemas organizados, robustos e adaptáveis, além de ser uma base crucial para o sucesso de projetos de software complexos.
O que significa SOLID e quais seus princípios:
SOLID é um acrônimo que representa cinco princípios fundamentais do design de software orientado a objetos, visando melhorar a modularidade e a manutenção do código. Os princípios SOLID são:
S - Single Responsibility Principle (SRP): Uma classe deve ter apenas uma razão para mudar, significando que deve ter uma única responsabilidade ou função.
O - Open/Closed Principle (OCP): O software deve ser aberto para extensão, mas fechado para modificação, permitindo que novas funcionalidades sejam adicionadas sem alterar o código existente.
L - Liskov Substitution Principle (LSP): Objetos de uma classe base devem poder ser substituídos por objetos de uma classe derivada sem alterar o comportamento desejado do sistema.
I - Interface Segregation Principle (ISP): Uma interface deve ser específica e não forçar implementações a depender de métodos que não utilizam, promovendo interfaces mais coesas.
D - Dependency Inversion Principle (DIP): Dependências devem ser baseadas em abstrações (interfaces), não em implementações concretas, o que promove a flexibilidade e desacoplamento.
Esses princípios ajudam a criar sistemas mais flexíveis, reutilizáveis e fáceis de manter.



