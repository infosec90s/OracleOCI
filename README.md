# Certificação Oracle Cloud Infrastructure Foundations - OCI

## 1 - Introdução ao Curso

### Inicio

Bem-vindo ao curso de certificação Oracle Cloud Infrastructure Foundation. Estou tão feliz que você está aqui. Este curso foi criado especificamente para você começar a aprender o Oracle Cloud Infrastructure e se tornar bem versado nos fundamentos da OCI.

Meu nome é Rohit Rahi e faço parte da equipe Oracle Cloud. Eu serei seu instrutor para este curso. Tive a sorte de passar mais de 10 anos no espaço de nuvem e fazer parte da equipe Oracle Cloud desde o início.

Minha equipe cria certificações e treinamentos OCI. E nos últimos anos, treinamos centenas e milhares de alunos no Oracle Cloud Infrastructure. Este curso lhe dará o conhecimento, as habilidades e a confiança para passar no OCI Foundations Exam e, além disso, fornecerá o conhecimento básico necessário para projetos da OCI.

O curso cobrirá todas as áreas do OCI Foundations Exam. Começaremos com uma rápida introdução da plataforma OCI e, em seguida, nos aprofundaremos nos principais primitivos, computação, armazenamento, rede, identidade, bancos de dados, segurança e muito mais. Abordarei arquiteturas orientadas a eventos e serviços para desenvolvedores. Também discutirei nossa plataforma de Observabilidade e Gerenciamento e Capacidades Híbridas. E por último, mas não menos importante, discutirei nossos preços diferenciados, SLA e opções de suporte.

No início do curso, mostrarei como criar uma conta de nível gratuito do Oracle Cloud e demonstrar vários serviços e recursos usando essa conta de nível gratuito. Espero que você crie sua própria conta de nível gratuito e acompanhe.

Ao longo do curso, usarei analogias divertidas para explicar tópicos complexos e aproveitar slides visuais para ajudá-lo a reter melhor as informações. Há uma verificação de habilidades no final de cada módulo. Assim, você pode validar seu conhecimento e ganhar confiança para passar no exame.

E, finalmente, entendemos que você está ocupado. Portanto, a maioria das nossas aulas do curso duram menos de 5 minutos. Nosso objetivo é ajudá-lo a reter informações e mantê-lo engajado. Espero que você esteja tão empolgado quanto eu para começar este curso. Obrigado por se inscrever.

Vamos começar.

## 2- OCI Introdução

### OCI Overview

Algumas das maiores empresas do mundo estão executando suas cargas de trabalho de missão crítica na plataforma de nuvem de próxima geração da Oracle chamada Oracle Cloud Infrastructure. E hoje, estou muito animado para contar mais sobre isso. Nesta lição, você verá uma visão geral do que pode fazer no OCI. Vamos começar.

Para simplificar, vamos dividi-los em sete categorias principais: Infraestrutura central, Serviços de banco de dados, Dados e IA, Análise, Governança e administração, Serviços para desenvolvedores e Serviços de aplicativos.

Mas primeiro, a base de qualquer plataforma de nuvem é a presença global das regiões. Temos muitas regiões geralmente disponíveis no mundo, juntamente com suporte Multi-Cloud com Microsoft Azure e uma oferta híbrida diferenciada chamada Dedicated Region Cloud at Customer.

Temos blocos de construção em cima dessa presença global, as sete categorias que acabamos de mencionar. Na parte inferior, temos as primitivas centrais - computação, armazenamento e rede. Os Serviços de Computação abrangem Máquinas Virtuais, Servidores Bare Metal, contêineres, um Serviço Kubernetes gerenciado e um Serviço VMWare gerenciado.

Esses serviços são principalmente para realizar cálculos, executar lógica e executar aplicativos. O armazenamento em nuvem inclui discos anexados a máquinas virtuais, armazenamento de arquivos, armazenamento de objetos, armazenamento de arquivos e serviços de migração de dados. A OCI oferece uma gama completa de serviços de armazenamento para você armazenar, acessar, controlar e analisar seus dados estruturados ou não estruturados.

Os recursos de rede permitem que você configure redes privadas definidas por software no Oracle Cloud. A OCI fornece o conjunto mais amplo e profundo de serviços de rede com a mais alta confiabilidade, a maioria dos recursos de segurança e o mais alto desempenho.

Depois temos os Serviços de Banco de Dados, temos vários tipos de serviços de banco de dados, tanto Oracle quanto de código aberto. Somos a única nuvem que executa bancos de dados autônomos e vários tipos deles, incluindo OLTP, OLAP e JSON.

E então você pode executar bancos de dados e máquinas virtuais, servidores Bare Metal ou até Exadata na nuvem. Você também pode executar bancos de dados de código aberto, como MySQL e NoSQL no Oracle Cloud Infrastructure.

Data and AI Services, temos um serviço gerenciado Apache Spark chamado Dataflow, um serviço gerenciado para rastrear artefatos de dados em OCI chamado Data Catalog e um serviço gerenciado para ingestão de dados e ETL chamado Data Integration.

Também temos uma plataforma de ciência de dados gerenciada para modelos e treinamento de machine learning. Também temos um serviço Apache Kafka gerenciado para casos de uso de streaming de eventos.

Então temos os serviços de Governança e Administração, esses serviços incluem segurança, identidade e observabilidade e gerenciamento. Temos recursos exclusivos, como compartimentos, que facilitam operacionalmente o gerenciamento de ambientes grandes e complexos. A segurança está integrada em todos os aspectos da OCI, seja detecção ou correção automática, o que normalmente chamamos de Cloud Security Posture Management, proteção de rede robusta ou criptografia por padrão.

Temos uma plataforma integrada de observabilidade e gerenciamento com recursos como registro, análise de registro e gerenciamento de desempenho de aplicativos e muito mais.

Então nós temos um monte de serviços para desenvolvedores. Temos um serviço gerenciado de baixo código chamado APEX, vários outros serviços para desenvolvedores e um serviço gerenciado Terraform chamado Resource Manager.

Para análises, temos um serviço de análise gerenciada chamado Oracle Analytics Cloud que se integra a várias soluções de terceiros.

Em Serviços de aplicativo, temos uma oferta sem servidor gerenciada, funções de chamada e gateway de API e um Serviço de eventos para ajudá-lo a criar microsserviços e arquiteturas orientadas a eventos.

Temos um conjunto abrangente de SaaS conectado em todo o seu negócio, finanças, recursos humanos, cadeia de suprimentos, fabricação, publicidade, vendas, atendimento ao cliente e marketing, todos executados em OCI.

Essa é uma longa lista. E essas sete categorias e os serviços mencionados representam apenas uma pequena fração dos mais de 80 serviços atualmente disponíveis no OCI.

Felizmente, é rápido e fácil experimentar um novo serviço usando nossa conta de nível gratuito líder do setor. Somos a primeira nuvem a oferecer um servidor por apenas um centavo por hora de núcleo.

Esteja você começando com o Oracle Cloud Infrastructure ou migrando todo o seu conjunto de dados para ele, podemos apoiá-lo em sua jornada para a nuvem. É isso. OCI, uma plataforma de nuvem ampla e profunda. Obrigado por assistir.


### OCI Arquitetura

Bem-vindo a esta lição sobre Arquitetura OCI. Nesta lição, abordaremos as principais construções da arquitetura física da OCI, começando pelas regiões. Região é uma área geográfica localizada composta por um ou mais domínios de disponibilidade.

Os meios de disponibilidade são um ou mais data centers tolerantes a falhas localizados em uma região, mas conectados entre si por uma rede de baixa latência e alta largura de banda. Os domínios de falha são um agrupamento de hardware e infraestrutura dentro de um domínio de disponibilidade para fornecer antiafinidade. Portanto, pense neles como data centers lógicos.

Nós vimos isso na lição anterior. Hoje, a OCI tem uma enorme presença geográfica em todo o mundo, com várias regiões em todo o mundo. E também temos uma parceria multinuvem com o Microsoft Azure. E temos uma oferta diferenciada de nuvem híbrida chamada Dedicated Region Cloud@Customer.

Mas antes de mergulharmos na arquitetura física, vejamos como você escolhe uma região? A primeira coisa é escolher uma região, você escolhe uma região mais próxima de seus usuários para menor latência e maior desempenho. Então esse é um critério fundamental.

O segundo critério-chave é a residência de dados e os requisitos de conformidade. Muitos países têm requisitos rígidos de residência de dados e você deve cumpri-los. E assim você escolhe uma região com base nesses requisitos de conformidade.

O terceiro critério-chave é a disponibilidade do serviço. Novos serviços em nuvem são disponibilizados com base na demanda regional às vezes, motivos de conformidade regulatória, disponibilidade de recursos e vários outros fatores. Tenha estes três critérios em mente ao escolher uma região.

Então, vamos olhar para cada um deles com um pouco mais de detalhes. Domínio de disponibilidade. Os domínios de disponibilidade são isolados uns dos outros, tolerantes a falhas e muito improváveis ​​de falhar simultaneamente. Como os domínios de disponibilidade não compartilham infraestrutura física, como energia ou refrigeração ou a rede interna, uma falha que afete um domínio de disponibilidade provavelmente não afetará a disponibilidade de outros.

Então, como você pode ver neste gráfico aqui, uma determinada região tem três domínios de disponibilidade. Um domínio de disponibilidade tem algum tipo de interrupção, não está disponível. Mas os outros dois domínios de disponibilidade ainda estão funcionando.

Falamos sobre domínios de falhas um pouco antes. O que são domínios de falha? Pense que cada domínio de disponibilidade tem três domínios de falha. Portanto, pense nos domínios de falha como data centers lógicos dentro do domínio de disponibilidade.

Então, como você pode ver na imagem aqui, temos três domínios de disponibilidade e cada um deles tem três domínios de falha. Então a ideia é você colocar os recursos em diferentes domínios de falha, e eles não compartilham um único ponto de falha de hardware, como servidores físicos, rack físico, tipo de switch de rack, uma unidade de distribuição de energia. Você pode obter alta disponibilidade aproveitando domínios de falha.

Também aproveitamos domínios de falhas para nossos próprios serviços. Portanto, em qualquer região, os recursos nesse domínio de falha estão sendo ativamente alterados a qualquer momento. Isso significa que os problemas de disponibilidade causados ​​por procedimentos de mudança são isolados no nível do domínio da falha. Além disso, você pode controlar o posicionamento das instâncias do banco de dados do computador para o domínio de falha no momento da inicialização da instância. Assim, você pode especificar qual domínio de falha deseja usar.

Então, qual é a orientação geral? A orientação geral é que temos essas construções, como domínios de falha e domínios de disponibilidade, para ajudá-lo a evitar pontos únicos de falha. Fazemos isso por conta própria.

Assim, garantimos que os servidores, o switch do topo do rack, sejam todos redundantes. Assim você não tem falhas de hardware ou tentamos minimizar ao máximo essas falhas de hardware. Você precisa fazer o mesmo quando estiver projetando sua própria arquitetura.

Então vamos ver um exemplo. Você tem uma região. Você tem um domínio de habilidade. E como dissemos, um AD tem três domínios de falha, então você vê esses domínios de falha aqui.

Então, a primeira coisa que você faz é quando você cria um aplicativo, você cria essa rede virtual definida por software. E então vamos dizer que é uma aplicação muito simples. Você tem uma camada de aplicativo. Você tem uma camada de banco de dados.

Então, a primeira coisa que você pode fazer é executar várias cópias do seu aplicativo. Portanto, você tem uma camada de aplicativo que é replicada em domínios de falha. E então você tem um banco de dados, que também é replicado em domínios de falha.

Porque você faz isso? Bem, dá-lhe essa camada extra de redundância. Então, algo acontece com um domínio de falha, seu aplicativo ainda está em execução.

Agora, para ir para a próxima etapa, você pode replicar o mesmo design em outro domínio de disponibilidade. Portanto, você pode ter duas cópias do seu aplicativo em execução. E você pode ter duas cópias do seu banco de dados em execução.

Agora, uma coisa que surgirá é como você garante que seus dados estejam sincronizados entre essas cópias? Assim, você pode usar várias tecnologias, como o Oracle Data Guard, para garantir que seus dados primário e de espera - os dados sejam mantidos em sincronia aqui. E para que -- você possa projetar seu aplicativo -- seu arquiteturas como essas para evitar pontos únicos de falha. Mesmo para regiões onde temos um único domínio de disponibilidade, você ainda pode aproveitar a construção de domínio de falha para obter alta disponibilidade e evitar pontos únicos de falha.

Vamos resumir o que aprendemos nesta lição. Então nós olhamos para a região. A região é composta por domínios de disponibilidade. Os domínios de disponibilidade são compostos por domínios de falha.

Então, vamos olhar para a visão de dentro para fora. Então, primeiro, vamos começar com o domínio de falha. O domínio de falha fornece proteção contra falhas em um domínio de disponibilidade.

O domínio de disponibilidade em si fornece proteção contra falhas de domínio de disponibilidade inteira, principalmente em uma região multi-AD. E então você tem esse conceito de par de regiões, onde em cada país que operamos ou na maioria dos países que operamos, temos pelo menos dois data centers. Assim, você pode usar o segundo centro de dados para recuperação de desastres ou backup ou também ajuda a cumprir os requisitos de conformidade e residência de dados. E além disso, também temos SLAs sobre disponibilidade, gerenciamento e desempenho.

Para recapitular, analisamos a arquitetura física da OCI com regiões que são geolocalizações. Analisamos os domínios de disponibilidade. Cada região tem três domínios de disponibilidade.

E então cada domínio de disponibilidade tem três domínios de falha. Portanto, use essas construções arquitetônicas para projetar seus aplicativos altamente disponíveis e evitar pontos únicos de falha. Obrigado por assistir. 


### Exercicios

Teste: Verificação de Habilidade: Introdução ao OCI
Responda a(s) pergunta(s) nesta página. Em seguida, clique em Enviar respostas para ver o feedback.

### Exercicios Introdução ao OCI

(Responda a todas as perguntas nesta seção)

1. Qual afirmação descreve com precisão uma região OCI?

- [ ] Cada Domínio de Falha possui vários Domínios de Disponibilidade.
- [ ] Cada Domínio de Disponibilidade tem um único Domínio de Falha.
- [ ] Cada região tem um único domínio de falha.
- [x] Cada Domínio de Disponibilidade tem três Domínios de Falha.

2. Qual construção OCI protege contra falhas em um domínio de disponibilidade?

- [ ] Arrendamento
- [ ] Balanceador de carga
- [ ] Compartimentos
- [ ] Regiões
- [x] Domínio de falha

3. Qual afirmação é verdadeira sobre a arquitetura OCI e seus componentes principais?

- [x] Cada domínio de disponibilidade tem três domínios de falha.
- [ ] Cada domínio de falha tem três domínios de disponibilidade.
- [ ] Todas as regiões OCI têm três domínios de disponibilidade.
- [ ] Os domínios de falha atuam como data centers físicos em um domínio de disponibilidade.

4. Você se inscreveu em uma região OCI, que possui um único domínio de disponibilidade. Você deseja implantar um aplicativo altamente disponível com dois servidores Web e um banco de dados de 2 nós.

Como você colocaria os componentes para manter a alta disponibilidade do aplicativo?

- [x] Coloque um servidor e um nó de banco de dados em um domínio de falha e o segundo servidor e um nó de banco de dados em outro domínio de falha.
- [ ] Coloque todos os componentes no mesmo domínio de falha.
- [ ] Coloque os servidores em um domínio de falha e os nós do banco de dados em outro domínio de falha.
- [ ] A alta disponibilidade não é possível porque há apenas um domínio de disponibilidade na região.


Correto. Os domínios de falha fornecem antiafinidade: eles permitem que você distribua suas instâncias para que as instâncias não estejam no mesmo hardware físico em um único domínio de disponibilidade. Uma falha de hardware que afeta um domínio de falha não afeta instâncias em outros domínios de falha.

5. Qual afirmação é verdadeira sobre OCI?

- [x] Uma região OCI é uma área geográfica localizada.
- [ ] Um domínio de disponibilidade é um datacenter lógico.
- [ ] Os domínios de disponibilidade compartilham infraestrutura como energia, refrigeração ou rede de domínio de disponibilidade interna em uma região.
- [ ] Um único domínio de falha pode ser associado a vários domínios de disponibilidade em uma região.

Correto. O Oracle Cloud Infrastructure é hospedado em regiões e domínios de disponibilidade. Uma região é uma área geográfica localizada.

## 3- Oracle Cloud Free Tier Account


###  Oracle Cloud Free Tier Sign-up

Bem vindo.

Nesta lição, vou orientá-lo no processo de criação de uma conta do Oracle Cloud FreeTier. Mas antes de fazermos isso, vamos primeiro discutir o que é o Oracle Cloud FreeTier. O Oracle Cloud FreeTier permite que você se inscreva em uma conta do Oracle Cloud, que fornece vários desses serviços gratuitos e uma avaliação gratuita, os US$ 300 de crédito gratuito para usar em todos os serviços OCI qualificados por até 30 dias. Então é uma combinação de duas coisas diferentes. Vamos falar um pouco mais sobre estes.

Os serviços Sempre Gratuitos estão disponíveis por um período de tempo ilimitado para qualquer pessoa. A avaliação gratuita, por outro lado, deve ser usada até que seus US$ 300 em créditos gratuitos sejam consumidos ou os 30 dias tenham expirado, o que ocorrer primeiro. Portanto, o processo de criação da conta do Oracle Cloud FreeTier é bastante simples. Deixe-me guiá-lo através dele.

Então aqui estou eu na página da web Oracle.com/cloud/free. E você pode ver este botão aqui, que é Iniciar de graça. Se eu tivesse uma conta existente, clicaria aqui, entraria no Oracle Cloud e isso me permitiria acessar minha conta real. Eu não tenho um. Vou orientá-lo sobre como criar um de graça.

Então deixe-me clicar neste botão aqui. E enquanto eu faço isso, ele está me pedindo algumas informações importantes. A primeira coisa é o meu país. E deixe-me apenas clicar aqui. Então, ele está pedindo para fornecer um nome. E está pedindo um ID de e-mail.

E aqui embaixo você vê um captcha, uma resposta de desafio para verificar se os bots automatizados não estão usando mal esse sistema. Então eu clico aqui dizendo que sou humano. E então, quando faço isso, está me pedindo para verificar isso. É o típico desafio captcha tradicional. Assim diz, por favor clique em cada imagem que contém um barco. Deixe-me certificar-me de que posso verificar todos os barcos aqui. Este é um barco. Isso pode ser um barco. Clique em próximo.

Contendo um barco. Definitivamente um barco, definitivamente um barco aqui, barco aqui, barco aqui, e verifique. E isso deve me deixar entrar, verificando que sou humano. E então eu preciso verificar meu e-mail. Então clique aqui. E ele me enviará um e-mail com uma etapa de verificação solicitando que eu verifique isso. E esse é o primeiro passo para abrir uma conta. Deixe-me pausar o vídeo aqui e verificar minha conta de e-mail.

Acabei de verificar meu ID de e-mail. E agora está me pedindo para fornecer mais informações aqui. Então, a primeira coisa que preciso fazer é inserir uma senha válida. Então deixe-me digitar um aqui. E está feliz com essa senha. Deixe-me apenas confirmar novamente.

Tudo bem. E então ele está me pedindo um nome de empresa. Providencie isso aqui. E está pedindo um nome de conta na nuvem. Agora, essa conta pode não estar disponível, então deixe-me usar uma que vamos usar para este curso de treinamento.

Este é um treinamento da OCI Foundations. E na minha região de origem, está me pedindo para selecionar a região de origem. E vamos rolar para baixo aqui e escolher na América do Norte. Então vou escolher a região mais próxima de mim seria o Oeste dos EUA, San Jose. Então eu escolheria isso. Então clique em Continuar.

E então o próximo passo seria inserir todas as minhas informações aqui. Então deixe-me colocar o local do meu escritório. Preciso fornecer meu número de telefone. E agora está pedindo para adicionar uma carta de verificação de pagamento. Então eu preciso fornecer o número do meu cartão de crédito aqui. E então o cartão de crédito não é cobrado, a menos que você opte por atualizar esta conta. Então eu posso dizer cartão de crédito aqui. E então você adiciona o número do cartão de crédito aqui. Vou adicionar cartão Visa. Clique em Concluir aqui.

E agora eu preciso clicar nesta caixa aqui, que diz, eu concordo com os termos e condições aqui. E você pode ler mais sobre os termos e condições, se quiser. Há links aqui para que você possa ler mais aqui. Todas as informações parecem corretas. Incluí meu cartão. E clicarei em Iniciar minha conta de avaliação gratuita.

E neste ponto, ele deve abrir minha própria conta de nível de avaliação gratuita, que é sempre gratuita e uma avaliação gratuita com US $ 300 para ser consumida em 30 dias. E assim que esse processo estiver concluído -- pode levar alguns minutos -- terei uma conta Oracle Cloud FreeTier. Parece que, enquanto eu estava fazendo isso, levei alguns segundos. E aqui estou eu. Esta é minha conta do Oracle Cloud. Espero que você tenha achado esta lição útil. 

### Demo: OCI console walk-through

Bem vindo de volta. Nesta lição, veremos como você pode começar a usar o console OCI. Portanto, a primeira coisa que você faz para acessar o console OCI é acessar cloud.oracle.com e clicar no nome da sua conta Cloud aqui. Em um dos vídeos anteriores, abrimos uma conta FreeTier. E nomeamos a conta como treinamento de fundamentos OCI, pois isso faz parte do treinamento de fundamentos OCI. Por isso, forneci o nome da conta do Cloud aqui. E então você clica em Avançar.

Ao fazer isso, ele vai me pedir um nome de usuário e senha. Também poderíamos fazer o logon único de federações de identidade, mas isso está além do escopo deste curso introdutório. Então vamos pular. E vou apenas fornecer meu nome de usuário aqui.

Agora, este é o nome de usuário que usei com esta conta em particular. E deixe-me inserir minha senha. E com isso, estou autenticado no console da web.

Então, o que é esse console da web? O console da Web é a interface de usuário baseada na Web simples e intuitiva que você pode usar para acessar e gerenciar o Oracle Cloud Infrastructure. Assim, ao fornecer meu nome de usuário e senha, sou autenticado. Estou no console aqui. Deixe-me guiá-lo por algumas das principais características do console e algumas das coisas que podem ajudá-lo a começar rapidamente.

Então aqui na barra de navegação esquerda você vê este ícone. Se você clicar nele, ele abrirá o painel de navegação do serviço. E você pode ver todas as principais categorias de serviços que temos, começando com computação, armazenamento, rede, bancos de dados e alguns dos outros serviços. Se você quiser acessar recursos individuais ou serviços individuais dentro de uma categoria, basta clicar aqui, por exemplo, em computação, e eu posso abrir instâncias, posso criar instâncias ou gerenciá-las aqui. Ou eu também poderia abrir um serviço, que faz parte da computação, chamado gerenciamento de SO. Eu poderia trabalhar nisso.

E se você estiver com algumas camadas de profundidade aqui e quiser voltar ao menu principal, basta clicar neste ícone novamente. E traz você de volta ao painel de navegação do serviço. Portanto, este é o painel que você usaria muito à medida que avançamos e fazemos várias demos. Este seria o nosso ponto de partida. Então esse é o número um.

Número dois, quero mostrar a você esse recurso de pesquisa. Então, se eu quiser procurar por algum recurso, eu poderia vir aqui e procurar por esses recursos. Por exemplo, se eu quiser ver quem são meus usuários nessa locação específica, posso fornecer a palavra-chave como usuários. E isso traria a lista de todos os usuários que existem nesta locação no momento. Eu sou o administrador do aluguel, então meu nome está listado aqui. Não há outros usuários no momento.

Portanto, a pesquisa é realmente útil quando você realmente precisa descobrir algo rapidamente. Você pode fazer pesquisas simples, assim como fazer pesquisas complexas usando algo chamado Advanced Resource Query. E vamos analisá-lo posteriormente.

A terceira coisa que quero falar são as regiões. Se você clicar na região aqui, esta é a minha região de origem. A região de origem é a região que você fornece quando se inscreve em uma conta. E você pode ver que a região de origem está listada aqui.

Mas posso ter acesso a outras regiões também. Ao clicar nele, você pode ver que existem muitas regiões disponíveis nos EUA e em todo o mundo. Se eu quiser me inscrever em uma região específica, basta clicar em Inscrever-se aqui. E isso me permitiria assinar essa região específica, o que significa que posso criar recursos nessas regiões. Veremos isso em algumas das demonstrações subsequentes. Por enquanto, estou bem em ter acesso a apenas uma região, que é minha região de origem aqui.

Eu também tenho essa coisa aqui, que é o Cloud Shell. E o Cloud Shell é um terminal baseado em navegador da Web acessível no console do Oracle Cloud, como você pode ver aqui. Em segundo plano, o Cloud Shell é uma pequena máquina virtual, que executa um shell bash que você acessa por meio do console OCI. E você pode usá-lo para executar comandos que você realmente não precisa instalar. A CLI está instalada aqui, a interface de linha de comando OCI. Então você não precisa fazer essa instalação local.

Então pense em acessar recursos no navegador. E você pode ficar no navegador. Você não precisa de nenhum tipo de dependência de máquina local para SSH em suas máquinas Unix ou executar qualquer tipo de CLI localmente em sua máquina. Você pode usar o Cloud Shell para todas essas atividades.

E aqui está o ícone nos anúncios. E se houver anúncios no OCI, todos eles estão listados aqui. Então, para conhecer todas as coisas da OCI, basta clicar aqui e ver as novidades que apareceram. Há o ícone de ajuda aqui que você pode usar para criar uma solicitação de suporte. Você pode visualizar essas solicitações de suporte. E você também pode solicitar o aumento do limite de serviço usando esses links aqui. Então, alguns links realmente úteis para suporte.

Há também uma opção de chat ao vivo. E isso em segundo plano roda o Oracle Digital Assistant. E para qualquer tipo de ajuda que você precisa com sua locação ou em geral você está procurando recursos, você pode usar o assistente virtual para isso. Então, você pode chamar ng as línguas. Acho que hoje suportamos 29 idiomas e a lista continua aumentando. Portanto, se você deseja alterar o idioma do navegador para outro idioma que não seja o inglês, clique no menu suspenso aqui.

E, finalmente, há o meu perfil de usuário. Eu sou o administrador do arrendamento. Portanto, se eu clicar em Configurações do usuário aqui, posso ver algumas das configurações rápidas da minha conta. Posso habilitar a autenticação multifator. Essa é uma boa prática recomendada para aplicar. Falaremos sobre isso em uma lição subsequente. E posso obter mais informações aqui -- coisas como meus tokens de autenticação, etc.

Portanto, este é apenas um passo a passo rápido do console OCI. 

### Demo: Setting up your tenancy

Bem-vindo à nossa lição sobre como configurar sua própria locação. Depois que a Oracle criar sua locação no OCI, um administrador de sua empresa precisará executar um conjunto de tarefas e estabelecer um plano organizacional para seus recursos e usuários da Nuvem. Vamos ver rapidamente como você pode fazer isso.

Portanto, a primeira coisa a entender é quando nos referimos como o que chamamos de locação também é chamado de compartimento raiz. Existe um conceito de compartimentos na OCI, que são isolamentos lógicos que podem ser usados ​​para controle de acesso e isolamento lógico de seus recursos. Veremos o que isso significa no módulo e nas lições de gerenciamento de identidade e acesso. Mas, por enquanto, lembre-se de que quando nos referimos como locação, às vezes também é chamado de compartimento raiz.

Agora, quando você configura sua conta -- quando você, por exemplo, se inscreve para a conta FreeTier Oracle Cloud, a Oracle cria um administrador de locação para você. E esta é a pessoa que configura a conta com seu ID de e-mail. E assim configuramos este primeiro usuário. E também colocamos esse usuário como parte de um grupo. E esse grupo é chamado de administradores.

Esta é uma palavra-chave reservada. E você não pode mudá-lo. E o que torna esse grupo realmente poderoso é essa política específica aqui, que permite que esse grupo específico - administradores - gerencie esse é o nível mais alto de acesso a todos os recursos do painel, ou seja, todos os recursos, todos os recursos nessa locação específica. Locação significa sua conta.

E não se preocupe se alguns desses itens não estiverem claros para você -- usuários, grupos, políticas. Vamos analisá-los no módulo de gerenciamento de identidade e acesso. E, claro, sua conta vem com limites de serviço. E você pode enviar uma solicitação de suporte para aumentar esses limites de serviço.

Também vou falar sobre três práticas recomendadas para aplicar desde o início. Portanto, o compartimento raiz - ou sua locação - pode conter todos os recursos do Cloud. Você pode colocar seus recursos de computação aqui, seu armazenamento, seus bancos de dados, rede, tudo como parte do seu compartimento raiz. Mas a melhor prática é criar compartimentos dedicados para isolar recursos.

Por quê? A ideia dos compartimentos é permitir que você compartimentalize seus recursos, isole-os logicamente para que você possa fornecer o nível certo de acesso aos usuários para esses recursos. Portanto, não coloque todos os seus recursos de nuvem no compartimento raiz. Essa definitivamente não é a melhor prática.

A segunda coisa a ter em mente é que seus administradores de locação devem sempre criar outros administradores ou administradores e permitir que esses administradores gerenciem a conta. Então o que quero dizer com isso? Como você pode ver aqui, há um administrador de locação. E esse administrador específico foi em frente e criou alguns administradores aqui. Por falta de uma palavra melhor, estamos nos referindo a eles como administradores de serviço. Mas estes podem ser qualquer tipo de administradores -- administradores de projeto, administradores de segurança, administradores de serviço, qualquer que seja a forma de categorizar suas contas.

E esses administradores pertencem a seus próprios grupos e têm seu próprio conjunto de políticas. Então, apenas para ficar com este exemplo, temos alguns administradores de serviço para armazenamento e rede. E eles pertencem ao grupo de administradores de armazenamento porque, na prática, você sempre terá mais de um tipo de administrador ou algumas pessoas que são administradores como parte de um grupo específico, ou pelo menos mais de uma pessoa.

A prática recomendada aqui é não usar a conta de administrador de locação para operações diárias. Deve ser reservado apenas para certos tipos de propósitos de correção. E você deve ter seus administradores de serviço realmente cuidando dos usuários e gastos de recursos e gerenciando essa conta. Essa é a nossa segunda melhor prática.

A terceira prática recomendada é proteger sua conta. Você deve impor o uso da autenticação multifator. Portanto, a autenticação multifator é uma autenticação de duas etapas em que você sabe uma coisa, sua senha. E então você tem algo, como um dispositivo, que pode ser usado para autenticar seu usuário. Portanto, é sempre uma boa prática impor o uso da autenticação multifator.

Então, essas são as três melhores práticas. Mantenha-os em mente. Alguns desses itens podem não estar claros agora. À medida que entrarmos nas lições subsequentes, elas ficarão claras. Deixe-me ir rapidamente ao console e mostrar alguns deles em ação.

Então aqui estou eu no meu console do Cloud. E os usuários, grupos e políticas fazem parte dos serviços de configuração de identidade e segurança. Então, podemos clicar em identidade e segurança aqui. Em identidade, posso ver usuários, grupos e políticas.

Então, se eu apenas clicar em Usuários aqui, rapidamente quero mostrar a você que tenho meu usuário. Este é o ID de e-mail do usuário que usei para me inscrever nesta conta. E assim posso ver que este usuário em particular está disponível aqui. E é parte do grupo de disco chamado administradores.

E se eu voltar aos meus grupos aqui, posso ver que atualmente tenho apenas um grupo. Chama-se administradores. E há apenas um membro neste grupo. Eu posso criar qualquer coisa disso quando eu provar iso minha conta. A Oracle fez isso por mim. Este é o meu administrador de locação. E este é o meu grupo de administradores de arrendamento. E é chamado de Administradores. Essa é uma palavra-chave reservada.

E a última coisa que quero mostrar são as políticas. E esta é uma política de administração de locatário padrão que novamente foi criada pela Oracle como uma provisão por conta. E dá a esse grupo específico e a todos os usuários desse grupo acesso para gerenciar todos os recursos nessa locação específica, sendo a locação essa conta.

A última coisa sobre a qual não falamos realmente sobre esses conceitos são os compartimentos. E posso ver aqui que tenho um compartimento raiz, que também é -- se você ver o ano do texto, também é o mesmo nome do meu arrendamento. Lembre-se, este é o nome da dependência que abrimos. Então tenancy/rootcompartment. Prefira a mesma coisa. E diz aqui compartimento raiz da locação.

Agora, posso colocar todos os meus recursos aqui, ou posso criar compartimentos individuais. Há um compartimento já criado por padrão. Novamente, é um curso introdutório, então não precisamos entrar em alguns desses tópicos mais avançados. Mas eu poderia vir aqui e poderia criar mais compartimentos.

Espero que essa tenha sido uma visão geral rápida de como você configurou sua locação e as primeiras etapas que você dá à medida que sua conta é provisionada. E, posteriormente, a partir daqui, você criaria usuários, criaria grupos, criaria esses administradores, escreveria políticas e criaria compartimentos. Veremos alguns deles no módulo de gerenciamento de identidade e acesso. Espero que você tenha achado esta lição útil.

### Demo: MFA and Budget setup

Bem vindo de volta. Nesta demonstração específica, veremos como você pode configurar a autenticação multifator. Como vimos em uma das lições teóricas, é uma prática recomendada aplicar a autenticação multifator -- ou MFA -- especialmente para seus administradores, como os administradores de locações, porque esses logins precisam ser realmente seguros. Portanto, é uma boa ideia usar a autenticação multifator para seus administradores, especialmente para seu administrador de locação.

Então, aqui na página de documentação, você pode ver todos os detalhes sobre como trabalhar com MFA. As duas coisas que quero destacar são as pessoas que não estão familiarizadas com o MFA, basicamente, é uma autenticação de dois fatores onde você inclui algo que você conhece, como uma senha, e depois algo que você tem, como um dispositivo. E você pode ler sobre os conceitos gerais aqui.

A única coisa que quero apontar na documentação é que você precisa de um aplicativo autenticador. E este é um aplicativo que você instala em seu dispositivo móvel que pode fornecer token seguro baseado em software para verificação de identidade. Agora, os dois aplicativos de autenticação móvel suportados são o Oracle Mobile Authenticator e o Google Authenticator. E esses são os dois suportados aqui atualmente. E você pode ler mais sobre alguns dos detalhes aqui.

Então, vamos em frente e configurar o MFA para nosso administrador de locação. Então aqui estou logado como meu administrador de locação. Se eu clicar em Configurações do usuário, você verá que minhas configurações de usuário aparecem aqui. E aqui está um botão, que habilita a autenticação multifator. Então deixe-me ir aqui e clicar neste botão em particular.

E então traz as etapas a serem executadas para habilitar o MFA. Portanto, no meu dispositivo, tenho o Google Authenticator. Então eu só vou usar isso. Deixe-me apenas trazê-lo e tirar uma foto. Eu tenho que escanear este código QR. E eu consegui. E agora preciso inserir o código que é exibido no meu dispositivo. E eu clico em verificar.

E é isso. Agora meu MFA está ativo. E a maneira que eu usaria é-- deixe-me apenas sair e entrar novamente. E ele me pediria minha autenticação de segundo fator. Então eu vou sair. E eu vou entrar novamente. Este é o meu administrador de locação.

E eu clico aqui. E está me pedindo uma senha de uso único. E essa senha, novamente, posso obter do meu dispositivo móvel de um dos autenticadores que tenho. E eu insiro esse número. E eu devo ser capaz de fazer login agora. Portanto, isso é tão simples quanto o processo de configuração do MFA. Definitivamente algo a considerar, especialmente para suas contas de administrador.

A segunda coisa que quero mostrar rapidamente aqui é configurar um alerta de cobrança. Sei que abordaremos vários deles em governança e administração, mas é uma boa prática recomendada configurar seus orçamentos e alertas de cobrança. E deixe-me mostrar como você faz isso ao abrir uma nova conta, por exemplo. Então clique em Criar Orçamento aqui. E agora eu posso definir um orçamento, escopo em um compartimento ou há algo chamado imposto de rastreamento de custos que eu poderia usá-los.

Então, digamos que estou usando isso -- ao longo deste curso, estamos usando o compartimento sandbox. Então eu diria que é o orçamento do sandbox. E aqui eu poderia escolher meu compartimento. E eu vou escolher meu compartimento sandbox aqui porque é isso que eu quero realmente ver sobre que tipo de custo usa em um compartimento específico. Posso inserir um valor de orçamento mensal.

Agora, eu poderia usar um número muito pequeno aqui apenas para fins de demonstração. Na prática, você estaria usando algo muito maior. E o dia do mês para iniciar esse processo orçamentário-- e se você quiser ser o primeiro dia ou seu mês fiscal não estiver alinhado ao mês do calendário diferente, você pode fazer isso aqui.

E então você pode criar uma regra de alerta de orçamento aqui. Você pode ver que a métrica de limite que é violada é o gasto real ou o gasto previsto. Eu vou dizer que é um gasto real. E você também pode escolher uma porcentagem limite para que seu alerta seja acionado quando o orçamento atingir uma porcentagem especificada do orçamento total ou um valor especificado. Eu direi que quando atingir 90%, você deve me enviar um e-mail.

E então eu posso fornecer meus destinatários de e-mail aqui. Deixe-me fornecer o e-mail do administrador da locação. E eu poderia inserir mensagem aqui. Então eu clico em Criar. E agora meu alerta de orçamento foi criado.

Então, sempre que eu exceder os $10 -- eu vou 90% desse valor de $ 10 -- eu recebo um e-mail. Também é sempre uma boa prática, principalmente quando você está abrindo sua conta. Faça esse tipo de configuração para não ter nenhum tipo de surpresa no faturamento.

Então, nesta demonstração rápida, vimos como você pode configurar a MFA e como configurar um alerta de cobrança. Estas são duas práticas recomendadas que você definitivamente deve aplicar ao abrir sua própria conta.

## 4- Identity and Access Management

### IAM Introduction

Bem-vindo a esta lição sobre OCI Identity and Access Management Service. Nesta lição específica, vamos ver rapidamente o que é o serviço IAM.

Portanto, IAM significa serviço de gerenciamento de identidade e acesso. E você ouviria esse termo chamado controle de acesso refinado. O controle de acesso refinado é um método de controlar quem pode acessar determinados recursos. Às vezes, também é chamado de controle de acesso baseado em função de retorno, que é a mesma coisa em que você controla o acesso usando funções e privilégios. Você define determinadas funções e fornece esses privilégios, privilégios específicos, a funções específicas.

Os dois conceitos-chave no gerenciamento de identidade e acesso estão relacionados à autenticação, também chamada de AuthN, que basicamente determina se você é a pessoa ou o recurso que você diz ser. Então, isso é tudo com o que a autenticação lida.

A autorização basicamente lida com que tipo de permissões você tem. Então lembre-se, Identity and Access Management Service, baseado em duas ideias centrais sobre autenticação -- quem é você e autorização, que tipo de permissões você tem.

Agora existem vários conceitos no Identity and Access Management Service, conceitos sobre usuários, princípios, grupos, políticas, compartimentos, recursos. E veremos cada um deles nas próximas lições. Mas vamos olhar para o conceito central aqui. Bem, a primeira coisa que você faz no gerenciamento de identidade e acesso é definir seus usuários. Você cria seus usuários.

Agora, os usuários podem ser seres humanos, como está sendo mostrado na tela aqui, ou os usuários podem ser serviços específicos ou podem ser instâncias de computação específicas. Por exemplo, em OCI, existe um conceito chamado princípio de instância. Basicamente, o princípio de instância permite que instâncias e aplicativos executados nessas instâncias façam chamadas de API em relação a outros serviços OCI.

Assim, os princípios podem ser seres humanos, podem ser instâncias de computação ou podem ser outros serviços. Pense no princípio como uma entidade de mensagens instantâneas que tem permissão para interagir com recursos OCI.

Então você agrupa esses usuários no que chamamos de grupos. Pense no grupo como uma coleção de usuários que precisam do mesmo tipo de acesso a um determinado conjunto de recursos. Assim, você pode criar grupos específicos de serviço, administradores de armazenamento, administradores de rede ou pode criar grupos com base em seus requisitos geográficos, ou seja, um grupo de usuários na América do Norte etc. Então você entendeu a idéia.

E então você escreve essas políticas que são basicamente a autorização. E eles decidem que tipo de permissões os usuários desses grupos específicos têm. E você escreve essas políticas em compartimentos, compartimentos específicos, que são entidades lógicas, para isolar e controlar o acesso de recursos, ou escreve suas políticas em toda a conta, sua locação.

E dentro de suas contas ou seus compartimentos residem os recursos reais. Então, os recursos, você literalmente através desse mecanismo está fornecendo acesso a esses recursos para um grupo de usuários escrevendo essas políticas. Portanto, esta é a equipe principal do OCI Identity and Access Management Service.

E examinaremos cada um deles com mais detalhes nas lições subsequentes. Então, uma coisa que você pode estar pensando é, bem, quais são esses recursos. Bem, os recursos são objetos de nuvem. Portanto, tudo o que você cria na nuvem, seja um armazenamento em bloco, armazenamento de objetos, instâncias de computação, bancos de dados, são recursos.

Então, como realmente identificamos esses recursos? Bem, você identifica esses recursos por meio de um identificador exclusivo chamado Oracle Cloud ID, ou OCID. Este é um valor exclusivo atribuído pela Oracle, identificador.

E pense no OCID como identificador exclusivo para recursos em um serviço OCI que contém metadados sobre os recursos. Então você vê esse tipo de sintaxe aqui, começa com OCID. E há um tipo de recurso, há algo chamado realm, há uma região e há uma string exclusiva aqui, um ID exclusivo.

Realm é basicamente um conjunto de regiões que compartilham entidades. Então você verá OCID1 sendo referido como um reino muitas vezes. OCID1 é basicamente o reino comercial que temos. Isso é o que significa OCID1.

Agora, se você observar alguns exemplos rápidos, há o OCID para uma locação. Então você pode ver que começa com OCID1, como acabamos de descrever. Então a locação aqui é a palavra-chave, que basicamente diz que esse identificador exclusivo OCID é para a locação. E OCID1 é o reino comercial. E então há a string única aqui.

Se você observar outro exemplo, um volume de bloco, agora poderá ver que ele começa com OCID1. Mas há um volume aqui que diz que esse tipo de recurso é um volume de bloco. OCID1 é o domínio comercial. Isso também tem uma região, porque o volume do bloco é um serviço regional ou construção regional. Então você vê esta região aqui, que diz que este volume de bloco é criado nesta região específica. E depois há o identificador exclusivo.

Na maioria das vezes, você não precisaria saber o OCID real, porque é um ID exclusivo atribuído pela Oracle e o sistema, o plano de controle, o plano de dados cuida disso. Você realmente não precisa saber  ou coloque-o em qualquer uma de suas políticas ou qualquer coisa. Mas é bom saber porque é assim que o controle e os planos de dados identificam um recurso de nuvem exclusivo.

Tão bem, é isso. Esta é apenas uma introdução rápida sobre o OCI Identity and Access Management Service. Lembre-se, o conceito central em torno de autenticação, autorização e, em seguida, você tem um grupo de usuários. E você dá a esses usuários do grupo acesso a determinados recursos escrevendo o que essas coisas são chamadas de políticas. E você escreve essas políticas em compartimentos ou locações.

Nas próximas lições, vamos nos aprofundar em cada um desses conceitos individuais. Obrigado por assistir. Espero que você tenha achado esta lição útil.

### AuthN AuthZ

Bem-vindo de volta a esta lição sobre autenticação e autorização. Antes de entrarmos em detalhes mais específicos, vamos ver o que é um principal? Um principal é uma entidade do IAM que tem permissão para interagir com recursos OCI.

Existem dois tipos de principais principalmente em OCI. Um deles são seus usuários. Pense nas pessoas que estão acessando seu console ou usando seus usuários CLI ou SDKs, seres humanos que realmente usam seus recursos de nuvem. E então os próprios recursos podem ser os principais. Portanto, um bom exemplo de um principal de recurso é um principal de instância que, na verdade, é uma instância que se torna um principal, o que significa que ele pode fazer chamadas de API em relação a outros serviços OCI, como armazenamento.

Além disso, quando falamos de princípios, temos grupos. E os grupos são basicamente uma coleção de usuários que possuem o mesmo tipo de requisitos de acesso aos recursos. Então você pode ter um grupo de administradores de armazenamento onde você pode agrupar todos os seres humanos que são administradores de armazenamento e assim por diante.

Vejamos alguns detalhes, começando pela autenticação. Às vezes, a autenticação também é chamada de AuthN. E como recapitulamos da lição anterior, a autenticação é basicamente descobrir quem você diz que é? E a maneira mais fácil de entender isso é que todos nós lidamos com isso diariamente. Quando você acessa nosso site e fornece seu nome de usuário e senha para acessar alguns dos conteúdos, você está sendo autenticado.

Existem outras maneiras de fazer autenticação. O único FOR Cloud comum são as chaves de assinatura de API. Portanto, ao fazer chamadas de API, seja usando o SDK ou a CLI, você usaria as Chaves de assinatura de API que usam um par de chaves públicas privadas para fazer -- para assinar essas chamadas de APIs e autenticar essas chamadas de APIs. Ele usa um par de chaves RSA, como você pode ver aqui, com uma chave pública e uma chave privada.

Há também uma terceira maneira de fazer autenticação, que é baseada em tokens de autenticação. E essas são strings de token geradas pela Oracle. E a ideia aqui é que você pode autenticar APIs de terceiros que não suportam o modelo de autenticação OCI.

Portanto, neste exemplo, estamos mostrando um ADW, chamando uma chamada de API ADW Autonomous Data Warehouse, onde estamos usando esses tokens AuthN. Ainda que sua identidade esteja sendo seguida, esses tokens AuthN podem ser usados ​​para essa finalidade.

Agora, vamos ver rapidamente a autorização. Então a autorização lida com permissões e descobrir quais permissões você tem? Na OCI, a autorização é feita por meio do que chamamos de políticas do IAM. E políticas, pense nisso como instruções legíveis por humanos para definir permissões granulares.

Então você tem alguns exemplos aqui. E a sintaxe da política é sempre algo semelhante. No próximo slide, falarei um pouco mais sobre o que essa afirmação significa.

Lembre-se de que as políticas podem ser anexadas a um compartimento ou podem ser anexadas a uma locação. Se eles estiverem vinculados a uma locação, isso se aplica a tudo dentro dessa locação. Se for aplicado a um compartimento, aplica-se apenas aos recursos desse compartimento.

Então, como o AuthZ é feito no OCI? Conversamos sobre políticas. Como é a sintaxe? Como você pode ver aqui, a sintaxe é sempre -- sempre você tem que começar com uma permissão. Tudo é negado por padrão, então você não precisa escrever uma declaração de negação.

Então você diz permitir group_name. Um grupo é basicamente uma coleção de usuários. Então você não pode escrever uma política para usuários individuais, você sempre opera em nível de grupo. Para fazer algo, há um verbo. Em alguns recursos, há um tipo de recurso e um local.

A localização pode ser um arrendamento. A localização pode ser um compartimento. E você pode tornar essas políticas realmente complexas com a adição de condições. E novamente, curso de fundamentos, então não estamos entrando em muitos desses tópicos complexos, mas você pode realmente escrever políticas complexas.

Então, só para dar uma ideia de como os verbos podem se parecer. Existem quatro níveis de verbo. Há um gerenciamento, um uso, uma leitura e uma inspeção. E à medida que você desce, eles se tornam aditivos.

Portanto, gerenciar basicamente significa que você pode gerenciar seus recursos, usar basicamente significa que você pode ler, mas não pode fazer coisas como atualizar e excluir e assim por diante. E você pode ler mais na documentação. O tipo de recurso basicamente pode ser todos os recursos, ou seja, tudo em sua conta, ou pode ser recursos de computador, recursos de banco de dados, outros enfeites, todos os recursos que você possui.

Agora, você pode operar em um nível de família, o que significa todas as entidades dentro dessa família de recursos, ou pode até ser muito granular. Então você poderia dizer que em computação, eu só quero que alguém opere nas instâncias, mas não trabalhe nas imagens dessas instâncias. Então você poderia realmente fazer isso.

Então é assim que você escreveria uma política. Existem algumas exceções a essa regra. Existem políticas que você escreveria para serviços e tal. Mas, novamente, é um curso básico, então não vamos entrar nesses detalhes avançados. Normalmente, é assim que você faria uma autorização no OCI.

Para encerrar, procuramos em como você faz uma autenticação no OCI, os três mecanismos, nome de usuário, senhas, chaves de login da API, tokens de autenticação. E então vimos como você faz a autorização no OCI por meio de políticas. As políticas são realmente poderosas, são muito fáceis de entender, legíveis por humanos. Mas, ao mesmo tempo, eles oferecem muitos recursos avançados para fazer -- implementar um controle de acesso realmente refinado.

### Compartments

Bem-vindo a esta lição sobre Compartimentos OCI. Os compartimentos são um recurso exclusivo da OCI. E estes são realmente poderosos, então vamos explorar.

Então, o que é um compartimento? Ao abrir uma conta no OCI, você obtém uma locação. Esse é outro nome chique para uma conta. E também oferecemos um Compartimento Raiz. Portanto, pense no Compartimento Raiz como essa construção lógica onde você pode manter todos os seus recursos de nuvem. E então o que você pode fazer é criar seus próprios compartimentos individuais, como você vê aqui.

Há um compartimento de rede. Há um compartimento de armazenamento. E a ideia é que você os crie para isolar e controlar o acesso. E você pode manter uma coleção de recursos relacionados em compartimentos específicos. Portanto, o recurso de rede tem -- um compartimento de rede possui recursos de rede e o compartimento de armazenamento possui recursos de armazenamento.

Agora, lembre-se, o Compartimento Raiz, como eu disse anteriormente, pode conter todos os recursos da nuvem. Então pode ser uma espécie de pia de cozinha. Você poderia colocar tudo lá. Mas a melhor prática é criar compartimentos dedicados para isolar recursos. Você vai ver o porquê. Deixe-me apenas explicar.

Então, a primeira coisa é que cada recurso que você cria pertence a um único compartimento. Então você cria uma máquina virtual, por exemplo. Ele vai para o Compartimento A. Ele não pode ir para o Compartimento B. Novamente, você precisa movê-lo do Compartimento A, ou excluir e recriar no Compartimento B. Lembre-se de que cada recurso pertence a um único compartimento.

O motivo pelo qual você deseja compartimentar seus recursos é mostrado exatamente neste slide. O motivo pelo qual você usa compartimentos em primeiro lugar é para controlar o acesso e o isolamento. Então, a maneira como você faz isso é, você tem os recursos, digamos, neste caso, um armazenamento em bloco, mantido no Compartimento A. Você não quer que eles sejam usados ​​por todos. Você deseja que eles sejam usados ​​apenas pelos administradores de computação e administradores de armazenamento.

Assim, você cria esses administradores como usuários e grupos, escreve essas políticas e eles podem acessar esses recursos neste compartimento. Então é muito importante. Não coloque todos os seus recursos no Compartimento Raiz. Crie compartimentos específicos de recursos ou da maneira que você quiser dividir suas locações e coloque os recursos de acordo.

Agora, como os recursos interagem se estiverem em compartimentos diferentes? Todos têm que estar no mesmo compartimento? Absolutamente não. Como você pode ver aqui, os recursos em um compartimento podem interagir com o recurso em outro compartimento. Aqui, a Virtual Cloud Network é -- a instância de computação usa a Virtual Cloud Network, mas elas estão em dois compartimentos diferentes. Portanto, isso é absolutamente suportado. E mantém seu design muito mais limpo.

Lembre-se de que os recursos também podem ser movidos de um compartimento para outro. Portanto, neste exemplo, o Compartimento A tinha uma máquina virtual. Podemos mover isso do Compartimento A para o Compartimento B. Outro conceito, que é muito importante entender, é que os compartimentos são construções globais, como tudo na identidade. Assim, os recursos de várias regiões podem estar no mesmo compartimento. Então, quando você vai para Phoenix, você vê esse compartimento existente. Você vai para Ashburn, você vê o mesmo compartimento.

Agora, você pode escrever políticas para impedir que usuários acessem recursos em uma região específica. Você poderia fazer isso. Mas lembre-se de que todos os compartimentos que você cria são globais e estão disponíveis em todas as regiões às quais você tem acesso. Os compartimentos também podem ser aninhados. Então você tem até seis níveis de aninhamento fornecidos por compartimentos. Você faria isso novamente porque isso pode imitar seu design atual, seja seu design organizacional ou sua hierarquia de ID. Você pode criar compartimentos aninhados. Isso apenas ajuda a manter seu design mais limpo.

E então, finalmente, você pode definir cotas e orçamentos em compartimentos. Então você poderia dizer que, no meu compartimento particular, você não pode criar uma máquina bare metal. Ou você não pode criar um recurso Exadata. Então você poderia controlá-lo assim. E então você também pode criar orçamentos em compartimentos. Então você poderia dizer que, se o uso em um compartimento específico ultrapassar $ 1.000, você será sinalizado e notificado. Então você poderia fazer isso.

Então isso é Compartimentos para você. É um recurso muito exclusivo dentro da OCI. Acreditamos que isso ajuda a manter suas locações muito melhor organizadas. E realmente suporta sua hierarquia e design de ID atuais.

### IAM Summary

Bem vindo de volta. Vamos recapitular o que você aprendeu neste módulo do IAM. IAM significa Gerenciamento de Identidade e Acesso. Analisamos como o IAM é implementado na OCI, incluindo autenticação e autorização. Em particular, analisamos a autorização, como ela é implementada usando políticas, como as políticas são poderosas e simples usando linguagem legível por humanos. E, finalmente, analisamos os compartimentos, como eles ajudam a isolar recursos dentro da OCI e controlar o acesso a esses recursos, e um recurso único e muito poderoso dentro da OCI.

### Exercicios

1. Qual recurso do serviço OCI Identity and Access Management (IAM) especifica a autorização para várias ações para principais autenticados?

- [x] Política
- [ ] Compartimento
- [ ] Grupo
- [ ] Função

2. Qual NÃO é um método válido para autenticar um Principal no serviço OCI Identity and Access Management (IAM)?

- [ ] Nome de usuário do console, senha
- [x] Chaves de criptografia mestre do Vault OCI
- [ ] Tokens de autenticação
- [ ] Chave de assinatura da API


3. Qual afirmação é verdadeira sobre o OCI Identity and Access Management (IAM)?

- [x] É usado para controlar o acesso aos recursos.
- [ ] Permite apenas a autorização para a locação.
- [ ] Ele habilita apenas a autenticação para a locação.
- [ ] Ele permite trazer seus próprios dispositivos.

4. Qual NÃO é uma declaração válida em relação aos Compartimentos OCI?

- [ ] Você pode conceder acesso a compartimentos a grupos de usuários escrevendo políticas.
- [ ] Cada recurso pertence a um único compartimento.
- [X] Os compartimentos são restritos a uma única região.
- [ ] Os recursos podem interagir com outros recursos em diferentes compartimentos.

5. Como é identificado um recurso em OCI?

- [ ] Nome do Compartimento
- [ ] Nome do usuário
- [x] OCID
- [ ] ID de locação


## 5- Networking

### VCN Introduction

Bem-vindo a este módulo sobre redes OCI. Vamos começar com uma introdução. Então, o que é uma Rede Virtual em Nuvem? Em sua essência, é uma rede privada definida por software que você cria no Oracle Cloud. É usado para comunicação segura. Independentemente de instâncias conversando entre si, instâncias conversando com ambientes locais ou instâncias conversando com outras instâncias em diferentes regiões, você usaria o Virtual Cloud Network.

Ele vive em uma região OCI. Como dissemos, é um serviço regional. É altamente disponível, altamente escalável e seguro. E nós cuidamos dessas coisas para você. Portanto, antes de nos aprofundarmos na VCN e em todas as características e todos os recursos que ela possui, vejamos algumas das coisas básicas.

Então a primeira coisa é que a VCN tem um espaço de endereçamento. Nesse caso, você vê que esse espaço de endereço é indicado em uma notação CIDR. CIDR significa roteamento entre domínios sem classes. Esta é uma pontuação de base. Portanto, não vamos entrar nos detalhes de como você cria essas notações CIDR. Mas você pode ler mais na web. Ou você pode acessar uma calculadora de sub-rede e obter todos os detalhes.

Então você pode ver aqui, a VCN tem um intervalo de endereçamento IP. E o que isso significa é que você tem um intervalo de endereços. Você pega esse intervalo. E você pode dividi-lo em redes menores que são chamadas de sub-redes. E essas sub-redes são onde você instanciaria suas instâncias de computação.

Portanto, neste exemplo, como você pode ver, a rede 10.0.0.0/16 é dividida em 256 redes menores, algumas das quais são mostradas na tela -- a sub-rede pública 10.0.1.0/24 e a sub-rede privada. E como eu disse, suas instâncias são geradas nessas sub-redes.

Portanto, se você ativar uma instância da Web, ela obterá um endereço IP, conforme mostrado. Se você ativar uma instância de banco de dados, obterá um endereço IP -- endereço IP privado, conforme mostrado. E esse endereço IP é usado para todas as comunicações daqui para frente. Então, falando em comunicação, que mecanismos diferentes existem dentro de uma VCN? Então, primeiro, há uma noção de gateway de internet. Este é um gateway que é massivamente escalável, altamente disponível e é usado para comunicação com qualquer coisa na Internet.

Então, se você tem um servidor web que deseja conversar com outros sites na web podendo ser acessados ​​publicamente, você usaria um gateway de internet. Então, indo para a internet e voltando da internet. Você também tem esse roteador altamente disponível e altamente escalável chamado gateway NAT.

E é usado para fornecer NAT como um serviço. Então o que isso significa é que o tráfego é unidirecional. Ele pode ir de suas sub-redes privadas para a Internet. Mas os usuários da Internet não podem usar o gateway NAT para acessar suas instâncias executadas em uma sub-rede privada. Portanto, a ideia do gateway NAT é permitir a comunicação de saída para a Internet, mas bloquear as comunicações de entrada ou conexões iniciadas na Internet.

Então temos outro roteador que se chama Service Gateway. E a ideia é permitir que recursos na VCN acessem serviços públicos de OCI, como armazenamento de objetos, mas sem usar um gateway de internet ou NAT. Portanto, esses são os três cenários: gateway de Internet para internet, gateway NAT também para internet, mas unidirecional, e gateway de serviço para acessar serviços públicos OCI, que estão disponíveis na internet, mas acessando-os de maneira segura.

E então a outra construção é chamada de Gateway de roteamento dinâmico. Este é um roteador virtual que fornece um caminho para tráfego privado entre sua VCN e destinos diferentes da Internet. Então, quais podem ser esses destinos? Bem, este pode ser o seu ambiente local.

Apenas para recapitular, VCN-- sua rede definida por software, altamente escalável, segura e altamente disponível. E você tem vários mecanismos, vários roteadores para habilitar a comunicação, seja indo para a internet ou indo para seu ambiente local.

### VCN Routing

Bem-vindo de volta a esta lição sobre roteamento OCI. Como você pode ver neste gráfico aqui, temos esse conceito de tabela de rotas. A VCN usa tabelas de rotas para enviar tráfego da VCN para a Internet, para redes locais ou para VCN com peering, e analisamos cada um desses cenários.

As tabelas de rotas consistem em um conjunto de regras de rota. Cada regra especifica um bloco CIDR de destino e um destino de rota. Pense no destino da rota como o próximo salto para o tráfego que corresponde a esse bloco CIDR de destino.

Agora, lembre-se de que o tráfego na sub-rede da VCN é tratado automaticamente pelo roteamento local da VCN. Então você vê uma sub-rede pública e uma sub-rede privada aqui. Não há roteamento necessário para rotear os dados. Não há nenhuma entrada em uma tabela de rotas necessária para rotear esses dados entre a sub-rede pública e a sub-rede privada. Isso é cuidado pela própria VCN.

Então, como isso funciona na realidade? Como você pode ver aqui, tenho uma sub-rede privada e uma sub-rede pública e estou mostrando a tabela de rotas apenas para a sub-rede privada apenas para fins de ilustração. E como você pode ver aqui, existem dois tipos de movimentação de dados acontecendo na sub-rede privada.

Estamos aproveitando o gateway NAT. Provavelmente há um banco de dados em execução aqui, então você está usando um gateway NAT para obter alguns patches da Internet. Então você pode ver aquela seta verde indo do gateway NAT até a internet.

E então a segunda parte é que você está usando um Gateway de Roteamento Dinâmico. Esse é um tipo de roteador virtual que você usa para comunicação local e está passando pelo ambiente local. Talvez você esteja executando um servidor DNS no local onde o banco de dados precisa resolver seu DNS.

Agora, se você olhar para as entradas da tabela de rotas, temos duas entradas lá. Há uma notação CIDR, CIDR de decisão e há um destino de rota. O primeiro diz 0.0.0.0/0 e vai para o gateway NAT. O segundo tem um bloco CIDR para rede local.

Então, como isso funciona na realidade? Bem, o que acontece é que a tabela de rotas analisa tanto as rotas quanto a rota que é mais específica ou tem prioridade. Às vezes também nos referimos como a correspondência de prefixo mais longa. Então, se você olhar para esses dois blocos CIDR, o /16 é maior ou mais específico que /0, então isso tem prioridade.

Então, primeiro, o tráfego passa pelo Gateway de Roteamento Dinâmico para seu ambiente local, seus servidores DNS. E então o tráfego que não é destinado ao seu ambiente local vai para a Internet através do gateway NAT e esperamos obter um patch neste exemplo. Portanto, esta é uma ilustração muito rápida, mas espero que mostre como a tabela de rotas funciona.

Agora, há também um cenário sobre o qual não falamos anteriormente, que é o peering. Se você tiver várias redes, como elas se comunicam? Portanto, há dois cenários possíveis aqui.

Se as redes estiverem dentro da mesma região OCI, elas podem se comunicar por meio de um mecanismo chamado peering local. E você pode ver aqui que temos esse conceito de um gateway de peering local. Esse é um tipo de roteador virtual que permite gerenciar essa comunicação.

Se as duas redes estiverem em duas regiões de data center OCI diferentes, você terá o mesmo conceito, um conceito semelhante, mas agora é um emparelhamento remoto. E em vez de usar o peering local, agora você está usando os Gateways de Roteamento Dinâmicos. Lembre-se de que falamos sobre Gateways de Roteamento Dinâmicos usados ​​para comunicação local, qualquer coisa que não seja para internet. Portanto, este também é um caso de uso para o Gateway de Roteamento Dinâmico que permite a comunicação entre redes em diferentes regiões.

Agora, uma coisa você pode olhar para essa imagem e dizer que isso é ótimo se houver duas redes conversando entre si em uma região. Bastante simples de usar algo como um gateway de peering local. O que acontece se você tiver, digamos, 10 dessas VCNs? Ou Deus me livre, se você tem 300 dessas VCNs, como você vai se comunicar?

Em um ambiente complexo real, esta é uma possibilidade. Esta é uma realidade. Muitos clientes lutam com muitas redes. E então como essa comunicação acontece caso você tenha um grande número de redes?

Então, neste caso, o que fizemos foi lançar uma versão mais recente do DRG. É chamado DRG v2. E o que ele faz é que você não precisa mais manter a conectividade ponto a ponto usando um gateway de peering local, em vez disso, as VCNs podem se comunicar usando DRG. E esse recurso também permite dimensionar até 300 VCNs em um único DRG. Se essa opção não for suficiente, você sempre poderá conectar um DRG extra por meio de uma conexão de emparelhamento remoto. Portanto, a ideia é simplificar e dimensionar essa experiência usando este DRG v2.

Então, para encerrar, nesta seção, analisamos o roteamento OCI e como a VCN usa tabelas de rotas para enviar tráfego para a VCN, para a Internet, para a rede local ou para uma VCN com peering.

### VCN Security

Então dentro da VCN, você tem esse conceito de lista de segurança. Pense na lista de segurança como regras de firewall associadas a uma sub-rede e aplicadas a todas as instâncias dentro da sub-rede. Então, como é que isso se parece? A lista de segurança consiste em regras que especificam o tipo de tráfego permitido dentro ou fora da sub-rede. Isso se aplica a uma determinada instância, seja ela conversando com outra instância na VCN ou com um host fora da VCN.

E você pode ver algumas entradas aqui. Essas regras podem ser com ou sem estado. Stateful significa que, se o tráfego for permitido em uma determinada porta, permitido dentro, sempre será permitido sair dessa porta e vice-versa.

Então você pode ver aqui alguns exemplos. O tráfego está chegando na porta 80 e o tráfego está vindo de qualquer lugar na web. Então isso é 0.0.0.0/0. Essa é a fonte. Pode ser em qualquer lugar. O protocolo é TCP. E está chegando na porta 80. Isso é tráfego da web.

E a segunda regra diz que o tráfego está indo da primeira sub-rede para a segunda sub-rede. Então você vê que a origem é o IP, o bloco CIDR para a primeira sub-rede e, na verdade, é o tráfego de saída. Portanto, é a origem da segunda sub-rede, a sub-rede privada. E o tráfego está indo na porta 1521. Essa é a porta do banco de dados Oracle.

E você pode ver, da mesma forma para a sub-rede privada, você tem suas próprias regras de firewall. E neste caso, está dizendo que por ser uma sub-rede privada, você não quer nenhum tipo de tráfego na web. Então a única regra aqui é o tráfego vindo da sub-rede pública, do servidor web, para que o CIDR de origem seja 10.0.1.0/24 e a porta seja 1521, certo? Portanto, é assim que você definiria as listas de segurança em um serviço OCI VCN.

Agora, há também outro conceito, que é chamado de grupos de segurança de rede, ou NSG. Essas são construções muito semelhantes às da lista de segurança, mas a principal diferença é que elas se aplicam apenas a um conjunto de placas de interface de rede virtual em uma única VCN. E outra grande diferença aqui é que os NSGs podem ser a origem ou o destino nas regras. Compare isso com as regras da lista de segurança em que você especifica um CIDR, apenas um CIDR, como origem ou destino.

Então, como você pode ver aqui neste exemplo, o tráfego de saída, a origem é NSG B. Então esse é o NSG que está anexado ao meu banco de dados. Da mesma forma para o segundo grupo de segurança de rede, você pode ver que a origem é o primeiro grupo de segurança de rede. Isso é NSG A.

Além disso, lembre-se de que, à medida que você aproveita os grupos de segurança de rede, porque eles se aplicam a VNICs individuais, agora você pode ter duas instâncias em uma única sub-rede e elas podem ter construções de segurança diferentes. Então, um pode ter NSG com diferentes tipos de regras, e a outra instância, você pode ver, tem um NSG-- neste caso, dizemos NSG C. Tem diferentes conjuntos de regras. Direito? Então você pode ter esse tipo de cenário habilitado usando grupos de segurança de rede.

Então é isso. Apenas para recapitular, existem dois mecanismos para criar essas regras de firewall na OCI VCN. Uma é uma lista de segurança e a outra são os grupos de segurança de rede.

### Criando chave SSH Oracle Shell

Oracle Cloud Shell

mkdir .ssh

cd .ssh

ss-keygen -b 2048 -t rsa -f cloudshellkey

ls

cat cloudshell.pub


### Conectando Oracle Linux Pelo Oracle Shell

ssh ocp@ippublic  -i cloudshellkey

obs.: Usuário padrão do Oracle Linux é "opc" já na distribuição Ubuntu o usuário padrão é "ubuntu"

ippublic = Endereço IP Publico exibido na vm.

cloudshellkey = È a chave privada que fica no diretorio .ssh


### Instalando Apache Oracle Linux 

sudo yum update  (Atualizar o Sistema)

sudo yum install httpd (Instalar apache)

sudo firewall-cmd --permanent --add-port=80/tcp (Liberar apache no firewall)

sudo firewall-cmd --reload (Recarregar o serviço de firewall)

sudo systemctl start httpd (Inicializar o Apache)


### Configurando Putty

Configurar o IP Publico

Protocolo SSH Porta 22

Connection -> Data -> Auto-Login Username = opc

SSH -> Auth -> Procurar atraves do Browser a chave privada de acesso.

Obs. Qdo geramos as chaves no diretorio .ssh no Oracle Shell é criado dois arquivos sendo que um é a chave publica que é a chave que inserimos
na criação da VM e a chave privada é que utilizamos para conectar na VM.

Porém no putty não basta colocar direto essa chave privada, mandando buscar no browser (SSH -> Auth) temps que carregar essa chave privada no PuttyGen inserir a senha e salvar com chave privada no formato *.ppk para funcionar no putty.


### Load Balancer


Então, normalmente, a maneira como o Load Balancer funciona é, eles também são chamados de proxies reversos, você teria um Load Balancer, que seria usado para acessar vários clientes, vários clientes. E esses clientes atingiriam o Load Balancer, e o Load Balancer faria proxy desse tráfego para os vários servidores de back-end. Dessa forma, ele não apenas protege os vários servidores de back-end, mas também fornece alta disponibilidade. Caso um servidor de backend específico não esteja disponível, o aplicativo ainda pode estar em execução. E também fornece escalabilidade porque, se muitos clientes começarem a acessar o Load Balancer, você poderá adicionar facilmente mais back-ends ou mais servidores de back-end.

E existem vários outros recursos avançados, como terminação SSL e passagem SSL e muitos outros recursos avançados. Nós não estamos chegando a eles porque é um curso fundamental. Mas espero que isso lhe dê uma boa ideia do que um Load Balancer faz - quero dizer, os benefícios de usar um Load Balancer.

Portanto, o primeiro tipo de Load Balancer que temos no OCI é um Load Balancer de camada 7. A camada 7 basicamente significa que entende HTTP e HTTPS. Esse é o modelo OSI. E há vários recursos disponíveis aqui.

Então, a primeira coisa é que o Load Balancer vem em duas formas diferentes. Um é chamado de forma flexível, onde você define o mínimo e o máximo e define o intervalo. E seu Load Balancer pode atingir qualquer tipo de -- suportar qualquer tipo de tráfego nesse intervalo específico, indo de 10 Mbps até 8 Gbps.

O segundo tipo de forma é chamado de dinâmica, onde você predefine as formas. Então você tem micro, pequeno, médio, grande e você predefine a forma. E você não precisa aquecer seu Load Balancer. Se o tráfego chegar a essa forma específica, o Load Balancer será dimensionado automaticamente.

Você sempre pode fazer um Load Balancer público e um privado. Público significa que o Load Balancer está disponível na web. Privado significa que suas várias camadas, como uma camada da Web, podem se comunicar com sua camada de banco de dados e equilibrar o tráfego entre elas, mas ambas as camadas não precisam ser públicas.

Um Load Balancer é altamente disponível, altamente escalável por design e possui muitos recursos avançados de camada 7. Coisas como roteamento baseado em conteúdo são suportadas. E há muitos outros recursos SSL, outros recursos, que este está sendo um curso fundamental, não vamos entrar neles. Mas tem muitos recursos ricos.

O segundo tipo de Load Balancer que temos na OCI é chamado de Network Load Balancer. E, como o nome especifica, o Network Load Balancer opera na camada 4, camada 3 e camada 4, portanto, entende TCP, UDP e também suporta ICMP. Novamente, como o HTTP Load Balancer, ele tem uma opção pública e privada, para que você possa criar um Network Load Balancer público ou um Network Load Balancer privado. É altamente disponível, altamente escalável, todos esses recursos são suportados.

Agora, por que você usaria o Network Load Balancer ou um HTTP Load Balancer? A principal razão pela qual você o usaria é que é muito mais rápido que o HTTP Load Balancer. Tem latência muito menor. Portanto, se o desempenho for um critério importante para você, use o Network Load Balancer.

Pelo contrário, o HTTP Load Balancer tem inteligência de nível superior porque pode examinar os pacotes, inspecionar os pacotes e obter essa inteligência. Portanto, se você estiver procurando por esse tipo de inteligência de roteamento, escolha o HTTP Load Balancer.

Então, apenas para recapitular, o OCI fornece a você tanto o Network Load Balancer de camada 3 e camada 4 quanto o balanceador de carga HTTP de camada 7 com muitos recursos avançados.

### Network Summary

Bem vindo de volta. Vamos recapitular o que você aprendeu neste módulo. Analisamos o Virtual Cloud Network, que são redes virtuais definidas por software que você cria no Oracle Cloud Infrastructure. Analisamos os vários gateways suportados - gateway de internet, gateway NAT, gateway de serviço e gateway de roteamento dinâmico. Analisamos o roteamento e como ele funciona. Também analisamos o peering e os vários cenários -- peering local e peering remoto.

Então nós olhamos para a segurança. Examinamos os firewalls virtuais que você pode criar em redes OCI, incluindo lista de segurança e grupos de segurança de rede. E então concluímos olhando para os dois tipos de balanceadores de carga suportados no OCI, tanto a camada 3 e 4, quanto a camada 7.

A rede geralmente é um tópico complexo e é provável que você, quando inicia sua jornada com a nuvem, a primeira coisa que começa a pensar é a rede. Espero que esta lição, este módulo, ajude você a entender o conceito de rede OCI. Obrigado por assistir.

### Exercicios

1. Qual componente de rede virtual na nuvem (VCN) permite tráfego de entrada e saída entre uma VCN e a Internet?

- [ ] Gateway de serviço
- [ ] Gateway de roteamento dinâmico
- [x] Gateway de Internet
- [ ] Gateway NAT


2. Qual afirmação é verdadeira sobre uma rede virtual na nuvem (VCN)?

- [ ] Uma VCN pode ter apenas uma sub-rede pública e apenas uma sub-rede privada.
- [ ] Uma VCN pode ser usada com apenas uma instância.
- [x] Cada sub-rede em uma VCN pode existir em um único domínio de disponibilidade ou em uma região inteira.
- [ ] Uma VCN pode ter apenas uma sub-rede pública e mais de uma sub-rede privada.


3. Qual componente de rede virtual na nuvem (VCN) bloqueia o tráfego de entrada, mas permite o tráfego de saída para a Internet?

- [ ] Gateway de roteamento dinâmico
- [x] Gateway NAT
- [ ] Gateway de serviço
- [ ] Gateway de Internet


4. Quais afirmações são verdadeiras sobre o serviço de Balanceamento de Carga do Oracle Cloud Infrastructure (OCI)?

- [ ] Funciona apenas com endereços IP públicos.
- [x] Ele distribui o tráfego para diferentes servidores de back-end em uma rede virtual em nuvem (VCN).
- [ ] Pode abranger regiões OCI.
- [ ] Ele suporta apenas os protocolos TCP e HTTP.


5. Quais componentes são criados por padrão com a criação de uma rede virtual em nuvem (VCN)? (Escolha três)

(Escolha todas as respostas corretas)

- [ ] Gateway de roteamento dinâmico
- [x] Tabela de rotas padrão, sem regras de rota
- [x] Lista de segurança padrão, com regras de segurança padrão
- [x] Conjunto padrão de opções de DHCP, com valores padrão
- [ ] Gateway de peering local


## 6- Compute

### Compute Introduction

Bem-vindo a este módulo sobre Computação OCI. Vamos começar com uma introdução. Assim, o serviço OCI Compute fornece máquinas virtuais e servidores bare metal para atender aos seus requisitos de computação e aplicativo. As três características definidoras desse serviço incluem essa noção de escalabilidade infinita, alto desempenho e preços mais baixos. Nos próximos slides, falarei sobre cada um deles com um pouco mais de detalhes.

Portanto, a primeira coisa no serviço OCI Compute é que você tem essa noção de forma flexível. O que isso significa? Bem, isso significa que você pode escolher seu próprio curso, seus processadores de CPU e também pode escolher sua própria memória. E como você pode ver os controles deslizantes aqui, você pode escolher uma combinação de curso de CPU e memória e há uma proporção lá. Mas você tem flexibilidade para escolher sua própria configuração.

Literalmente, existem milhares e milhares de configurações que você pode escolher. Agora, qual é a utilidade de fazer isso? O uso de fazer isso é que você pode selecionar o tipo de máquina certo usando nossas formas flexíveis.

E na nuvem, há essa noção de tamanho de camiseta. Portanto, você tem formas pequenas, médias e grandes, e seu aplicativo precisa se adequar a essas formas. E às vezes você provisiona em excesso ou em falta, e precisa passar por esse processo doloroso de alterar seus tipos de máquina. Esperamos que com essas formas flexíveis, você não precise fazer isso.

Se você ainda quiser usar a abordagem tradicional, temos máquinas virtuais, servidores bare metal e host dedicado. E você pode usar qualquer um deles ou todos eles. E servidores bare metal basicamente significam que você obtém uma máquina completa, um servidor completo que é totalmente dedicado a você. Host dedicado basicamente significa que você obtém uma máquina bare metal totalmente dedicada. Mas, além disso, você pode executar máquinas virtuais.

Qual é a diferença entre host dedicado e VMs? Bem, as VMs, como você vê no slide aqui, são compartilhadas e com vários locatários, o que significa que o host pode executar VMs de vários clientes. Eles têm um forte isolamento de segurança, então você não precisa se preocupar com isso. Mas alguns clientes querem um host dedicado onde possam executar suas próprias VMs. E as VMs -- elas não têm VMs de nenhum outro cliente rodando lá. Portanto, essa opção também é fornecida usando um host dedicado.

Não apenas isso, mas a OCI é apenas um dos dois provedores de nuvem para fornecer opções de processadores. Assim, você pode executar instâncias baseadas em AMD, instâncias baseadas em Intel e também instâncias baseadas em Arm - são realmente uma coisa poderosa para computação móvel. Os telefones que você está usando hoje provavelmente estão rodando em processadores Arm. Agora, a Arm está entrando nos data centers.

Então, hoje, estamos usando a família de processadores Ampere Altra. As instâncias Ampere A1 tiveram um desempenho muito bom em muitos casos de uso. Então, como você pode ver na tela aqui, estamos usando o NGINX, algum número de desempenho de preço. É um bom exemplo de cargas de trabalho de alto rendimento, como servidores web, microsserviços, gateways de API.

Nos testes da Arm do NGINX como uma solicitação de proxy reverso por segundo, você pode ver aqui que o Ampere A1, que é o processador que temos -- que estamos usando para o Arm teve desempenho de preço 32% melhor do que o processador AMD equivalente e 69% melhor desempenho do que o processador Intel. Portanto, isso realmente fala sobre nossa capacidade de desempenho de preço que define o setor, principalmente com processadores Arm.

E, finalmente, no lado dos preços, o serviço implementa preços de pagamento conforme o uso. Somos 50% mais baratos do que qualquer outra nuvem por aí, só para começar. E não apenas isso, você pode usar algo como VMs preemptivas para reduzir seu custo em mais de 50% de suas instâncias regulares.

As VMs preemptivas são VMs de curta duração de baixo custo, adequadas para trabalhos em lote e cargas de trabalho tolerantes a falhas. São semelhantes às instâncias regulares, mas com preço 50% menor. Assim, você pode usá-los para reduzir ainda mais seu custo.

Então, apenas para recapitular, um serviço muito poderoso. As três características definidoras sobre as quais falamos, há noção de escala, há noção de desempenho superior, vimos um exemplo disso, e preços mais baixos fornecidos pelo serviço de computação. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Instance Basics

Bem-vindo a esta lição sobre noções básicas de instância. Vejamos alguns dos fundamentos da instância aqui. Então, quando dizemos uma instância, o que queremos dizer é um host de computação. E tem várias dependências. Então vamos olhar para eles.

Então você tem uma região do Oracle Cloud aqui. Uma região é composta por vários ADs. Um AD nada mais é do que um data center, como você pode ver aqui. A primeira dependência que o serviço de computação ou os hosts de computação têm é na Virtual Cloud Network. Portanto, para ativar uma instância de computação, você precisa de uma Rede Virtual em Nuvem. Como você pode ver aqui, você tem uma rede dividida em partes menores chamadas sub-redes. Portanto, você tem uma sub-rede aqui e precisa criá-la antes de ativar um host de computação.

Agora você pode ativar um host de computação. É uma construção física. A rede é uma construção virtual. Então, como eles estão relacionados? Dentro de um host de computação, você tem uma placa de interface de rede física e virtualiza essa placa. Nós virtualizamos esse cartão -- fornecemos essa NIC virtual. E essa NIC virtual é colocada dentro da sub-rede, como você pode ver aqui. E essa é a associação para o host de computação. E é daí que vem o IP privado para o host de computação, porque cada host de computação ou VM que você está executando, ou uma máquina bare metal, tem um endereço IP privado.

Agora, há outro conjunto de dependências que as instâncias de computação têm, e isso é para o volume de inicialização e o disco de inicialização e os volumes de blocos. O que isso significa? Bem, cada um desses hosts de computação que você está ativando tem um sistema operacional. E a imagem usada para iniciar uma instância determina seu sistema operacional e outros softwares. Então você tem esse conceito de uma imagem que vem desse disco de armazenamento de rede chamado disco de inicialização. Portanto, ele não fica no host de computação, na verdade está morando na rede em algum lugar.

E você também tem dados, como sistemas de arquivos, etc. Você está trabalhando nas instâncias de computação. Eles também vivem na rede. Portanto, há os discos de dados e os discos do sistema operacional juntos. Há um serviço chamado serviço de volume de bloco que o host de computação usa para executar seu sistema operacional e seus discos de dados. Agora, estes são armazenamento remoto, como você pode ver aqui. Então, apenas para recapitular, o plano de controle de computação depende do plano de controle de rede e do plano de controle de armazenamento em bloco.

Há mais um recurso que é realmente relevante quando você está falando sobre instâncias de computação: a migração ao vivo. Sabemos que os computadores falham o tempo todo. Então, como podemos garantir que qualquer host de computação que você esteja executando esteja sempre funcionando? Portanto, temos esse recurso chamado migração ao vivo. E a ideia aqui é que, se um dos hosts de computação ficar inativo, houver um problema, migraremos sua VM para outro host em nosso data center e será transparente para você. Existem várias opções que você fornece - seja opt-in ou opt-out - você pode escolher. Mas a ideia é migrarmos suas máquinas virtuais para que você possa migrar ao vivo entre hosts sem reinicializar. Isso mantém seus aplicativos em execução mesmo durante eventos de manutenção. Conseguir isso em seus próprios data centers é uma tarefa não tão trivial, mas nós fazemos isso sem problemas dentro da OCI.

Então, apenas para recapitular, nesta lição vimos os fundamentos das dependências do plano de controle e depois falamos sobre migração ao vivo. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Scaling

Bem-vindo a esta lição sobre dimensionamento, um conceito muito importante dentro do Compute. Então, o que é escalar? Existem dois tipos de dimensionamento que é possível? Um é chamado de dimensionamento vertical; um é chamado de escala horizontal. Como o nome significa aqui, o dimensionamento vertical basicamente significa que você está aumentando ou diminuindo as formas de instância. Agora, o que você pode escalar? Bem, você pode dimensionar o curso, você pode dimensionar a memória. E algumas das outras características são dimensionadas de acordo.

O importante a ter em mente aqui é que, quando você aumenta ou diminui a escala, há um tempo de inatividade necessário porque, provavelmente, pegamos sua máquina e instanciamos uma nova -- quando você institui uma nova forma. Na verdade, vai para outro host. Portanto, há algum tipo de tempo de inatividade necessário. Tenha isso em mente ao fazer o dimensionamento vertical. Há outra boa prática aqui: você pare sua instância antes de fazer qualquer tipo de dimensionamento vertical.

Há outro tipo de dimensionamento chamado Autoscaling, também conhecido como dimensionamento horizontal. Agora, como você pode ver na imagem, isso basicamente significa que você adiciona mais VMs da mesma forma ou pega um pouco mais da mesma forma. Isso permite a implantação em larga escala de VMs. Há escala, como você pode ver na imagem. Você está passando de uma VM para quatro VMs. E também há dimensionamento. Estamos indo de quatro VMs de volta para uma VM. Portanto, ambos os modelos o suportam.

Por que isso é tão popular e poderoso? A razão pela qual ele é tão poderoso é que ele oferece essa capacidade de dimensionamento, mas também oferece essa alta disponibilidade. Nesse caso, uma máquina virtual falha; outros ainda podem continuar trabalhando, como você pode ver na imagem. E uma coisa que o torna realmente poderoso é que você pode atender à demanda de tráfego adicionando a remoção de VMs automaticamente.

Então, digamos que você esteja operando uma loja virtual. De repente, você começa a receber mais tráfego. Você pode facilmente dimensionar automaticamente. E você pode adicionar mais VMs. O tráfego cai, você pode tirar essas VMs. É assim que funciona. Não há custo extra para usar o escalonamento automático.

Então, como funciona e na prática? Há três etapas que você deve seguir para obter o escalonamento automático. E é super fácil de fazer. A primeira coisa que você faz é ter uma instância em execução na qual deseja fazer o escalonamento automático. Então você cria um modelo. E um modelo é chamado de configuração na terminologia OCI. São basicamente coisas como a imagem do seu sistema operacional, seus metadados, a forma, o tamanho e algumas outras características, como armazenamento, rede, etc.

Então, primeiro você cria um carimbo. Você tem uma instância em execução. Você cria um carimbo dessa instância em execução. O segundo passo é você pegar aquele carimbo, e então você cria essa coisa chamada instance poo. E pool é basicamente uma coleção dessas instâncias com antecedência. Você cria isso.

E a ideia aqui é que você pode gerenciar todas essas instâncias como uma unidade. Então você pode parar todos eles ao mesmo tempo. Você pode iniciá-los, encerrá-los e, para obter alta disponibilidade, pode colocá-los em diferentes domínios de disponibilidade em diferentes data centers. Então esse é o passo número dois.

E a etapa número três é: você pega seu pool de instâncias e escreve essas regras de escalonamento automático nele. Você começa com um tamanho desejado ou inicial. Há um tamanho mínimo e, em seguida, há um tamanho máximo. E você escreve uma regra. Como você pode ver na tela, se a CPU ou a memória ultrapassarem um determinado limite percentual, adicione algumas instâncias. Ou se ficar abaixo de algum limite, remova algumas instâncias. E o Autoscaling monitora constantemente seu tráfego. Está constantemente monitorando o uso da CPU. E está analisando se deve adicionar instâncias ou remover instâncias.

Então, como você pode ver nesta foto aqui, começamos com um tamanho inicial de 2. E então, se a CPU ultrapassar 70%, temos que adicionar mais duas instâncias. E se isso acontecer, você acaba com quatro instâncias. Portanto, o escalonamento automático não apenas ajuda você a atender à demanda de tráfego, mas também oferece alta disponibilidade. Essa é uma recapitulação, um recurso muito poderoso do Autoscaling. E também analisamos outra forma de dimensionamento, o dimensionamento vertical. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### OS Management Service

Bem-vindo a esta lição sobre gerenciamento de SO. Se você é um administrador do sistema, vai adorar este serviço. Vamos ver por quê.

O gerenciamento de patches e pacotes é uma tarefa complexa, especialmente quando você tem implantações maiores de instâncias na nuvem ou quando está gerenciando ambientes de SO mistos e usando várias ferramentas de gerenciamento ou usando versões diferentes de instâncias do Oracle Linux e Windows Server. O OS Management Service ajuda os administradores de sistema a automatizar o gerenciamento de instâncias do Oracle Linux e do Windows Server.

Existem duas características principais do serviço: gerenciamento automatizado de patches e gerenciamento simplificado de pacotes. Mas antes de nos aprofundarmos nesses tópicos, vamos primeiro ver o que é gerenciamento de patches e o que é gerenciamento de pacotes.

Gerenciamento de patches, basicamente está relacionado ao gerenciamento dos patches, que são lançados. E esses patches geralmente são lançados conforme necessário para corrigir bugs, melhorar o desempenho ou adicionar novos recursos aos sistemas operacionais. Agora, todos nós sabemos que os ambientes de TI corporativos contêm milhares de computadores que exigem patches.

Se você estiver usando suas próprias máquinas em um ambiente corporativo, estiver familiarizado com a aplicação de patches, precisará manter suas máquinas constantemente corrigidas e atualizadas. A correção manual é complexa e sujeita a erros. Você não quer fazê-lo manualmente, ou pelo menos não quer fazê-lo manualmente em escala para um grande número de máquinas.

O gerenciamento de pacotes, por outro lado, trata da instalação, aplicação de patches e remoção de pacotes de software. É uma tarefa sysadmin comum. Você tem que lidar com isso no dia a dia. Mas é muito difícil catalogar pacotes e atualizações instalados e disponíveis. E, novamente, fazer isso em escala é bastante complexo e propenso a erros. Então, como o Serviço de Gerenciamento de SO ajuda?

Bem, a primeira coisa que ele faz é ajudar a automatizar o gerenciamento de patches e ajudar a reduzir a complexidade e os erros do gerenciamento de lotes, fornecendo um único serviço consolidado. Atualmente, ele suporta os sistemas operacionais Oracle Linux e Windows. Ele suporta várias versões dos sistemas operacionais e grupos de instâncias. Portanto, funciona não apenas para uma instância, mas pode funcionar em um grande grupo de instâncias, então realmente funciona em escala.

Então, o segundo recurso que temos é o gerenciamento de pacotes simplificado, onde você pode facilmente pesquisar, instalar e remover pacotes. Ele também fornece um inventário de pacotes e atualizações instalados e disponíveis. O terceiro recurso que temos é a pesquisa de vulnerabilidades e exposições comuns. Essas vulnerabilidades são armazenadas em um banco de dados, o banco de dados CBE que está disponível e, portanto, o serviço analisa esse banco de dados e permite que você instale os pacotes para que as vulnerabilidades possam ser corrigidas facilmente.

Então esse é outro recurso disponível com o OS Management Service. E lembre-se de que não há cobrança para os clientes usarem o Serviço de Gerenciamento de SO. Além disso, se você estiver usando instâncias do Oracle Linux, o suporte também será fornecido sem custo adicional como parte deste serviço.

Apenas para recapitular, o gerenciamento de patches e o gerenciamento de pacotes são bastante complexos, propensos a erros e muito difíceis de fazer em escala. O OS Management Service ajuda a automatizar o gerenciamento de patches e simplificar o gerenciamento de pacotes. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Compute Summary

Bem vindo de volta. Vamos recapitular o que você aprendeu neste módulo. Então, analisamos o serviço OCI Compute, as três características definidoras, a noção de escalabilidade infinita, maior desempenho e preços mais baixos. Nós olhamos para todas essas três coisas.

Em seguida, analisamos alguns dos fundamentos da instância, a dependência dos planos de controle. E também analisamos as duas maneiras diferentes de fazer dimensionamento, dimensionamento vertical, dimensionamento horizontal, também conhecido como dimensionamento automático.

E, finalmente, analisamos o OS Management Service, particularmente útil para automatizar o gerenciamento de patches e simplificar o gerenciamento de pacotes, especialmente para milhares de computadores que fazem isso em escala. A computação é um recurso central em qualquer um dos ambientes de nuvem. Então, espero que você tenha achado esta lição útil. Obrigado por assistir. Olhe para você. Mais lição para baixo.

### Exercicios

1. Qual NÃO é uma opção de forma de computação válida no serviço de computação OCI?

-[] Bare Metal
-[] Máquina virtual
-[] Host de máquina virtual dedicado
-[x] Instância de contêiner

2. Você tem um aplicativo da web que recebe 10 vezes mais tráfego nos fins de semana do que nos dias de semana. Você precisa ajustar automaticamente a capacidade à demanda, manter o aplicativo sempre em funcionamento e economizar custos.

Qual recurso de computação OCI pode ser usado para atender a esses requisitos?

-[x] Escalonamento automático
-[] Escala paralela
-[] Escala vertical
-[] Dimensionamento manual

3. Qual parâmetro NÃO é modificável?

-[] Quantidade de memória
-[x] Endereço IP privado primário
-[] Número de OCPUs
-[] Domínio de falha

4. Qual é um recurso do OCI OS Management Service?

-[] Escalonamento automático
-[] Criptografia de disco
-[] Gerenciamento de custos
-[x] Gerenciamento automatizado de patches

5. Qual afirmação é verdadeira sobre o OCI Compute Service?

-[x] Ele fornece opções para criar Bare Metal ou uma instância de Máquina Virtual.
-[] Ele não suporta cargas de trabalho do Windows.
-[] Ele fornece um tamanho único para diferentes tipos de cargas de trabalho.
-[] Ele é usado apenas para executar bancos de dados.

## 7- Storage


### Storage Introduction

Bem-vindo a este módulo sobre serviços de armazenamento OCI, o que são e como funcionam. Antes de nos aprofundarmos nos vários serviços de armazenamento disponíveis na OCI, vejamos os requisitos de armazenamento porque eles são muitos e variados.

Então, primeiro é quando você decide que tipo de armazenamento usar, você quer responder se deseja armazenamento persistente ou armazenamento não persistente. Então você tem que responder, que tipo de dados você está armazenando? São arquivos de banco de dados? São vídeos? São áudios, fotos, texto? Que tipo de desempenho você precisa? Que tipo de capacidade você precisa? Quantas entradas/saídas por segundo, IOPS? Quanto é o rendimento?

Então você precisa decidir sobre a durabilidade, quantas cópias de dados você deseja manter. Há uma diferença entre persistência e durabilidade. Persistência basicamente significa que você armazena os dados com segurança. Durabilidade significa fazer várias cópias dos dados, replicando os dados. Portanto, caso você os esteja armazenando com segurança, mesmo que uma cópia fique ruim, você ainda terá outras cópias para usar.

A conectividade também é importante, quer você queira armazenamento local ou armazenamento em rede. E como seu aplicativo acessa esses dados de armazenamento? E, finalmente, o protocolo, porque determina que tipo de aplicativos você pode construir, seja bloco, arquivo ou algo tão simples quanto HTTP. Agora, esses são alguns requisitos de armazenamento e tenho certeza de que há muitos mais. Mas você precisa lidar com isso antes de decidir quais serviços de armazenamento usar.

Vejamos a linha de serviços de armazenamento OCI. E eu vou cobrir apenas alguns dos poucos -- os principais aqui. Existem outros, que abordaremos nas próximas lições. Portanto, a primeira coisa é o NVMe local. NVMe local significa, como você vê na imagem aqui, que você tem um data center, que chamamos de "domínio de disponibilidade" dentro da OCI. Você tem um servidor de computação e um armazenamento conectado localmente.

Portanto, quando você pensar em NVMe local, pense em armazenamento conectado localmente. Estes são SSDs NVMe. O desempenho super alto oferece centenas de milhares de IOPS. E você pode executar seus aplicativos mais sensíveis ao desempenho usando NVMe local. Então, o que fazemos é pegar esse armazenamento conectado localmente e movê-lo para um servidor remoto, um servidor de rede.

Então, nesta imagem, você vê que há uma instância de computação e está se comunicando com um servidor de armazenamento, que está na rede. Portanto, a vantagem aqui é que o armazenamento pode ser realmente persistente e durável e se estender além do tempo de vida da própria instância. Esse tipo de armazenamento é chamado de "volume em bloco". Neste caso, o armazenamento, os dados são gerenciados como blocos de tamanho fixo. Então você cria uma partição. Você cria um sistema de arquivos. Em seguida, você monta o sistema de arquivos. E é assim que suas instâncias de computação usam o serviço de armazenamento -- então bloqueie o volume.

O armazenamento de arquivos é um tipo semelhante de armazenamento, ainda no mesmo domínio de disponibilidade, mas é um sistema de armazenamento de arquivos compartilhado. Portanto, neste caso, você vê duas instâncias de computação. E então, eles precisam ter um sistema de armazenamento compartilhado, onde possam ler e escrever, mas o armazenamento é compartilhado. Portanto, é muito semelhante ao volume de blocos, mas a diferença aqui é que você gerencia o armazenamento como arquivos e diretórios. Você não particiona o disco. Você ainda faz algumas coisas como montar o sistema de arquivos. E é assim que suas instâncias usam o armazenamento compartilhado. Então pense compartilhado, pense em armazenamento de arquivos.

E, finalmente, temos o armazenamento de objetos, que é o armazenamento para a web. Então você tem armazenamento -- este é um tipo de armazenamento que você usaria para fotos, vídeos, arquivos de log, arquivo de texto, qualquer tipo de arquivo que você armazena na web. Normalmente, a maneira como ele é acessado é que você tem um cliente de internet, que acessa esse particular -- esses objetos usando verbos HTTP simples e familiares, como PUT e GET -- PUT significa que você cria um objeto, GET significa que você baixa um objeto.

E assim, esses são os principais serviços de armazenamento que existem dentro da OCI. Junto com isso, temos vários serviços de migração de dados. Portanto, temos dois que estão relacionados à transferência de dados -- disco de transferência de dados e dispositivo. Disco é, basicamente, você nos enviar seus discos, e nós migramos os dados. Appliance é você usar um appliance muito maior para nos enviar os dados. E, finalmente, temos um serviço chamado Storage Gateway, que é um dispositivo Linux. Fica em seu data center e, usando isso, você pode migrar dados para OCI.

Então é isso -- um monte de serviços de armazenamento, cada um adequado para diferentes casos de uso. Nas próximas lições, vamos nos aprofundar em cada um deles. Obrigado por assistir.

### Object Storage

Bem-vindo de volta à lição sobre OCI Object Storage. O que é OCI Object Storage? Bem, é uma plataforma de armazenamento de alto desempenho em escala de internet. Aqui, os dados são gerenciados como objetos. Independentemente do tipo de dados que você armazena, todos eles são gerenciados como objetos.

É ideal para dados não estruturados, como seus logs, seus vídeos, suas fotos, seus arquivos de texto. É um serviço regional. É um serviço público. Existem várias camadas de armazenamento e analisaremos cada uma delas.

Você ainda pode ter acesso privado de recursos OCI, como suas instâncias de computação. Então, mesmo sendo um serviço público, você ainda pode ter acesso privado e vários outros mecanismos para fazer isso. E depois há muitos recursos avançados. Este é um curso básico, então não vamos entrar nesses recursos. Mas é um serviço muito rico em recursos.

Então, quais são os cenários em que você usaria um OCI Object Storage? Bem, você o usa como um repositório de conteúdo. Como eu disse, você pode usá-lo para dados estruturados e semiestruturados. Você pode usar para cenários de Big Data. E muito importante, você pode usá-lo para fins de arquivamento e backup.

Então, como funciona o armazenamento de objetos? Vamos olhar para isso. Quais são os principais recursos aqui?

Então a primeira coisa é o próprio objeto. Tudo o que você armazena no Object Storage é referenciado como objeto. Pense no objeto como pares de valores-chave ou pares de valores de nome, nome sendo o nome do arquivo que você está armazenando e o valor sendo o valor real do arquivo. E então os objetos também podem ter metadados de objetos, e você pode definir seus próprios metadados lá.

Os objetos são armazenados em um bucket, como você pode ver no gráfico aqui. E os buckets têm seu nome exclusivo em uma locação. Uma coisa importante a ter em mente é que existe uma hierarquia plana, e sempre que você vê um tipo de estrutura de pastas, isso é estimulado pelo serviço Object Storage usando algo chamado prefixos. Portanto, lembre-se, todos os objetos que você armazena apenas seguem uma hierarquia plana dentro do serviço.

Há também algo chamado namespace. Um namespace é uma entidade lógica. É um contêiner de nível superior para todos os objetos buckets e precisa ter um nome globalmente exclusivo.

Vejamos, então, um exemplo de como isso funciona. Você pode ver aqui, eu tenho esta URL, que é o endpoint da API para Object Storage. É assim que você acessa esses objetos.

Lembre-se, há um serviço público. Você os acessa usando um endpoint de API pública. E esse endpoint da API é um dos exemplos mostrados aqui.

Então, neste caso, vamos começar de baixo. Você tem um objeto que tem uma notação /o, e qualquer coisa além disso-- depois disso é o nome do objeto. Então aqui, estou armazenando o objeto que é log.zip, ele vai para um bucket que é chamado de desenvolvimento e é indicado pelo /b, e então há um namespace que é o nome da conta. E você pode ver isso aí.

Então é assim que a API é construída. E as primeiras coisas, mas há o nome do serviço de armazenamento de objetos, e é um serviço regional. Então você vê uma região lá, US San Jose 1.

Então, vamos olhar para algumas das camadas. Falamos sobre as camadas do Object Storage. Portanto, a primeira camada no Object Storage é chamada de camada Standard. Também é referido como o nível quente.

O que significa é que você mantém todos os dados críticos que deseja recuperar instantaneamente, você os mantém aqui. A recuperação é instantânea e também fortemente consistente. Assim, sempre que você atualizar os dados, forneceremos a cópia mais recente desses dados.

Há uma segunda camada, chamada Acesso Infrequente. O que isso significa é que você ainda tem dados críticos, mas esses são dados críticos de longo prazo. Você não precisa disso imediatamente. Então pense em backups. Você os manteria em Acesso Infrequente.

Existem algumas restrições aqui. Os dados devem ser armazenados por um período mínimo de 31 dias e há taxas de recuperação quando você recupera os dados. Qual é a vantagem? É 60% mais barato que o nível Standard. E há uma taxa de recuperação, mas é significativamente mais barata que o nível Standard.

E depois há uma terceira camada, que é chamada de camada de arquivo. Isso é para seus dados que você não precisa imediatamente. Você raramente acessa esses dados. Então pense no armazenamento em fita. É basicamente armazenamento em fita na nuvem, mas muito mais fácil e muito mais rico em recursos.

Portanto, há um requisito mínimo de retenção de 90 dias. E há um processo em que os objetos precisam ser restaurados e depois baixados. Portanto, ao colocar dados no Armazenamento de arquivo, você precisará restaurá-lo. O tempo mínimo necessário para restaurar é uma hora, e então você precisa fazer o download. E você obtém 24 horas, que pode estender para 40 horas, mas precisa baixar os dados para a camada Standard e, em seguida, pode acessar a partir da camada Standard.

Mas isso não é tudo. Há um recurso chamado auto-tiering, e o que ele faz é examinar seu padrão de acesso. E digamos que você tenha um padrão de acesso desconhecido ou seu padrão de acesso a dados continua mudando, ele pode mover os dados da camada Standard para a camada de Acesso Infrequente e vice-versa. E pode voltar para o padrão se o seu objeto iniciar se acostumando novamente.

A ideia aqui é que isso é inteligência dada pelo serviço. Não há taxas de recuperação. Não há taxas de armazenamento rateadas. E usando esse recurso, você pode reduzir significativamente seu custo, pois pode ir do Acesso Padrão para o Acesso Infrequente, 60% mais barato, e depois voltar se seu objeto começar a ser usado.

Não é isso. Existem muitos outros recursos. Um recurso que é realmente importante é o gerenciamento do ciclo de vida. E, como você pode ver aqui, ele ajuda a fazer a transição dos dados do nível de custo mais baixo para os níveis de custo mais baixo. Portanto, você pode dizer após 30 dias, mover meus dados das camadas Standard para as camadas de arquivo e excluí-los após 180 dias. E você escreve uma regra, e o serviço cuida disso.

Você também pode fazer o controle de versão porque, conforme armazena seus dados, pode ter várias versões desses dados. E esses objetos são versionados automaticamente. Você apenas especifica isso no bucket, e nós cuidamos disso.

Portanto, criptografia de dados. É muito importante porque você está armazenando dados confidenciais na nuvem. Você quer que seja seguro, por isso oferecemos criptografia de dados por padrão. Você não pode desligar isso. Você sempre pode trazer suas próprias chaves. Para requisitos muito rigorosos, você tem essa opção.

Como você acessa todos esses dados? Você acessa todos os dados usando uma simples chamada de API, como mostrei no início. Você chama essa API, usa palavras STTP familiares e pode acessar esses dados.

Então é isso, pessoal. Object Storage, um serviço muito rico em recursos. Da próxima vez que você tirar essa foto, é provável que ela esteja armazenada em um Object Storage. Obrigado por assistir.

### Block Volume

Bem vindo de volta. Vejamos o Serviço de Volume de Blocos OCI.

No núcleo, o Block Volume Service fornece armazenamento persistente e durável para computar instâncias. Como você pode ver neste gráfico aqui, há uma instância de computação, que está conversando com discos, discos permanentes e duráveis, que estão em um servidor de rede. Portanto, a ideia central aqui é obter o armazenamento persistente e durável. O que isso realmente significa?

Bem, se você olhar para a mesma imagem novamente, sua instância de computação conversando com um disco de armazenamento em bloco, você pode criar e anexar esses discos às instâncias de computação, você pode desanexar e excluir os discos e, o mais importante, você pode manter os dados mesmo depois de excluir a instância. Assim, os dados são armazenados independentemente do ciclo de vida da instância.

E essa é a razão número um pela qual você usaria um Block Volume Service para fornecer esse armazenamento persistente e durável. Persistente, o que significa que é um armazenamento salvo, permanece além do ciclo de vida das próprias instâncias de computação. A instância de computação é encerrada, ainda é segura. E durável significa que fazemos várias cópias, portanto, mesmo se perdermos uma cópia, teremos outras cópias dos dados disponíveis no data center.

Vejamos os níveis de volume de bloco. Começamos com uma camada chamada Basic, isso é bom para grandes cargas de trabalho de E/S sequenciais, como streaming, data warehousing. Então você tem um nível balanceado, que é uma escolha balanceada para E/S aleatória, coisas como seus discos de inicialização. Em seguida, temos um nível de desempenho superior, que é para as cargas de trabalho mais exigentes de E/S. E, em seguida, temos o nível de desempenho ultra-superior, que é para as cargas de trabalho mais exigentes de E/S, como seus bancos de dados relacionais.

E você pode ver as características abaixo, começando com 2 IOPs por show, indo até 225 IOPs por show.

E também temos esse recurso, que é chamado de desempenho de ajuste automático, e o que ele faz, altera o desempenho do volume para um custo menor quando o volume é desanexado. Quando o volume é reconectado, o desempenho do volume é ajustado automaticamente para a configuração anterior. Porque você faria isso? Bem, isso ajuda você a economizar no custo.

Portanto, com Block Volumes ou dados em geral, você deseja que os dados sejam armazenados com segurança. Portanto, temos a criptografia ativada por padrão. Você não pode desligar isso. E você pode trazer suas próprias chaves. E também temos criptografia para dados em repouso, e também temos criptografia em trânsito, ou seja, quando sua máquina virtual está conversando com o Block Storage Service, o tráfego é criptografado em trânsito entre a máquina virtual e o Block Service.

O Block Service também tem esse recurso chamado Read/Write Shareable, onde um único disco pode ser compartilhado com várias VMs, e essas VMs podem ler e gravar em um único volume de bloco.

Também temos essa capacidade de redimensionar volumes de blocos, e isso significa que você pode fazer redimensionamento online ou redimensionamento offline. Com o redimensionamento online, você pode expandir o tamanho do volume sem desanexar o volume de uma instância, mantendo seus aplicativos em execução e você ainda pode alterar o tamanho de seus volumes em blocos.

Também temos um recurso, que se chama Replicação de Volumes de Blocos. E como você pode ver neste recurso -- neste gráfico aqui, os volumes de blocos estão sendo replicados de uma região para outra. Por que você faria isso? Você faria isso para recuperação de desastres, faria isso para migração ou, se estiver expandindo seus negócios, aproveitaria esse recurso. A ideia aqui é replicar os dados para várias regiões. E lembre-se, essa replicação é assíncrona.

E, finalmente, temos esse recurso chamado Grupos de Volume. O Block Volume Service oferece a capacidade de agrupar vários volumes no que chamamos de grupo de volumes. Isso simplifica o processo para criar backups consistentes no tempo de aplicativos em execução que abrangem vários volumes em várias instâncias. E a ideia aqui é que, depois de criar um grupo de volumes, você pode restaurar um grupo inteiro de volumes de um backup de grupo de volumes.

Então pessoal, é isso, isso é Block Volume. Da próxima vez que você pensar sobre o que dá super poder às suas instâncias de computação executadas em um data center, raramente são os volumes em blocos.


### File Storage

Bem vindo de volta. Vejamos o serviço de armazenamento de arquivos OCI. Antes de nos aprofundarmos no serviço, vejamos primeiro o que é armazenamento de arquivos? Muito simplesmente, o armazenamento de arquivos é uma coleção hierárquica de documentos organizados em diretórios de nomes. Todos nós estamos familiarizados com ele, se você está usando máquinas Linux ou Windows, você está familiarizado com a forma como organiza seus arquivos em pastas e diretórios e vários deles.

Agora, a diferença está na nuvem, temos sistemas de Arquivos Distribuídos. Estes não são locais para sua máquina. E os dois mais comuns que usamos são NFS para Linux, Network File System e Server Messaging Block, SMB, para Windows. Tanto os protocolos quanto os padrões são suportados pelo UNIX e Windows. E há muitos detalhes sobre sistemas operacionais e hipervisor que suportam isso.

Então, quais são os casos de uso para o armazenamento de arquivos? Bem, o primeiro caso de uso são muitos dos aplicativos corporativos que a Oracle possui aplicativos como EBS, E-Business Suite, que realmente precisam de armazenamento de arquivos compartilhados. Então, isso é fornecido pelo serviço File Storage.

Existem sistemas de arquivos de uso geral. Todos nós usamos diretórios corporativos onde compartilhamos pastas onde guardamos nosso conteúdo. Então esse é um exemplo de um sistema de arquivos de uso geral.

Na verdade, os micro serviços e contêineres geralmente são sem estado. E se você pensar em como criamos essas arquiteturas, deve haver um lugar onde você mantenha o estado desses microsserviços e contêineres. Muitas vezes, os clientes usariam o sistema de arquivos compartilhado para gerenciar esse estado. E há vários outros casos de uso, como HPC, aplicativos de escala horizontal, análises e muitos outros, nos quais você usaria o serviço de armazenamento de arquivos.

Então, em poucas palavras, como funciona o armazenamento de arquivos? Como você pode ver na imagem aqui, você tem um único data center em uma região OCI. Você tem algumas instâncias de computação. Eles estão todos conversando com o sistema de arquivos compartilhado, e esse é o seu serviço de armazenamento de arquivos OCI. Portanto, é armazenamento compartilhado para instâncias de computação.

Hoje, atualmente, oferecemos suporte ao NFS v3 como um padrão de sistema de arquivos distribuído. Você pode fazer backup do sistema de arquivos, o que chamamos de instantâneos. Assim, isso fornece proteção se suas pastas forem -- os diretórios forem excluídos, você sempre poderá tirar instantâneos de backup.

E então levamos a segurança muito a sério. Então você tem criptografia de dados em repouso e também tem criptografia em trânsito. Ou seja, quando suas instâncias de computação estão conversando com o sistema de arquivos compartilhado, é que o tráfego é criptografado.

Como este é um curso básico, não vamos aprofundar como você cria um sistema de arquivos, os pontos de montagem e todos os detalhes. Mas a ideia básica é você criar um sistema de arquivos e montá-lo nas instâncias de computação. E então você começa a usá-los. Muitas instâncias podem compartilhar o mesmo sistema de arquivos e podem ler e gravar a partir desse sistema de arquivos.

Então é isso. Sistema de arquivos - da próxima vez que você estiver pensando em diretórios e pastas e sistema de arquivos de uso geral, pense em usar o serviço de armazenamento de arquivos OCI. Obrigado por assistir

### Migration Services

Bem vindo de volta. Vejamos os serviços de migração de dados disponíveis no OCI. Portanto, esta imagem aqui nos ajuda a identificar os vários mecanismos que podemos usar para a transferência de dados. Um está offline, outro está online.

Offline basicamente significa que você tem seus servidores e seus dados residindo em seus data centers. E suponha que você não tenha largura de banda alta o suficiente, você pode usar esse mecanismo para enviar dados para nós.

O segundo mecanismo é a transferência online. E neste caso, temos um serviço chamado Storage Gateway. É um dispositivo Linux. Você coloca isso em seu data center e, em seguida, pode transferir os dados usando sua rede de longa distância.

Para ver, agora estimamos a largura de banda de um caminhão FedEx. Você pode ver o caminhão transportando grandes quantidades de dados usando a migração offline. E então no segundo mecanismo, Storage Gateway, poderíamos usar uma rede de longa distância para transferir seus dados para o Oracle Cloud.

Vejamos cada um deles com um pouco mais de detalhes. O primeiro é o serviço de transporte de dados offline. Existem dois sabores. O primeiro é chamado de discos de transferência de dados.

Neste caso, você compra -- você compra seu próprio disco de mercadoria. Você coloca seus dados nele. Você pode usar, acredito, até 10 discos, sendo a capacidade total de 100 terabytes.

Os dados são transferidos para um site de transferência. É sempre criptografado. Nós carregamos os dados, verificamos, apagamos e, em seguida, os discos são entregues a você.

O segundo tipo é o dispositivo de transferência de dados. Isso é útil para enviar grandes quantidades de dados. Às vezes, não é prático enviar discos individuais, então você usará um dispositivo de transferência de dados.

Enviamos o aparelho para você, você transfere os dados, coloca os dados nele, envia para um site de transferência. Transferimos os dados, são sempre encriptados. Nós carregamos, verificamos. São os dados do dispositivo de transferência de dados. E seguimos vários padrões para apagamentos de dados e afins.

Portanto, esses são dois exemplos de transporte de dados offline. Envio de dados através de um disco. Enviando dados para um dispositivo.

Na área de migração de dados online, temos esse serviço chamado Storage Gateway. E a maneira como isso funciona é que o Storage Gateway é um Linux Docker Appliance que é instalado em um ou mais hosts em seu data center local. O Storage Gateway expõe um ponto de montagem NFS que pode ser montado em qualquer host que ofereça suporte a um cliente NFS. E, em seguida, esse ponto de montagem é mapeado para um bucket de armazenamento de objetos no site da OCI. E, em seguida, pode obter os dados do seu ambiente local.

Qualquer arquivo colocado no sistema de arquivos do Storage Gateway é gravado como um objeto com o mesmo nome no bucket de armazenamento de objetos associado. E você pode usar um Object Storage ou pode usar o armazenamento de arquivos. Portanto, isso é ótimo para migração de dados, mas também pode ser usado para camadas de nuvem, por exemplo. Também pode ser usado para recuperação de desastres ou backup. Ótimo serviço para usar, não apenas para migração de dados.

Então aí está. Dados, enviar grande quantidade de dados para a nuvem é um desafio. Temos vários serviços tanto offline, seja para enviar seus discos ou usar nosso appliance de transferência de dados ou usar um serviço online como o Storage Gateway para mapear seus dados para OCI e começar a migrar seus dados. Obrigado por assistir.

### Storage Summary

Vamos recapitular o que aprendemos neste módulo. Examinamos os vários serviços de armazenamento disponíveis na OCI, começando com o armazenamento de objetos, que é o armazenamento para a web. Da próxima vez que você estiver tirando fotos, pense onde isso está sendo armazenado. Isso é armazenamento de objetos.

Analisamos o armazenamento em bloco, o volume em bloco. Isso dá o super poder às suas instâncias de computação onde você pode armazenar seus dados com segurança. Mesmo que sua instância seja encerrada, seus dados são duráveis e persistentes.

Analisamos o armazenamento de arquivos, onde várias instâncias podem ler e gravar em um sistema de arquivos compartilhado, muitos cenários sendo desbloqueados com isso. E então analisamos vários serviços de transferência de dados, incluindo o Data Transfer Disk, o Data Transfer Appliance e o Storage Gateway.

Isso é apenas uma fração de toda a funcionalidade que temos nos serviços de armazenamento OCI. Este é um curso básico. Então, queríamos mantê-lo em um nível muito alto. Espero que você tenha achado este módulo útil. Obrigado por assistir.

### Exercicios

1. Qual afirmação é verdadeira sobre o armazenamento de arquivos OCI?

- [] Ele é suportado apenas por sistemas operacionais Linux.
- [x] Ele organiza arquivos em uma hierarquia de diretórios nomeados.
- [] É suportado apenas pelo sistema operacional Windows.
- [] É um sistema de arquivos local para uma instância de computação.

2. Você armazena várias versões de objetos em um bucket, mas sua equipe de TI solicitou que você exclua todas as versões anteriores do objeto 120 dias após a transição da versão do objeto da versão mais recente para uma versão anterior.

Qual recurso OCI Object Storage pode ser usado para essa finalidade?

- [] Regras de retenção
- [x] Gerenciamento do ciclo de vida do objeto
- [] Carregamentos em várias partes
- [] Solicitações pré-autenticadas


3. Qual afirmação é verdadeira sobre o serviço de armazenamento OCI Block?

- [x] Ele pode ser anexado a uma instância de computação.
- [] Não é durável
- [] Ele só é compatível com instâncias do Linux.
- [] Ele armazena dados em blocos de tamanho variável.

4. Qual opção de armazenamento NÃO está disponível no OCI?

- [x] Volume de nuvem da NetApp
- [] Armazenamento de objetos
- [] Armazenamento de arquivo
- [] Armazenamento de arquivo

5. Você deseja armazenar o backup de um banco de dados no armazenamento em nuvem por um longo período de tempo.

Que tipo de armazenamento você deve configurar para esses arquivos?

- [] Armazenamento de arquivo
- [] Volume do bloco
- [x] Armazenamento de arquivo
- [] Armazenamento de objetos


## 8- Database Introduction

Nesta lição, veremos que tipo de serviços de gerenciamento de banco de dados você obtém no Oracle Cloud Infrastructure. Então vamos ver essas opções aqui. A OCI oferece sistemas de banco de dados de nó único em máquinas bare metal ou virtuais e sistemas de banco de dados de cluster de aplicativos reais de 2 nós em máquinas virtuais. Vamos analisar cada um deles separadamente.

Para sistemas de banco de dados de máquina virtual de um nó, o OCI fornece uma opção de provisionamento rápido que permite criar seus sistemas de banco de dados usando algo chamado Logical Volume Manager como sua camada de gerenciamento de armazenamento. A alternativa é chamada de provisionamento padrão e é provisionada com o Oracle Automatic Storage Management, também conhecido como ASM. Portanto, o uso do gerenciador de volume lógico fornece a esse sistema de banco de dados de VM sistemas de banco de dados de máquina virtual de um nó tempos de provisionamento rápidos.

Por outro lado, a OCI também possui um sistema de banco de dados bare metal que consiste em um único servidor bare metal executando Oracle Linux com armazenamento NVMe conectado localmente. Se este único nó falhar, você pode simplesmente iniciar outro sistema e restaurar o banco de dados dos backups atuais.

Em seguida, também temos a opção de provisionar um sistema Real Application Cluster DB de 2 nós, que é executado em OCI. Nesse caso, quando você provisiona esse sistema de banco de dados RAC de 2 nós, o sistema atribui cada nó a um domínio de falha diferente. E é assim que podemos fornecer a você alta disponibilidade gerenciada com esse cluster de 2 nós. Portanto, essas são as três primeiras opções, ao que normalmente nos referimos também como sistemas de banco de dados.

E vamos ver algumas outras opções. A quarta opção disponível é o Exadata Cloud Service. E pense nisso como um serviço que permite aproveitar o poder do Exadata na nuvem. As cargas de trabalho da Oracle têm o mais alto desempenho em execução neste Exadata Cloud Service. Na versão mais recente do serviço X8M, oferecemos suporte a um curso de servidor de banco de dados líder do setor de 1.600, 12 milhões de leitura e cerca de 6 milhões de IOPs de gravação e bancos de dados que podem ter até 2,5 petabytes em escala. Isso é apenas uma escala massiva que não pode ser alcançada em nenhum outro lugar em qualquer oferta de banco de dados gerenciado em nuvem.

E então a outra opção de banco de dados que está disponível no OCI são os bancos de dados autônomos. Agora, banco de dados autônomo é um banco de dados em nuvem que usa aprendizado de máquina para automatizar o ajuste de banco de dados, segurança, backups, atualizações e outras tarefas de gerenciamento de rotina tradicionalmente executadas por DBAs. Há dois tipos de cargas de trabalho com suporte como parte do banco de dados autônomo. Um é chamado Autonomous Data Warehouse, também conhecido como ADW, e o outro é Autonomous Transaction Processing, também conhecido como ATP. Portanto, essas são as duas cargas de trabalho com suporte como parte dos bancos de dados autônomos.

Existem dois tipos de modelos de implantação. O primeiro, como você pode ver na tela aqui, é chamado de modelo de implantação compartilhada. Aqui, você provisiona e gerencia apenas o banco de dados autônomo enquanto a Oracle lida com a implantação e o gerenciamento da infraestrutura Exadata. Como você pode ver neste slide, o autônomo faz uso do Exadata abaixo. Então essa é a primeira opção de implantação.

A segunda opção de implantação é dedicada. Com esta opção, você tem o uso exclusivo do hardware Exadata que roda por baixo. Então, compartilhado, pense no que é um ambiente compartilhado multilocatário, dedicado, único locatário dedicado a você.

Agora, com Exadata, você aqui esses três termos o tempo todo. O que esses termos significam? Bem, autocondução, como acabamos de explicar, significa que todos os processos de gerenciamento, monitoramento e ajuste de banco de dados e infraestrutura são automatizados. Assim, os DBAs agora podem se concentrar em tarefas mais importantes. Então é isso que queremos dizer com auto-condução.

Autoproteção basicamente significa que o banco de dados autônomo possui recursos integrados que protegem contra ataques externos e usuários internos mal-intencionados. Assim como esses robustos recursos de segurança integrados. E a autorreparação significa que o banco de dados pode evitar o tempo de inatividade, incluindo manutenção não planejada, e existem alguns SLAs em torno disso.

Então, isso é o que queremos dizer com auto-condução, auto-segurança e auto-reparação. Portanto, essas são as primeiras cinco ou seis opções de banco de dados disponíveis como bancos de dados de nuvem gerenciados no OCI. Alguns dos - e você pode ver o amplo espectro aqui, desde provisionamento rápido, desempenho rápido, até opções de banco de dados completamente automatizadas, autônomas, autoprotegidas e autorreparáveis.

Novamente, algumas das outras opções disponíveis no OCI também incluem algumas opções de banco de dados de código aberto, incluindo MySQL. Portanto, o serviço de banco de dados MySQL é um serviço OCI totalmente gerenciado. Ele é desenvolvido, gerenciado e suportado pela equipe MySQL que trabalha na Oracle.

Também temos um serviço de banco de dados NoSQL que oferece throughput sob demanda e provisionamento baseado em armazenamento. Esse serviço específico oferece suporte a tipos de dados JSON, tabela e valor-chave, todos com garantias de transação flexíveis e latências de milissegundos de um dígito. E o último é o banco de dados JSON autônomo. E este é voltado para o desenvolvimento de NoSQL aplicativos de estilo que usam documentos JSON.

Então, apenas para recapitular, analisamos todas as ofertas de banco de dados em nuvem gerenciada na OCI. E há oito ou nove opções diferentes começando com sistemas VMT, sistemas de banco de dados bare metal, banco de dados VM de 2 nós, clusters de banco de dados RAC, Exadata Cloud Service, autônomo que vem em dois tipos de cargas de trabalho, data warehouse, processamento de transações, dois modelos de implantação compartilhados e dedicado. E, em seguida, alguns outros serviços de banco de dados, incluindo opções de banco de dados de código aberto como MySQL e serviço de banco de dados NoSQL, bem como esse serviço de banco de dados JSON.

So This OCI oferece uma gama completa de serviços de banco de dados em nuvem gerenciados amplos e profundos. E assim, nas próximas lições, vamos nos aprofundar em muitos desses serviços. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Autonomous DB

Bem-vindo a esta lição sobre Bancos de Dados Autônomos.

Resumimos o que são bancos de dados autônomos na lição de introdução, mas vamos analisá-los com um pouco mais de detalhes aqui.

Portanto, a ideia principal do Autonomous Database, Autonomous Databases, é um banco de dados em nuvem que usa Machine Learning para automatizar o ajuste de banco de dados, segurança, backups, atualizações e outras tarefas de gerenciamento de rotina tradicionalmente realizadas pelo DBS.

Portanto, a ideia é que todos os processos de gerenciamento, monitoramento e ajuste de banco de dados e infraestrutura sejam automatizados, e o DBS agora pode se concentrar em tarefas mais importantes. Essa é a ideia chave por trás dos Autonomous Databases.

Então é isso que está sendo mostrado aqui, é uma automação de infraestrutura completa. É uma automação completa de banco de dados e operações automatizadas de data center e aprendizado de máquina. Então a ideia é que você pode, o quanto você puder automatizar, e deixar seus usuários focarem em tarefas diferenciadas, de nível superior, melhor, né, porque eles não precisam se envolver com muitas tarefas manuais e repetitivas tarefas.

Eles não precisam fazer isso, porque algumas dessas tarefas também são propensas a erros. Então, usando tecnologias como aprendizado de máquina, podemos tirar isso da equação, deixá-los focar no valor agregado para tarefas diferenciadas de nível superior.

Então, que tipo de opções e sabores são suportados no OCI hoje? Portanto, há duas opções suportadas, uma é chamada de Compartilhada e outra é chamada de Dedicada. Como o nome especifica, Dedicated basicamente significa que você tem uso exclusivo do hardware Exadata, hardware Exadata subjacente. É aqui que você tem o Autonomous Database e o Exadata totalmente dedicado a você.

No modelo Compartilhado, você provisiona e gerencia apenas o banco de dados autônomo, enquanto a Oracle lida com a implantação e o gerenciamento da infraestrutura Exadata, sendo novamente compatível com esses modelos. Quais são esses dois modelos?

Dentro do Exadata, você tem dois tipos de banco de dados, que são suportados, um é chamado Autonomous Transaction Processing, isso é para o seu OLTP, então pense nas transações. E o segundo é o Autonomous Data Warehouse, para seu processamento analítico online. Portanto, há suporte para dois modelos de tipo de banco de dados distintos, suporte para cargas de trabalho e suporte para a opção Compartilhado e para a opção Dedicado.

E novamente, como dissemos muitas vezes, autônomo, independentemente de você estar executando Scared ou Dedicated, ou ATP ou ADW, essas são a nomenclatura para Processamento de Transações e Data Warehousing.

Algumas dessas tarefas listadas no slide são todas automatizadas. Então, coisas como backup, coisas como patch, upgrade, ajuste de banco de dados, tudo isso é automatizado para você.

Mais uma vez, apenas esse tipo de tema continua voltando de novo e de novo. É uma automação completa que é um grande foco para o Autonomous, então coisas como expansão, expansão, ajuste, patch de segurança, tudo isso é suportado. E a ideia principal é a ideia de autoproteção para que tenhamos recursos de proteção contra ataques externos e usuários internos mal-intencionados.

Auto-reparação significa auto-ajuste, o que significa que podemos evitar o tempo de inatividade, incluindo manutenção não planejada e condução autônoma, o que significa que muitas dessas tarefas manuais repetitivas são automatizadas, para que os usuários possam se concentrar em tarefas aditivas diferenciadas de valor mais alto, certo.

E você pode ver que, embora façamos tudo isso, nenhuma das vantagens do banco de dados, coisas como RAC, Data Guard, Database Vault, todos esses recursos, não sacrificamos, e todos eles ainda são suportados neste modelo de banco de dados autônomo .

Então pessoal, isso é Autonomous Database. Da próxima vez que você pensar em fazer aquela tarefa repetitiva de banco de dados, não faça isso. Basta adotar Bancos de Dados Autônomos e você verá a diferença por si mesmo. Obrigado por assistir.

### Demo: Autonomous Data Warehouse

Bem-vindo a esta demonstração do Autonomous Data Warehouse. Para começar, clique no menu de navegação de serviços no lado esquerdo. E clique no banco de dados Oracle. E você vê várias opções para criar bancos de dados Oracle, seja um banco de dados autônomo, seja um sistema Bare Metal e Exadata DB, e assim por diante.

Então, nesta demonstração em particular, vamos criar um Autonomous Data Warehouse. Então clique em Autonomous Data Warehouse. E isso deve abrir um assistente para criar o Autonomous Data Warehouse. Então eu clico nisso. E então ele me fornece várias opções. A primeira coisa é que você precisa escolher o compartimento. Todas as nossas demos, estamos usando o compartimento sandbox.

E estou aqui logado como administrador da OCI, o mesmo administrador que usamos para todas as nossas outras demos. Ele escolhe um nome de exibição para o banco de dados. Estou feliz com esse nome. Ele também escolhe um nome para o banco de dados. Estou bem com isso. E então aqui, temos que escolher uma carga de trabalho.

Normalmente, você escolheria um data warehouse para processamento de transações OLAP para OLTP, JSON para desenvolvimento de aplicativos centrados em JSON. E há também um ambiente de desenvolvimento de baixo código chamado APEX. Então você pode escolher isso dependendo se você está planejando usá-lo. Para nossos propósitos, estamos escolhendo Data Warehouse. Então, isso vem como verificado aqui.

E há dois tipos de modelos de implantação. Uma é a infraestrutura compartilhada em que você está executando esse banco de dados autônomo em uma infraestrutura compartilhada do Exadata. E a segunda opção é executar isso em uma infraestrutura dedicada. Estou bem com a infraestrutura compartilhada aqui. Eu posso ver todas essas três opções aqui. Por mim tudo bem. Posso escolher uma versão do banco de dados. 19C é bom.

E agora aqui eu posso escolher o número de CPUs que vai de 1 a 128. Como estou executando em uma conta de nível gratuito, tudo bem com a conta de 1 OCPU. E aqui o armazenamento também é massivamente escalável de 1 a 128 terabyte. Estou bem com um terabyte.

E o escalonamento automático aqui é um recurso interessante. Ele permite que o sistema use até três vezes o número provisionado claro, se esta opção ocorrer e recursos de E/S para atender a demanda de carga de trabalho. Portanto, esta opção está marcada aqui. Vou mantê-lo assim.

E aqui eu tenho que criar minhas credenciais de administrador. Deixe-me inserir rapidamente minhas credenciais aqui. Estou feliz com isso. E agora diz escolha Acesso à rede. Posso escolher acesso seguro de qualquer lugar. Ou eu poderia escolher Acesso de apenas uma VCN específica.

E também posso configurar o que chamamos de regras de controle de acesso. E a regra de controle de acesso conforme o texto especifica aqui bloqueia todos os endereços IP, blocos CIDR e VCNs que não estão nesta lista. Eu poderia fornecer essa opção. Para esta demonstração em particular, vou ignorá-la. E então posso escolher meu tipo de licença-- traga sua própria licença ou licença incluída. Licença incluída é bom para mim. Então eu vou fazer essa opção. E é quase isso.

Para a opção avançada, eu poderia escolher as chaves de criptografia. Nesse caso, o Oracle gerencia a criptografia. Portanto, essa opção está ativada por padrão. Caso contrário, os clientes podem usar suas próprias chaves. Portanto, há uma opção de usar criptografia para fazer criptografia usando chaves gerenciadas pelo cliente.

Então, com essas opções, clicarei em Create Autonomous Database, neste caso, criando Autonomous Data Warehouse. E você veria dentro de alguns segundos, na verdade, este Autonomous Data Warehouse estaria funcionando. E então o que faremos é usar algo chamado SQL Worksheet e executar nossa primeira consulta. Então deixe-me pausar minha demonstração aqui. E assim que o Autonomous Data Warehouse estiver funcionando, prosseguiremos com as próximas etapas.

E como você pode ver aqui, levou literalmente menos de 30 segundos. E meu Autonomous Data Warehouse está funcionando. Eu posso ver que tem um armazenamento de 1 terabyte, tem uma conta de CPU. E há alguns outros detalhes aqui. Você pode ver a janela para a próxima manutenção e assim por diante e assim por diante - operações dentro, alguns dos recursos avançados.

Agora, o que realmente nos interessa -- e você pode ver algumas matrizes e backups, etc. aqui. Então, o que estamos interessados ​​em fazer aqui é usar algo chamado SQL Worksheet para se conectar a este Autonomous Data Warehouse e executar alguns recursos.

Então, o primeiro passo aqui é que temos que nos conectar com a planilha SQL. Então deixe-me clicar em Ações do Banco de Dados aqui. E você pode ver o monte de opções disponíveis. Eu poderia trazer o Graph Studio. Há uma administração de usuários de aprendizado de máquina aqui. E essa coisa aqui chamada Database Actions. Deixe-me apenas clicar nele.

E agora preciso logar na planilha MySQL. Então deixe-me apenas fornecer as credenciais que fornecemos quando instanciamos o Autonomous Data Warehouse. Deixe-me fornecer minha senha aqui. E clique em Entrar. E como você verá aqui, nesta demonstração específica, estamos usando o SQL Worksheet, que é um dos recursos das ações do banco de dados, interface baseada na web para Oracle Autonomous Database.

E como você pode ver aqui, o monte de opções que posso usar para começar. Há alguma ajuda opções, etc. Eu posso carregar dados. Eu posso ver um catálogo. E há opções para desempenho, ajuda, etc. Há também opções para administração. Para esta demonstração específica, estou interessado apenas em executar uma consulta básica. Então, deixe-me clicar aqui e, em seguida, executar uma consulta simples que me retornará alguns dados.

Portanto, o aplicativo que vamos usar é baseado no Data Warehouse incluído no ADW. O ADW fornece o esquema de amostra do histórico de vendas do Oracle e o conjunto de dados de referência do Star Schema. Esses conjuntos de dados estão no esquema SHN SSB. Então, o que vamos fazer é executar uma consulta básica no conjunto de dados SSB, que é de aproximadamente 1 terabyte de conjunto de dados com uma tabela de fatos e cerca de 6 bilhões de linhas e várias tabelas de dimensões.

E você verá que a consulta executará uma consulta e me retornará os resultados rapidamente. Então deixe-me executar isso. Portanto, esta é a consulta que vou executar aqui. Como você pode ver, essa consulta será executada no benchmark de esquema em estrela SSB.customer. Este é um dos dois conjuntos de dados de amostra ATW, que podem ser acessados ​​de qualquer instância ATW. Então, deixe-me executar rapidamente esta consulta.

E você veria que essa consulta está passando por aproximadamente 6 bilhões de registros. E demorei dois segundos. E ele me retorna esse conjunto específico de resultados aqui. E há várias outras opções que você pode ver aqui. ATW também armazena em cache os resultados de uma consulta para você. Portanto, se você executar essas consultas idênticas mais de uma vez, notará um tempo de resposta muito menor. E seus resultados foram armazenados em cache.

Então deixe-me tentar novamente e você verá que agora está sendo executado em 0,011 segundos. Tantas, muitas vezes menores, porque está armazenando esses resultados em cache. E então você tem outras opções, opções avançadas, como rastreamento automático, etc., que você pode obter aqui.

Espero que tenha sido uma demonstração rápida de como criar um Data Warehouse Anônimo. Literalmente, levamos menos de 30 segundos e, em seguida, como você se conecta a ele usando uma planilha SQL e, em seguida, começa a usar o Autonomous Data Warehouse executando consultas, carregando dados etc. Espero que você tenha achado esta demonstração útil. Obrigado pelo seu tempo.


### DB Systems

Bem-vindo a esta lição sobre sistemas de banco de dados OCI, também chamados de sistemas de banco de dados.

Então, quais são esses sistemas de banco de dados? Vamos analisá-los com um pouco mais de detalhes.

Portanto, esses são bancos de dados Oracle totalmente gerenciados e com todos os recursos executados na nuvem. Eles suportam Enterprise ou Standard Edition, você pode ver todas as versões suportadas de 11 a 21c, e você tem diferentes tipos de opções de licenciamento, incluindo trazer suas próprias licenças.

Você pode executar esses sistemas de banco de dados de banco de dados em máquinas virtuais ou em formas bare metal, também há suporte para Exadata, eles estão disponíveis em todas as regiões do mundo. E você pode automatizar totalmente seu ambiente, começando com provisionamento, aplicação de patches, backup e até recuperação de desastres. E nos próximos slides, veremos alguns deles com um pouco mais de detalhes.

Portanto, antes de analisarmos os recursos, vamos falar sobre algumas das configurações disponíveis. Portanto, a primeira configuração disponível é o Virtual Machine DB Systems, você pode ir até 24 OCPUs, obter até 320 giga de RAM e obter 40 terabytes de armazenamento em bloco utilizável.

Lembre-se, esta é uma máquina virtual, portanto, os dados estão sendo armazenados em uma VM, em um armazenamento em bloco, para que você possa proteger esses dados com segurança, armazená-los mesmo além do ciclo de vida da própria instância de computação.

Em um Oracle RAC on Virtual Machine estende isso e oferece essa alta disponibilidade. Portanto, agora você pode criar dois nós e obter essa alta disponibilidade por meio do Oracle RAC Configuration.

E a terceira opção é executar o Oracle DB em servidores Bare Metal. Mas lembre-se, neste caso, seu banco de dados está sendo executado em armazenamento local, mas você pode obter até 16 terabytes de armazenamento NVMe local utilizável e 52 OCPU e 768 GB de RAM.

Se você quiser provisionar algo rapidamente, poderá usar a máquina virtual. Se você realmente deseja desempenho rápido, pode optar pela opção Bare Metal aqui.

Vejamos alguns dos recursos que estão disponíveis em sistemas de banco de dados. Então falamos sobre o fato de que você pode usar um sistema de banco de dados de máquina virtual, você pode usar um sistema de banco de dados Bare Metal, um RAC. O Exadata está além do escopo deste curso, então não abordamos isso.

Mas esses sistemas de banco de dados vêm em vários tipos ou várias formas, conforme listado na tela, e também ajudam na automação completa do ciclo de vida. Portanto, seja provisionando, corrigindo, fazendo backup ou restaurando, todos esses recursos são suportados.

A alta disponibilidade é suportada usando recursos como RAC, Real Application Clusters e também por meio do Data Guard, onde você pode criar um primário e um stand-by, e pode sincronizar seus dados na mesma região ou entre regiões.

Você também pode fazer escalabilidade por meio do dimensionamento dinâmico de CPU e armazenamento, para que você possa aumentar e diminuir e também alterar seu armazenamento.

E a segurança é incorporada em várias camadas, então essa diferença é profunda, para que você tenha segurança na camada de infraestrutura por meio de coisas como gerenciamento de identidade e acesso, autorização, autenticação.

Você também tem segurança dentro do banco de dados, então coisas como criptografia de dados transparente, seus backups são sempre criptografados, os volumes de blocos são sempre criptografados e coisas assim.

E, finalmente, você pode trazer suas próprias licenças neste modelo específico. A única coisa que não está listada no slide é o modelo de cobrança. Acredito que para máquinas virtuais, você poderia fazer cobranças de forma permanente. Eu acredito que para Bare Metal, acho que é por hora, mas você deve sempre verificar a documentação. Mas quero mencionar que o faturamento permanente é suportado para esses sistemas de banco de dados.

E é isso. Os sistemas de banco de dados são realmente poderosos. É uma maneira fácil de você começar. Se você estiver usando sistemas de banco de dados de máquina virtual, se quiser desempenho massivo, vá com o Bare Metal. Se você quiser ainda mais desempenho, vá com o Exadata DB Systems.

Então pessoal, isso é um envoltório. Isso é DB Systems para você. Obrigado por assistir.

### MySQL
Bem-vindo a esta lição sobre MySQL Cloud Service, às vezes também chamado de MySQL Database Cloud Service. Vamos examinar todos os recursos desse serviço específico e aprimoraremos dois conceitos-chave ou dois recursos-chave desse serviço específico. Portanto, alguns dos recursos genéricos, você pode hospedar bancos de dados MySQL na nuvem por meio deste serviço. Você pode provisioná-los rapidamente. Você pode aplicar patches, reverter, fazer todas essas coisas.

É tudo computação elástica, então você pode aumentar ou diminuir suas fontes, seja computação ou armazenamento. Você pode fazer replicações e tem todos os tipos de recursos de segurança disponíveis. E então reduz seu custo de propriedade porque agora você está usando o MySQL como um serviço de nuvem em vez de executá-lo por conta própria.

Os dois recursos que eu realmente quero destacar nesta lição em particular são Alta Disponibilidade e HeatWave, então o que é Alta Disponibilidade? A Alta Disponibilidade basicamente oferece essa tolerância e tem muitos benefícios, como failover automático, maior tempo de atividade, perda zero de dados. Assim, você pode criar um banco de dados MySQL autônomo no OCI ou pode criar esse banco de dados de alta disponibilidade.

Agora, o que isso realmente significa? Com a opção autônoma, você obtém uma única instância do MySQL DB Systems, com back-end do OCI Block Volume resiliente e seguro. Essa opção é boa para o ambiente de desenvolvimento, teste e desenvolvimento, mas se você estiver executando em produção, você realmente deseja usar a opção de alta disponibilidade. Essa opção permite que os aplicativos atendam a requisitos de tempo de atividade mais altos e configurem a tolerância zero à perda de dados.

Quando você seleciona a opção High Availability, o MySQL DB System com três instâncias é provisionado em diferentes domínios de disponibilidade ou domínios remotos diferentes. Os dados são replicados entre as instâncias. Agora, quando seu aplicativo se conecta ao único endpoint para ler e gravar dados no banco de dados, em caso de falha, se um domínio de disponibilidade não estiver disponível ou um domínio remoto não estiver disponível, o MySQL Database Service fará o failover automaticamente em minutos para uma instância secundária sem perda de dados e sem a necessidade de reconfigurar o aplicativo. Então, da próxima vez que você estiver executando o MySQL em produção, definitivamente pense em usar a opção de Alta Disponibilidade por causa de todos os benefícios que ela oferece.

O segundo recurso chave sobre o qual quero falar é o MySQL Database Service com HeatWave, então o que é HeatWave? O HeatWave é um novo acelerador de consulta na memória integrado e de alto desempenho para o MySQL Database Service que acelera o desempenho do MySQL por ordem de grandeza para análises e consultas de transação. O HeatWave é dimensionado para milhares de núcleos.

O MySQL Database Service com HeatWave é o único serviço disponível no mercado que permite que administradores de banco de dados e desenvolvedores de aplicativos executem cargas de trabalho OLTP e OLAP diretamente de seu banco de dados MySQL. Isso elimina a necessidade de movimentação de dados complexa, demorada e cara e integração com um banco de dados de análise separado. Além disso, lembre-se de que esse serviço é otimizado e está disponível exclusivamente no Oracle Cloud Infrastructure.

Novamente, é um recurso muito novo. Dê-lhe um tiro. Ele definitivamente agrega muito valor, comparado à abordagem tradicional de usar o MySQL apenas para fins de OLTP.

Vamos encerrar. As duas principais características definidoras do MySQL Database Cloud Service são o recurso de alta disponibilidade, que você definitivamente deve usar para produção, e o HeatWave, que permite fazer transações OLAP e OLTP usando o MySQL Database Cloud Service. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### NoSQL

Bem-vindo a esta lição sobre o Oracle NoSQL Database Cloud Service. Esta será uma pequena lição. Vejamos alguns dos principais recursos fornecidos por esse serviço específico. Portanto, algumas das características definidoras desse serviço estão listadas neste slide específico. É uma lista longa.

O serviço é totalmente gerenciado. É elástico. Possui alto desempenho. E o número a ser observado, portanto, são as latências previsíveis de milissegundos de um dígito com altas cargas de trabalho, com alta largura de banda. Você tem flexibilidades de modelo de dados. Então, usando o mesmo banco de dados, você poderia -- seu banco de dados suporta modelos de documentos, esquemas fixos, valores-chave. E há uma única interface de aplicativo. E suporta todos esses modelos.

Você obtém segurança de nível empresarial. Você pode gerenciar todos os tipos de acesso. É um custo operacional baixo, pois você está rodando na Nuvem. Claro, o banco de dados NoSQL é muito usado pelos desenvolvedores. Portanto, é amigável ao desenvolvedor. Ele tem essas APIs Rest. Está sempre disponível. Assim, ele aproveita todos os recursos de alta disponibilidade do Oracle Cloud Infrastructure. E então ele também é executado no local.

Então eu sei que essa é uma longa lista de recursos. Mas alguns dos principais recursos a serem lembrados aqui são a flexibilidade do modelo de dados, documento de suporte, esquema fixo, pagadores de valor-chave, alto desempenho, latências de milissegundos de um dígito e o fato de estar disponível na nuvem e on-line. instalações. E funciona perfeitamente nos dois lugares. Esses são os principais recursos a serem considerados para este serviço específico.

Quais são alguns dos principais casos de uso do NoSQL Database Cloud Service, muitos desses aplicativos modernos, sejam aplicativos móveis, IoT, muitos desses aplicativos de publicidade on-line, todos esses aplicativos em que há uma grande quantidade de volume, a principal coisa que é comum entre todos esses aplicativos - grande quantidade de volume que você usaria no NoSQL Database Cloud Service.

Novamente, esta deveria ser uma lição muito curta. A ideia é dar a você apenas uma rápida introdução sobre o que é o Oracle NoSQL Database Cloud Service. Espero que você tenha achado esta introdução rápida útil. Obrigado por assistir.

### Database Summary

Vamos resumir o que você aprendeu neste módulo. Oracle Databases-- as muitas opções de banco de dados disponíveis no Oracle Cloud Infrastructure.

Analisamos todas as várias opções disponíveis, sejam máquinas virtuais, que podem ser usadas para provisionamento rápido, seja um cluster RAC de dois nós para fornecer alta disponibilidade em um domínio de disponibilidade, sejam máquinas Bare Metal, o único nó Bare Máquinas de metal onde você pode executar bancos de dados para obter um desempenho realmente rápido, ou seja Exadata, um quarto de rack, meio rack, rack completo Exadata perdoando a enorme quantidade de desempenho que você precisa.

E então, finalmente, analisamos os Autonomous Databases e o fato de que eles são autoprotegidos, auto-reparáveis ​​e autodirigidos e têm muita bondade, muita automação incorporada. Analisamos cada um deles com mais detalhes.

E também analisamos as outras opções de banco de dados de código aberto disponíveis no Oracle Cloud Infrastructure usando MySQL e os dois principais recursos de definição, incluindo Alta Disponibilidade e Heat Wave.

E então abordamos rapidamente o NoSQL Cloud Service. Espero que você tenha achado esta informação útil. Obrigado por assistir.

### Exercicios

1. Qual edição de banco de dados você usaria para iniciar um sistema de banco de dados Oracle RAC de dois nós?

- [x] Oracle Enterprise Edition - Desempenho Extremo.
- [] Edição padrão do banco de dados
- [] Banco de dados Enterprise Edition
- [] Banco de dados Enterprise Edition de alto desempenho

2. Qual opção de infraestrutura está disponível para criar e gerenciar um Autonomous Database?

- [] Exadata Cloud@Customer
- [x] Infraestrutura Dedicada
- [] Sistema de banco de dados VM
- [] Infraestrutura Bare Metal

3. Qual banco de dados totalmente gerenciado você usaria para atingir uma latência de milissegundos de um dígito com cargas de trabalho de alto desempenho?

- [x] NoSQL
- [] MySQL
- [] Sistema de banco de dados
- [] Autônomo

4. Quais tipos de sistemas de banco de dados NÃO estão disponíveis no OCI?

- [] Sistemas de banco de dados Bare Metal
- [x] Sistema de banco de dados ATP
- [] Sistema de banco de dados Exadata
- [] Sistema de banco de dados VM

5. Qual tarefa NÃO é executada por padrão por um Autonomous Database?

- [] Patch de Firmware
- [] Atualizações de banco de dados
- [x] Carregando dados
- [] Backups

## 9- Security

### Security Introduction

Bem-vindo a este módulo sobre Segurança OCI. Vamos começar com uma introdução. Então, em segurança, você sempre ouve esse termo chamado modelo de segurança compartilhado. O que isso realmente significa? Bem, em um ambiente local, você possui toda a pilha e é responsável pela segurança de ponta a ponta. Conforme você muda para a Nuvem, algumas das responsabilidades são transferidas para o provedor de Nuvem, neste caso a Oracle, e algumas são retidas por você. Então é isso que queremos dizer com um modelo de segurança compartilhada.

Como é na Nuvem? Bem, na Nuvem, o Oracle Cloud Infrastructure é responsável pela segurança da Nuvem, o que significa coisas como o data center físico, a rede física, o host físico e até a camada de virtualização, garantindo que seja rápido e atualizado. Todas essas são responsabilidades da Oracle. Então essa é basicamente a segurança da Nuvem.

Você é responsável pela segurança na nuvem. O que isso significa? Bem, isso significa que você é responsável pelos dados, você é responsável pelos terminais, dispositivos, dispositivos móveis ou PCs, ou seus servidores, seus PCs que os acessam. E você é responsável pelo gerenciamento de contas e acessos, portanto, gerenciamento de identidades e acessos.

E há algumas outras coisas pelas quais você é responsável, como se estiver usando sistemas operacionais, você precisa ter certeza de que eles estão corrigidos e atualizados. Portanto, este é o modelo na nuvem, algumas responsabilidades mudam para o provedor da nuvem. Algumas responsabilidades ainda são mantidas por você. Então, vamos olhar para o portfólio de segurança OCI disponível atualmente no OCI.

Coloquei no slide os casos de uso e os serviços. Então você realmente entende não apenas os serviços, mas também o contexto em que eles operam. Assim, a primeira camada baseia-se na abordagem em camadas. E também é bom porque mostra que a segurança segue a defesa em profundidade, o que significa que você tem segurança em diferentes camadas da pilha. A segurança não é apenas um complemento. Não é apenas algo que você acessa separadamente. É diferente em profundidade.

Está disponível em diferentes camadas da pilha. Então, a primeira coisa com a qual começamos é a proteção da infraestrutura. E isso basicamente temos vários serviços para DDoS, firewall de aplicação, etc, o que ajuda na proteção da infraestrutura. O DDoS pode ser categorizado em camada 7, camada 3 e 4. E temos serviços para cada uma das camadas. Portanto, o WAF ajuda com parte da proteção DDoS da camada 7.

E a proteção DDoS de camada 3 e camada 4 está ativada por padrão. Então, indo além disso, você precisa proteger o sistema operacional e a proteção da carga de trabalho. Portanto, temos vários recursos para ajudar lá. Temos um serviço chamado Gerenciamento de SO, que ajuda a automatizar patches e simplificar a implantação de pacotes.

Temos servidores bare metal onde você pode ter um host dedicado, que pode ser isolado em um único modelo de locatário, etc. Além disso, temos esse conjunto de serviços que fornecem inteligência na detecção de segurança e também na correção automática. Às vezes, eles são chamados de recursos de gerenciamento de postura de segurança na nuvem, CSPM.

E sob esses serviços, temos muitos recursos, como Cloud Guard e zonas de segurança. E veremos cada um deles nas próximas lições. A proteção de dados é tão importante como sempre e há muitos serviços que você pode aproveitar, incluindo o gerenciamento de chaves fornecido a um serviço chamado Vault.

Existe um serviço chamado Data Safe, que está disponível com nossos bancos de dados em nuvem, etc. Além disso, uma coisa a ter em mente aqui é que a criptografia está sempre ativada por padrão no OCI. Além disso, você tem gerenciamento de identidade e acesso, onde pode gerenciar autenticação e autorização e também coisas como autenticação multifator.

Esta é a nossa linha de segurança. A coisa a ter em mente é a defesa em profundidade. Portanto, a segurança, como você pode ver aqui, é implementada em várias camadas da pilha. Então, como tudo isso funciona? Como você pode ver neste gráfico aqui, você tem um ambiente onde você tem algumas redes virtuais. E você está usando vários serviços de segurança, seja verificação de vulnerabilidades, auditoria, Bastion Service, Vault ou o serviço Identity Access Management.

Então, novamente, na próxima lição, entraremos em muitos desses serviços em detalhes. Mas lembre-se de que temos um conjunto muito amplo e extenso de serviços de segurança. Então, apenas para recapitular, na nuvem, quando você migra para a nuvem, basicamente você obtém esse modelo de segurança compartilhado.

E você é responsável por alguns dos aspectos de segurança e o provedor de nuvem cuida dos outros aspectos. E a segurança não é apenas um serviço ou um complemento, há todo um extenso conjunto de serviços disponíveis em diferentes camadas da pilha. Passamos por alguns deles. Nas próximas lições, veremos alguns deles com mais detalhes. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Cloud Guard


Bem vindo de volta. Nesta lição, veremos o Oracle Cloud Guard. O Oracle Cloud Guard é um recurso muito exclusivo disponível no Oracle Cloud Infrastructure.

O que é o Oracle Cloud Guard? O Cloud Guard é um serviço que se enquadra na categoria de segurança -- gerenciamento de postura do Cloud Security. Ele ajuda a monitorar e identificar possíveis problemas de segurança e corrigi-los. O que é realmente interessante sobre o Cloud Guard é que ele pode automatizar completamente a correção.

Como você pode ver aqui, os dois aspectos principais -- você detecta um problema. E há algumas maneiras de fazer isso. Você pode verificar as configurações, monitorar as atividades e, em seguida, aplicar uma resposta. E você pode automatizar essa resposta.

Então, como isso realmente funciona na prática? Então, a primeira coisa que você faz é especificar um alvo. E um destino basicamente define o escopo dos recursos a serem examinados para que os compartimentos OCI possam ser segmentados e seu compartimento filho possa ser o destino. Assim, o alvo nada mais é do que recursos a serem examinados.

Então você tem detectores. E esses detectores são basicamente problemas identificados. Detectores são componentes do Cloud Guard que identificam problemas com recursos ou ações do usuário e alertam quando um problema é encontrado. Então, como você pode ver aqui, se houver uma instância pública onde não deveria estar, ele sinalizará isso. Se houver um bucket público, ele sinalizaria isso, etc.

Então você tem problemas, e os problemas são potenciais problemas de segurança. Então, de certa forma, falar sobre problemas como notificações de que uma configuração ou atividade é um possível problema de segurança. E, finalmente, temos os respondedores, que fornecem notificações e ações corretivas para problemas de segurança. Então, como você pode ver aqui, se as instâncias forem públicas, você poderá parar essa instância. Se um bucket for público, você poderá desativá-lo ou torná-lo privado e assim por diante. Você pode decidir que tipo de respondedores deseja.

Agora, vamos ver isso em ação. Portanto, o cenário aqui é um bucket público e você não deseja que esse bucket seja público. Você quer que este seja um bucket privado porque isso se alinha com sua postura de segurança. Então, primeiro, o que o Cloud Guard faz, suponha que esse bucket esteja vivendo em um compartimento, que é monitorado pelo Cloud Guard.

O Cloud Guard está executando esse monitoramento de configuração. Então, ele está olhando para o seu bucket e aciona um sinalizador dizendo que esse bucket específico é público. E sinaliza isso como um problema crítico, e um problema é criado. Então pense no nosso problema como uma espécie de bilhete. Então, é criado dizendo que o bucket é público. E, ao mesmo tempo, porque atribui uma pontuação de segurança, diz que é um risco crítico. Então ele notifica que é um risco crítico.

E, então, há respondentes, que olham para isso. E eles dizem, meu respondedor está ativado para esse tipo de problema? E se a resposta for sim, ele também pode ter funcionalidades adicionais -- coisas como Cloud Event. Ele pode ir para o Cloud Event, acioná-lo como um evento e, em seguida, você pode receber notificações disso.

Você também pode ir para as funções OCI, que é nosso serviço sem servidor, e pode fazer outra coisa. Isso pode te desanimar ou algo assim. Portanto, poderia ter algum outro recurso embutido. Então, o respondente analisa isso e depois o entrega a um operador do Cloud Guard. Esta é uma política que você escreve, que diz, posso remediar o problema?

Tenho permissão para corrigir o problema porque uma coisa interessante sobre o Cloud Guard é que você pode automatizar tudo isso. E se a resposta for sim, então ele responde. E torna o bucket privado. E é assim que você vai para aquele risco crítico, e a situação fica verde novamente.

Portanto, esse é um fluxo de trabalho de ponta a ponta sobre como o Cloud Guard funciona. Muito disso é transparente. Você não vê. E é uma ótima maneira de detectar e corrigir problemas automaticamente.

Apenas para recapitular, o Cloud Guard é um serviço que se enquadra na categoria Cloud Security Posture Management. Ele ajuda a monitorar e identificar possíveis problemas de segurança e corrigi-los. Você também pode corrigir automaticamente esses problemas. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Security Zones and Security Advisor

Bem-vindo a esta lição sobre Zonas de Segurança e Consultor de Segurança. Zona de segurança é configurar um local no qual você não pode desabilitar a segurança. O Security Advisor é um serviço que unifica o Security Zone, o Cloud Guard e alguns outros recursos em um todo coeso. Nesta lição, examinaremos esses dois serviços.

Então, primeiro, vamos ver as Zonas de Segurança. O que são as Zonas de Segurança? Bem, falamos que você tem recursos em seus compartimentos. Como você pode ver aqui, você tem dois compartimentos chamados compartimento A e compartimento B. Você pode designar o compartimento B como uma zona de segurança. O que isso significa?

Bem, isso significa que este compartimento em particular, uma vez que é atribuído a essa nomenclatura da Zona de Segurança, tem um conjunto de receitas da Zona de Segurança. Estas não são nada além de suas políticas que são aplicadas aqui. E sempre que há uma violação de política, essa operação é negada.

Então, como isso se parece? Quais serviços são suportados? Bem, os principais primitivos hoje são suportados, incluindo rede, armazenamento, computação e bancos de dados. O que isso realmente significa? Bem, se você especificar que a sub-rede sempre tem que ser privada, se você criar uma sub-rede pública, essa operação será negada. Se as regras disserem que as chaves mestras de criptografia do cliente devem ser usadas em vez do provedor, gerencie as chaves de criptografia. E se isso for violado, a operação será negada.

Então a ideia é você pegar uma parte do seu arrendamento, pensar na sua própria casa. Você tem os itens mais seguros que possui, seja seu passaporte, documentos, jóias ou qualquer outra coisa, você pode mantê-los em um cofre seguro. Torná-lo seguro contra incêndios, etc., para que esteja protegido em caso de qualquer tipo de violação ou desastre natural.

Então a mesma ideia se aplica aqui. Você pega sua locação, nem tudo em sua locação é super seguro, mas alguns elementos em sua locação, algumas partes dela serão super seguras. Você cria zonas de segurança. Às vezes, também é referido como Max Security Zones. E os recursos ali mantidos têm uma espécie de política aplicada a eles, receitas aplicadas a eles. E essas políticas não podem ser violadas.

A maneira simples de pensar em zonas de segurança. O consultor de segurança é realmente um serviço combinado que reúne a funcionalidade fornecida pelo Cloud Guard e pelo Security Zone, bem como alguns dos outros serviços de segurança. Então, de certa forma, é nosso próprio ponto de vista sobre como a segurança deve ser feita. Os serviços que são suportados hoje são armazenamento de objetos, armazenamento de arquivos, volume de blocos e máquinas virtuais.

E, novamente, alguns dos exemplos sobre os quais falamos anteriormente, os buckets não podem ser públicos. E isso pode ser imposto pelo Security Advisor. O Security Advisor orientará você sobre como criar um bucket em uma zona de segurança. E vem com seu próprio conjunto de requisitos.

Você tem que usar uma chave de gerenciamento de cliente e assim por diante. Portanto, o Security Advisor realmente seguiria as etapas necessárias para fazer isso. Em uma demonstração, podemos dar uma olhada em como funciona. E então você entenderá um pouco melhor em comparação com apenas passar pelos slides.

Só para recapitular. Estes dois novamente são um serviço exclusivo. As zonas de segurança configuram um local no qual você não pode desabilitar a segurança. O Security Advisor unifica o Security Zone, o Cloud Guard ou outros recursos de segurança em um todo coeso. Espero que você ache esta lição útil. Obrigado por assistir.

### Demo: Security Zone and Security Advisor

Bem-vindo a esta demonstração do Security Zone e do Security Advisor. A Zona de Segurança basicamente configura um local no qual você não pode desabilitar a segurança. A segurança é aplicada no momento da criação do recurso e não pode ser desabilitada em nenhum momento no futuro. Ele vem com seu próprio conjunto de regras predefinidas e vamos dar uma olhada nisso.

O Security Advisor é um serviço que unifica zonas de segurança, Cloud Guard e outros serviços de segurança em um todo coeso. É realmente uma combinação de serviços. Serviço que pega a funcionalidade fornecida por esses vários serviços como Cloud Guard e Security Zone, bem como outros serviços do portfólio de segurança e os reúne. Vamos dar uma olhada nisso também.

Então, para começar, clique no menu de navegação do serviço aqui. Clique em Identidade e Segurança. E a primeira coisa que vamos fazer é criar uma zona de segurança. Então clique na Zona de Segurança aqui e precisamos dar um nome a ela. Então, diremos que é Max Security Zone e há uma descrição que você pode fornecer aqui.

E vou criar isso no compartimento raiz. Estou usando essa conta específica. Então eu vou criar a zona de segurança. E como você pode ver, como eu criei a zona, eu tenho algumas outras zonas de segurança em execução também, ela vem com sua própria receita. E quais são essas receitas? Essas receitas são basicamente políticas que ditam certo tipo de postura de segurança.

Assim diz, por exemplo, você não pode ter um volume de bloco sem usar chaves do serviço de cofre e assim por diante. E se você rolar para baixo aqui, poderá ver que existem políticas no banco de dados, existem políticas em volumes de blocos, existem políticas em buckets de armazenamento de objetos e instâncias de computação e rede e assim por diante.

Como você pode ver aqui, há uma política que diz que não podemos criar buckets públicos. E há uma política que também diz que não podemos criar buckets sem usar as chaves do cofre, como acabamos de ver com o volume do bloco. Então, essas são algumas das receitas que são fornecidas pela Oracle e, com o tempo, haverá coisas como receitas personalizadas. Mas agora, estas são as receitas que são fornecidas pela Oracle.

E você pode ver aqui, essas são as duas políticas que vamos testar. Você não pode criar buckets sem atribuir chaves de cofre e não pode ter buckets públicos. Então, essas são todas as operações de negação aqui. Direito. Então vamos passar por isso muito rapidamente. Vá para Storage primeiro e vamos tentar criar um bucket. Então eu venho aqui no depósito. Eu vou dizer, eu quero criar um bucket. E, na verdade, a primeira coisa que precisamos fazer é escolher o compartimento certo. Então vamos para as zonas de segurança máxima. Porque outros compartimentos devem ser capazes de criar, por exemplo, um balde público, mas não nesta zona por causa das receitas que acabamos de ver.

Então eu vou clicar em Criar Bucket. Nome está bem. Todas as opções padrão aqui estão OK. Como você pode ver, estamos usando chaves gerenciadas da Oracle para criptografia de dados em repouso. E quando clico em Criar aqui, deve dar erro, pois neste compartimento não tenho permissão para ter esse tipo de criptografia, onde as chaves são gerenciadas pelo Oracle.

Eu tenho que usar as chaves que são gerenciadas pelo cliente. Então, clico em Criar aqui e diz que criptografe o bucket com uma chave de criptografia de gerenciamento do cliente ou use o fluxo de trabalho a seguir para criar uma nova chave e um bucket. Por isso, dá-me uma recomendação sobre como proceder. E diz, crie um bucket seguro aqui.

Então, se você clicar neste Create Secure Bucket, ele agora basicamente abre o Security Advisor. E o Security Advisor, como discutimos anteriormente, reúne essas coisas de zonas de segurança e um Cloud Guard e outros serviços. Portanto, o primeiro passo é escrever algumas políticas para que isso funcione e as três primeiras políticas estão basicamente dando permissões para gerenciar objetos, famílias, cofre e chaves. Temos essas permissões porque esse usuário específico tem a capacidade de gerenciar todos os recursos nesse compartimento específico, a zona de segurança máxima.

Mas ele não tem essas políticas, pelo menos a última política aqui. Então deixe-me copiar isso rapidamente e criar uma nova política com isso. Então, voltarei para Identidade e Segurança, voltarei para Políticas e criarei uma política aqui.

Chame isso de política de zona de segurança. E eu vou fazer um manual e diz, permitir armazenamento de objetos de serviço e o nome da região é que estamos na região de San Jose. Acredito que esta seja a região certa para usar chaves no compartimento e o nome do compartimento aqui é zona de segurança de segurança máxima. Eu acredito que esta é a afirmação correta, mas se não for, isso me dará um erro.

Então vamos tentar isso. Tudo bem. Assim passou. Então parece que isso funcionou e eu deveria ser capaz de correr a partir daqui. Então, deixe-me voltar ao fluxo de trabalho e tentar criar um bucket público novamente. Max Security Zone, vou criar um bucket ou tentar criar um bucket com chaves Oracle. E vai me dar um erro. Crie um bucket seguro. E seguiremos esse fluxo de trabalho.

Então, no próximo ano, ele diz que não há cofre disponível neste compartimento articular. Então vamos criar um novo cofre aqui. Portanto, forneça um nome para o cofre e diríamos que é um cofre na Max Security Zone. E estou bem com o cofre definido por software. Eu não quero o cofre HSM porque é mais caro. Então eu não quero torná-lo uma parte virtual privada.

E você pode ler mais sobre os preços. O cofre que é gerenciado por software é realmente gratuito. Então, vou usar isso, clique em Avançar. E preciso fornecer um nome para uma chave, então direi que esta é minha chave mestra para Max Security Zone. E estou feliz com a forma da chave, etc., então clicarei em Avançar. E agora ele me pede o nome do bucket e diz que cria neste compartimento.

Eu posso escolher a camada de armazenamento e posso escolher algumas outras opções, como controle de versão de objeto e tudo mais. Estou feliz com essas escolhas. Então, clicarei em Criar bucket seguro e isso levará alguns minutos. E à medida que o fluxo de trabalho for concluído, você verá que teríamos criado um bucket de armazenamento no qual não estamos usando chaves gerenciadas da Oracle para criptografia de dados em repouso. Estamos usando chaves gerenciadas pelo cliente porque essa é a receita que essa zona de segurança específica impõe.

Deixe-me pausar o vídeo aqui e se o fluxo de trabalho terminar, voltaremos e daremos uma olhada. Tudo bem. Então isso levou alguns minutos. E como você pode ver aqui, o cofre é criado. Criamos uma chave mestra e, em seguida, criamos um bucket. Agora, posso ir ao bucket e ver que o bucket foi criado. Posso ver alguns detalhes. É um bucket privado e sua criptografia é feita pela chave, que acabamos de criar em nosso cofre, portanto, não está usando as chaves gerenciadas do Oracle.

E eu poderia usar este balde. Direito. Depressa, deixe-me mostrar-lhe. Se eu alterar a visibilidade para pública, não me deixaria fazer isso, porque diz que é uma violação da zona de segurança. Os buckets de armazenamento de objetos não podem ser públicos, então acabamos de analisar o armazenamento de objetos, mas o Security Zone, Security Advisor, como você viu nas políticas, tem políticas para armazenamento de objetos, bancos de dados, rede e computação. E outros serviços também seriam adicionados ao longo do tempo. Espero que esta tenha sido uma demonstração rápida para mostrar como as Zonas de Segurança e o Consultor de Segurança funcionam. Obrigado pelo seu tempo.

### Vulnerability Scanning

Bem-vindo a esta lição sobre verificação de vulnerabilidades, às vezes também chamada de verificação simples. Então, o que é este serviço? Bem, em um nível muito alto, o serviço de verificação de vulnerabilidades verifica rotineiramente os hosts em busca de possíveis vulnerabilidades. Você também ouve esse termo chamado CVE, Vulnerabilidades e exposições comuns. E há um banco de dados que é um CVE - você pode pensar no CVE como um banco de dados conhecido de vulnerabilidades, cada um atribuído a um ID exclusivo.

Portanto, o trabalho do serviço é ir contra nosso banco de dados e verificar regularmente e relatar vulnerabilidades e exposições. Agora, a forma como o serviço funciona, mesmo que não seja mostrado na tela aqui, é você criar essas coisas, que são chamadas de receitas de digitalização. E as receitas de digitalização determinam quais informações examinar e com que frequência examinar. As duas opções disponíveis hoje são diárias ou semanais.

Então, basicamente, você escreve esta receita. Você diz com que frequência examinar esses CVEs, especificando diariamente ou semanalmente. E então, há alguns outros parâmetros importantes que você especifica. Uma delas é a varredura de portas. Assim, quando você especifica essa opção, o serviço verifica as 1.000 portas comuns e vê se alguma das portas foi deixada aberta involuntariamente e esse tipo de coisa. Ele verifica essas portas.

O segundo parâmetro importante que você especifica nas receitas verificadas é chamado de verificação baseada em agente. E o que isso significa é que o serviço verifica os benchmarks padrão publicados pelo Center for Internet Security, também conhecido como CIS. Ele atribui um nível de risco. Se o relatório atender a 20% dos benchmarks, ele atribui uma pontuação. É 40%, atribui uma pontuação, 80%, atribui uma pontuação e assim por diante. E você deve ler isso na documentação.

Então é basicamente isso que o serviço de varredura de vulnerabilidades faz, verifica rotineiramente essas informações, diariamente ou semanalmente, varredura de portas ou varredura baseada em agente. E então gera relatórios e níveis de risco. Ele também informa coisas como pacotes de SO que exigem atualizações e lotes para resolver essas vulnerabilidades. E também fornece detalhes sobre as configurações do sistema operacional que os hackers podem explorar.

Portanto, para recapitular, lembre-se de que a verificação de vulnerabilidades ou o serviço de verificação foram projetados para verificar vulnerabilidades e desvios das práticas recomendadas para instâncias de computação e sistemas operacionais. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Vault
Nesta lição, vamos ver o que é OCI Vault Service. Portanto, o OCI Vault é um serviço gerenciado que permite gerenciar centralmente chaves de criptografia e credenciais secretas. O Vault elimina a necessidade de armazenar chaves e segredos de criptografia em arquivos de configuração ou em código. Então, o que são essas coisas chamadas chaves e segredos?

Uma chave especifica como transformar texto simples em texto cifrado durante a criptografia e como transformar texto cifrado em texto simples durante a descriptografia. Os segredos são credenciais como senhas, certificados, chaves SSH ou tokens de autenticação que você pode usar com os serviços do Oracle Cloud Infrastructure. Portanto, esse serviço específico permite que você gerencie centralmente essas chaves de criptografia e credenciais.

A ideia é que você não precise armazenar isso em arquivos de configuração que estão em código, porque isso pode levar a violações de segurança. Esse é o aspecto de gerenciamento central de chaves e credenciais secretas. Agora, existem dois tipos de modos de proteção para chaves. Um é chamado de software. Um é chamado de módulos de segurança de hardware. Temos módulos de segurança de hardware em OCI que atendem à certificação fips 140-2 security level III. Isso é um bocado.

Esse é um padrão federal para alguns desses módulos HSM. Mas qual é a diferença entre software e esses HSM? A chave mestra de criptografia protegida por um HSM é armazenada em um dispositivo de módulo de segurança de hardware e não pode ser exportada do HSM. Fica dentro do HSM.

Todas as operações criptográficas envolvendo a chave também acontecem no HSM. Enquanto isso, uma chave mestra de criptografia protegida por software é armazenada em um servidor e, portanto, pode ser exportada do servidor para realizar operações criptográficas no cliente em vez de no servidor.

Então, quando digo servidor aqui, basicamente significa o host do seu computador ou o host de armazenamento onde o armazenamento remoto ou o armazenamento de objetos é armazenado. Essa é a grande diferença entre o HSM e o gerenciamento das chaves no HSM versus o gerenciamento das chaves no software. Agora, quais são os diferentes tipos de algoritmos que o Vault suporta? Vamos olhar para eles muito rapidamente. Portanto, o Vault Service oferece suporte aos algoritmos AES, RSA e ECDSA. Qual é a diferença?

AES é um algoritmo simétrico. A mesma chave criptografa e descriptografa dados. RSA é uma criptografia assimétrica, portanto, a chave pública criptografa os dados e a chave privada descriptografa os dados. As chaves ECDSA são usadas na assinatura digital, mas não podem ser usadas para criptografar ou descriptografar dados. Portanto, existem vários casos de uso e vários algoritmos simétricos e assimétricos suportados por esse serviço específico.

As chaves são integradas com outros serviços OCI. Nos próximos slides, veremos isso. Você pode girar suas chaves mestras e dessa forma não precisa fazer um conjunto completo de criptografia novamente. E uma coisa que não está listada no slide aqui é que o serviço é um serviço regional e tem um endpoint de API público que você pode usar.

Agora, vamos examinar alguns dos outros conceitos básicos que envolvem o uso das chaves. Então, em essência, a maneira como o Vault opera é chamada de criptografia de envelope. Pense nisso como uma hierarquia de duas camadas para chaves. A criptografia real acontece com essas chaves chamadas chaves de criptografia de dados. Eles são usados ​​para criptografar os dados do cliente. E as chaves mestras de criptografia realmente criptografam as chaves de dados.

Então você pode ver na imagem aqui, há a chave mestra que é usada para criptografar a chave de dados. E então você vê isso na caixa do meio, onde os dados são criptografados pela chave mestra, mas a criptografia real para armazenamento, digamos, é armazenamento em bloco ou armazenamento de objetos ou armazenamento de arquivos, é realmente feita usando a chave de dados.

Portanto, essa criptografia de duas camadas é chamada de criptografia de envelope. E você pode usar políticas de mensagens instantâneas para autorizar o acesso a chaves mestras. Portanto, nem todos têm acesso a essas chaves, e você também pode fazer logs de auditoria para monitorar todas as atividades relacionadas às chaves. Assim, você protege seu cofre de chaves usando essas coisas, como políticas e logs de auditoria de log. Então, como eu disse, esta é a criptografia do envelope.

Quais são os benefícios? É mais fácil de gerenciar, limita o raio de explosão e o fato de você estar usando chaves mestras, não gera uma recriptografia completa dos dados. Como você pode simplesmente girar a chave mestra, não precisa fazer a criptografia completa aqui. Mas uma coisa a ter em mente é que você tem que ter cuidado.

Se a chave mestra for excluída, não haverá como recuperar os dados. É por isso que excluímos as chaves com um intervalo de sete dias. E você deve fazer backups necessários. A coisa a ter em mente é que o Vault não pode ser excluído imediatamente. Você pode agendar a exclusão configurando um período de espera, como permanecer no slide, de 7 a 30 dias.

O Vault e todas as chaves criadas dentro do Vault são excluídas no final desse período de espera. E todos os dados que foram protegidos por essas chaves não estarão mais acessíveis depois que o Vault for excluído. Lembre-se de que, depois que o Vault for excluído, ele não poderá ser recuperado. Então é por isso que esse período de 7 a 30 dias está lá por design. Agora, vejamos um exemplo o como isso funciona com um serviço OCI.

Então aqui, você tem um cofre de chaves e há uma chave mestra aqui. Você pode escrever políticas para gerenciar quem tem acesso a essas chaves e também pode fazer logs de auditoria para ver quem está usando essas chaves. Agora, vamos ver o processo de criptografia e o processo de descriptografia no contexto do armazenamento de objetos.

Digamos que você tenha um objeto em um bucket de armazenamento de objetos. Você carrega alguns dados de texto simples lá. A primeira coisa que o serviço faz e você deseja criptografá-lo. A criptografia está realmente ativada por padrão. Você pode trazer suas próprias chaves. Se você não fizer isso, nós realmente fazemos a criptografia por padrão. Então, isso mostra como o processo realmente funciona.

Portanto, o serviço de armazenamento de objetos chama o serviço Vault e solicita a geração de uma chave de dados. E o serviço Vault retorna uma chave de dados, assim como a chave de dados criptografada com uma chave mestra. Então é por isso que você vê aquelas duas caixas ali.

E então o armazenamento de objetos pega essas chaves, essa chave de dados e faz a criptografia com a chave de dados de texto simples. E então ele joga fora a chave de dados. Mas no bucket, ele mantém o objeto criptografado no bucket. E também mantém a chave de dados criptografada com ele. Direito. Então você verá por que ele mantém a chave de dados criptografada.

No momento de fazer uma solicitação para descriptografar esses dados, os dados da chave de dados criptografados e a chave de dados criptografada são armazenados como você vê no bucket. Portanto, o armazenamento de objetos agora faz uma solicitação ao Vault e envia essa chave de dados criptografada como parte da solicitação. O Vault examina a chave de dados criptografada. Ele conhece a chave mestra porque está armazenada dentro do Vault. Então, ele remove a outra parte e envia a chave de dados de volta para lembrar.

Essa chave de dados é a que é usada para criptografia e descriptografia. Agora, depois de ter os dados, você pode realmente descriptografar seus dados de texto simples com essa chave de dados. Portanto, isso é um pouco mais avançado para um curso básico. Mas espero que você tenha uma ideia de como o Vault funciona, como essa criptografia de envelope, a criptografia de duas camadas funciona e por que é útil. Porque limita seu raio de explosão e você não precisa fazer criptografia novamente caso gire suas chaves.

Apenas para recapitular, o Vault é um serviço que você pode usar para gerenciar centralmente suas chaves e credenciais secretas. Tem muitos recursos avançados. Acabamos de ver alguns exemplos rápidos de como a criptografia de envelope funciona. Espero que esta lição tenha sido útil. Obrigado por assistir.

### Web Application Firewall

Nesta lição, vamos ver o que são firewalls de aplicativos da web. Bem, você está familiarizado com firewalls. Os firewalls geralmente operam nas camadas 3, 4 e 5. Isso significa que eles podem entender IP, TCP, UDP e sessões. Mas eles não conseguem entender a camada 7. Então, o que acontece é que eles não conseguem entender a camada 7, eles não podem interrogar os pacotes olhando para quais aplicativos exploram esses pacotes podem conter.

Um firewall de aplicativo da Web protege contra ataques complexos da camada 7 ou da camada de aplicativo. Quais são esses tipos de ataques? São coisas como injeções de SQL e explorações de script entre sites. Bem, este é um curso básico. Então vamos mantê-lo em um nível elevado. Mas isso é essencialmente o que é um firewall de aplicativo da web.

Como acabamos de descrever, é um plug-in do lado do servidor do dispositivo ou um filtro que aplica um conjunto de regras ao tráfego HTTP ou HTTPS. Ao interceptar esse tráfego HTTPS ou tráfego HTTP e passá-los por meio de um conjunto de filtros e regras, um firewall de aplicativo da Web é capaz de descobrir e proteger contra fluxos de ataque, como injeções de SQL que atingem um aplicativo da Web.

A resposta típica de um firewall de aplicativo da Web permitirá que a solicitação passe, audite e registre a solicitação ou bloqueie a solicitação respondendo com uma página de erro. Portanto, esses são alguns dos cenários típicos comuns que um firewall de aplicativo da Web fará.

Então, vamos ver alguns dos recursos muito rapidamente. E novamente, sendo um curso fundamental, este é um tópico muito complexo. Portanto, não vamos entrar em todos os detalhes aqui. Mas o serviço OCI WAF suporta mais de 250 conjuntos de regras para proteção contra injeções de SQL, scripts entre sites, injeções de STML, etc.

Existe todo um conjunto de capacidades. Tenho certeza que você já usou a web, então você está familiarizado com CAPTCHA. Portanto, há coisas como desafio de JavaScript, recursos de lista de permissões de desafio de impressão digital do dispositivo de desafio CAPTCHA. Todos eles trabalham em conjunto com o conjunto de regras para detectar e mitigar ainda mais os bots ruins e permitir apenas tráfego legítimo.

Então pense em como podemos prevenir esses bots ruins em primeiro lugar, o WAF é útil lá. Existe esse conceito de controle de acesso do usuário, que pode ser configurado com base em países, endereços IP, URL e outros atributos de solicitação para proibir tráfego arriscado. Por exemplo, ele pode filtrar com base na localização. E aumentou a conscientização, para que possa filtrar com base na quantidade de algo se um determinado endereço IP estiver tentando fazer uma determinada coisa com uma determinada frequência ou acima, o WAF pode bloquear essa atividade.

Portanto, é realmente útil para esses tipos de cenários. E, finalmente, o serviço OCI WAF tem suporte a várias nuvens. Ele funciona para qualquer aplicativo voltado para a Internet em qualquer ambiente, seja OCI, no local ou em implantações de várias nuvens. Para recapitular, esse é o firewall do aplicativo da web. Pense na próxima vez o que realmente ajuda a filtrar o tráfego na camada 7. Isso é firewall de aplicativo da web. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Bastion

Nesta lição, veremos o que são Bastiões. Este é um serviço dentro da OCI, e é um serviço muito útil. Vamos ver o que ele faz.

Portanto, em um nível muito alto, o Bastion é um serviço totalmente gerenciado que você provisiona dentro de sua rede virtual. Ele fornece conectividade RDP ou SSH segura e contínua para suas VMs diretamente. Então, como isso funciona? Como você pode ver na imagem aqui, Bastions são entidades lógicas que fornecem acesso público seguro a recursos de destino na nuvem que você não pode alcançar da Internet.

Portanto, esses recursos podem ser seu banco de dados, como você pode ver na imagem aqui, há um banco de dados e uma instância de computação. Eles estão no que é chamado de sub-rede privada. Então eles podem sempre, usando o gateway NAT, eles podem ir para a internet, e eles podem obter alguns patches. Mas aí você tem que gerenciar esse gateway NAT e tal, mas eles não podem ser acessados ​​diretamente da internet. Assim, o Bastion realmente ajuda você a chegar a essas instâncias.

Bastion, porque eles fazem esse tipo de acesso a instâncias na sub-rede privada, eles precisam estar em uma sub-rede pública. E eles estabeleceram uma infraestrutura de rede necessária para conectar um usuário a um recurso de destino em uma sub-rede privada, como acabamos de descrever. Então isso é ótimo, mas como você faz -- você endureceu o próprio Bastião? Então, porque agora você está indo para essas instâncias privadas, você precisa protegê-las.

Portanto, existem vários mecanismos que você pode fazer. Então, primeiro, dentro do OCI, você tem integração com o serviço de mensagens instantâneas. Isso ajuda -- isso fornece autenticação e autorização. Assim, você pode decidir quem pode acessar o Bastion em primeiro lugar e que tipo de permissões eles têm.

Há também uma camada extra de segurança que, por meio de uma configuração de lista de permissões de blocos CIDR. Esta lista de permissões de bloco CIDR especifica qual endereço IP ou endereços podem se conectar a um Bastion-- conectar a uma sessão hospedada pelo Bastion. Portanto, se o endereço IP de sua máquina local enquanto você está se conectando como cliente não estiver nessa lista de permissões, os campos de comando SSH. Portanto, existem vários mecanismos pelos quais você pode proteger o próprio Bastion para que ele seja protegido e apenas as pessoas com a autenticação correta ou tradicional ou os endereços IP do cliente possam acessar esses Bastions.

Então, como resumimos, o Bastion fornece acesso restrito aos recursos de destino. E elimina a necessidade de criar e manter seus próprios Bastions porque, novamente, isso pode levar a possíveis violações de segurança. Por isso, gerenciamos esse serviço para você. Além disso, está disponível sem qualquer custo.

Então, em poucas palavras, o Bastion Service. Espero que você ache esta lição útil. Obrigado por assistir.

### Security Summary

Vamos resumir o que você aprendeu neste módulo. Analisamos vários serviços de segurança, seja o Web Application Firewall ou o serviço OCI Bastion, ou vários desses serviços que se enquadram no Cloud Security Posture Management.

Então, coisas como o Cloud Guard, que é automático para encontrar um problema e corrigi-lo automaticamente, a correção, as zonas de segurança. Você designa uma parte de sua locação como super segura. Você não pode desligar a segurança. Verificação de vulnerabilidade -- você procura vulnerabilidades e exposições comuns. Ou consultores de segurança que reúnem todos esses serviços. Também analisamos o Vault e alguns dos recursos avançados que o Vault oferece.

E o que acabamos de abordar é uma fração dos serviços de segurança que temos na OCI. A segurança é muitas vezes um tema muito temido. Felizmente, esta lição tirou um pouco disso. Você não precisa se preocupar com vários serviços de segurança disponíveis no OCI. Obrigado por assistir. Espero que você tenha achado este módulo útil.

### Exercicios

1. Sua equipe de TI criou um site de marketing baseado na Web que precisa ser protegido contra ameaças da Internet, incluindo Cross-Site Scripting (XSS) e SQL Injection.

Qual serviço de segurança OCI eles devem usar?

- [] Cofre
- [x] Firewall de aplicativo da Web
- [] Verificação de vulnerabilidade
- [] Bastião

2. Você deseja gerenciar centralmente as chaves de criptografia e as credenciais secretas que protegem seus dados.
O que você deve usar para conseguir isso?

- [] Guarda Nuvem
- [] Carteira de criptografia
- [x] Cofre
- [] Dados Seguros

3. Qual afirmação é verdadeira sobre as Zonas de Segurança?

- [x] Eles estão associados a um compartimento.
- [] Os recursos existentes não podem ser movidos para uma zona de segurança.
- [] Os dados em uma zona de segurança podem ser copiados para outro compartimento padrão.
- [] Eles estão associados a um domínio de disponibilidade.

4. Você deseja adicionar outra etapa de verificação do usuário junto com a autenticação de senha.
O que você deve usar para conseguir isso?

- [] Provedor de identidade
- [] Federação de identidade
- [] Gerenciamento de identidade e acesso
- [x] Autenticação multifator

5. Qual algoritmo de criptografia de chave NÃO é suportado pelo serviço OCI Vault?

- [] Algoritmo de assinatura digital de curva elíptica (ECDSA)
- [x] Algoritmo da Web JSON (JWA)
- [] Rivest-Shamir-Adleman (RSA)
- [] Padrão de criptografia avançada (AES)


## 10- APP Dev

### App Dev Introduction

Bem-vindo a este módulo sobre desenvolvimento de aplicativos. Vamos começar com uma introdução. Então, no passado, todos costumavam criar aplicativos monolíticos. Pense em aplicativos monolíticos como aplicativos em que todas as camadas estão fortemente agrupadas.

Então você tem uma camada frontal, uma camada intermediária e uma camada de back-end. Estão todos agrupados. A desvantagem neste modelo é que os componentes parecem juntos, escalam juntos e também são construídos juntos. Portanto, mesmo que um componente falhe, todo o aplicativo pode falhar.

Agora, há uma tendência mais recente para a arquitetura de microsserviços, como você vê na tela. Aqui, cada microsserviço ou microsserviço possui uma tarefa simples e se comunica com o cliente ou com outros microsserviços usando mecanismos de comunicação leves, como as chamadas da API REST. A vantagem aqui é que as camadas podem ser dimensionadas de forma independente, desacopladas e construídas apenas para os recursos -- somente quando os recursos são consumidos. Portanto, a outra vantagem é porque as camadas são desacopladas, o aplicativo ainda pode estar altamente disponível mesmo quando uma parte do aplicativo está indisponível ou algumas partes dos microsserviços dentro dessas camadas estão indisponíveis. Portanto, tem muitos grandes benefícios e é por isso que há uma forte adoção de microsserviços e até arquiteturas orientadas.

Mas o que é comum em -- o que é um conjunto comum de considerações são os principais critérios para os desenvolvedores quando eles procuram adotar microsserviços. Existem muitos deles. Vou apenas listar os três primeiros ou os três mais comuns.

O primeiro critério-chave é Infraestrutura como Código. Aqui, você trata seus recursos de infraestrutura como código. As vantagens que você pode tratá-los como código, você pode gerenciá-los de versão e você pode compartilhar recursos entre as equipes. Você pode colaborar melhor nesses recursos.

O segundo critério-chave é adotar implantações baseadas em contêiner. Principalmente porque eles são portáteis e você escreve uma vez, você pode implantar em qualquer lugar. Ele também ajuda você na adoção do DevOps.

O terceiro critério-chave é fornecer acesso a esses microsserviços. Quando você cria esses microsserviços, às vezes eles não têm uma interface web. Então, como um microsserviço vai se comunicar com o outro? Tem que ser decidido.

E você também precisa aplicar políticas de segurança. Portanto, você precisa de algum tipo de mecanismo de gateway para que esses microsserviços se comuniquem. E tenho certeza de que há muitos, muitos outros critérios, mas esses são alguns dos mais comuns que ouvimos o tempo todo.

Agora, quais são alguns dos principais serviços de desenvolvimento de aplicativos OCI que estão disponíveis hoje? Então, a primeira coisa é que temos uma oferta gerenciada do Terraform chamada gerenciador de recursos. Temos funções de chamada de oferta sem servidor.

Temos uma oferta gerenciada do Kubernetes chamada de mecanismo de contêiner ou também chamada de OKE. Junto com isso, também temos um registro gerenciado chamado registro de contêiner. E, finalmente, temos um gateway de API.

Portanto, esses são os principais serviços de desenvolvedor da OCI. E há muito mais recursos ou muito mais serviços. Mas nas próximas lições, abordaremos cada um deles com mais detalhes.

Então, apenas para encerrar, há essa grande tendência para microsserviços e arquitetura orientada a eventos. E a OCI como plataforma de nuvem fornece esses recursos para ajudá-lo a escrever microsserviços e adotar arquiteturas orientadas a eventos. Espero que você ache esta lição útil. Obrigado por assistir.

### Resource Manager

Bem-vindo a esta lição sobre o OCI Resource Manager. Vejamos o que é OCI Resource Manager, também conhecido como ORM. O Oracle Resource Manager automatiza o processo de provisionamento de seus recursos OCI. Ele ajuda a instalar, configurar e gerenciar recursos por meio da infraestrutura como modelo de código.

Pense no Resource Manager como um serviço gerenciado do Terraform. Para pessoas que não estão familiarizadas com o Terraform, o Terraform é infraestrutura como código. A ideia é que você pegue seus componentes de infraestrutura e os descreva usando uma sintaxe de configuração de alto nível. Isso permite que um blueprint de sua infraestrutura seja versionado e tratado como código.

Além disso, a infraestrutura pode ser compartilhada e reutilizada. Você pode configurar e destruir pilhas. E isso é muito importante porque quando você cria pilhas manualmente por meio do console, é muito difícil voltar e descobrir todas as dependências e configurar algo e destruir essa configuração. Portanto, o Resource Manager ajuda você a evitar esse cenário.

Quais são alguns dos benefícios? Melhora a colaboração da equipe, permite a automação como falamos porque agora sua configuração pode ser tratada como código e pode ser automatizada. É perfeitamente integrado a outros serviços OCI. Por exemplo, se você criar um cluster Kubernetes, poderá criá-lo no console OCI. E você pode salvar isso como uma pilha do Terraform. E mais tarde, você poderia aplicar essa pilha.

Assim, você nem precisa começar do zero. O console permite que você faça isso para muitos serviços, uma integração perfeita com a plataforma OCI. E também fornece uma experiência de interface do usuário do console apenas para o Resource Manager, para que você não precise instalar o Terraform em suas máquinas locais e trabalhar com tudo isso.

Agora, como funciona o Gerenciador de Recursos? Como você pode ver aqui, o fluxo de trabalho do Resource Manager é bastante simples. Você carrega um arquivo de configuração do Terraform empacotado, seu código real do Terraform. Você cria uma pilha e, em seguida, executa a ação do Terraform nessa pilha. Portanto, é basicamente um processo de três etapas.

Agora, como você pode ver aqui neste gráfico, sua fonte pode estar em qualquer lugar. Sua fonte pode ser o GitHub. Você pode ter sua versão de código do Terraform lá. Você poderia mantê-lo em uma pasta. Você pode mantê-lo em um bucket de armazenamento de objetos.

Pode ser um modelo que você cria. Pode ser um arquivo zip. Então, essas são as diferentes fontes que você tem para o seu código. Você pode trazer de qualquer lugar. E então o que você cria no Resource Manager é chamado de pilha.

A pilha define um conjunto distinto de recursos do Cloud dentro do compartimento. E um trabalho é o conjunto de comandos do Terraform que podem ser executados em uma pilha. Quais são esses empregos? Esses trabalhos nada mais são do que comandos padrão do Terraform que são planejar, aplicar e destruir.

Depois de executar uma ação do Terraform, o arquivo de estado atualizado do Terraform é gerenciado com segurança pelo Resource Manager e, posteriormente, atualizado para cada ação do Terraform coordenada pelo Resource Manager. Ao gerenciar o arquivo de estado do Terraform para você, o Resource Manager garante uma única fonte de verdade para o estado atual da infraestrutura. Essa é uma das grandes vantagens que o Terraform tem em relação a fazer você mesmo.

Então, em poucas palavras, o Oracle Resource Manager. É um serviço gerenciado do Terraform. E isso realmente ajuda a automatizar suas implantações e compartilhar suas implantações com a equipe mais ampla. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Demo: Resource Manager

Bem-vindo a esta demonstração no OCI Resource Manager. O Resource Manager é um serviço gerenciado do Terraform. Para pessoas que não estão familiarizadas com o Terraform, o Terraform é uma infraestrutura como código. A ideia é que você pegue seus componentes de infraestrutura e os descreva usando uma sintaxe de configuração de alto nível. Então vamos começar.

Então, para abrir o serviço Resource Manager, clique em Developer Services aqui e clique em Resource Manager. E isso deve abrir o painel do serviço OCI Resource Manager. E como você pode ver aqui, o fluxo de trabalho do Resource Manager é direto. Você carrega um arquivo de configuração do Terraform empacotado. E você pode fazer upload de um arquivo ZIP, você pode fazer upload de um modelo e assim por diante. Você pode ir ao Git e obter os arquivos de lá.

E você acaba criando uma pilha -- o que chamamos de pilha no Resource Manager -- e então você executa o Terraform na pilha. Stack não é nada, mas define um conjunto distinto de recursos de nuvem dentro de um compartimento. E um job é um conjunto de comandos do Terraform que podem ser executados em uma pilha. E como você pode imaginar, os comandos do Terraform suportados incluem planejar, aplicar e destruir. E o plano basicamente cria um plano de execução. O comando Apply executa as ações propostas em um plano do Terraform. Tão bem direto.

Então vamos começar. Então eu clico em Stacks aqui. E a primeira coisa que farei é criar uma pilha. Então, neste caso, vou usar um arquivo ZIP. Eu poderia escolher um modelo ou ir a um sistema de controle de origem, ou até mesmo ir a um compartimento. Mas vou escolher um arquivo ZIP aqui e clicar em Procurar. E eu já tenho esse arquivo ZIP específico onde guardei todos os meus arquivos de configuração do Terraform. E eu vou te mostrar isso em um minuto ou assim.

Então mostra isso. Estou feliz com o nome. E eu poderia escolher uma versão do Terraform para usar. Eu poderia usar 1.0, ou neste caso vou usar 0.14. E, em seguida, clique em Avançar.

E então ele está me pedindo algumas variáveis. Qual é o tamanho mínimo de largura de banda? Qual é a largura de banda máxima para o balanceador de carga? Neste exemplo específico, vamos criar um balanceador de carga e colocar algumas instâncias atrás do balanceador de carga. E você verá que usando o Terraform, toda essa noção de infraestrutura como código, o trabalho como desenvolvedor é muito mais fácil porque posso criar essa pilha de uma só vez e depois destruir a pilha se não precisar não mais. Muito mais fácil e automatizado do que fazer tudo manualmente.

Assim, pude escolher a largura de banda mínima e máxima para o balanceador de carga. Bem aqui eu poderia escolher o tamanho da minha máquina virtual. 2.1 é bom. Eu poderia usar meu domínio de disponibilidade. E eu posso colar minhas chaves SSH. Acredito que já tenho minhas chaves SSH. E aqui posso escolher o nome da VCN. Estou feliz com o nome aqui, e o bloco CIDR está bem. O nome da sub-rede está correto. E clicarei em Criar aqui.

E o que isso fará agora é criar uma pilha do Resource Manager. A próxima coisa é executar o plano nele, que é basicamente um plano de execução. E está executando um plano do Terraform como um trabalho. E você veria como está rodando, isso me daria alguns logs aqui, logs parciais. E quando o processo for concluído, ele mudará o status de Em andamento para Bem-sucedido. E me mostraria o plano de execução, que tipo de recursos seriam criados, etc.

E aqui, como você pode ver, os logs começam a aparecer. E se eu rolar para baixo, você pode ver alguns detalhes. Deixe-me rolar para baixo.

Ainda está em processo. E bem aqui, diz Sucesso. E se eu rolar para baixo até o fim, diria que o total de recursos seria criado e a saída seria o IP do balanceador de carga.

Então agora, com este plano de execução, deixe-me seguir em frente e aplicá-lo. Então eu clico em Aplicar aqui, e dá um nome para o trabalho. E eu poderia mudar isso, mas estou feliz com isso. E eu clicarei em Aplicar. E isso levará alguns segundos para executar basicamente as ações que foram propostas no estado do plano Terraform, que vimos anteriormente.

Então, enquanto está chegando, deixe-me -- enquanto os logs estão chegando, deixe-me mostrar rapidamente os arquivos aqui. Então, esses são os arquivos que estavam dentro desse arquivo ZIP que eu carreguei. Como você pode ver, há quatro ou cinco arquivos Terraform aqui -- um para computação, um para balanceador de carga, um para rede e alguns arquivos de saída e variáveis.

Portanto, o arquivo de computação do Terraform está basicamente me mostrando todos os detalhes das instâncias de computação. Então, estamos criando duas instâncias aqui, web01, web02. Você pode ver alguns detalhes como qual é a sua placa de interface de rede, seu domínio de capacidade, etc.

Se eu passar para o arquivo do balanceador de carga, você verá que estou definindo o conjunto de back-end, que tipo de algoritmo usar e assim por diante, e assim por diante -- todos os detalhes aqui. Mesma coisa com VCN. Posso ver o nome da VCN, o bloco CIDR, o nome da sub-rede, o bloco da sub-rede etc.

E o interessante de ver aqui é que, se eu observar a saída, há uma única saída, que é o IP público do meu balanceador de carga. E então, se eu olhar para as variáveis, estas são as variaveis ables que selecionamos quando estávamos instanciando toda esta pilha. Então, coisas como o bloco CIDR da VCN, o domínio de capacidade a ser usado, as formas de instância a serem escolhidas etc. Então, essas foram algumas das coisas que vimos anteriormente.

Então, deixe-me voltar ao meu estado de aplicação e ver se isso é feito aqui. E eu posso ver alguns logs parciais aqui. Vou rolar para baixo. Acho que o estado, ainda diz como Em Andamento. Então deixe-me pausar o vídeo aqui. Pode demorar mais alguns segundos, ou talvez alguns minutos. E quando esse processo estiver concluído, retomarei a demonstração.

Parece que meu trabalho de inscrição acabou e, literalmente, levou menos de um minuto. E eu recebo este IP público aqui. Isto é para o meu balanceador de carga. E se eu pegar esse endereço IP público aqui, colar no meu navegador, posso ver que está fazendo ping no meu primeiro servidor. E então, se eu clicar aqui, está pingando meu segundo servidor. E isso está acontecendo na moda round-robin.

E se eu quiser mostrar rapidamente todos os recursos que foram criados-- então, se eu clicar em Computar, posso ver as duas instâncias que foram criadas, Servidor Web 02 e Servidor Web 01. Se eu voltar para minha rede, você pode ver isso-- volte para Rede, veja em meus balanceadores de carga-- você pode ver que meu balanceador de carga foi criado aqui. E você pode ver todos os detalhes aqui. O status diz OK, a saúde está OK, etc.

Então é assim que é fácil começar com o Resource Manager. A coisa que eu também quero mostrar é que se eu voltar ao Resource Manager, posso destruir toda a pilha. Então é tudo -- você pode ver que os dois servidores web estão funcionando, o balanceador de carga está funcionando. Mas eu posso vir aqui, e posso voltar para minha pilha que acabamos de criar, e então podemos destruir essa pilha.

E essa ideia aqui é que agora sua infraestrutura pode ser considerada como código. Assim, você pode gerenciar a versão, pode colaborar com outras equipes. E então, se você gosta de código, pode fazer alterações. Então você levanta toda essa infraestrutura e pode excluir toda a infraestrutura. Então, isso só o torna muito mais poderoso. Espero que você tenha achado esta demonstração útil.

###  Functions

Bem-vindo a este módulo do Oracle Functions. O Functions é uma oferta sem servidor. Você pode se perguntar, o que é serverless. Vamos olhar para ele.

Então, quando você olha para a jornada em um eixo, se você plotar abstrações e outro eixo, você plota esse controle, e em uma espécie de preocupação decrescente, é uma espécie de jornada onde você começa com uma máquina Bare Metal onde você tem acesso ao máquina completa, então há Máquinas Virtuais onde você pega aquele grande servidor Bare Metal e o divide em segmentos menores que podem ser executados independentemente uns dos outros, então você tem essas VMs.

E então há um movimento em direção ao Container, você pegou todas as VMs eram muito pesadas, levavam muito tempo para inicializar, levavam até a uma baixa utilização de recursos e muitos outros problemas, não eram portáteis, etc. .

Então, pegamos tudo isso e criamos os Containers, onde você tem um tempo de execução do container, os containers compartilham o kernel do SO e têm um isolamento de segurança um pouco mais fraco, mas têm um bom isolamento de recursos em termos de CPU e memória.

Assim, eles podem impulsionar sua utilização geral de recursos e, ao mesmo tempo, são portáteis, para que realmente ajudem na adoção do DevOps. Você escreve uma vez, pode implantar em qualquer lugar, certo, e é por isso que os contêineres se tornaram realmente poderosos.

E depois há essa jornada em direção ao Functions, onde você realmente escreve seu código em um determinado tempo de execução e não se preocupa com servidores, não se preocupa com nenhuma infraestrutura, apenas fornece o código e o provedor de nuvem é responsável por executar esse código.

E uma das maiores vantagens aqui é que ele realmente leva você a um modelo de precificação baseado em consumo, no qual você é cobrado apenas pelo tempo em que sua função está em execução. Assim, você passa da precificação de pagamento conforme o uso para uma precificação totalmente baseada no consumo, e essa é uma das razões pelas quais a adoção do Function está aumentando dia a dia.

Então, vamos ver o Oracle Functions e quais são as principais características desse serviço específico. Então, a primeira coisa é a sua Função como Serviço. Então você escreve o código e o código é executado. Algumas pessoas também gostam de chamá-la de Arquitetura Orientada a Eventos, então algum tipo de evento acontece quando a função é invocada.

Na realidade, as funções são executadas dentro de um contêiner. Você é cobrado apenas pela duração da execução da função e é capaz de execução altamente paralela. Agora, uma coisa que também é relevante no caso da Oracle é que o Oracle Functions é alimentado pelo mecanismo de código aberto Fn Project.

Portanto, ao contrário de alguns dos outros fornecedores de nuvem, esse serviço específico é construído no mecanismo Fn de código aberto, mecanismo de código aberto. E falamos sobre algumas das coisas que você vê no lado direito, é um modelo de precificação verdadeiramente baseado no consumo, o serviço é meio autônomo, é dimensionado, é capaz de execução altamente paralela e é orientado a eventos. Você invoca a função e os quadrantes com base nessa invocação.

Então, como isso realmente funciona na realidade? O processo é realmente simples. Deixe-me guiá-lo através do processo. Em um nível alto, seu código e configuração carregados são empacotados como uma imagem de contêiner e armazenados no Registro OCI. Em seguida, você configura as ações de gatilho. Você pode invocar usando CLI ou API, ou eventos OCI podem acioná-lo. E, em seguida, o Oracle Functions executa o código em resposta ao gatilho ou invocação, que pode invocar qualquer número de outras integrações com outros serviços OCI ou mesmo sistemas externos.

O que o torna realmente interessante é que é um modelo de preços verdadeiramente baseado no consumo. Você paga apenas pelo tempo de execução do código. Da outra vez, quando a função está parada e não é chamada, você não paga nada por isso. E como discuti, o Functions tem invocação, pode ser acionado diretamente ou por meio de algo como eventos OCI e, em seguida, tem integração com outros Serviços OCI.

Agora esta é uma visão muito simplificada. Muitos outros detalhes sobre como o serviço funciona. É muito poderoso, muitos recursos avançados. Dado que é um curso básico, esse tipo de curso ajuda você a entender como o Oracle Functions funciona.

E é isso, sem servidor. Da próxima vez que alguém disser sem servidor, existem servidores, lembre-se, existem servidores, eles estão rodando no data center, mas você não se importa. Você nos dá seu código e o código é executado. Embora seja chamado de serverless, sempre há servidores em execução no data center. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Demo: Functions

Bem vindo de volta. Nesta demonstração específica, veremos o Oracle Functions. O Oracle Functions é uma plataforma de serviço totalmente gerenciada, multilocatário e altamente escalável como uma plataforma de serviço. Para começar, clique no menu de navegação de serviços aqui. Clique em Developer Services e, em Developer Services, clique em Functions. E isso abriria a página inicial do Functions para criar essas funções.

Agora, a primeira coisa que precisamos escolher é o compartimento. Estamos usando o compartimento sandbox. Estamos logados como admin da OCI, o usuário que usamos ao longo deste curso. Então você precisa criar um aplicativo. No Oracle Functions, um aplicativo é um agrupamento lógico de funções. Então vamos dar um nome. Vou chamá-lo de meu primeiro aplicativo.

Você precisa escolher uma VCN, estamos usando essa VCN específica para algumas de nossas outras demonstrações. Então vamos continuar fazendo isso. E vou escolher uma sub-rede pública aqui e é basicamente isso. Criamos um aplicativo. Agora, podemos criar várias funções e essas funções serão todas isoladas, mas podemos agrupá-las neste aplicativo específico.

Agora, existem algumas maneiras de começar. Poderíamos usar o Cloud Shell para fazer essa demonstração básica ou fazer uma configuração local em uma máquina de desenvolvimento local. Já tenho o Cloud Shell em execução aqui. Então deixe-me trazê-lo aqui e você tem que seguir alguns passos para começar.

A primeira coisa que você precisa fazer é definir o contexto, o que já fizemos na etapa anterior. E então você precisa configurar uma região porque estamos na região oeste de San Jose dos EUA. Então nós fizemos isso. Você também precisa definir o contexto para o compartimento. Estamos no compartimento da caixa de areia. Então, só precisamos definir esse contexto.

E então você também precisa definir o contexto em qual repositório de registro usar como parte do registro de contêiner Oracle. Agora, eu já tenho uma configuração de repositório. É chamado de função repo, então deixe-me apenas definir o contexto. Certifique-se de que estamos usando esse repositório específico. Agora, você precisa gerar um token de autenticação, porque esse é o token que usaríamos para fazer login no registro de contêiner.

Então, para fazer isso, deixe-me abrir isso em uma nova guia e gerar o token de autenticação aqui. Ao fazer isso, você precisa copiar isso porque o token de autenticação é mostrado apenas uma vez. Diz que não será exibido novamente. Então deixe-me copiar isso e fechá-lo e colocar isso em um bloco de notas, para não perdê-lo. Tudo bem.

Então nós temos isso. Agora, deixe-me voltar aqui e fazer login no registro de contêiner usando esse token de autenticação específico que acabamos de copiar. Então este é o meu login, está pedindo uma senha, vamos pegar essa senha rapidamente. Cole-o aqui e isso deve nos deixar entrar. Agora, podemos listar todos os nossos aplicativos que são para essa função específica que estamos criando e está listando meu primeiro aplicativo, que acabamos de criar.

Então deixe-me apenas limpar a tela aqui. Portanto, esses são os pré-requisitos que basicamente são configurar a CLI no Cloud Shell e garantir que possamos usar a FN CLI. Agora, as próximas três ou quatro etapas são basicamente criar a função, implantar a função e invocar a função. Então, para fazer isso, vamos apenas fazer uma aplicação básica do helloworld.

Então deixe-me apenas colar este comando aqui. O que isso fará, gerará uma função padrão helloworld e acabou de fazer isso. E vamos apenas cd para esse diretório específico. E se eu quiser mostrar rapidamente o que está nesse diretório específico, o que você vê aqui é um arquivo de definição de função chamado func.yaml. Você vê isso aqui.

Você vê um diretório de origem, que contém os arquivos e diretórios de origem para a função helloworld. Você também vê um arquivo de configuração do Maven chamado pom.xml que especifica a dependência necessária para compilar a função. Então este é apenas um exemplo. Java é uma das várias linguagens suportadas.

Então criamos uma função. Agora, vamos implantar essa função específica. Então, para implantar isso, deixe-me voltar aos comandos aqui. E ele diz que, se você estiver usando o FN CLI detalhado no traço, implantamos e este é o aplicativo que acabamos de criar. Então deixe-me apenas colar este comando aqui.

E o que faria agora é implantar essa função específica. Como está acontecendo, você pode ver que ele fez muito rapidamente. E agora, o próximo passo para nós é invocar esta função. Então deixe-me apenas copiá-lo aqui e invocar a função aqui. E como é um tipo de função helloworld muito simples, então o resultado de retorno aqui seria apenas imprimir uma mensagem helloworld na tela.

Enquanto isso, deixe-me ir rapidamente para a documentação e mostrar como o Oracle Function funciona. Portanto, há boas informações aqui sobre coisas como o que acontece quando você implanta uma função no Oracle Functions. E este gráfico faz um bom trabalho dizendo o que acontece. Quando uma função é invocada pela primeira vez, o Oracle Functions verifica a autenticação de IM, autorização, tudo isso.

E, em seguida, o Oracle Function passa a solicitação para o servidor FN, que usa a definição da função para identificar o docker age ou a função para extrair do registro do docker. É por isso que especificamos o registro do docker que usaríamos ou o registro do contêiner neste caso. E então ele executa a função executando a imagem da função como um contêiner em uma instância na sub-rede que escolhemos.

Lembre-se, escolhemos a VCN e a sub-rede, ela faz isso. E então fala sobre como as funções podem invocar outros serviços. E quando a função termina a execução e supõe que não está sendo chamada, está ociosa, esse contêiner docker é removido. E então se for chamado novamente, ele recebe uma chamada que chama novamente, ele faz a mesma coisa.

E uma coisa a ter em mente, conforme observado aqui, o serviço pode ser dimensionado horizontalmente para atender às solicitações recebidas e se houver mais contêineres que precisam ser iniciados. Portanto, esta é uma boa documentação. Você deve definitivamente dar uma olhada em como as funções funcionam.

Vamos voltar ao nosso console. E como você pode ver aqui -- deixe-me aumentar um pouco, você pode ver aqui que a função é executada corretamente. E esta é a mensagem que imprime. Lembre-se, da última vez, levou alguns segundos. Agora, se você invocá-lo novamente, ele voltará rapidamente. Direito. Porque a primeira invocação demora mais.

Se houver solicitações subsequentes para a mesma função, o Oracle Function direciona essas solicitações para o mesmo contêiner. Na primeira vez, leva mais tempo para executar essa função. Espero que tenha sido uma demonstração rápida e tenha dado uma boa visão geral de como o Oracle Functions funciona. Obrigado pelo seu tempo

### OKE

Bem-vindo a esta lição sobre o Oracle Container Engine. Às vezes também é chamado de OKE, K substitui o Container lá. Antes de entrarmos nos detalhes do serviço, vamos primeiro ver por que os containers se tornaram tão populares, qual é o caso de uso, por que eles estão sendo usados.

Então, se você olhar para o modelo tradicional, se você pensar no kernel do sistema operacional, o kernel é realmente responsável por interagir com o hardware subjacente.

No caso da Máquina Virtual, cada VM tem seu próprio kernel, também chamado de SO dentro da VM. Isso leva a uma menor utilização, porque todas as VMs podem não estar usando o hardware subjacente, o que gera sobrecarga. Essas VMs são grandes. Eles consomem mais espaço em disco. Eles são pesados. Eles são executados em centenas de megabytes ou mesmo gigabytes de tamanho.

Agora, no caso de Containers, o que fazemos é colocar o tempo de execução do container entre o sistema operacional e os containers. E os containers, a ideia é que eles compartilhem o mesmo kernel, então são leves, consomem menos espaço, inicializam mais rápido, pois não há sistema operacional que precise inicializar.

A ideia é que eles compartilhem alguns recursos, tenham algum tipo de isolamento, mas compartilhem os recursos, e empacotam todas as dependências e as bibliotecas dentro do container. Eles podem ser portáteis e podem ser implantados em vários ambientes.

Uma coisa a ter em mente, como eu disse, eles fornecem menos isolamento. Os contêineres de isolamento fornecidos são para a CPU e a memória. Isso não funciona no lado da segurança, então você precisa de tecnologias adicionais como complemento, algo como um Hypervisor ou algum outro tipo de tecnologia de isolamento.

Mas se você estiver bem com isso, os benefícios são muitos. Principalmente, estes são leves e podem ser portáteis. Assim, você escreve uma vez e pode implantar em qualquer lugar. Então, essa é basicamente uma das principais razões pelas quais os contêineres estão se tornando tão populares, porque são muito benéficos para o DevOps.

Uma coisa a ter em mente é que se você estiver usando containers, para torná-los realmente úteis, você precisa de um sistema de orquestração. É aí que algo como o Kubernetes entra em cena. Kubernetes para pessoas que este é um curso básico, pessoas que não estão familiarizadas com ele, é um sistema de código aberto para automatizar a implantação, dimensionamento e gerenciamento de aplicativos em contêiner.

Então, o que é o Oracle Container Engine? E o nome completo é Oracle Container Engine for Kubernetes. É um serviço totalmente gerenciado, escalável e altamente disponível que você pode usar para implantar seus aplicativos em contêiner na nuvem. Então, eu sei que este é um curso básico e não tenho um slide no Kubernetes, mas deixe-me explicar alguns conceitos rápidos aqui.

Porque você vê um nó e um pod, e o pod tem alguns contêineres aqui. Então a ideia básica é um cluster Kubernetes, se você pensar bem, é um grupo de nós. Cada nó pode ser uma máquina física ou uma máquina Bare Metal ou uma Máquina Virtual. Um cluster é composto por nós do plano de controle, normalmente você teria mais de um, talvez três, definitivamente três para alta disponibilidade.

E então você tem o segundo tipo de nós que são chamados de nós de trabalho. Quando um aplicativo em execução em um nó do trabalhador é composto por vários contêineres, como você pode ver aqui, o Kubernetes agrupa os contêineres em uma única unidade lógica chamada pod. Você pode ver alguns pods aqui na tela, cada um deles com alguns contêineres.

Agora, o Kubernetes faz isso para facilitar o gerenciamento e a descoberta. Os contêineres nos pods compartilham o mesmo espaço de nome de rede e o mesmo espaço de armazenamento, e há alguns -- o Kubernetes pode gerenciá-los como uma única unidade.

Vários pods que fornecem a mesma funcionalidade podem ser agrupados em um único conjunto lógico conhecido como serviço. Isso é suficiente apenas para o básico do que é o Kubernetes.

Quais são alguns dos recursos que definem o Oracle Container Engine? Há alguns que eu só quero destacar muito rapidamente. Uma é que você pode dimensionar clusters e pods. Pods que poderíamos dimensionar e sempre - mas o novo recurso, que foi adicionado, é chamado Cluster Autoscaler.

E o Cluster Autoscaler ajusta automaticamente o tamanho de um nó de cluster Kubernetes com base na demanda de carga de trabalho. Portanto, é um recurso importante porque seu padrão de tráfego, sua carga de aplicativo é incerta e, portanto, você não pode simplesmente dimensionar seus pods horizontal e verticalmente. Agora você também pode dimensionar seus clusters.

O Oracle Container Engine também oferece suporte a atualizações automáticas e também faz autocorreção de nós de cluster, portanto, quando detecta uma falha de nó, o Container Engine provisiona automaticamente novos nós de trabalho para manter a disponibilidade do cluster.

Lembre-se também de que não cobramos nenhuma taxa de administração. Portanto, para o Gerenciamento de Cluster, não há taxas envolvidas, embora cuidemos de garantir que o plano de controle esteja altamente disponível em três cópias, etc., não há cobrança por isso. Muitos recursos realmente ricos e estou apenas tocando em alguns deles, porque é suposto ser um curso fundamental.

Em outra lição, veremos o Container Registry. Mas basicamente pense nisso como um repositório onde você pode enviar imagens, extrair imagens e implantá-las no Container Engine. E falaremos mais sobre isso em uma lição subsequente.

Então isso é uma recapitulação, é isso. Os contêineres estão realmente se tornando populares. A maioria dos novos aplicativos, aplicativos modernos estão usando contêineres, e o Oracle Container Engine oferece uma oferta gerenciada de Kubernetes, para que você não precise fazer isso sozinho, não precise gerenciar alta disponibilidade e muitos outros recursos. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### OCIR

Vamos ver o que é registro de contêiner? Também conhecido como OCIR. Portanto, em qualquer aplicativo real, você não apenas precisa criar e empacotar seu aplicativo, mas também distribuí-lo ao redor do mundo. Os desenvolvedores podem enviar sua imagem para um repositório e, em seguida, podem puxar a imagem onde quer que ela esteja, seja em seus próprios data centers ou, neste caso, OCI. E isso, em poucas palavras, é um registro de contêiner.

No caso do registro de contêiner Oracle OCIR é um serviço de registro de contêiner Docker gerenciado e pode ser usado para armazenar, compartilhar e gerenciar imagens de contêiner. Como você pode ver aqui, é fácil armazenar, gerenciar e compartilhar imagens de contêiner usando algo como um OCIR. Assim, você pode enviar imagens aqui e implantá-las no Oracle Cloud.

Agora, existem dois tipos de registros de contêiner disponíveis no OCIR. Você pode usar o registro de contêiner como um registro privado do Docker para uso interno, enviando e extraindo imagens do Docker também e do registro de contêiner usando a interface de linha de comando padrão do Docker. A segunda maneira de usar isso é usar o registro de contêiner como um registro público do Docker, permitindo que qualquer usuário com acesso à Internet e conhecimento da URL apropriada extraia imagens de repositórios públicos no registro de contêiner. E como vimos em outra lição, ele é totalmente integrado ao OKE Oracle Container Engine e aproveita todos os recursos da OCI. E também é totalmente integrado com as funções de uma oferta sem servidor, porque as funções realmente sob o capô são executadas em contêiner.

Então, em poucas palavras, é o registro de contêiner. É realmente o que dá, torna os containers poderosos. Você não apenas pode criar esses contêineres, mas também pode empacotá-los e implantá-los em qualquer lugar do mundo usando esse tipo de registro de contêiner. Espero que você ache isso útil. Obrigado por assistir.

### API Gateway

Bem-vindo a esta lição sobre o API Gateway. Vamos ver o que é um OCI API Gateway. Antes de entrarmos nisso, primeiro o que queremos dizer com uma API? Vamos tentar responder isso.

Bem, se você está trabalhando em qualquer linguagem de programação, você está familiarizado com o conceito de APIs. Mas agora neste curso, estamos falando de APIs da Web, também chamadas de RESTful e REST APIs. Então esse será o foco para esta lição em particular.

Se você já trabalhou com OCI, temos SDKs em diferentes linguagens para interagir com recursos OCI. Mas não estamos falando sobre essas APIs -- estamos falando sobre APIs da web.

Então, o que queremos dizer com APIs RESTful? REST significa Transferência de Estado Representacional. Agora, essas APIs são acessadas por HTTP. Eles são apátridas. Eles se comunicam por fio.

Normalmente é uma comunicação cliente-servidor. Cliente e servidor podem ser escritos em linguagem completamente diferente.

E o principal aqui é que eles usam verbos e recursos SGTP familiares. Então, neste caso, como exemplo, você poderia dizer obter tickets, recuperar uma lista de tickets. Você poderia dizer post tickets, e isso cria um ou mais tickets, então muito familiar muito fácil de entender os verbos SGTP comuns.

Agora, o que acontece nessa arquitetura de microsserviços? Veja que há um movimento para a criação de arquiteturas e microsserviços orientados a eventos.

E como você pode ver na tela do lado esquerdo aqui, você tem esses microsserviços. E você tem vários clientes que estão acessando esses microsserviços.

Agora, um padrão de acesso pode ser os clientes acessando microsserviços por conta própria. Mas isso pode levar à complexidade muito rapidamente. Porque imagine se cada cliente for falar com todos os microsserviços, a complexidade que você precisa gerenciar será enorme.

Então, como resolvemos esse problema? Portanto, temos um padrão em que colocamos um gateway entre o cliente e os microsserviços. Então, neste caso, a comunicação acontece através do gateway. E os clientes apenas invocam o gateway, e o gateway é responsável por conversar com os microsserviços.

Agora, o principal a ter em mente aqui é que quando você define uma API, como está definindo com esses microsserviços, você precisa definir o acesso para essa API. Então você precisa de alguma política para essa API.

E essa política é definida nesse gateway. Ele impõe coisas como autenticação, SLAs, faz alguma mediação e também faz coisas como registro, métricas, monitoramento etc.

Também muito importante-- API Gateway é onde a API é disponibilizada. Portanto, há um terminal no gateway que aplica uma ou mais políticas à solicitação para decidir se essa solicitação deve ir para o serviço de back-end para atender à solicitação.

A API não é executada no gateway. Ele é implementado por sua escolha de tecnologia. O endpoint para acessar essa API está disponível no gateway. Esse é um ponto muito crítico para entender.

A API não é executada no gateway. O endpoint para acessar essa API está disponível no gateway.

Então, na OCI, temos um serviço API Gateway. O API Gateway é um dispositivo conectado à rede, muito parecido com um balanceador de carga. É sem servidor, você o cria e ele se conecta à sua rede.

É totalmente gerenciado pela Oracle. E como eu disse, nós aplicamos a política de segurança. Fazemos monitoramento, registro, métricas. E há algum tipo de mediação que é realizada.

Então, quais são os principais recursos do Oracle Cloud Infrastructure API Gateway? Bem, é um serviço gerenciado, é um serviço regional.

Como eu disse no slide anterior, ele aparece como um dispositivo de rede na VCN do cliente. Existem recursos como autorização e limitação de taxa.

O que a limitação de taxa faz é limitar o número de chamadas de API que você pode fazer para os servidores de back-end. Portanto, não há cenários em que você sobrecarrega o servidor e leva a um ataque DDOS. Então você pode fazer essa limitação de taxa usando o API Gateway.

E há muitos recursos avançados. Você sempre pode criar um gateway privado e um gateway público porque os próprios gateways são criados em uma VCN. Então você pode fazer um gateway em uma sub-rede privada ou em uma sub-rede pública. Você poderia fazer domínio personalizado.

Como falei anteriormente, você poderia fazer o monitoramento, o registro. E tem muita integração com outros serviços, incluindo Oracle Integration Cloud.

E também suporta padrões Open API, Open API 2 e 3. E há muitos recursos, como testes simulados integrados, onde você pode realmente fazer protótipos de seu site de API. Então, antes de colocá-los em produção, você pode fazer isso.

E como você vê no lado direito, ele apenas mostra os vários pontos de integração, se você está invocando-- API Gateway se torna um front-end. É mais ou menos esse padrão -- é chamado de padrão de fachada em que o gateway da API é um front-end para funções. É um front-end para OKE, AutoVM ou pode ser para testes simulados ou de terceiros, outros cenários em que você pode usar gateways de API com serviços OCI, bem como serviços de terceiros.

Então, para recapitular, a coisa mais importante, a principal lição daqui é quando você define uma API, você precisa definir o acesso para essa API. Então você precisa de algum tipo de política para essa API específica. Essa política é definida no API Gateway.

Muito importante lembrar-- A API não é executada no gateway. Ele é implementado por sua escolha de tecnologia. O endpoint para acessar essa API está disponível nesse gateway.

Espero que você tenha achado esta lição útil. Obrigado por assistir.

### App Dev Summary

Vamos resumir o que você aprendeu neste módulo específico. Neste módulo específico, analisamos como os padrões de aplicativos estão mudando de monolíticos, onde todas as camadas estão vinculadas, para essa arquitetura de microsserviços, na qual você pode dimensionar as camadas de forma independente. Você pode pagar por eles com base no modelo de consumo e obter muitos benefícios.

Examinamos todos os serviços disponíveis na OCI para dar suporte a esse tipo de padrão de aplicativo ou arquitetura de aplicativo. Analisamos o gerenciador de recursos, que é uma oferta de terraform gerenciada, por isso realmente ajuda você a seguir a infraestrutura como uma rota de código. Analisamos as funções, que é nossa oferta sem servidor.

Analisamos o mecanismo de contêiner Oracle, que é uma oferta gerenciada do Kubernetes. Permite executar aplicativos em contêiner na OCI. Analisamos o registro de contêiner, que oferece suporte a funções e OKE, e pode ser implantado de maneira privada ou pode ter um registro público.

E, finalmente, analisamos o gateway de API, que fornece esse gateway para que os microsserviços se comuniquem entre si e também se comuniquem com os clientes. Espero que você tenha achado este módulo útil. Obrigado por assistir.


### Exercicios

1. Uma plataforma bancária foi redesenhada para uma arquitetura baseada em microsserviços usando contêineres Docker.

Qual serviço OCI deve ser usado para implantação desses novos microsserviços?

-[] Serviço de eventos
- [x] Oracle Container Engine para Kubernetes
- [] Serviço de streaming
- [] Gateway de API

2. Qual serviço OCI permite executar código sem provisionar nenhuma infraestrutura subjacente, como máquinas virtuais?

- [] Oracle Container Engine para Kubernetes
- []Gateway de API
- [] Gateway de armazenamento
- [x] Funções do Oracle

3. Qual declaração é válida para OCI Container Registry (OCIR)?

- [] Você pode criar apenas repositórios públicos do Docker no OCIR.
- [x] Um único registro pode conter repositórios privados e públicos do Docker.
- [] Um único registro pode conter apenas repositórios privados ou públicos do Docker
- [] Você pode criar apenas repositórios privados do Docker no OCIR.


4. O que não é uma característica do serviço OCI API Gateway?

- [x] Ele fornece uma plataforma de implantação para suas implementações de API.
- [] Ele suporta servidores Oracle e OAuth de terceiros.
- [] É um serviço sem servidor gerenciado pela Oracle.
- [] Ele aparece como um dispositivo de rede em sua rede virtual na nuvem.

5. Qual serviço da OCI aproveita o Terraform para habilitar a infraestrutura como código?

- [] Calcular
- [] Funções do Oracle
- [x] Gerente de Recursos
- [] Eventos



## 11- Observability and Management


### Observability and Management Introduction

Deixe-me falar um pouco mais sobre nossa plataforma de Observabilidade e Gerenciamento. A observabilidade é mais do que um simples monitoramento antigo. Vamos olhar para ele.

Então, a primeira coisa que você vê aqui é o monte de serviços que temos. Temos uma plataforma integrada que combina esses serviços e os faz funcionar perfeitamente. Tudo aqui funciona em nossa plataforma local e em outras nuvens para oferecer essa visão unificada. Portanto, ele suporta a nuvem primária e também suporta outros provedores de nuvem.

Fornecemos uma visão entre camadas de infraestrutura, bancos de dados e aplicativos. Sejam aplicativos nativos da nuvem ou tradicionais, você pode usar essas ferramentas. Portanto, se você está usando as novas tecnologias mais interessantes escritas -- escrevendo coisas em movimento ou operando em Kubernetes ou se você tem um aplicativo WebLogic baseado em Java, nosso conjunto de ferramentas unifica todos esses aplicativos juntos.

E, finalmente, nossas ferramentas são construídas em padrões abertos e são interoperáveis ​​com soluções de terceiros. Nas próximas lições, veremos alguns desses serviços, incluindo os que você vê na parte superior, monitoramento, registro e análise de registro. Deixe-me falar rapidamente sobre os outros serviços porque é um curso básico. Não vamos cobrir tudo aqui.

O Operations Insight e o Database Management concentram-se na utilização e diagnóstico de recursos de banco de dados. O Application Performance Management está focado no desempenho dos aplicativos e fornece a capacidade de diagnosticar problemas rapidamente. Estes, não vamos tocar neste curso em particular. Mas aqueles, monitoramento, registro, análise de registro, vamos nos aprofundar nas próximas lições. Obrigado por assistir.

## Monitoring

Monitoramento. Deixe-me contar um pouco mais sobre isso. O que é monitoramento? O que isso faz? Bem, o monitoramento em um nível muito alto permite que você monitore seus recursos de nuvem. Serviços como computação, banco de dados e muitos outros serviços emitem continuamente métricas para monitorar o serviço, o que chamamos de monitoramento ativo.

E então você tem um recurso chamado Alarmes, que usa essas métricas para monitoramento passivo. O alarme tem uma ação de disparo e um método de notificação. Assim, o acionador de alarme é acionado quando uma métrica viola os limites de alarme. Nesse momento, uma notificação é invocada. E como você pode ver aqui, este gráfico tenta lhe dizer isso.

Os recursos estão emitindo métricas, chega a esse serviço de monitoramento, agrega essas matrizes. E se houver um determinado limite que é violado para uma determinada métrica, o alarme é acionado e tem uma integração com o serviço de notificação, então a notificação é enviada. Isso em alto nível é o que o monitoramento faz.

Agora, vamos ver algumas dessas coisas com um pouco mais de detalhes, começando com as métricas. Então, o que a coisa métrica faz? Bem, as medições métricas permitem que você monitore a integridade, a capacidade e o desempenho de seus recursos de nuvem. Por exemplo, você pode monitorar a utilização da CPU e o alcance do disco de suas instâncias de computação. Em seguida, você pode usar esses dados para determinar quando iniciar mais instâncias para lidar com o aumento da carga, solucionar problemas com sua instância ou entender melhor o comportamento do sistema.

Agora, vamos ver como uma consulta de métrica é composta. Então você pode ver aqui, há uma métrica, que é a utilização da CPU, que é o uso da CPU de uma instância. Portanto, há três partes de uma métrica se você observar todos os detalhes. É composto por um namespace, dimensão e metadados.

Namespace é um indicador do recurso, serviço ou aplicativo que emite a métrica. Assim, por exemplo, a métrica de utilização da CPU lista o agente de computação de sublinhado OCI do namespace da métrica em sua origem. Portanto, pense que é uma maneira única de identificar de onde essa métrica está vindo. Direito. Está vindo desse agente de computação, que está sentado nessa instância específica.

Agora, dimensão, pense nisso como um qualificador para filtrar nossos dados de métrica de grupo. Por exemplo, você poderia dizer, dê-me a utilização da CPU para todas as instâncias em execução no domínio de disponibilidade e assim por diante. Direito. Você poderia qualificá-lo ainda mais. E esses metadados são basicamente sobre fornecer informações adicionais para uma métrica.

Assim, por exemplo, a unidade que pode estar em bytes para uma métrica como o alcance de bytes de disco fornece informações adicionais para uma métrica. Então é assim que uma métrica específica é construída. Novamente, este é um curso fundamental, por isso estamos mantendo-o em alto nível. Mas, em geral, você tem uma ideia de quando dizemos métrica, ela é composta de namespace, que é a origem, dimensão, que é um qualificador, e os metadados, que fornecem detalhes adicionais sobre as métricas.

Vejamos os alarmes e como funcionam os alarmes. Portanto, o recurso de alarme notifica você quando as métricas atendem aos acionadores especificados dos alarmes. Portanto, o recurso de alarme do serviço de monitoramento funciona como dissemos anteriormente em conjunto com o serviço de notificação para notificá-lo quando as métricas atendem aos acionadores de alarmes especificados. Então, como você pode ver nesta ilustração em particular, ela descreve o fluxo.

Então você começa com o recurso, que está emitindo dados de métrica para o serviço de monitoramento. E então, se um determinado limite for violado, o alarme será acionado. E quando o alarme é acionado, ele envia uma mensagem de alarme para um tópico configurado. Tópico, é um método de sub de publicação na notificação, que o serviço envia a mensagem em todas as assinaturas de tópicos.

Assim, você pode ver várias dessas assinaturas listadas lá, seja e-mail, seja uma função de chamada sem servidor, ou slack, ou SMS, ou outros enfeites. Então é assim que funciona.

E há três estados diferentes para alarmes. Estado de disparo quando é acionado. Redefinir quando você redefini-lo de volta. Ou se estiver em um estado suspenso. Então isso é, em poucas palavras, o monitoramento. Um nível muito alto, é sobre monitoramento ativo e monitoramento passivo. Monitoramento ativo feito através de métricas. Monitoramento passivo feito através de alarmes. Quando um determinado limite é violado, os alarmes são acionados. E os alarmes têm integração com notificação para notificá-lo de que uma determinada métrica foi violada. Isso tudo em um serviço de monitoramento de alto nível. Obrigado por assistir.

### Demo: Monitoring

Bem vindo de volta. Nesta demonstração em particular, veremos o Serviço de Monitoramento OCI. O OCI Monitoring Service permite que você monitore seus recursos de nuvem. Conforme discutimos na lição teórica, serviços como banco de dados de computação, etc., métricas continuamente para o serviço de monitoramento do que chamamos de monitoramento ativo.

E então o serviço de monitoramento tem um componente chamado alarmes. Podemos usar estes -- que usa essas métricas emitidas pelos serviços para o que chamamos de monitoramento passivo. Portanto, monitoramento ativo e passivo.

Então vamos começar. Para abrir o serviço de monitoramento, clique no menu de navegação do serviço no lado esquerdo, abra observabilidade e gerenciamento. E, novamente, como vimos na lição teórica, temos uma plataforma integrada de observabilidade e gerenciamento muito rica em recursos.

Nesta demonstração em particular, vamos apenas analisar o aspecto de monitoramento e incluir métricas e alarmes. Então deixe-me clicar em Monitoramento. E a primeira coisa que você vê aqui é que está pedindo para escolher o compartimento. Estamos usando o compartimento sandbox para todas as nossas demos, então vamos fazer isso.

E então você pode escolher os namespaces. E pense neles como uma espécie de agentes ou serviços que estão emitindo métricas. Então você vê serviços como armazenamento em bloco, eventos, funções, armazenamento de arquivos, computação, banco de dados autônomo, etc. Escolheremos o agente de computação aqui.

E como você pode ver neste gráfico -- nesses gráficos, na verdade, ele me mostra várias métricas emitidas pelo agente de computação ou capturadas pelo agente de computação. Assim, posso ver coisas como utilização de CPU, utilização de memória, E/S de leitura/gravação de disco, etc., bytes de rede enviados, recebidos etc. Então eu posso ver todos esses valores aqui. E isso mudará dependendo de qual serviço você escolher, isso mudará.

Outra maneira de ver isso é se você quiser realmente explorar o que está acontecendo, criando isso que é chamado de linguagem de consulta métrica. E criando uma linguagem de consulta métrica e você pode escrevê-la manualmente, mas é bastante simples. Então eu faria a mesma coisa. Eu escolho o agente de computação aqui e, em seguida, ele me pede para escolher uma métrica específica. Nesse caso, escolherei a utilização da CPU.

Está demorando um pouco para aparecer. Eu escolheria um intervalo, de 1 a 5 minutos. A maioria dos serviços emite métricas por minuto. E então eu posso escolher uma estatística aqui. Eu vou para max ou min ou contagem. eu diria máx.

E eu também posso fazer dimensões aqui. E pense nas dimensões como basicamente filtros. Então eu poderia filtrar pelo nome do recurso, eu poderia filtrar pelo domínio de disponibilidade, etc. Então eu escolho a utilização da CPU e posso escolher um valor aqui. Eu poderia dizer apenas mostre-me métricas para uma forma específica ou uma instância específica ou todas as instâncias em execução em um domínio de disponibilidade específico, eu poderia fazer tudo isso. Vou deixar assim, e atualizarei este gráfico aqui.

E o que você veria imediatamente é que está me mostrando a utilização da CPU para todas as instâncias que estou executando. Na verdade, agora, estou executando apenas duas instâncias aqui. Se eu quiser alterá-lo, posso alterar e apenas exibir a métrica para uma única instância.

Digamos que eu queira apenas obter a métrica para esta instância específica, que é chamada de monitoramento, eu pude ver a utilização da CPU aqui imediatamente. Se eu quiser ver todas as instâncias em execução nesse domínio de disponibilidade, posso fazer isso. E também posso agregar esses fluxos de métricas.

Então eu poderia atualizar isso, e agora vejo um único conjunto de valores, valores consolidados. Se eu não fizer isso, posso ver valores individuais aqui. Então, fica muito mais fácil olhar para essas métricas e consultá-las e explorá-las usando essa ferramenta específica aqui, que o Metrics Explorer.

Agora, vamos falar rapidamente sobre -- então discutimos a parte de métricas do serviço de monitoramento. Permite falar sobre a parte do alarme. Portanto, a maneira de definir alarmes é que você pode defini-lo aqui, criar um alarme aqui ou criar uma definição de alarme aqui. Realmente não importa. Vou apenas escolher Criar um alarme aqui e vou criar alguns alarmes.

Portanto, o primeiro alarme é um recurso para cima/para baixo. E basicamente o que vou fazer é ver no meu compartimento específico se uma instância específica está inativa. E se a instância estiver inativa, vamos tomar uma ação.

Queremos, digamos, garantir que ele esteja sempre funcionando. Então é por isso que nomeei esse recurso up/down. Eu escolho meu compartimento sandbox. Estamos ficando com agentes de computação, então faremos isso. Utilização da CPU, 1 minuto é bom.

E aqui, eu direi contar. E logo abaixo, eu escolheria um nome de recurso específico. Eu sei que essa instância específica está encerrada porque eu a desliguei manualmente. Mas, na prática, você teria isso rodando em um compartimento. E se algo acontecer nesse compartimento, você escreveria e poderia criar um alarme com base nisso.

E na regra do gatilho, eu diria que se a utilização da CPU estiver inativa por um minuto - o minuto de atraso do gatilho basicamente é o número de minutos que a condição deve ser mantida antes que o alarme esteja em estado de disparo. Portanto, se estiver inativo por um minuto, acionará um alarme.

E depois de criar um alarme, você também precisa vinculá-lo a um mecanismo de notificação. Este é um serviço do Pub/Sub que enviará essa notificação, seja um e-mail, uma página ou qualquer outra coisa, uma mensagem do Slack. Você pode fazer tudo isso usando o serviço Pub/Sub que temos.

Então, vou escolher este tópico, que já criei no tópico sandbox. E eu assinei meu e-mail para ele. Assim, receberei uma notificação por e-mail assim que este alarme for acionado. E eu poderia repetir esta notificação a cada -- se eu disser que repito a cada meia hora ou 60 minutos ou mudar isso ou eu também poderia suprimir essas notificações por um período de tempo. Eu poderia dizer que estou trabalhando nessa questão, então não continue me enviando essas notificações porque estou trabalhando nessa janela. Mas eu amo esses são por enquanto, e vou ver se esse alarme.

E o que você veria é porque essa instância em particular está no estado de desligamento agora, esse alarme agora diz, OK, isso será acionado. Enquanto isso, deixe-me criar outro alarme aqui. E você pode ver a definição de alarme aqui que acabamos de criar.

Então deixe-me criar outro alarme. E isso é basicamente um alarme de instância crítica. E isso eu vou dizer CPU crítica. E o que isso significa é que se a CPU ultrapassar um determinado limite, queremos acionar um alarme.

E assim faremos a mesma coisa que fizemos anteriormente. Escolheremos o agente de computação aqui. Diremos utilização da CPU, 1 minuto está bom. E agora, eu vou dizer que é um máximo.

E eu preciso escolher -- eu poderia fazer isso novamente para todas as instâncias ou, neste caso, vou acionar isso manualmente. Então eu vou escolher esta instância em particular. E vou dizer que se for maior que 40%, acione esse alarme.

Na realidade, na prática, você faria algo como 80% ou mais. Mas apenas para o bem da demonstração, estou dizendo que se ultrapassar 40%, que parece que foi uma vez antes, foi para 100%, acione o alarme. E a mesma coisa aqui, eu escolheria um tópico e criaria esse alarme.

E como você pode ver, este alarme também está em uma orquestra agora, porque tanto este quanto o alarme provavelmente não estão disparando agora. Deixe-me voltar para aquele alarme. E como estávamos fazendo na demonstração anterior, você pode ver imediatamente que esse alarme é acionado. Por quê? Porque esta instância está inativa. Esta instância não está respondendo.

Então, normalmente, o que aconteceria neste caso é que você receberia um e-mail de notificação. Eu vou te mostrar isso em um segundo. Irei à minha instância e deixar-me-ei reiniciá-la, e então você saberá que eu não levantaria para o alarme sobre isso.

Então deixa eu vir aqui. E esta é a instância particular que paramos. Então deixe-me reiniciá-lo. E estou iniciando esta instância.

Então, neste ponto, eu também receberia uma notificação por e-mail. Eu teria recebido uma notificação por e-mail que me informaria que essa instância específica estava inativa. Então, se eu voltar ao status de alarme, leva alguns minutos para mostrar os alarmes de disparo aqui. Mas se eu for para a definição de alarme e chamar esse alarme em particular, vejo que ele foi acionado.

Então, deixe-me mostrar meu e-mail e posso mostrar a notificação por e-mail que eu teria recebido. E como você pode ver aqui, eu recebi esta notificação por e-mail alguns minutos atrás dizendo que-- basicamente indicando que o alarme foi disparado. Dá-me este BLOB aqui e porque estou inscrito neste tópico específico.

E este alarme ainda está em estado de disparo. E você pode ver o estado aqui onde diz disparando. Quando faz a transição para um estado de não disparo, o estado estaria OK e poderia voltar para um estado de não disparo.

Deixe-me voltar ao outro alarme que criamos e dar uma olhada nele. E este alarme está realmente OK agora. Então vamos acionar isso. Você pode ver que a utilização da CPU aumentou um pouco, mas não passou de 40%.

Então, para fazer isso, deixe-me fazer login rapidamente nesta instância específica na qual criamos esse alarme. Então, apenas SSH nesta instância. E então deixe-me executar este utilitário chamado stress. E o stress é um utilitário que gera várias ameaças para que você possa realmente testar sua CPU. Então eu diria gerar 10 ameaças com um tempo limite de 20 segundos.

Então deixe-me apenas pausar o vídeo aqui. Depois que esse utilitário for executado nessa instância, a utilização da CPU ultrapassará 40% e, em seguida, um alarme será acionado e será acionado. E porque atingiria o limite, eu receberia uma notificação por e-mail e deveria poder vir e ver o status do alarme.

Tudo bem, esperamos alguns minutos e executei o utilitário de estresse para realmente estressar essa instância em particular. E como você pode ver aqui, esse alarme específico que chamamos de crítico da CPU foi acionado.

E você pode ver que o tipo, diz OK_TO_FIRING. É a primeira vez que é demitido. E então diz FIRING_TO_OK porque assim que o limite -- você pode ver rig ht aqui, esta janela aqui, a janela de seleção, mostra que quando o limite foi violado, mostrado pela linha vermelha, o alarme foi acionado porque atingiu esse limite.

E depois, assim que a utilização da CPU caiu, caiu abaixo dessa linha vermelha, o estado mudou de volta para OK. Então, primeiro, fomos de OK_TO_FIRING, depois fomos de FIRING_TO_OK. E parece que o utilitário de estresse ainda está sendo executado em segundo plano, então a utilização da CPU foi encerrada novamente. E você pode ver que o alarme é acionado mais uma vez. E você pode ver o estado de luta aqui.

Espero que esta seja uma demonstração rápida de como o monitoramento funciona. Analisamos os dois aspectos principais, tanto a métrica, quanto o Metrics Explorer, que oferece esse tipo de visão sobre quais tipos de métricas estão disponíveis. Você poderia fazer algumas perguntas. E então analisamos os alarmes, como funcionam os alarmes. Criamos alguns alarmes rápidos e vimos isso em ação.

Espero que você tenha achado esta demonstração mais útil. Obrigado pelo seu tempo.

### Demo: Notification and Events

Nesta demonstração, veremos como você pode usar os serviços de notificação e eventos no Oracle Cloud Infrastructure. Então, estou na página inicial aqui no console. Deixe-me ir rapidamente para o serviço de notificações, que está disponível nesta categoria de serviços para desenvolvedores. Ou você pode simplesmente procurar por notificação aqui. E você poderia chegar a ele também.

Então eu clico em notificação. O serviço de notificação basicamente transmite mensagens para componentes distribuídos por meio de um padrão de assinatura publicado, também conhecido como padrão pub-sub. E você vê algumas coisas aqui -- tópico e assinatura. Tópico é um canal de comunicação para envio de mensagens para a assinatura que estão lá no tópico. Cada nome de tópico é exclusivo. Portanto, lembre-se disso - exclusivo em toda a locação, ou seja, sua própria conta.

A assinatura é um ponto final para um tópico. Portanto, quando uma mensagem é publicada em um tópico, o serviço de notificação envia a mensagem para todas as assinaturas de tópicos. Então é bem direto. Deixa eu vir aqui e criar um tópico.

Eu preciso dar um nome aqui. Então eu diria que este é o meu tópico sandbox. E eu vou criar isso no meu compartimento sandbox. E clicarei em Criar aqui.

E uma vez que eu fizer isso, eu preciso criar uma assinatura aqui. E como eu disse, a assinatura é um ponto final para o nosso tópico. E posso escolher vários protocolos aqui -- e-mail, funções OCI, Slack, etc., ou até mesmo SMS.

Aqui, vou usar meu ID de e-mail para essa assinatura específica. E eu clicarei em Criar. E o motivo que diz pendente aqui é que preciso fazer login na minha conta de e-mail e confirmar esta assinatura. Assim que eu fizer isso, minha assinatura será confirmada. E eu teria literalmente criado um modelo de assinatura publicado no OCI que posso usar para mostrar a você o próximo serviço que vou demonstrar, que é chamado de serviço de eventos.

Então aqui estou eu no meu e-mail. E posso ver aqui que me enviou um e-mail dizendo que preciso escolher e assinar este tópico do sandbox, e preciso confirmar a assinatura. Então vou em frente e confirmo. E ao fazer isso, você verá que o status mudará aqui.

Agora, deixe-me voltar rapidamente ao segundo serviço que quero demonstrar, que é o serviço de eventos. E você pode ver aqui que a assinatura está ativa porque acabei de confirmar. Então, se eu for para a categoria de serviços de observabilidade e gerenciamento, posso ver que há um serviço chamado serviço de eventos.

Os eventos basicamente permitem que você crie automação com base nas alterações de estado dos recursos em toda a sua locação. Então, o que acontece em segundo plano é que todos esses serviços OCI emitem eventos, que são mensagens estruturadas que indicam mudanças nos recursos. E esse serviço específico permite capturar esses eventos e criar o que é chamado de regras e ações. A ideia básica é que você pode criar alguma automação e trazer diferentes equipes na mesma página.

Então deixe-me criar uma regra aqui. E pense na regra como um objeto adjacente que você cria para assinar um tipo de evento e acionar uma ação caso esse evento ocorra. Então, o que isso significa? Vamos ver isso rapidamente.

Então, criarei, para computação, eventos no meu compartimento de sandbox. E eu posso colocar uma descrição aqui. E então aqui está pedindo uma condição de regra. E é um evento que eu quero usar. E para o serviço, eu escolheria computar.

E ao fazer isso, você verá que tenho todo um conjunto de eventos que são emitidos pelo serviço de computação. E são coisas como dimensionamento automático, você anexa um volume de inicialização ou volume de bloco, reserva capacidade e assim por diante. Há muitas opções que o serviço oferece aqui.

Então, os que realmente me interessam são quando executo uma instância. Assim começa o lançamento. Quando o lançamento terminar - e isso é literalmente em alguns segundos, mas ainda quero capturar isso. Então deixe-me trazer isso aqui. E quando a instância é excluída porque são aquelas que eu quero capturar e talvez minha equipe de operações - eles precisam dessas informações apenas para garantir que ninguém esteja criando instâncias ou encerrando instâncias que não deveriam estar em primeiro lugar - mas eles não deveria estar fazendo isso em primeiro lugar.

Então agora eu criei tipos de eventos. Os tipos de eventos que estou capturando são iniciar uma instância, quando a execução começa, quando a execução termina, encerrando uma instância, quando ela começa, quando termina. E você pode ver aqui a regra é criada.

E então a segunda parte que eu preciso fazer aqui é criar uma ação. Ações são respostas que você define para suas correspondências de eventos. Então, definimos as correspondências de eventos aqui. Evento é computação, isso é feito para a computação do serviço. E estes são os tipos de eventos.

Agora, posso escolher duas ações diferentes. Pode ser notificações de streaming ou pode acionar uma função, que é nossa oferta sem servidor. Então, para este exemplo, vou escolher a notificação. E já criamos um tópico. E eu vou apenas trazer esse tópico aqui.

E eu crio uma regra. Eu escolho uma ação. Novamente, a ação é basicamente uma resposta que você você define para suas partidas de eventos. E eu clicaria em Criar Regra aqui.

E agora o que aconteceria é que eu criei essa regra como parte do serviço de eventos. Agora, sempre que eu abro uma instância, ela me notifica. Ou se eu cometesse uma instância, ele me notificaria. Então vamos verificar isso bem rápido.

Então eu viria aqui. Eu tenho algumas instâncias em execução. Deixe-me criar rapidamente uma instância. Vou apenas escolher os padrões aqui. Eu não vou usar o SSH nesta instância, então eu realmente não me importo com as chaves SSH.

E deixe-me apenas clicar em Criar. E isso me avisa, dizendo que não tenho um SSH, então você não poderá se conectar a esta instância. E tudo bem porque para esta demonstração, eu só quero mostrar como o serviço de eventos funciona.

E como você pode ver aqui, minha instância está sendo provisionada. E à medida que é provisionado, eu seria notificado sobre o início da execução da instância e o término da execução da instância. E se eu entrar na minha conta de e-mail, posso ver o início da instância de lançamento. Ele me dá todos os detalhes. E então ele me dá uma notificação na instância de lançamento. E leva literalmente alguns segundos no meio, mas eu recebo todas essas informações.

E agora posso operar com essa informação. Eu posso receber uma notificação do Slack, e-mail ou SMS, e posso agir sobre isso. Portanto, toda a ideia é automatizar com base nas mensagens que recebo. Felizmente, esta demonstração rápida mostrou como você pode usar o serviço de notificação e eventos e achou útil.

###  Logging

Vamos falar sobre o serviço de log OCI. O serviço de log é um serviço distribuído nativo da nuvem, totalmente gerenciado e que simplifica a ingestão, o gerenciamento e a análise de logs de toda a sua pilha. O serviço reúne todos os seus logs em uma única visualização, sejam eles provenientes de aplicativos de infraestrutura, auditoria e bancos de dados. Então, está dando a você esse gerenciamento de log centralizado. Você pode usar o poderoso mecanismo de pesquisa de logs para explorar os logs e pode ver um exemplo que é mostrado na tela.

Agora, além dessa visualização de gerenciamento de log centralizado, fornecemos um mecanismo de ações baseado em regras. Assim, você pode converter seus logs em dados de série temporal. Você pode realmente executar alertas em seus logs ou receber notificações ou armazenar esses logs em locais completamente diferentes, sejam soluções de parceiros de terceiros, se puder fazer isso.

O serviço é construído em padrões abertos. Aproveitamos os logs de ingestão padrão fluentes e o serviço é compatível com os padrões CNCF, Cloud Native Computing Foundation, Cloud Events 1.0.

Existem três tipos de logs que estão disponíveis hoje como parte do serviço de log. O primeiro são os logs de auditoria. Estes são logs relacionados a eventos emitidos pelo serviço de Auditoria OCI. O segundo tipo de logs nossos logs de serviço. Eles são emitidos por serviços nativos da OCI, como gateways de API, eventos, armazenamento de objetos, balanceador de carga e logs de fluxo de VCN.

E então o terceiro tipo de logs são os logs personalizados. Esses são os logs que contêm informações de diagnóstico de aplicativos personalizados, outros provedores de nuvem ou até mesmo ambientes locais. Então, em poucas palavras, é o serviço de log que fornece essa visão de gerenciamento de log centralizado e um mecanismo de ações baseado em regras em cima disso. Obrigado por assistir.


### Logging Analytics

Análise de Log. O que é isso? Vamos olhar para ele. O registro é realmente sobre transmitir dados e armazená-los para você, arquivá-los para você. Logging Analytics, pense nisso como uma maneira fácil de se aprofundar no conteúdo desses logs para visualizar o que está acontecendo para que você possa obter insights rapidamente. E também é uma maneira fácil de você agir em um enorme conjunto heterogêneo de diferentes formatos de log.

Então, quais são alguns dos recursos fornecidos pelo serviço aqui na tela? Então, a primeira coisa é que o serviço Logging Analytics fornece enriquecimento de log pronto para uso que revela o significado dos dados de log. Não apenas os dados em si, ele também facilita as perguntas, fornecendo aprendizado de máquina e visualizações otimizados para operações pré-ajustadas, você vê alguns deles listados aqui, que são qualificados em milhares de logs ou até milhões ou dezenas de milhões de entradas de log. Como você pode ver no gráfico, as visualizações avançadas facilitam a obtenção de insights de muitos dados. Então pense em como você navega e entende todos esses dados de máquina, transformando os dados em insights, esse é basicamente o primeiro trabalho do Log Analytics.

O serviço OCI Logging Analytics também reconhece a topologia. O que significa que os logs são colocados automaticamente no contexto da topologia do aplicativo. Essa automação facilita a localização de informações sobre outros componentes relacionados e a ampliação e redução das dependências conforme necessário. Então você pode ver que o gráfico abaixo tem a topologia listada lá e os logs estão alinhados a isso. Por isso, torna a exploração ainda muito mais fácil.

O Logging Analytics também fornece centenas de analisadores de log prontos para uso que oferecem suporte a uma ampla variedade de tecnologias comerciais e de código aberto populares. Os analisadores podem coletar esses logs por meio de vários métodos baseados em API e em agentes. Portanto, ele fornece essa visualização única usando esses diferentes tipos de analisadores de log.

Então, em poucas palavras, é o Logging Analytics. Pense novamente, os logs basicamente fornecem todos esses dados. O Logging Analytics transforma esses dados em insights. Espero que você ache isso útil. Obrigado por assistir.

### Observability and Management Summary

vamos resumir o que você aprendeu neste módulo. Analisamos a observabilidade e a plataforma de gerenciamento. Lembre-se, observabilidade e gerenciamento são muito mais do que apenas o velho monitoramento simples.

Analisamos todos os serviços, como temos uma plataforma integrada. Funciona não apenas para OCI, mas também para locais, também para outros provedores de nuvem, e fornecemos essa visão multicamada de seus dados, seja em execução em aplicativos, seja em execução na camada de aplicativo, seja em uma infraestrutura camada, sua camada de banco de dados. Reunimos tudo isso.

Especificamente, analisamos o monitoramento. Analisamos o registro e analisamos a análise do registro. Espero que você tenha achado este módulo útil. Obrigado por assistir.

### Exercicios

1. Quais afirmações são verdadeiras em relação ao serviço de Log da Oracle Cloud Infrastructure (OCI)?

- [] Ele permite monitorar recursos de nuvem usando métricas e alarmes.
- [] Ele pode indexar, enriquecer e agregar dados de log de aplicativos.
- [x] Ele pode analisar informações de diagnóstico críticas que descrevem o desempenho dos recursos.
- [] Ele permite que você analise recursos de nuvem usando métricas personalizadas

2. Quais tipos de logs NÃO são suportados pelo serviço OCI Logging?

- [] Registros de serviço
- [] Registros personalizados
- [] Registros de auditoria
- [x] Registros de alerta

3. Qual serviço OCI enviará um alerta para alto uso da CPU?

- [] Registro
- [] Análise de registro
- [] Eventos
- [x] Monitoramento

4. Quais serviços NÃO fazem parte dos serviços de Observabilidade e Gestão da OCI?

- [] Análise de registro
- [] Monitoramento
- [x] Registro OCI
- [] Exploração de registro

5. Qual recurso do serviço OCI Monitoring usa métricas para monitoramento e consiste em uma ação de gatilho e um método de notificação?

- [] Gatilhos
- [] Namespace
- [x] Alarmes
- [] Consultas

## 12- Analytics and AI

### Analytics and AI Introduction

Bem-vindo a este módulo sobre Analytics e IA. Embora o módulo diga Analytics e IA, vamos nos concentrar um pouco mais no lado dos dados e no lado da IA. Temos um serviço Manage Analytics, Oracle Analytics Cloud. Não vamos abordar isso neste curso de certificação atual. Mas vamos nos aprofundar nos serviços de dados e IA.

Ou seja, existem quatro serviços, embora estejam sob esse guarda-chuva. Analytics e IA incluem muito mais recursos. Vamos olhar para esses quatro serviços. Quais são esses serviços? Vamos começar com o primeiro serviço que é chamado de Integração de Dados. Este é um serviço de nuvem nativo que ajuda você com extração, carregamento e transformação comuns, o que é comumente referido como ETL.

Tarefas de ETL, como ingestão de dados de diferentes fontes, limpeza desses dados, transformação desses dados, reformulação desses dados e, em seguida, carregá-los com eficiência para fontes de dados de destino. E temos lição sobre este serviço em particular.

O segundo serviço que é realmente interessante é um serviço para executar aplicativos Apache Spark. Ele permite que os desenvolvedores se concentrem em seus aplicativos e fornece um ambiente de tempo de execução fácil para executá-los. O terceiro serviço que temos chama-se Data Catalog. Este é um serviço de gerenciamento de metadados que ajuda os profissionais de dados a descobrir dados e dar suporte a tópicos de governança de dados que são realmente importantes para as empresas.

E, finalmente, temos uma plataforma de ciência de dados. Isso ajuda os cientistas de dados a criar, treinar, implantar e gerenciar rapidamente modelos de aprendizado de máquina. Então é isso. Analytics e IA é um conjunto bastante amplo de serviços que temos neste curso atual. Mantendo-o em um nível muito alto, examinaremos esses quatro serviços na próxima lição. Obrigada.

### Data Integration

Bem-vindo a esta lição sobre integração de dados. Vejamos o que este serviço faz. Como você pode ver em alguns dos gráficos na tela, o Oracle Data Integration é um serviço de ETL gerenciado pela Oracle nativo da nuvem - extração, transformação e carregamento.

Ele fornece uma interface gráfica agradável para projetar fluxos de dados no que você vê é o que você obtém como uma tela, que você pode ver aqui. Essa abordagem sem código permite que usuários de negócios, desenvolvedores de ETL e engenheiros de dados com uma compreensão profunda dos dados desenvolvam seus próprios pipelines de integração de dados sem exigir nenhum conhecimento técnico. E você pode ver algumas dessas fotos na tela aqui.

Então, como o serviço realmente funciona? Bem, a primeira coisa é que você pode ingerir dados de várias fontes, como arquivos ou bancos de dados, suporte para muitos formatos de arquivo de Big Data, como AVRO e Parquet, também é suportado. Você registra essas fontes como ativos de dados. Bem direto. Você pode ver neste gráfico. Grupo de ativos de dados listados na tela. E há muito mais. Você deve sempre ler a documentação.

Em seguida, você projeta os fluxos de integração de dados. Você pode limpar, transformar e processar os dados. Você também pode usar os modelos internos ou construir seus próprios modelos usando o Visual Data Flow Designer. E lembre-se, este é um tipo de abordagem sem código - tudo de arrastar e soltar. Depois de limpar os dados, você pode carregá-los com eficiência em bancos de dados autônomos, MySQL. Ou você pode colocar isso em um Data Lake. Então você pode ver com esse Data Lake mostrado na parte inferior da tela.

Então, isso é basicamente o que a integração de dados faz. É um serviço de ETL gerenciado pela Oracle nativo da nuvem. Nós apenas cobrimos isso em um nível muito alto. Definitivamente, à medida que você se aprofunda, o serviço possui muitos recursos mais avançados. Espero que você tenha achado isso útil. Obrigado por assistir.

###  Data Flow

Nesta lição, vamos ver o serviço OCI Data Flow. O Data Flow é um serviço OCI totalmente gerenciado que permite executar aplicativos Apache Spark em qualquer escala com praticamente nenhuma administração.

Antes de nos aprofundarmos no Data Flow e em alguns de seus conceitos, vamos falar rapidamente sobre o Apache Spark e o que o torna único. O Apache Spark, para quem não conhece, é o mecanismo de análise unificado para processamento de Big Data com módulos integrados para streaming, SQL, aprendizado de máquina e processamento de gráficos. O que torna o Spark Apache Spark realmente único é que ele é a única estrutura de software que combina dados e IA.

Usando o Spark, você pode fazer transformação e análise de dados em larga escala e, em seguida, executar imediatamente aprendizado de máquina e algoritmos de IA nesses dados. E é super útil para criar serviços de IA em larga escala porque a IA é tão boa quanto os dados abaixo dela e o suporte. Portanto, é isso que realmente torna esse tipo de combinação o que torna o Apache Spark único. E é uma das principais razões pelas quais está ganhando tanta popularidade.

Então, vamos dar uma olhada no serviço Data Flow. Como eu disse no início, o serviço OCI Data Flow é um serviço Apache Spark totalmente gerenciado sem servidor em execução no OCI. Você tem praticamente zero sobrecarga administrativa. O Data Flow analisa os dados do OCI Object Storage e do Autonomous Data Warehouse. E também analisa dados de vários sistemas de banco de dados relacionais de terceiros. Você também pode importar e executar aplicativos desenvolvidos no EMR, Databricks e Hadoop como parte deste serviço.

Vejamos alguns dos conceitos porque é muito importante entender o conceito para entender esse serviço específico. Então, o primeiro conceito é em torno do usuário. Portanto, um usuário é um -- um aplicativo Spark usa a API Spark para executar tarefas de processamento de dados distribuídos. Depois que um desenvolvedor cria um aplicativo de fluxo de dados, qualquer pessoa pode reutilizá-lo sem se preocupar com as complexidades de implantá-lo, configurá-lo ou executá-lo. Portanto, esta é a primeira coisa que você faria como usuário, seria criar um aplicativo Apache Spark.

Então você tem o conceito de biblioteca. A biblioteca é o repositório central de aplicativos de fluxo de dados. Qualquer pessoa pode navegar, pesquisar e executar aplicativos publicados na biblioteca.

Depois, há esse conceito de corridas. Toda vez que um aplicativo de fluxo de dados é executado ou executado, uma execução é criada, aspas sem aspas "execução é criada". A execução do fluxo de dados captura a saída, os logs e as estatísticas dos aplicativos que são armazenados de forma automática e segura. Portanto, essas são algumas das tarefas ou alguns dos conceitos com os quais você estaria envolvido como usuário desse serviço específico.

Então temos toda essa camada administrativa. O serviço Data Flow permite que você defina limites de serviço e crie administradores que tenham controle total sobre quais aplicativos podem ser executados e quais execuções podem acontecer, quais execuções podem acontecer. E então, como você pode ver aqui, o Data Flow aproveita o Elastic Compute e o Elastic Storage.

E, como eu disse no início, é uma oferta sem servidor totalmente gerenciada com quase zero de sobrecarga administrativa. Então, o que isso significa é que o Data Flow aloca suas VMs, executa os trabalhos, captura com segurança toda a saída e, em seguida, desliga o cluster quando não está em execução. Portanto, é uma oferta completamente sem servidor.

E o serviço Data Flow, é claro, aproveita o serviço OCI Identity and Access Management para autenticação e autorização. Então esses são alguns dos conceitos. Como você pode ver aqui, alguns deles estão relacionados às tarefas do usuário, criação de aplicativos, bibliotecas e execução desses aplicativos. E algumas delas são tarefas administrativas.

E alguns desses conceitos aqui ou algumas dessas tarefas como Elastic Compute and Storage, o serviço gerencia de forma transparente de forma serverless. Então, aí está, serviço de fluxo de dados totalmente gerenciado em OCI que permite executar aplicativos Apache Spark em qualquer escala com praticamente zero esforços administrativos. Espero que você ache esta lição útil. Obrigado por assistir.

###  Data Catalog

Bem-vindo a esta lição sobre o serviço OCI Data Catalog. Antes de nos aprofundarmos no que o serviço faz, vamos dar uma olhada -- vamos definir algum contexto. Portanto, em uma empresa típica, você tem regras como analista de dados e engenheiro de dados e cientista de dados, e eles geralmente lutam para encontrar e acessar dados para suas necessidades específicas. Ou até mesmo funções como administradores de dados que lutam para construir um vocabulário de negócios em toda a empresa para governança de dados. Todos nós já passamos por esses desafios.

Portanto, o catálogo de dados é um serviço que oferece uma solução de descoberta e governança de dados de autoatendimento para seus dados corporativos. Ele fornece um único ambiente colaborativo para gerenciar metadados técnicos, comerciais e operacionais. Você pode coletar, organizar, localizar, acessar, entender, enriquecer e ativar esses metadados.

Ele também fornece valor agregado para outros serviços OCI, incluindo ferramentas de gerenciamento de dados, análises, ciência de dados e integração de dados. Então, isso é muito para definir o contexto. Vamos ver como o catálogo de dados realmente funciona.

Portanto, é um processo de várias etapas aqui. E vou tentar mantê-lo em um nível muito alto. Primeiro, o que você faz é coletar metadados técnicos de uma ampla variedade de fontes de dados compatíveis. Eles podem acessar usando suas APIs públicas ou privadas. Em seguida, você cria e gerencia um vocabulário corporativo comum com um glossário de negócios. Você cria uma hierarquia de categorias, subcategorias e termos com uma descrição detalhada de rich text.

Em seguida, você enriquece esses metadados coletados com anotações e vincula-se a entidades e atributos de dados. E depois de ter feito isso, você pode pesquisar, navegar ou explorar o catálogo de dados. Você também pode automatizar todo esse processo usando agendamentos. E então você pode integrar os recursos de classe empresarial do seu catálogo de dados com outros aplicativos usando APIs REST e SDKs.

Pense no catálogo de dados como realmente oferecendo a solução de governança e descoberta de dados de autoatendimento para as necessidades da empresa. E gente, é isso. Isso é o Catálogo de Dados para você.

### Data Science

Ciência de dados. Qual é o serviço? Vamos olhar para os detalhes. Bem, a ciência de dados é uma plataforma totalmente gerenciada e sem servidor para que equipes de ciência de dados ou cientistas de dados treinem e gerenciem modelos de aprendizado de máquina usando o Oracle Cloud Infrastructure.

Então, quais são alguns dos principais recursos desse serviço específico? A primeira coisa é que ele fornece um espaço de trabalho colaborativo orientado a projetos. E com isso quero dizer que permite acesso sem servidor de autoatendimento à infraestrutura para cargas de trabalho de ciência de dados.

Ele possui uma rica integração com o restante da pilha OCI, incluindo funções de uma oferta sem servidor, fluxo de dados que é nosso serviço Manage Apache Spark, Autonomous Data Warehouse e armazenamento de objetos. Por exemplo, usando funções do Oracle, você pode criar um endpoint de API REST para seu modelo, enviar essa imagem do Docker para nosso registro de contêiner e executar a função. Esse é apenas um exemplo do que você pode fazer para configurar a integração com o restante da pilha OCI. E então ele suporta open-- tem suporte para as mais recentes ferramentas de código aberto para Python, incluindo JupyterLabs e alguma outra ferramenta no TensorFlow, etc. Então, esses são alguns dos temas-chave deste serviço em particular.

Em um nível muito alto, como funciona o serviço? Ou quais são alguns dos conceitos-chave a ter em mente? Portanto, a primeira coisa a ter em mente ou começar com a ciência de dados é que existem projetos. Esses são espaços de trabalho colaborativos para organizar e documentar esses ativos de ciência de dados, como sessões de notebook e modelos.

Em seguida, temos Sessões de Notebook de ciência de dados. Essas sessões são ambientes de codificação interativos para construção e treinamento de modelos. As Sessões de Notebook vêm com muitos softwares abertos pré-instalados e a Oracle desenvolve pacotes de aprendizado de máquina e ciência de dados.

Depois de ter esses notebooks, então temos modelos. Eles definem uma representação matemática de seus dados e processos de negócios. O catálogo de modelos é um local para armazenar, rastrear, compartilhar e gerenciar modelos.

O último item que quero discutir aqui ou mencionar aqui é o Oracle Accelerated Data Science SDK. Esta é uma biblioteca Python incluída como parte do serviço OCI Data Science. O Accelerated Data Science oferece uma interface de usuário amigável com objetos e métodos que cobrem todas as etapas envolvidas no ciclo de vida dos modelos de aprendizado de máquina, desde a aquisição de dados até a avaliação e interpretação do modelo.

Então pessoal, é isso. A ciência de dados é uma plataforma para cientistas de dados criarem, treinarem e gerenciarem modelos de aprendizado de máquina usando o Oracle Cloud Infrastructure. Espero que você ache esta lição útil. Obrigada.

### Analytics and AI Summary

Vamos resumir o que você aprendeu neste módulo específico.

Analisamos quatro serviços principais como parte de nosso portfólio de Analytics e IA. Analisamos a integração de dados, que é um serviço de ETL gerenciado. Analisamos o catálogo de dados, que ajuda na governança de dados e na descoberta de dados. Analisamos o fluxo de dados, que é nosso serviço Apache Spark gerenciado. E então analisamos a ciência de dados, que é nossa plataforma gerenciada para criar, treinar e executar seus modelos de aprendizado de máquina.

Agora, este é apenas um pequeno subconjunto de todos os serviços, que estão disponíveis em Analytics e AI, mas espero que você tenha achado este módulo útil. Obrigado por assistir.

### Exercicios

1. Seu cliente precisa mover seu processo Extract-Transform-Load (ETL) para o Oracle Cloud Infrastructure (OCI). Eles querem adotar uma abordagem sem código.

Qual serviço OCI você deve recomendar?

- [] Ciência de dados
- [] Catálogo de dados
- [x] Integração de dados
- [] Fluxo de dados

2. Sua organização tem um aplicativo Spark que às vezes consome uma grande quantidade de recursos de computação. Você precisa executar isso no OCI.

Qual serviço OCI pode ser usado para atender a esse requisito?

- [x] Fluxo de dados
- [] Armazenamento de arquivo
- [] Integração de dados
- [] Catálogo de dados

3. Sua organização consome e analisa dados de uma ampla variedade de fontes. Muitos departamentos estão lutando para encontrar fontes de dados confiáveis.

Qual serviço OCI você deve usar para coletar os metadados e fornecer um repositório central?

- [] Armazém de dados autônomo
- [x]Catálogo de dados
- [] Integração de dados
- [] Fluxo de dados

4. Qual é um recurso do serviço OCI Data Catalog?

- [x] Ele fornece um repositório de metadados pesquisáveis.
- [] É uma alternativa ao Autonomous Data Warehouse.
- [] Ele executa trabalhos do Spark em escala.
- [] Possui uma biblioteca acelerada para construir rapidamente modelos de análise.

5. Qual declaração descreve corretamente o SDK de ciência de dados acelerado da OCI?

- [] É uma biblioteca JavaScript que torna as tarefas comuns mais rápidas, fáceis e menos propensas a erros.
- [x] É uma biblioteca Python que torna as tarefas comuns mais rápidas, fáceis e menos propensas a erros.
- [] É uma biblioteca PHP que torna as tarefas comuns mais rápidas, fáceis e menos propensas a erros.
- [] É um custo adicional ao serviço de Data Science.


## 13- Hybrid

### Hybrid Introduction

Bem-vindo a esta lição sobre nuvem híbrida. O que é a Nuvem Híbrida da Oracle? Vamos olhar para ele.

Então, em um nível muito alto, a maneira como pensamos sobre a nuvem híbrida é ao longo dessas duas dimensões -- basicamente, o tamanho da implantação, seja ela pequena ou grande, e o modelo de implantação, seja autônomo ou remotamente vinculado. Vamos falar sobre o que significa remotamente amarrado. Mas, por enquanto, neste slide, concentre-se apenas no papel independente.

Então você pode ter uma pequena implantação, você pode ter uma grande implantação. No lado da implantação grande, você vê Regiões Públicas OCI. Temos muitas regiões no mundo hoje. Quando você estiver assistindo a esta lição, teremos ainda mais regiões.

Agora, existe essa coisa chamada Dedicated Region Cloud@Customer. O que é aquilo? OCI Dedicated Region Cloud@Customer é uma região de nuvem totalmente gerenciada que traz todos os nossos serviços de nuvem para os data centers do cliente em um modelo independente. Então é por isso que você vê isso do lado de Autocontido nessa linha em particular.

Nesse modelo, os clientes obtêm exatamente a mesma arquitetura, fazem exatamente o mesmo modelo de cobrança, têm exatamente o mesmo modelo operacional, segurança e o mesmo conjunto de serviços disponíveis na Nuvem Pública. E temos uma lição sobre Região Dedicada onde vamos mergulhar mais fundo.

Então, vamos dar uma olhada no outro serviço disponível como parte de nossa oferta de nuvem híbrida, e esse é o OCI Exadata Cloud@Customer. Agora, isso está sob esta linha Remotely Tethered. O que isso significa? Bem, em um padrão comum de Nuvem Híbrida, há um rack ou servidor conectado remotamente nas instalações do cliente. E o que quero dizer com remotamente amarrado é o plano de controle ou o gerenciamento de serviço executado na Nuvem Pública para aproveitar os serviços, governança e controle operacional existentes, enquanto o hardware e os dados permanecem no local.

Por exemplo, quando você faz logon no console, devido a essa opção Remotely Tethered, você gerencia seus recursos de nuvem, mas também pode gerenciar seus recursos locais -- neste caso, Exadata Cloud@Customer. E por que você faria isso? Bem, o Exadata Cloud@Customer oferece alto desempenho diretamente ao data center do cliente. Ele tem alguns números impressionantes, como você pode ter capacidade de até 500 terabytes, 12 milhões de IOPS de leitura, largura de banda de 300 Gbps e assim por diante. Você pode ler todas as especificações.

A principal razão pela qual você faria isso seria atender ao requisito de soberania e segurança de dados estritos, retendo todos os dados no local, enquanto muda o gerenciamento operacional para um serviço de nuvem gerenciado por OCI. Então, meio que lhe dá o melhor dos dois mundos.

Então essa é a nossa segunda oferta. Lembre-se, remotamente amarrado - em grande escala. Não é a mesma escala que uma Nuvem Pública, mas escala e desempenho decentes. Você obtém desempenho massivo usando Cloud@Customer.

Agora, a terceira opção que temos é chamada de infraestrutura Roving Edge. E, como você vê aqui, é novamente um modelo independente, mas está próximo da implantação de pequeno porte. Então, o que é a infraestrutura Roving Edge? É um serviço que estende os recursos fundamentais de OCI a um dispositivo robusto.

O que significa-- o principal componente do Oracle Roving Edge é o Roving Edge Device, também conhecido como RED, R-E-D. É um nó de servidor portátil e de alta potência. Os clientes configuram um R-E-D, ou um RED, em seu console OCI, com os mesmos serviços, aplicativos e dados que usam na nuvem. Em seguida, enviamos o dispositivo para o cliente. Os dispositivos são implantados no campo.

Então, digamos que você esteja no campo agrícola ou em um local remoto. Você os implantaria e poderia operá-los com uma conectividade de rede à Internet ou sem uma conectividade de rede. E então você pode levá-los para um site de transferência de vez em quando, e podemos fazer a sincronização de dados. E há muitos detalhes por trás do tamanho do seu nó, o que mais você pode fazer. Então pense nisso como um dispositivo portátil que pega nosso plano de controle, operações de plano de dados, e você pode fazer um certo subconjunto do que você poderia fazer na Nuvem Pública em seu próprio ambiente, seja conectado à Internet ou em um modo completamente desconectado .

Um tópico que não abordamos anteriormente é a solução Oracle Cloud VMware, também conhecida como OCVS. Vamos ver como essa solução se encaixa em nossa história híbrida geral.

Portanto, a VMware é a base da maioria dos data centers corporativos. Até o momento, as empresas optaram por implantar o VMware com controle total no local ou delegar o controle a um provedor de serviços gerenciados ou a um provedor de hospedagem. Então você vê esses dois modelos aqui.

Agora, nos últimos anos, os clientes começaram a implantar suas cargas de trabalho VMware em diferentes nuvens públicas. A vantagem aqui é que as nuvens públicas oferecem benefícios não encontrados em data centers tradicionais, incluindo itens como provisionamento just-in-time, dimensionamento de capacidade elástica e modelos de pagamento por uso. No entanto, a execução do VMware em outras nuvens públicas exige que você abra mão do controle total sobre administração, acesso e atualizações.

A solução Oracle Cloud VMware é a única solução no mercado que fornece um ambiente de nuvem nativo baseado em VMware com controle completo usando ferramentas VMware familiares.

Então, o que exatamente queremos dizer com isso? Se você vir essa foto aqui embaixo, estamos falando sobre o nível de controle -- baixo, alto -- e várias dimensões. Portanto, a primeira coisa que você vê aqui é que a solução Oracle Cloud VMware oferece ao cliente acesso de administrador completo. E então o que isso significa? Bem, os clientes têm controle total sobre quando e se desejam atualizar seus clusters. Portanto, há um controle completo sobre atualização, aplicação de patches e os clientes têm controle total sobre esse ciclo. Em outras nuvens públicas, eles não têm esse controle.

E eles também têm acesso de administrador. Por exemplo, eles possuem credenciais raiz para seu cluster. Eles possuem credenciais e metadados raiz e podem fazer alterações.

Então pense dessa forma. Da mesma forma que os clientes estão acostumados a gerenciar o VMware localmente, eles podem fazer o mesmo na solução Oracle Cloud VMware. E agora, em vez de rodar em seus próprios datacenters, está sendo executado no datacenter do Oracle Cloud. Isso significa que eles podem migrar cargas de trabalho VMware para a nuvem sem precisar modificá-las. Eles podem usar a solução Oracle Cloud VMware para mover ou estender cargas de trabalho baseadas em VMware no local para OCI em todas as regiões, incluindo nossas regiões dedicadas no local sobre as quais falamos anteriormente nesta lição, sem ter que rearquitetar o aplicativo ou reequipar nenhum dos as operações.

Então é isso. Bem, temos uma lição sobre a solução Oracle Cloud VMware. Vamos mergulhar mais fundo nisso mais tarde. Espero que você tenha achado esta lição útil. Obrigado pelo seu tempo.

### Dedicated Regions

Nesta lição, vamos ver o que é Região Dedicada, uma região que é dedicada. O que é aquilo? Vamos olhar para ele.

Bem, em um nível muito alto, a Região Dedicada às vezes também chamada de Região Dedicada Cloud@Customer é uma região de nuvem totalmente gerenciada que traz todos os nossos serviços de nuvem para os data centers do cliente em um modelo independente. O que isso significa? Como você pode ver nesta imagem aqui, você tem um data center, que é o data center de clientes no local.

Colocamos exatamente o mesmo hardware. Colocamos exatamente o mesmo conjunto de software, o plano de controle, o plano de dados, que temos em nossa nuvem pública. Então, de certa forma, pegamos todo o nosso software e hardware de nuvem pública e os colocamos em seus data centers.

Por que faríamos isso? Bem, você faria isso por motivos de soberania de dados. Você faria isso por razões de conformidade. Muitos setores têm regulamentações rígidas, portanto, você deseja manter os dados no local e, portanto, isso oferece o melhor dos dois mundos. Você obtém a escalabilidade operacional, a capacidade de gerenciamento, a segurança da nuvem, a agilidade da nuvem. Ao mesmo tempo, você pode atender aos requisitos regulatórios de conformidade de soberania de dados.

E como você pode ver aqui, é completamente simétrico. Esse é um dos recursos exclusivos do Oracle Cloud. Nenhum outro fornecedor de nuvem tem esse tipo de recurso existente hoje.

Bem, vamos ver como é essa simetria exata. A primeira coisa é que você tem exatamente o mesmo número de serviços, então você tem todos os serviços hoje, além de 80 serviços disponíveis na nuvem pública. Esses mesmos serviços estão disponíveis na Região Dedicada.

Você tem o mesmo modelo operacional. Você tem os mesmos SLAs. Você tem a mesma economia.

Você trabalha neste modelo de pagamento conforme o uso e no mesmo modelo de suporte. Portanto, é exatamente o mesmo conjunto de atividades que você faria na nuvem pública. Você poderia fazer isso no local.

Então essa é a Região Dedicada. É uma região dedicada a você, e você pode ler na web todos os detalhes. É uma capacidade verdadeiramente única que realmente diferenciamos. Você deve ler mais sobre o que todas as coisas estão disponíveis e como funciona a Região Dedicada. Obrigado por assistir.

### Oracle Cloud VMware Solution

Bem-vindo a esta lição sobre a solução Oracle Cloud VMware. Qual é a solução também chamada de OCBS? Vamos olhar para ele. Bem, se você olhar para o VMware, ele tem sido a base da maioria dos data centers corporativos. Até o momento, as empresas optaram por implantar o VMware com controle total sobre os dispositivos ou delegar o controle a um provedor de hospedagem.

Agora, quando esses serviços estão disponíveis na nuvem, eles fornecem benefícios não encontrados em ambientes de infraestrutura tradicionais, incluindo itens como provisionamento just-in-time, capacidade elástica, capacidade de escalar para cima e para baixo e pagar pelo modelo de uso. No entanto, os Serviços de Nuvem tradicionais exigem a renúncia ao controle total sobre administração, acesso e atualizações.

O que é realmente único sobre a solução Oracle Cloud VMware é que oferecemos esses benefícios e, ao mesmo tempo, concedemos aos administradores VMware controle total sobre seu ambiente. Assim, você pode ver a solução aqui, onde estamos executando o VMware no Oracle Cloud Infrastructure sobre configurações de instâncias de computação bare metal. Mas você tem todo o software VMware rodando nele.

Então, coisas como vSAN, todo o software básico, vSphere, vSAN, NSX, tudo que é executado no Oracle Cloud Infrastructure. Mas, ao mesmo tempo, fornecemos acesso total ao controle de administrador, para que você possa atualizar seus clusters. E você não está limitado de forma alguma.

E este slide em particular tenta mostrar isso. Sua experiência é tão semelhante à sua experiência no local. Então, no slide, você tem as instalações de um lado. Você está executando toda a pilha familiar do VMware. E você pode fazer exatamente a mesma coisa no Oracle Cloud Infrastructure sem passar por nenhum tipo de mudança.

Assim, você tem controle administrativo total, pode atualizar seus clusters, fazer login como usuários root e obter todos esses recursos. Isso é importante, porque você pode atualizar e corrigir seus clusters por conta própria. E você não precisa seguir o que o provedor de nuvem está fazendo. Então essa é a diferenciação única.

Você não sente diferença. É apenas que sua infraestrutura subjacente não está no local, agora está sendo executada na nuvem, neste caso, Oracle Cloud Infrastructure. Assim, você pode aproveitar a mesma experiência, ferramentas e processos com os quais está acostumado a executar no local e pode fazer o mesmo na nuvem. Então é isso. Isso é OCVS. Novamente, uma oferta realmente diferenciada onde você pode executar VMware no Oracle Cloud Infrastructure. Obrigada.

### Hybrid Summary

Híbrido-- vamos recapitular o que você aprendeu nesta lição. Analisamos a Oracle Cloud Dedicated Region e como ela é única em termos de oferecer a você o mesmo conjunto de serviços que na nuvem pública. Analisamos o Exadata Cloud@Customer e o enorme desempenho que ele oferece.

Analisamos a solução Oracle Cloud VMware. Ele oferece acesso de administrador completo em execução no Oracle - executando VMware no Oracle Cloud Infrastructure. E, finalmente, analisamos os dispositivos Roving Edge. São dispositivos portáteis que você pode usar de forma totalmente desconectada.

São muitos recursos e serviços. Você pode ler mais sobre esses recursos. Híbrido-- mais uma lição. Olhe para você.

### Exercicios

1. A solução Oracle Cloud VMware usa que tipo de formas de computação?

- [] Exadata
- [x] Bare Metal
- [] Máquina virtual
- [] Autônomo

2. O que NÃO é um recurso de um Oracle Dedicated Region Cloud@Customer?

- [] Região de nuvem independente
- [] Uma VCN pode ter apenas uma sub-rede pública e mais de uma sub-rede privada.
- [x] Alta latência
- [] Modelo de preços de pagamento conforme o uso
- [] SLA de disponibilidade de 99,95%

3. O que NÃO é um caso de uso principal para a Solução Oracle Cloud VMware?

- [] Extensão do centro de dados
- [] Recuperação de desastres
- [] Migração de nuvem
- [x] Cargas de trabalho do Hyper-V

4. Qual NÃO é um cenário desejado para usar o Oracle Dedicated Region Cloud@Customer?

- [] Para oferecer suporte a aplicativos com requisitos rigorosos de privacidade de dados
- [x] Para executar um site de comércio eletrônico acessível ao público com padrão de demanda variável
- [] Para dar suporte a aplicativos com requisitos de latência extremamente baixos
- [] Para dar suporte a aplicativos que têm requisitos de residência de dados locais

5. Qual oferta da Oracle permite que um cliente forneça serviços OCI em seus próprios data centers em um modelo independente, alcançando a mesma arquitetura e faturamento da nuvem pública OCI?

- [x] Região Dedicada OCI
- [] Região privada da OCI
- [] Solução Oracle Cloud VMware
- [] Região do cliente OCI


## 14- Governance and Administration


### Pricing

Bem-vindo a este módulo sobre governança e administração. Como parte deste módulo, a primeira lição que veremos é sobre preços. Agora, o preço é um tema complexo. Muitos preços com muitos provedores de nuvem são complexos. O preço da Oracle é simples. É transparente. E é um preço mais baixo do que nossos concorrentes. Então, vamos ver alguns deles nesta lição em particular.

A primeira coisa é que tipo de modelos de preços nós suportamos? Portanto, definitivamente apoiamos os preços de pagamento conforme o uso, onde você cobra apenas pelos recursos que consome. Não há compromisso inicial. Não há período mínimo de serviço. E o uso é medido. Este é o Pay as you go para a maioria dos recursos.

Mas para alguns recursos, como nossa plataforma sem servidor gerenciada chamada Functions, isso leva você ao próximo nível. Então você tem esse conceito de preço baseado no consumo, onde você é cobrado apenas quando você consome o recurso que é diferente de pagar conforme o uso, porque você tem que pagar pelas VMs, mesmo que você não as esteja usando ou elas possam ser funcionando ocioso.

Por isso, apoiamos o pagamento conforme o uso e os preços baseados no consumo e todos os tipos de modelos intermediários. E então o segundo modelo que apoiamos é chamado de Créditos Universais Anuais. E a ideia aqui é você se comprometer com um pool anual de fundos. Em troca, por causa desse compromisso, você obtém economias significativas. Mas a questão é que você tem que usar esses créditos em 12 meses.

Se você acabar usando mais recursos, pagará por eles conforme o uso. E os descontos aqui variam de acordo com o tamanho e o prazo do negócio. Há também algo chamado Crédito Universal Mensal. E você deve ler mais sobre isso em nosso site.

E a última opção é trazer suas próprias licenças. Isso é para clientes que executam licenças no local se quiserem reutilizá-las na nuvem. Porque você faria isso? Isso reduz seu custo geral e você pode reutilizar essas licenças na nuvem.

Agora vamos analisar os fatores que afetam os preços. O primeiro fator que afeta o preço é o tamanho do recurso. Portanto, recursos maiores vão custar mais. Isso é natural, porque o preço do serviço é baseado no consumo e no tipo de recurso que você usa. Assim, os recursos maiores vão custar-lhe mais.

A transferência de dados é uma grande parte do preço. E falaremos sobre isso no próximo slide. O tipo de recurso escolhido também determina seu preço. Portanto, as máquinas virtuais versus o bare metal têm um preço diferente e o serverless tem um preço diferente. Se você trouxer suas próprias licenças, elas terão um modelo de preços completamente diferente. Portanto, tenha tudo isso em mente.

Uma coisa a ter em mente com a OCI é que temos os mesmos preços em todo o mundo. Portanto, todas as regiões OCI têm o mesmo preço. Isso é muito diferente do modelo tradicional de nuvem típico, onde o preço é muito local. Então você paga um lugar diferente nos EUA. Você paga um local diferente fora dos EUA em diferentes países onde as regiões de nuvem operam.

Vejamos o custo de transferência de dados e por que é tão importante. Bem, a questão é que a transferência de dados pode ser de até um quarto da sua conta ou até mais. E o motivo é que seus aplicativos estão sempre se comunicando, quer estejam se comunicando com os usuários finais ou se comunicando internamente.

Então, para dar um exemplo, se você observar a Região 1 da OCI, temos 2 domínios de disponibilidade. Você tem um aplicativo que pode estar sendo executado em um modo de alta disponibilidade em dois domínios de disponibilidade. Agora, no caso de OCI, você realmente não paga por nenhuma transferência de dados acontecendo entre esses dois ADs, como você pode ver no gráfico aqui. No caso de alguns outros provedores de nuvem, eles cobram pela transferência de dados entre ADs.

De certa forma, isso está penalizando os clientes por alcançar alta disponibilidade, que é um dos objetivos da computação em nuvem. Então não faz muito sentido assim. Também com o Oracle, o tráfego de entrada é gratuito, pois é o padrão do setor. Mas o tráfego de saída é 10 vezes menor do que alguns dos outros provedores de nuvem. E você me ouviu direito. É 10 vezes menor. Não é 10% menor. É quase 10 vezes menor.

Assim, você economiza muito dinheiro, principalmente se tiver aplicativos com alto uso de transferência de dados. Você acaba economizando significativamente usando OCI. E é isso. Queríamos manter um nível muito alto, muito simples - os três modelos de preços que apoiamos.

E então o destaque de nossos preços é que é simples. É transparente. E alguns dos elementos, como a transferência de dados, custam 10 vezes menos. Portanto, é definitivamente muito mais barato do que alguns dos preços tradicionais da nuvem por aí. Obrigado por assistir.

### Cost Management

Bem-vindo a esta lição sobre Gerenciamento de Custos. Vejamos quais ferramentas a OCI fornece para você gerenciar seus custos. Portanto, a primeira opção que você tem são essas coisas chamadas de Orçamentos OCI. Você pode usar orçamentos para acompanhar os custos em sua locação. Depois de criar um orçamento para um compartimento, você pode configurar alertas que o notificarão se um orçamento for excedido ou se os gastos ultrapassarem um determinado valor.

Como você pode ver aqui na tela, temos dois tipos de orçamentos definidos, um para US$ 1.000, outro para US$ 100. E você pode olhar para a previsão e outras coisas e ser notificado se estiver perto de exceder isso ou se o tiver excedido. É uma forma importante de você gerenciar seu custo e ser notificado se o custo ultrapassar sua previsão ou seus planos.

A segunda ferramenta, que está disponível para você, é em torno da análise de custos. E isso, como o nome indica, você pode analisar seu custo depois de gastá-lo, mas é uma boa maneira de analisar seu custo passado e depois fazer alterações para o futuro. Se houver elementos que você deseja alterar, esta é uma ótima maneira de fazer isso.

Há também relatórios de uso. Hoje, atualmente, os relatórios de uso são baixados na forma desses arquivos CSV e são gerados diariamente. E eles mostram dados de uso para cada recurso em sua locação. Os arquivos CSV são armazenados em um bucket de armazenamento de objetos que pode ser acessado por meio de uma política de locação cruzada, para que você possa examinar não apenas sua locação, mas também várias locações se houver várias locações sendo usadas.

Agora, algumas outras ferramentas nessa área incluem limites de serviço, a ferramenta para definir seus limites, cota e uso. Assim como em qualquer nuvem, limitamos quantos recursos você pode executar em uma locação tradicional para evitar coisas como fraude e uso indevido. Mas você sempre pode... para casos legítimos, você sempre pode alterar seus limites para um serviço específico, e há uma maneira de analisar seus limites atuais e alterá-los. E você pode enviar uma solicitação de suporte para fazer isso, mas essa ferramenta fornece rapidamente quais tipos de limites você dividiu por coisas como seu domínio de disponibilidade, para que você possa se aprofundar e obter mais detalhes aqui.

Então, finalmente, como falamos, compartimentos são essas entidades lógicas, que você pode usar para isolar recursos e ter melhor acesso a esses recursos, portanto, se você estiver usando esses compartimentos, poderá configurar cotas de compartimento. E a maneira como funciona é que você tem essas diferentes políticas que você pode escrever, onde você pode definir o número máximo de recursos de nuvem que podem ser usados ​​para um compartimento. Então você poderia dizer que, neste compartimento específico, você só pode usar, digamos, 10 máquinas virtuais. Você pode desdefinir isso e voltar aos limites de serviço padrão ou pode zerá-lo. Então, como exemplo, aqui, você poderia dizer que esse compartimento específico não deve ter nenhum recurso do Exadata. E você pode fazer isso para evitar o uso indevido e também economizar em seu custo.

Recapitulando, esse é o seu gerenciamento de custos - muitas ferramentas disponíveis, incluindo orçamento, relatórios de uso, análise de custos, capacidade de definir cotas, capacidade de aumentar seus limites de serviço e muito mais. Você deve verificar nossa documentação para saber mais sobre todas as maneiras de gerenciar seus custos no OCI. Espero que você tenha achado esta lição útil. Obrigado por assistir.

### Demo: Cloud Advisor and Cost Management

Nesta demonstração, veremos alguns dos recursos de Governança e Administração. Então, para abrir Governança e Administração, você clica no menu Navegação do Serviço e, em seguida, clica em Governança e Administração. E nessa categoria de serviços, você vê vários serviços listados: Gerenciamento de contas, Consultor de nuvem, Governança e Gerenciamento de custos.

Deixe-me começar com o Gerenciamento de Custos. Então, a primeira coisa que quero mostrar é que, antes do início deste curso, criamos um orçamento de US$ 10. E dissemos que, se meu orçamento exceder US$ 10, envie-me uma notificação por e-mail.

E como você pode ver, alguns dias se passaram desde que criamos este orçamento. E agora, você pode ver que meus gastos estão muito além disso, o dobro desse gasto. E isso me dá essa porcentagem, quanto extra eu gastei, e também me dá uma previsão. E também recebi um e-mail quando atingiu 90% desse limite, então sei que, se estiver excedendo o limite, posso ser notificado.

Isso foi acionado. Você pode ver logo no topo, estou executando uma conta de nível gratuito com $ 300 em crédito e os $ 20 que usei - são $ 280 restantes. Então eu quero mostrar isso primeiro.

A segunda coisa é que existe esse recurso de análise de custos, onde você pode baixar, e esses US$ 20-- agora eu poderia dizer, OK, onde gastei esse valor? E como você pode ver aqui, dá-lhe um detalhamento, onde gastamos esse dinheiro?

Então, como você pode ver -- e eu posso escolher esconder alguns deles. Deixe-me apenas recarregar esta página. OK, por algum motivo, não sei por que o gráfico não estava saindo corretamente. Mas, como você pode ver aqui, ele codifica os vários serviços por cores, então posso ver que a maioria dos meus gastos foi com banco de dados. Provavelmente estou executando algumas instâncias, ou uma instância aqui. E posso ver que é o custo do computador e depois o custo de armazenamento.

E isso me dá um detalhamento do número de dias em que estou executando isso, e me dá um custo nisso. Se eu quiser apenas remover alguns desses serviços do gráfico, eu poderia vir aqui e esconder um monte deles, porque eles não estão incorrendo em nenhum custo. Ou eu poderia até tirar aqueles que estão incorrendo em qualquer tipo de custo, apenas para detalhar e ver de onde vem meu custo.

Portanto, este é um bom utilitário. Isso me dá um total, e posso ver essa divisão de US$ 20, como essa divisão aparece. E eu também poderia detalhar. Eu poderia salvar isso como um relatório. Eu poderia filtrá-los por serviços. Eu poderia ir mensalmente. Eu também poderia olhar para o uso, olhar para as previsões. Portanto, há um monte de opções que você pode usar aqui.

O único serviço que quero mostrar rapidamente é o Cloud Advisor. Então vimos o orçamento, que tínhamos colocado. Ultrapassamos esse orçamento. Eu queria saber como o superamos, então fomos para a Análise de Custos. Vimos aquela repartição de $20, de onde veio o custo, todos os serviços.

E agora há também esse utilitário chamado Cloud Advisor. E o que ele faz: fornece recomendações para ajudá-lo a maximizar a economia de custos e melhorar a segurança em sua própria locação. Portanto, são recomendações, e você pode seguir essas recomendações e reduzir seu custo.

Então, principalmente, as duas coisas, que são abordadas aqui - uma é a segurança, a outra é o gerenciamento de custos. Eu irei até a segurança em um minuto. Então eu posso ver aqui que tem uma recomendação para mim. E também mostra aqui que há um pendente, e nada foi implementado. Então, se eu clicar nele, ele me mostra uma lista de recomendações. E o primeiro, que está pendente -- diz habilitar o gerenciamento do ciclo de vida do objeto.

Como você lembra da lição Object Storage, o gerenciamento do ciclo de vida basicamente permite que você escreva essas regras nas quais você pode fazer a transição de objetos de uma classe, classe de armazenamento, para outra. Principalmente você vai fazer isso para reduzir seu custo. Assim, você pode passar de um acesso padrão a um acesso pouco frequente ao seu arquivo ORM após um número predeterminado de dias e, dessa forma, pode aproveitar os níveis de custo mais baixos.

Portanto, ele me diz especificamente que esse bucket específico nesse compartimento específico não possui ferramentas de gerenciamento de ciclo de vida ativadas. E eu posso clicar em Implementar aqui, e eu poderia ir em frente e implementá-lo. Ou eu poderia decidir não fazê-lo, e poderia adiá-lo.

Também tem segurança. Isso me dá uma classificação de postura de segurança. Nesta conta específica, os dados na nuvem não estão habilitados. Então é por isso que eu não tenho isso mostrando. Caso contrário, se estiver ativado, você poderá ver minha classificação de postura de segurança e eu poderia obter algumas recomendações lá.

A última coisa que quero mostrar aqui é... deixe-me voltar. A última coisa que quero mostrar aqui é algo em Governança chamado Tenancy Explorer. E o que isso faz é permitir que você veja que tipo de recursos você está executando. E isso é muito útil, porque com o tempo, várias pessoas usando um compartimento -- você pode ter muitos recursos, que você não sabe se existem ou não. Portanto, eles podem ser volumes de blocos não anexados a instâncias. E você nem sabe se eles existem, porque às vezes é muito difícil conseguir esse inventário.

Assim como você pode ver aqui, ele me mostra tudo que existe neste compartimento em particular. E tenho usado este compartimento para executar várias demos. E eu poderia aprofundar ainda mais. Então, eu poderia dizer, mostre-me os volumes de inicialização, que estão lá, e esses volumes de inicialização estão anexados às instâncias que estamos executando. Ou me mostre todas as instâncias de computação que estamos executando.

Assim, eu poderia mostrar, novamente, as instâncias de computação que estão em execução e, novamente, apenas remover esse volume de inicialização, para que eu possa ver que três instâncias de computação estão em execução. Ou eu poderia - o custo majoritário veio do Autonomous Database. Então deixe-me ver se há uma instância do Autonomous Database em execução. Portanto, esta é uma maneira rápida de pesquisar e descobrir, de relance, que tipo de recursos estão disponíveis.

Se os recursos não aparecerem aqui, como esta caixa de aviso está dizendo, você pode clicar em Pesquisar e pode realmente -- esta é a documentação. Você pode realmente pesquisar aqui. Assim, você pode pesquisar um recurso específico ou também pode usar algo chamado Consulta de recursos avançados. E você pode escrever algumas consultas realmente sofisticadas e pesquisar recursos.

Espero que tenha sido uma demonstração rápida de Governança e Administração. Você viu algumas coisas lá no Gerenciamento de Custos, Cloud Advisor, basicamente dando recomendações sobre custo e segurança, e algumas das coisas que vimos em Governança sobre como você pode ver rapidamente seus recursos sendo executados em sua própria locação.

### Tagging

Bem-vindo a esta lição sobre marcação. A marcação é um recurso muito, muito importante dentro do OCI, e você definitivamente deve aproveitá-lo. Vamos falar mais sobre isso. Então, no fundo, o que é marcação? As tags são basicamente esses pares de valores-chave, que você pode usar para organizar melhor seus recursos.

Então, como você pode ver aqui, nesta instância em particular, eu coloquei duas tags diferentes. Então existe uma tag que é ambiente com valor de produção. E há outra tag que é projeto e tem valor de alfa. E eu poderia fazer várias tags. Você deve sempre verificar os limites de serviço de quantas tags eu poderia colocar em um objeto Cloud específico. Mas neste caso, estou colocando duas tags aqui.

E esses novamente, apenas para recapitular, são pares de valores-chave simples ou pares de valores de nome em que a chave é a chave para a tag e, em seguida, o valor é o valor que você deseja atribuir. Portanto, a ideia aqui é que você execute centenas ou milhares de recursos de nuvem. E como você está criando aplicativos, você está criando essas arquiteturas complexas, você pode marcá-las. E você pode identificar seus aplicativos, seus recursos usando essas tags.

Essa é a primeira razão pela qual você usaria suas tags, porque suas contas e seus recursos -- você usará muitos, muitos recursos. E as tags são um mecanismo muito fácil para organizar melhor seus recursos.

A segunda razão pela qual você usaria tags seria para gerenciamento de custos. Agora imagine todos esses recursos que você está marcando, você pode puxá-los pela etiqueta. E você pode descobrir qual é o custo de uso desses recursos. E essa é uma maneira muito importante de descobrir quanto seu aplicativo está consumindo.

Lembre-se de que a nuvem tem tudo a ver com preços de pagamento conforme o uso. E você pode apontar para um conjunto específico de recursos quanto ao tipo de custo em que está incorrendo. Então, a segunda razão pela qual você usaria tags é o gerenciamento de custos.

Você também pode fazer isso chamado controle de acesso baseado em tags. Assim, você pode controlar o acesso com base nas tags dos recursos, não nos usuários e nos grupos. Então, de certa forma, usando tags, torna-se ainda mais poderosa a capacidade de escrever políticas baseadas em tags. Então esses são alguns dos casos de uso. E há muitos, muitos mais. Mas essas são algumas das razões pelas quais você usaria tags.

Então, como falamos no OCI, existem dois tipos de tag. Há tags de forma livre. E há tags definidas. Então, primeiro vamos olhar para as tags de forma livre. Como você pode ver no gráfico aqui, há uma chave e um valor. Portanto, para essa tag específica, a chave é o ambiente. O valor é a produção. É um pagador de valor-chave muito simples. Não há esquema definido. Ou não há nenhum tipo de restrição de acesso.

Em seguida, definimos tags. E estes têm mais recursos e controle. E a primeira coisa a notar aqui, como você pode ver no gráfico, é que essas tags agora estão contidas em uma coisa chamada namespace. Então você especifica um namespace dizendo que, neste caso, são operações. E então você pode colocar quantas tags quiser nesses namespaces. Então você está definindo um esquema.

E outra coisa que você pode fazer também suporta políticas. Políticas de suporte de tags definidas para permitir que você controle quem pode aplicar suas tags definidas. Portanto, nem todo mundo poderia usar essas tags definidas. Você poderia escrever isso na política. E o namespace da tag é a entidade à qual você aplica essa política. Então você poderia dizer que um administrador de um grupo específico de operações só pode aplicar essa tag específica, porque o namespace tem operações nela. Então você poderia escrever uma política contra isso.

Então, como isso realmente parece na prática? Então, como exemplo aqui, há um namespace que é operações. E dentro disso, estou definindo um par chave-valor. Portanto, a chave é o meio ambiente, e o valor é a produção. E você pode levá-lo para o próximo nível. Então, como você pode ver aqui, as operações são o namespace. Ambiente é a chave. E a produção é o valor.

Agora, como falamos, namespace é um contêiner para um conjunto de tags com definições de chave de tag. As definições de chave de tag especificam a chave como está aqui. E você também pode especificar o tipo de valores permitidos. Você poderia dizer que o tipo é uma string. E permite qualquer valor, ou fica em branco. Ou você pode definir um conjunto específico de valores. E quando os usuários aplicam essa tag específica, eles só podem escolher entre esses valores específicos.

Portanto, é outra maneira de você determinar primeiro quem aplica a tag escrevendo as políticas. E então você também pode especificar que tipo de valores são permitidos. Então esse é realmente o esquema definido junto com a política que torna os recursos ainda mais organizados.

Uma coisa a ter em mente é que o namespace da tag, uma vez definido, não pode ser excluído. Mas você sempre pode aposentá-los e não precisa usá-lo. Isso é mais para fins de governança. Portanto, independentemente dos namespaces que você possui, você pode manter uma auditoria dos namespaces que tinha em sua conta. Então é isso.

Tagging-- um recurso muito importante, recurso útil na nuvem. E na OCI, levamos a marcação para o próximo nível usando essas tags definidas. Espero que você consiga usar o ta definido.

### Governance and Administration Summary

Vamos resumir o que você aprendeu em Governança e Administração. Analisamos os preços, que é um tópico importante, e como os preços da OCI são simples, transparentes e mais baixos do que alguns de nossos concorrentes. Analisamos o gerenciamento de custos e as várias ferramentas disponíveis para você gerenciar seus custos. E, finalmente, analisamos um recurso muito importante como parte da governança e administração, chamado de marcação e namespaces de marcação especificamente, e como ele pode ajudá-lo a organizar melhor seus recursos e também a gerenciar seus custos.

### Exercicios


1. Qual modelo de precificação é suportado pela OCI?

- [] Crédito universal semanal
- [] Licença incluída
- [x] Pague à medida que usa
- [] Créditos Universais Diários

2. Qual é um fator que afeta o preço da OCI?

- [x] Tipo de recurso
- [] Domínio de Disponibilidade
- [] Região OCI
- [] Domínio de falha

3. Quais tipos de tráfego são cobrados sob o custo de transferência de dados?

- [x] A saída é cobrada de e para a Internet
- [] A entrada e a saída são cobradas de e para a Internet
- [] A entrada é cobrada entre duas zonas de disponibilidade
- [] A entrada e a saída são cobradas entre instâncias em diferentes zonas de disponibilidade

4. Qual é uma meta válida para definir orçamentos de OCI?

- [] Domínio de Disponibilidade
- [x] Compartimento
- [] Arrendamento
- [] Região

## 15- SLA and Support

### SLA

Bem-vindo a esta lição sobre OCI SLA. SLAs são Acordos de Nível de Serviço. Vamos mergulhar mais fundo.

Então, o que é um Acordo de Nível de Serviço, também conhecido como SLA? Estes são compromissos apoiados financeiramente para fornecer um nível mínimo de serviço a você como cliente. Normalmente, estes são definidos como número de "nove" por um mês. Portanto, lembre-se de que eles são mensais e vêm com uma porcentagem de crédito.

Portanto, podemos dizer que se o seu tempo de atividade for inferior a 99,9% no mês, você receberá um crédito de 10% em seu uso para esse uso específico, para esse serviço específico, para esse mês específico. E estes são definidos em uma base de serviço para serviço. E geralmente, eles envolvem camadas e definição. Portanto, tenha isso em mente e vejamos como essas camadas e definições podem ser. É sempre bom explicar um conceito como SLA usando um exemplo.

Então, agora, estou usando um exemplo para um serviço OCI chamado Vault. O Vault é um serviço que você usaria para criar e gerenciar chaves de criptografia ou gerenciar seus segredos, como seu SSH ou senhas. É um serviço muito rico em recursos.

Assim, por exemplo, neste serviço Vault, disponível ou disponibilidade é definido por qualquer chamada de API válida que realiza uma operação criptográfica e retorna uma resposta 200, por exemplo, porque este serviço lida com operações criptográficas. Agora, a porcentagem de uptime mensal é calculada conforme você pega 100% e, a partir disso, você remove ou menos os minutos em que o serviço está indisponível. Agora, o que está indisponível? Basicamente, como dissemos agora, dissemos que disponível significa que você tem um código de sucesso que é escrito. Indisponível basicamente significa que você não pode obter esse código de sucesso.

Portanto, não há chamadas de API válidas nesse caso que executem com êxito uma operação criptográfica. E, claro, essa definição irá variar dependendo do tipo de serviço que você está usando como exemplo. Neste, é um Vault, e trata de operações criptográficas. Então é isso que disponibilidade e indisponível significa neste contexto.

Agora, quais são esses números finais? Como eles se parecem? Se você observar o SLA de disponibilidade do Vaults, a porcentagem de tempo de atividade mensal é inferior a 95%, o que significa que o serviço está disponível menos de 95% do tempo, você obtém 100% de crédito para esse mês.

Se for inferior a 99% mas igual ou superior a 95%, recebe 25% do crédito. E se for menor que 99,9%, triplo 9, mas igual ou maior que 99,0%, duplo 9, você ganha 10% de crédito. Então você pode ver, esses são os níveis e eles têm definições sobre o tipo de crédito que você recebe, dependendo de uma porcentagem de tempo de atividade mensal.

Agora, vamos ver outro exemplo rápido de como isso realmente funciona em ação. Então, vamos analisar dois cenários, cenário A e cenário B. No cenário A, o cliente experimenta 10 minutos de indisponibilidade durante um mês de 30 dias. Então, se você diz 30 dias, você calcula o número de minutos.

Em uma base de 24 horas, há 1.440 minutos. Você multiplica isso por 30, é um mês de 30 dias, você obtém esse número, 43.200. Então você pega esse número e reduz 10 minutos porque o serviço não está disponível. E, em seguida, para calcular o tempo de atividade percentual, você divide isso pelo número total de minutos do mês. Então você obtém um número como 99,98%. Agora, este não viola nenhum SLA para este serviço específico porque o nível aqui tem que ser menor que 99,9%, e isso é maior que 99,9% aqui -- 99,98%.

No segundo cenário, digamos que em vez de 10 minutos, se o serviço ficou indisponível por 60 minutos, 1 hora de indisponibilidade no mesmo mês de 30 dias. Agora, você reduz 60 minutos porque esse é o tempo em que o serviço fica indisponível e sua porcentagem de tempo de atividade mensal cai para 99,86%. Agora, o SLA foi violado porque você se enquadra neste último nível aqui.

E se o cliente enviar uma reclamação, ele será elegível para um crédito de 10% pelos gastos com esse serviço específico. Portanto, é uma base de serviço por serviço. E então estes -- todo serviço tem esses níveis, que você deve sempre verificar online.

Então, se você acessar nosso site, poderá acessar o SLA e dar uma olhada em como eles são. Deixe-me mostrar-lhe rapidamente. Então, se você acessar oracle.com/cloud/sla, há uma página aqui, que tem todos os detalhes sobre os serviços, serviços OCI, que vêm com SLAs de acordo de nível de serviço. E você pode ver os diferentes níveis aqui em torno de diferentes tipos de SLAs.

E se você abrir um documento aqui, esse documento tem todos os detalhes. E como você pode ver, ele é atualizado mensalmente. E você pode ver as definições aqui para os diferentes serviços. Você pode ver coisas como SLO, Objetivos de Nível de Serviço, acordos de nível de serviço e pode ver quais serviços são cobertos, o que significa disponível? O que significa indisponível?

Se eu for para o exemplo do Vault que estávamos vendo, você pode ver aqui que há uma descrição no Vault. E essas são as porcentagens mensais de tempo de atividade que estávamos analisando. E você pode ver novamente que os valores que analisamos são o percentual de uptime? O que está indisponível? 

E, novamente, isso-- você deve usar isso para todos os serviços que estiver usando. Isso forneceria mais detalhes sobre esse serviço específico e como são as camadas. E novamente, todas essas informações estão disponíveis em oracle.com/cloud/sla.

Tudo bem, então nós conversamos sobre isso. Vejamos algumas coisas que não abordamos no slide anterior. Acabamos de falar em geral como são os SLAs.

Agora, para o Oracle Cloud Infrastructure, somos o único fornecedor que oferece SLAs de ponta a ponta, abrangendo disponibilidade, capacidade de gerenciamento e desempenho. O que isso significa? Bem, a disponibilidade às vezes também é chamada de plano de dados. E isso significa que os serviços estão em operação com compromissos de tempo de atividade e conectividade. E analisamos a porcentagem mensal de uptime apenas no slide anterior para o serviço OCI chamado Vault.

Agora, se você observar a capacidade de gerenciamento, às vezes também chamada de plano de controle, é a capacidade de gerenciar, monitorar e modificar recursos OCI para cada serviço que possui um SLA. E então o desempenho basicamente significa que os serviços foram executados de forma consistente conforme o esperado. Portanto, lembre-se de que o SLA não é apenas uma coisa, são essas três dimensões, disponibilidade, capacidade de gerenciamento e desempenho.

Então, como devemos pensar sobre isso? Porque falamos sobre plano de controle, plano de dados. Então, o que esses termos realmente significam? Bem, o plano de controle se refere basicamente à administração de recursos. Portanto, trata de como você administra os recursos.

O plano de dados, por outro lado, trata do uso de recursos. Então, novamente, exemplo rápido. Se você pensar em um serviço como armazenamento de objetos, quando você cria um bucket, e bucket é onde você coloca seu objeto, você emite uma API, você executa essa API chamada Create Bucket. Esse é um exemplo de plano de controle porque você está administrando o recurso, está criando algo.

Mas quando você deseja listar o bucket ou obter o conteúdo do bucket, você diria algo como get GetBucket. E essa API específica faz parte das operações do plano de dados porque agora você está usando o recurso e o mesmo com algo como funções do Oracle. Quando você cria essa função, é uma operação de limpeza controlada. Quando você invoca essa função, é uma operação de plano de dados.

Portanto, tenha isso em mente. Quando falamos de SLAs, você realmente está falando de disponibilidade e capacidade de gerenciamento. A disponibilidade lida com o que às vezes chamamos de plano de controle, e a capacidade de gerenciamento são as operações do plano de dados.

Portanto, a ideia aqui é que os serviços principais e os planos de dados tenham dependências mínimas. Por exemplo, os planos de dados do volume de blocos de rede são autocontidos. O plano de dados de computação depende de volumes de blocos e planos de dados de rede. Mas a ideia é ter essas dependências mínimas entre os planos de dados.

Então, isso é praticamente tudo nos SLAs da OCI. Analisamos como OCI-- o que é um SLA. Analisamos um exemplo, OCI Vault e que tipo de porcentagens mensais de tempo de atividade esse serviço específico SLA oferece. E então analisamos os próprios SLAs da OCI em torno das três dimensões, disponibilidade, capacidade de gerenciamento e desempenho. Espero que você ache esta lição útil. Obrigado pelo seu tempo

###  Support

Bem-vindo a esta lição sobre suporte OCI. Especificamente nesta lição, veremos o Centro de Suporte OCI.

Então, o que é o Centro de Suporte? O painel do Centro de Suporte é seu único painel de controle para todas as suas necessidades de suporte e documentação de produtos. Ele tem algo que é chamado de botão Support Life Raft. E isso está disponível em todas as páginas do Management Console e fornece acesso com um clique ao suporte sempre que você precisar. E no próximo slide, mostrarei um visual rápido.

Quando você precisa criar uma nova solicitação de suporte, você só precisa descrever seu problema e o Centro de Suporte preencherá todos os principais detalhes do ambiente automaticamente. Por isso, estamos tornando super fácil para você trabalhar com o suporte e estamos tornando o suporte na nuvem mais fácil do que nunca. É meio que adicionar essa automação e contexto inteligente.

Então, como você pode ver aqui, este é o nosso painel, o painel do Centro de Suporte. Você pode ver que há um ticket aqui que é técnico e precisa da minha atenção. Este é o ticket de teste que eu estava criando, apenas brincando com ele. E me deu um número de solicitação de suporte, etc. Diz pendente com o cliente, pois preciso resolver e descrever meu problema.

Aqui você pode ver que este é o meu Centro de Suporte. Posso ver todas as minhas solicitações de suporte, sejam elas técnicas, de cobrança. Posso bater um papo rápido aqui. Posso ir à Oracle Cloud Community, obter mais detalhes. E aqui está toda a documentação. Então eu poderia olhar para documentação específica, olhar para coisas específicas se eu procurar computação ou armazenamento ou alguns dos serviços.

Agora, como você cria uma solicitação de suporte? Bem, abrir uma solicitação de serviço de suporte é muito mais fácil do que costumava ser. Então aqui, estou nesta página de computação. E como você pode ver, há uma instância de computação em execução. Digamos que teve algum problema e eu queria algum tipo de suporte técnico. Então, eu clicaria nesse botão Raft, que está disponível em todas as páginas do Console, e traria esse suporte técnico, suporte de cobrança. Se eu tiver que aumentar os limites, isso abriria essas janelas. E preenche-- se houver um problema, posso descrevê-lo aqui.

E então isso me dá diferentes níveis de criticidade, então se é um problema supercrítico, é um problema urgente, ou é algo que eu preciso de ajuda, mas não é urgente - é um problema padrão, certo? Além disso, o que o Centro de Suporte faz é adicionar automaticamente todas as principais informações para solução de problemas aqui mesmo. Assim, você pode ver as informações que o Console reuniu -- coisas como meu compartimento, domínio de disponibilidade, forma etc. -- a ideia é que o Centro de Suporte adiciona informações específicas do serviço para reduzir as idas e vindas com engenheiros de suporte. E adiciona automaticamente todas as informações importantes para solução de problemas.

Então, essa foi apenas uma introdução rápida sobre o Centro de Suporte e como ele funciona. Espero que você tenha achado esta lição útil. Obrigado pelo seu tempo.

### Exercicios

1. Qual declaração descreve corretamente os Acordos de Nível de Serviço da OCI?

- [] Definido como um número de noves para um trimestre e um crédito percentual.
- [] Definido como um número de noves por um ano e um crédito percentual.
- [x] Definido como um número de noves por um mês e um crédito percentual.
- [] Definido como um número de noves por uma semana e um crédito percentual.

2. Que tipo de SLA não é oferecido pelo serviço OCI Compute?

- [] Plano de dados
- [x] Plano de Aplicação
- [] Plano de controle
- [] Performance - Atuação

3. Qual dos seguintes não é coberto nos SLAs da OCI?

- [] Performance - Atuação
- [x] Confiabilidade
- [] Disponibilidade
- [] Capacidade de gerenciamento

4. Você está enfrentando um problema com o sistema de banco de dados em sua locação e deseja enviar uma solicitação de serviço ao Suporte Oracle.

Como cliente, quais informações não são necessárias para registrar uma solicitação de serviço?

- [x] IP do sistema de banco de dados
- [] OCID de locação
- [] Identificador de suporte ao cliente
- [] OCID do recurso

5. Que tipo de conta OCI permite abrir um ticket de suporte?

- [] Conta Sempre Gratuita
- [] 30 dias de teste gratuito
- [] Contas de demonstração
- [x] Conta paga


## 16- Course Summary

### Summary

Parabéns, você fez todo o curso. Com isso, você deve estar pronto para fazer o exame da OCI Foundation e obter sua certificação OCI. Mas antes de fazer isso, leia um pouco sobre os serviços OCI, abertura de conta de nível gratuito e acompanhe algumas das demonstrações mostradas no curso. Além disso, pratique com a Verificação de Habilidades no final de cada módulo.

Depois de obter seu certificado, comece a aplicar esse conhecimento em implementações OCI do mundo real e não pare por aqui. Eu recomendo fazer o OCI Architect Associate Exam como o próximo passo. Se você tiver sugestões para mim, ou para qualquer um de nós em geral, por favor, forneça seus comentários. Espero te ver em breve. Parabéns, e bem feito.

### Fonte: https://education.oracle.com/pt_BR/oracle-oci-certification#oracle-cloud-infrastructure



