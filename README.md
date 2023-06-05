# BeeHeroes - Documentação

## Repositórios

[beeheroes-api](https://github.com/camisbrussi/beeheroes-api) <br/>
[beeheroes-client](https://github.com/camisbrussi/beeheroes-client)

## Introdução

O BeeHeroes é um projeto de software inovador que busca unir pessoas e organizações para promover ações de voluntariado e solidariedade. Com o objetivo de criar uma plataforma web acessível e aberta a todos, o BeeHeroes visa facilitar a oferta e a busca de trabalhos voluntários, conectando entidades sem fins lucrativos e voluntários em uma comunidade dedicada a causas sociais.

O objetivo social do BeeHeroes é claro: promover ações positivas que impactem diretamente a sociedade. Sabemos que existem inúmeras entidades sem fins lucrativos realizando trabalhos valiosos em diversas áreas, mas muitas vezes enfrentam dificuldades para encontrar apoio voluntário. Ao mesmo tempo, existem indivíduos com disposição para ajudar, mas sem um canal eficiente para se engajarem em causas significativas.

Nesse contexto, o BeeHeroes surge como uma solução para preencher essa lacuna, proporcionando uma plataforma onde entidades sem fins lucrativos podem publicar serviços e materiais que necessitam, e voluntários podem se candidatar para oferecer seu tempo, habilidades e recursos. Através dessa conexão direta e eficiente, a plataforma visa fomentar a solidariedade, permitindo que pessoas interessadas em fazer a diferença encontrem oportunidades de voluntariado que se alinhem aos seus interesses e disponibilidade.

Ao oferecer uma plataforma gratuita e acessível a qualquer pessoa interessada em participar, o BeeHeroes busca criar uma comunidade engajada, onde cada ação voluntária é uma oportunidade de ser um herói. O objetivo é inspirar e capacitar indivíduos a dedicarem parte do seu tempo para causas sociais, impactando positivamente a vida de pessoas e comunidades.

Com o BeeHeroes, pretendemos transformar o voluntariado em uma experiência inclusiva, gratificante e significativa, proporcionando uma plataforma confiável, funcional e segura. Acreditamos no poder das pequenas ações e na capacidade de cada indivíduo fazer a diferença. Juntos, como uma comunidade unida, podemos construir um futuro melhor e mais solidário.

### Bem-vindo ao BeeHeroes, onde cada ação voluntária conta e todos podem se tornar heróis!

## Requisitos

### Requisitos Funcionais

1. Registro de Usuários:
   - Os usuários devem poder se registrar na plataforma fornecendo as seguintes informações: nome completo, endereço de e-mail e senha.
   - A plataforma deve verificar se o endereço de e-mail fornecido é único e válido.
   - Os usuários devem ter a opção de se registrar como "entidade sem fins lucrativos" ou "voluntário".
   - Após o registro, os usuários devem receber uma confirmação de e-mail para ativar suas contas.

2. Perfil de Usuários:
   - Os usuários registrados devem poder criar e atualizar seus perfis.
   - As entidades sem fins lucrativos devem fornecer informações adicionais em seus perfis, como nome da organização, descrição, área de atuação e informações de contato.
   - Os voluntários devem poder fornecer informações adicionais em seus perfis, como habilidades, interesses e disponibilidade.
   - Os perfis dos usuários devem ser públicos para que outros usuários possam visualizá-los.

3. Publicação de Serviços:
   - As entidades sem fins lucrativos devem poder publicar informações sobre os serviços e materiais que necessitam.
   - Cada publicação de serviço deve incluir um título, descrição, categoria, localização e uma estimativa de tempo necessário para realizar o serviço.
   - As entidades sem fins lucrativos devem poder editar ou remover suas publicações de serviço.

4. Busca de Serviços:
   - Os voluntários devem poder pesquisar serviços disponíveis com base em categorias, localização e palavras-chave.
   - Os voluntários devem visualizar os detalhes de um serviço, incluindo título, descrição, categoria, localização e informações da entidade sem fins lucrativos.
   - Os voluntários devem poder se candidatar para ajudar em um serviço específico.
   - A plataforma deve enviar notificações para a entidade sem fins lucrativos quando um voluntário se candidatar para um serviço.

5. Comunicação:
   - A plataforma deve fornecer um sistema de mensagens para que as entidades sem fins lucrativos e os voluntários possam se comunicar.
   - Os usuários devem poder enviar mensagens uns aos outros para discutir os detalhes do serviço, combinar horários e compartilhar informações relevantes.
   - As mensagens devem ser organizadas em threads de conversa para facilitar a leitura e acompanhamento.

6. Avaliação:
   - Após a conclusão de um serviço, os usuários envolvidos devem poder avaliar uns aos outros.
   - Os usuários devem poder atribuir uma classificação numérica (por exemplo, de 1 a 5 estrelas) e fornecer comentários adicionais.
   - As avaliações devem ser públicas e estar visíveis nos perfis dos usuários.
   - A média das avaliações recebidas por um usuário deve ser calculada e exibida em seu perfil.

### Requisitos não Funcionais

1. Usabilidade:
   - A plataforma deve ter uma interface intuitiva e fácil de usar, permitindo que usuários com diferentes níveis de habilidade tecnológica possam navegar e interagir com facilidade.
   - O design da plataforma deve ser responsivo, adaptando-se a diferentes dispositivos e tamanhos de tela, garantindo uma experiência consistente em desktops, tablets e smartphones.

2. Segurança:
   - A plataforma deve implementar medidas de segurança adequadas para proteger as informações pessoais dos usuários e garantir a integridade dos dados.
   - O armazenamento e o compartilhamento de informações sensíveis devem ser feitos de forma criptografada.
   - Os usuários devem ser autenticados e autorizados adequadamente, garantindo que apenas usuários registrados possam acessar certas funcionalidades da plataforma.

3. Desempenho:
   - A plataforma deve ser capaz de lidar com um grande número de usuários simultaneamente, garantindo tempos de resposta rápidos e evitando atrasos significativos.
   - As consultas de pesquisa e o carregamento de páginas devem ser otimizados para fornecer uma experiência ágil aos usuários.
   - O sistema de mensagens deve ser eficiente e responsivo, permitindo que as conversas ocorram em tempo real.

4. Confiabilidade:
   - A plataforma deve estar disponível e operacional de forma confiável, minimizando períodos de inatividade e interrupções.
   - Os dados dos usuários e as interações devem ser protegidos contra perda ou corrupção por meio de backups regulares e mecanismos de recuperação.
   - A plataforma deve ser testada e depurada adequadamente para evitar erros e comportamentos inesperados.

5. Escalabilidade:
   - A plataforma deve ser projetada para ser escalável, permitindo o crescimento do número de usuários, serviços e interações sem degradação significativa do desempenho.
   - Os recursos de infraestrutura devem ser dimensionados adequadamente para lidar com o aumento da carga de trabalho.


7. Manutenibilidade:
   - O código-fonte da plataforma deve ser modular, bem estruturado e documentado, facilitando a manutenção e evolução futura.
   - Atualizações e correções de bugs devem ser implementadas de forma eficiente, minimizando o impacto nas funcionalidades existentes.

Esses requisitos não funcionais ajudarão a garantir que a plataforma BeeHeroes seja usável, segura, de alto desempenho, confiável, escalável, internacionalizável/localizável e de fácil manutenção.

## Interface do usuário:
[TO DO]

## Fluxos de Navegação:
[TO DO]

## Arquitetura do Projeto:

A estrutura do projeto BeeHeroes é baseada em uma arquitetura de sistema distribuído, dividida em uma parte de front-end e uma parte de back-end, que colaboram para fornecer uma experiência de usuário completa e funcional.

### Front-end:
O front-end do BeeHeroes é desenvolvido utilizando o framework Next.js com a biblioteca React. O Next.js é escolhido por sua capacidade de renderização do lado do servidor (Server-Side Rendering - SSR), que melhora o desempenho e a experiência do usuário. O React é utilizado para criar componentes reutilizáveis e fornecer uma interface de usuário dinâmica e interativa.

A estrutura do front-end segue uma abordagem baseada em componentes, onde diferentes partes da interface são quebradas em componentes independentes. Isso facilita a manutenção, reutilização e escalabilidade do código. A comunicação com o back-end é feita por meio de chamadas de API assíncronas, utilizando a biblioteca Axios.

### Back-end:
O back-end do BeeHeroes é construído seguindo os princípios do SOLID e utilizando o padrão de arquitetura Repository. A linguagem de programação utilizada será, Node.js com fastify, entre outras opções populares.

A arquitetura do back-end é dividida em diferentes camadas e componentes:

1. Controladores (Controllers):
   - Os controladores são responsáveis por receber as requisições HTTP do front-end e direcioná-las para os casos de uso apropriados.
   - Eles lidam com a validação dos dados de entrada, autenticação de usuários e tratamento de erros.

2. Casos de Uso (Use Cases):
   - Os casos de uso representam as diferentes funcionalidades do sistema, como registro de usuários, publicação de serviços, busca de serviços, comunicação, avaliação, entre outros.
   - Eles encapsulam as regras de negócio e orquestram a interação entre os componentes do back-end.

3. Repositórios:
   - Os repositórios são responsáveis por interagir com a camada de persistência de dados, seja um banco de dados relacional, não-relacional ou qualquer outra forma de armazenamento.
   - Eles fornecem uma abstração para acessar, criar, atualizar e excluir os dados relacionados aos usuários, serviços e outras entidades do sistema.

4. Inversão de Dependência:
   - A inversão de dependência é aplicada para desacoplar os componentes do back-end e facilitar a testabilidade e a substituição de implementações.
   - As dependências externas, como os repositórios, são injetadas nos casos de uso por meio de interfaces, permitindo que diferentes implementações sejam usadas sem afetar o restante do sistema.

A estrutura do projeto BeeHeroes no back-end busca seguir boas práticas de desenvolvimento, promovendo a modularidade, a coesão, a reutilização de código e a testabilidade. A escolha da linguagem de programação e do framework pode variar dependendo das preferências e habilidades da equipe de desenvolvimento.

## Banco de dados
No projeto BeeHeroes, o banco de dados escolhido é o PostgreSQL, e a camada de acesso a dados será implementada utilizando o Prisma.

### Banco de Dados PostgreSQL:
O PostgreSQL é um sistema de gerenciamento de banco de dados relacional de código aberto, amplamente utilizado e conhecido por sua confiabilidade, desempenho e recursos avançados. Ele suporta consultas complexas, transações ACID e oferece recursos de segurança robustos.

O PostgreSQL será responsável por armazenar e gerenciar os dados do BeeHeroes, incluindo informações sobre usuários, entidades sem fins lucrativos, serviços, avaliações e outras entidades relevantes para o funcionamento da plataforma.

### Prisma:
O Prisma é uma ferramenta ORM (Object-Relational Mapping) moderna que facilita a interação com o banco de dados a partir do código-fonte. Ele oferece uma camada de abstração que simplifica as operações de leitura, gravação e manipulação de dados.

O Prisma será utilizado no projeto BeeHeroes para realizar as seguintes tarefas:

1. Modelagem de Dados: O Prisma permite a definição de modelos de dados que mapeiam as entidades do sistema para tabelas do banco de dados PostgreSQL. Cada modelo representa uma tabela e suas colunas correspondentes.

2. Migrações de Banco de Dados: O Prisma fornece recursos para gerenciar as alterações no esquema do banco de dados por meio de migrações. Isso permite que o esquema do banco de dados seja atualizado de forma controlada e consistente, acompanhando a evolução do projeto.

3. Consultas ao Banco de Dados: O Prisma oferece uma API fluente e intuitiva para realizar consultas ao banco de dados. Ele suporta uma ampla gama de operações, como criação, leitura, atualização e exclusão (CRUD), filtragem, ordenação e agregação de dados.

4. Relacionamentos entre Tabelas: O Prisma permite a definição de relacionamentos entre as tabelas do banco de dados, como relacionamentos um-para-um, um-para-muitos e muitos-para-muitos. Esses relacionamentos podem ser facilmente navegados e consultados através da API do Prisma.

5. Segurança e Validação: O Prisma ajuda a evitar vulnerabilidades de segurança, como ataques de injeção de SQL, ao fornecer mecanismos de consulta parametrizada. Além disso, ele oferece recursos de validação de dados para garantir a integridade e consistência dos dados armazenados.

A combinação do PostgreSQL como banco de dados e o Prisma como camada de acesso a dados proporciona um ambiente robusto, confiável e eficiente para armazenar, recuperar e manipular os dados do BeeHeroes. Essas tecnologias trabalham em conjunto para fornecer um acesso seguro e performático aos dados, mantendo a consistência e integridade do sistema.

## Segurança:
A segurança é uma preocupação essencial no projeto BeeHeroes para proteger os dados dos usuários e garantir a integridade da plataforma. Algumas medidas de segurança que devem ser implementadas são:

1. Autenticação e Autorização: Utilizar um sistema de autenticação seguro, como o uso de tokens de autenticação (por exemplo, JWT - JSON Web Tokens), para verificar a identidade dos usuários e controlar o acesso às funcionalidades da plataforma.

2. Proteção de Dados Pessoais: Implementar criptografia adequada para proteger informações sensíveis, como senhas dos usuários, utilizando algoritmos fortes e técnicas de hash seguras (por exemplo, bcrypt).

3. Prevenção de Ataques: Aplicar práticas de segurança para prevenir ataques, como injeção de SQL, cross-site scripting (XSS) e cross-site request forgery (CSRF). Utilizar mecanismos de validação de entrada e sanitização de dados para garantir a integridade dos dados recebidos e processados pela plataforma.

4. Proteção contra Acesso Não Autorizado: Implementar medidas de segurança para evitar acesso não autorizado às funcionalidades e dados da plataforma. Isso pode incluir restrições de acesso baseadas em papéis, verificações de autorização em diferentes níveis e uso de tokens de acesso com tempo de expiração.

## Testes:
Os testes são fundamentais para garantir a qualidade e a robustez do projeto BeeHeroes. Diferentes tipos de testes podem ser realizados, incluindo:

1. Testes Unitários: Testar individualmente cada componente e função do sistema para verificar se eles funcionam corretamente. Isso inclui testes de unidade para os casos de uso, controladores, modelos de dados e outras partes do projeto.

2. Testes de Integração: Realizar testes que verifiquem a integração correta entre os diferentes componentes do sistema, como a interação entre o front-end e o back-end, a comunicação com o banco de dados e a correta execução das funcionalidades principais.

3. Testes de Desempenho: Avaliar o desempenho do sistema em diferentes cenários de carga e identificar possíveis gargalos. Isso pode incluir testes de carga para verificar a capacidade do sistema de lidar com um grande número de usuários e solicitações simultâneas.

4. Testes de Segurança: Realizar testes de segurança para identificar possíveis vulnerabilidades e garantir que as medidas de segurança implementadas estejam funcionando adequadamente. Isso pode incluir testes de penetração e análise de vulnerabilidades.

5. Testes de Usabilidade: Avaliar a usabilidade da plataforma, garantindo que os usuários possam interagir com facilidade e que a experiência do usuário seja satisfatória. Isso pode incluir testes de usabilidade com usuários reais e a coleta de feedback para melhorias.

A implementação de testes é essencial para garantir a qualidade do software e identificar possíveis problemas antes que eles afetem os usuários finais. Os testes devem ser executados de forma regular e automatizada, integrados ao processo de desenvolvimento do projeto BeeHeroes.

## Conclusão:

O BeeHeroes é um projeto ambicioso que visa criar uma plataforma web para a oferta e busca de trabalhos voluntários, proporcionando uma oportunidade para entidades sem fins lucrativos encontrarem o apoio de voluntários dedicados. Através do desenvolvimento de um produto de software robusto e funcional, o BeeHeroes busca promover o engajamento cívico e a solidariedade, conectando pessoas que desejam fazer a diferença.

Ao longo desta documentação, foram apresentados os requisitos funcionais e não funcionais do projeto, bem como a estrutura, a tecnologia utilizada e a arquitetura adotada. A plataforma BeeHeroes baseia-se em uma arquitetura distribuída, com uma parte de front-end desenvolvida com Next.js e React, e uma parte de back-end construída com uma API utilizando os princípios SOLID e o padrão Repository Pattern.

O banco de dados PostgreSQL, aliado ao Prisma como camada de acesso a dados, fornecerá uma base sólida e segura para armazenar as informações dos usuários, serviços e avaliações. Medidas de segurança, como autenticação e autorização, proteção de dados pessoais e prevenção de ataques, serão implementadas para garantir a segurança dos dados e a privacidade dos usuários.

Além disso, a qualidade do projeto será garantida por meio da realização de testes abrangentes, incluindo testes unitários, testes de integração, testes de desempenho e testes de segurança. Esses testes asseguram que a plataforma funcione de maneira confiável, seja resistente a falhas e ofereça uma ótima experiência de usuário.

O BeeHeroes é mais do que um projeto de software, é uma iniciativa que busca impactar positivamente a sociedade, promovendo ações de voluntariado e solidariedade. Com a plataforma, entidades sem fins lucrativos poderão encontrar o apoio necessário para realizar seus projetos e voluntários terão a oportunidade de contribuir de forma significativa para causas importantes.

Esperamos que o BeeHeroes se torne uma ferramenta valiosa, capaz de unir pessoas com um propósito comum de fazer o bem. Através dessa plataforma, poderemos criar uma comunidade de heróis anônimos que, juntos, tornarão o mundo um lugar melhor.

Seja bem-vindo ao BeeHeroes, onde cada ação voluntária é uma oportunidade de ser um herói!
