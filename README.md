## Wiki da seção 3 do artigo "Internet of Things: A survey".


>[!NOTE]
>A tarefa da TDE em questão será fazer uma Wiki a respeito da seção 3 do artigo *Internet of Things: A survey*, de **ATZORI; IERA; MORABITO, 2010**. O título da seção é Enabling Technologies.

Como a Wiki em questão trata do primeiro assunto do ponto de vista cronológico, será feita uma breve introdução ao conceito da *Internet of Things*.

### 1. Introdução

A Internet das Coisas (*IoT - Internet of Things*) é um "novo" (no caso para o ano de 2010, de escrita do artigo em questão) que está rapidamente conquistando seu espaço no cenário de telecomunicações sem fio.
A ideia básica desse conceito é a presença **pervasiva** ao nosso redor de uma variedade de *coisas* ou *objetos*, como ***tags* de RFID** (vide a gênese do IoT), sensores, atuadores, telefones celulares, etc, os quais, **através de um esquema de endereçamento único** são capazes de interagir uns com os outros e cooperar entre si (no texto é escrito cooperar com seus vizinhos) a fim de atingir objetivos comuns.

Segundo o artigo, a principal força da ideia da *Internet of Things* se encontra no alto impacto que ela terá em diversos aspectos da vida cotidiana e no comportamento de potenciais usuários. Do ponto de vista de um usuário privado, os efeitos mais óbvios da introdução do *IoT* serão visíveis tanto no campo corporativo, de seu trabalho, quanto no campo doméstico.

>[!IMPORTANT]
>No contexto recém citado, a domótica, *assisted living*, no sentido de uma certa assistência da tecnologia com alguns cuidados especiais para pessoas que necessitam, *e-health*, aprendizagem melhorada, são apenas alguns dos cenários que esse novo paradigma terá um papel de destaque no futuro.

>[!NOTE]
>Da mesma forma, no ponto de vista de usuários corporativos, ou *business users*, as consequências mais aparentes serão igualmente visíveis em campos como automação da manufatura industrial, logística, gerenciamento de negócios/processos, e o transporte inteligente de pessoas e bens. 

> [!WARNING]  
> A *Internet of Things* está foi incluída pelo *National Intelligence Council* na lista das seis "Tecnologias Civis Disruptivas", com potenciais impactos no poder nacional dos EUA. O NIC aponta que pelo ano de 2025, os nodos de Internet deverão residir em todas as *coisas* do dia-a-dia. Oportunidades para o desenvolvimento econômico advindas da adoção da IoT são destacadas pelo Conselho, assim como ameaças consequentes da alta difusão dessa tecnologia são apontadas. "Tendo em vista que objetos do dia-a-dia podem se tornar riscos à segurança da informação, a IoT pode distribuir esses riscos de maneira que a Internet nunca foi capaz".

---
### 2. Tópico: 3. Enabling technologies ou, Tecnologias facilitadoras, ou que permitem a existência da Internet of Things

A concretização do conceito de *IoT* no mundo real é possível através da integração de uma série de "tecnologias facilitadoras", ou do inglês "*enabling technologies*"

>[!NOTE]
>A seção três tratará das "tecnologias facilitadoras" mais relevantes para o advento da *IoT*. O artigo apresenta uma breve descrição de cada uma das tecnologias citadas, apontando, principalmente, a relação da tecnologia em questão com a *IoT*, não necessariamente se aprofundando nela.
>

#### 2.1 Identificação, detecção (no sentido de sensoriamento) e tecnologias de comunicação

* "Em qualquer hora, em qualquer lugar, em qualquer tipo de dispositivo". Esse tem sido há um bom tempo, segundo o artigo, a visão que move adiante os avanços nas tecnologias de comunicação.

>[!IMPORTANT]
>Nesse contexto, pode-se afirmar que as tecnologias de comunicação sem fio possuem um papel determinante no contexto da *Internet of Things*, fazendo com que nos dias atuais (no caso do artigo, 2010) a proporção entre rádios (no caso qualquer dispositivo com tecnologias de RF) e humanos está próxima da proporção de 1:1.

No entanto, a redução em termos de tamanho, peso, consumo de energia e custo dos dispositivos com interface de rádio pode nos levar a uma nova era, onde a proporção em questão aumenta em ordem de magnitude. Esses fatores permitem que módulos de rádio sejam inseridos em praticamente todos os *objetos*, e, consequentemente, adicionar o termo "*qualquer coisa*" na visão citada previamente, que leva ao conceito de *IoT*.

##### *RFID* - A maneira de identificação única e a gênese da IoT

>[!NOTE]
>Uma tecnologia extremamente importante que acompanhou a *IoT* em seu princípio, satisfazendo a premissa de identificação única, é a tecnologia da *tag* de *RFID*. A presença de uma ou mais *tags* de *RFID* pode caracterizar um tipo de **sistema de *RFID***.

* Sistemas de *RFID* são compostos por um ou mais leitores, e várias *tags* *RFID*.

*Tags* de *RFID* são caracterizadas por um **identificador único** e são aplicados a **objetos, pessoas e até animais**.

Podemos descrever o funcionamento de uma *tag* de *RFID* da seguinte forma:

* A *tag* de *RFID* é basicamente um dispositivo que possui um identificador único e, geralmente, não possui alimentação elétrica;
* Na *tag*, uma identificação única relativa àquele dispositivo ou coisa é guardada;
* Em seu funcionamento, um leitor emite um sinal de rádio em uma determinada frequência;
* A *tag* então, recebe o sinal de rádio do leitor por meio de uma antena, que com ela transmite sua **identificação única** para o circuito leitor.

Sistemas *RFID* podem ser utilizados para monitorar objetos em tempo real sem que seja necessário propriamente ver o objeto. Assim é possível mapear o mundo real para um mundo virtual.

* *Tags* de *RFID* podem ser ativas, semi-passivas ou passivas. As diferenças entre elas podem ser verificadas em seguida:
	* *Tags* passivas não possuem uma fonte de alimentação em sua placa. Esse tipo de *tag* se utiliza do próprio sinal de rádio transmitido pelo leitor para alimentar o circuito de transmissão de seu *ID* via indução eletromagnética;
	* Nas *tags* semi-passivas, há a presença de uma bateria para alimentar o **circuito de recepção**. O circuito de transmissão continua sendo alimentado pela energia vinda da indução eletromagnética causada pela transmissão do leitor;
	* Já nas *tags* ativas, a bateria fornece energia também para a transmissão do sinal de rádio que carrega o *ID* da *tag*. A cobertura do sinal da *tag* ativa é o melhor entre as opções. Por outro lado, há o aumento de custo e do peso da *tag* de *RFID*.

##### Redes de Sensores

As redes de sensores também desempenharão um importante papel na *IoT*.

>[!NOTE]
>Sensores podem cooperar com sistemas de *RFID* para que se tenha disponível um maior acompanhamento das *coisas*, como por exemplo, o acompanhamento da sua localização, temperatura, movimentos, etc. O uso de redes de sensores tem sido proposto em uma gama de aplicações, que são elas: monitoramento ambiental, *e-health*, sistemas de transporte inteligente, uso militar, e monitoramento de plantas industriais.

Segundo o artigo, redes de sensores consistem em um certo número de nós (que pode ser um número alto) de sensores, que se comunicam sem o uso de fios (*wireless*). Ainda segundo o artigo, esses nós de sensores comumente enviam os resultados de suas leituras a um pequeno número de nodos especiais chamados *sinks*. Vários pesquisas cientificas foram feitas no tocante ao tema de Redes de Sensores, onde foram apontados os principais problemas em todas as camadas de seu protocolo utilizado.

Os objetivos das soluções propostas para os problemas encontrados nas Redes de Sensores são:
* Eficiência Energética (o recurso mais preocupante nos cenários que envolvem redes de sensores);
* Escalabilidade por conta do alto número de nodos;
* Confiabilidade, pois a rede de sensores pode ser utilizada para transmitir alarmes de prioridade altíssima;
* Robustez - nodos de sensores estão sujeitos a falhas por vários motivos.

>[!NOTE]
>Nos dias de hoje, a maior parte das soluções comerciais de redes de snsores sem fio são baseadas no padrão IEEE 802.15.4, que define as camadas física e de MAC para aplicações de comunicação sem fio de baixo consumo e com um baixo *bit rate*. Essa solução se destina a *Wireless Personal Area Networks*.  

A norma citada não inclui especificações das camadas superiores, responsáveis por integrar as redes de sensores à Internet. Essa é uma tarefa difícil, pois:
* Redes de Sensores podem conter um grande número de nodos. Isso, segundo o artigo, resultaria em problemas óbvios por conta da baixa disponibilidade de endereços IP;
* O maior tamanho de pacote da camada física da norma citada possui 127 *bytes*. Na camada de MAC (*media access control*), o tamanho do pacote é de 102 octetos. Tendo em vista o tamanho dos pacotes IP, e a necessidade de criptografia para garantir a *security*, os tamanhos citados são extremamente pequenos quando comparados com tamanhos de pacotes IP típicos (cujo MTU é de aproximadamente 1500 *bytes*, no caso do *frame ethernet*);
* Em diversos casos, os nodos de sensores passam boa parte em um modo de baixo consumo (*sleep*) a fim de economizar energia, não sendo capazes de se comunicarem durante esse período. Em redes IP, isso é uma anomalia.

##### A Integração de *tags RFID* e Redes de Sensores

A integração de tecnologias sensoriais com *tags RFID* passivas permitiriam várias aplicações completamente novas dentro do contexto da *IoT*, especialmente na área da *e-health*.
Essa integração permitirá a construção de redes de sensores com *RFID*.
Na prática, segundo o artigo, essa integração consiste em:
- Uma rede baseada em dispositivos baseados em *RFID* com a capacidade de captar determinada grandeza (no caso, atuar como um sensor) e de efetuar computação; e, leitores *RFID*. Os leitores comporiam o nodo principal, destino dos dados gerados pelos sensores com *RFID*, e responsável pela alimentação elétrica dos sensores.

##### Vantagens e desvantagens das tecnologias apresentadas na seção 2.1

* Sistemas baseados em autenticação via *RFID* possuem baixo tamanho e custo. Além do mais, seu tempo de vida útil não é limitado pela duração de uma bateria;
* Redes de sensores sem fio são o paradigma de alta cobertura de rádio e comunicação, não tendo a necessidade da presença direta de um leitor, como no item prévio. Sua comunicação é baseado no modelo de interação *peer to peer*;
* Redes de sensores com *RFID* são a possibilidade, segundo o artigo, de integrar tecnologias como: sensoriamento, computação e capacidade de comunicação em um sistema **passivo**.

#### 2.2 Middleware

O *Middleware*, segundo o artigo, é uma camada de *software*, ou um conjunto de sub-camadas (de *software*) interpostas entre os níveis tecnológico e de aplicação.

O termo tecnológico, nesse caso, está ligado diretamente à vasta gama de tecnologias (distintas) que podem ser utilizadas nos diferentes níveis hierárquicos de um dispositivo, ou melhor, de uma *coisa*. Essas tecnologias, sejam elas de sensores, atuadores, ou periféricos, possuem características e interfaces muitas vezes únicas e/ou extremamente específicas. A ideia do *middleware* se baseia em basicamente ser uma camada (ou o conjunto de camadas) responsável por esconder detalhes internos e/ou específicos de determinada tecnologia, a fim de isentar o programador que desenvolve uma camada superior, servida pelo *middleware*, de preocupações com essas características específicas. Essa camada chamada *middleware*, se localiza hierarquicamente entre a *coisa* e a aplicação. 

>[!NOTE]
>Segundo o artigo, o *middleware* teve destaque nos últimos anos (em relação a 2010) por simplificar o desenvolvimento de novos serviços e integração de tecnologias **legadas** a novas tecnologias, por isentar o programador (no caso o programador que fará a camada superior) de necessitar possuir o exato conhecimento de todas as tecnologias (variadas) adotadas nas camadas inferiores.

Esse tipo de arquitetura contendo uma camada intermediária, no caso o *middleware*, que esconde detalhes de camadas inferiores para servir camadas superiores, proposta no contexto da *IoT*, segue a abordagem da Arquitetura Orientada a Serviços, ou melhor dizendo, *Service Oriented Architecture* (SOA).

A adoção dos princípios *SOA* permite que um sistema monolítico e complexo seja decomposto em aplicações que consistem em um ecossistema de componentes mais simples e bem definidos quando comparados com sistemas monolíticos. O uso de protocolos padronizados e interfaces comuns fornecem uma visão horizontal de um sistema empresarial e/ou profissional. Essa abordagem permite e viabiliza o reuso de *hardware* e *software* para diferentes aplicações, já que não há uma imposição de uma tecnologia específica para a implementação do serviço.


##### 2.2.1 Arquitetura do Middleware

No artigo, é apresentada uma arquitetura de referência baseada em *SOA* para o *middleware* da Internet das Coisas. Essa arquitetura é composta por diferentes camadas responsáveis por organizar as funcionalidades necessárias para permitir a integração entre dispositivos físicos e aplicações distribuídas.

>[!NOTE]
>SOA seria sigla para "*Service Oriented Architecture*" ou "*Arquitetura Orientada a Serviço*"

Essas camadas possuem responsabilidades específicas dentro do sistema e trabalham juntas para lidar com desafios típicos da *IoT*, como a heterogeneidade de dispositivos, a descoberta dinâmica de serviços e a composição de funcionalidades mais complexas a partir de serviços simples.

A figura 2, a seguir, tenta elaborar a arquiteura SOA para IoT:

<p align="center">
<img src="Captura de tela 2026-03-11 220142.png" width="500">
</p>

>[!NOTE]
> HETEROGENEIDADE DE DISPOSITIVOS refere-se a grande diversidade e variedade de equipamentos, tecnologias, fabricantes, sistemas operacionais e protocolos de comunicação que estçao presentes em uma rede IoT

###### 2.1.2 Aplicações

Aplicações estão na camada mais alta do modelo arquitetural em questão, fornecendo todas as funcionalidades disponíveis no sistema para o usuário final. Essa camada não faz parte do *middleware*, mas é servida por ele, ou seja, explora todas as funcionalidades do *middleware*. Através do uso de protocolos padrões de *serviços web* e outras tecnologias com um modelo arquitetural semelhante, é possível efetuar uma integração perfeita entre aplicações *IoT* e **Sistemas Distribuídos**.

###### 2.1.3 Composição de Serviços 

Uma das camadas importantes dentro da arquitetura de *middleware* é a camada de composição de serviços.
- *Sua principal função é permitir a criação de serviços mais complexos por meio da combinação de serviços individuais oferecidos pelos objetos conectados.*

Nesse nível da arquitetura, os dispositivos físicos deixam de ser manipulados diretamente.
- *Em vez disso, suas funcionalidades passam a ser representadas na forma de **serviços disponíveis na rede**. Esses serviços podem então ser combinados para realizar tarefas mais complexas dentro de uma aplicação IoT.*

Para possibilitar essa composição, o *middleware* normalmente mantém um **repositório de serviços**, que contém informações sobre os serviços disponíveis no sistema em determinado momento.
- *A partir desse repositório, novos serviços compostos podem ser criados utilizando serviços mais simples como blocos fundamentais.*

A lógica responsável por coordenar esses serviços pode ser representada por **fluxos de trabalho, que descrevem a sequência de ações necessárias para realizar determinada funcionalidade dentro do sistema.

###### 2.1.4 Gerenciamento de Serviços

Outra camada fundamental do *middleware* é a camada de gerenciamento de serviços.
- *Essa camada fornece um conjunto de funcionalidades responsáveis por administrar os objetos e serviços presentes no ambiente IoT.*

Entre as principais funções fornecidas por essa camada **estão:**

- *Descoberta dinâmica de objetos na rede*  
- *Monitoramento do estado dos dispositivos*  
- *Configuração de serviços disponíveis*  
- *Gerenciamento da qualidade de serviço*

>[!NOTE]
>Além dessas funcionalidades básicas, algumas implementações de *middleware* também incluem mecanismos adicionais relacionados ao **gerenciamento de contexto**, **controle de políticas** e **gestão semântica dos serviços**.

Outro aspecto importante dessa camada é a possibilidade de **implantação dinâmica de novos serviços em tempo de execução**, permitindo que o sistema se adapte a novas necessidades ou mudanças no ambiente.

###### 2.1.5 Abstração do objeto, ou *coisa*

O universo dos dispositivos *IoT* abrange uma enorme heterogeneidade de *coisas*, cada uma provendo funcionalidades específicas acessíveis através de seu próprio protocolo. Ou seja, cada *coisa* pode ter seu próprio modo de ter suas respectivas funcionalidades acessadas. Essa característica das *coisas* implica na necessidade de haver uma camada de abstração capaz de padronizar o acesso a diferentes *coisas* por meio de uma linguagem e procedimento comum.

A camada de abstração da *coisa*, pode ser composta por duas sub-camadas caso a *coisa* não possua, segundo o artigo, a capacidade de oferecer serviços *web* detectáveis na rede IP. Essas duas sub-camadas seriam as seguintes:
- Sub-camada de interface;
- Sub-camada de comunicação.

>[!IMPORTANT]
>A sub-camada de interface provê os **métodos** necessários para que aquela *coisa* seja acessada por meio do padrão de *serviços web*. Ela é responsável por gerenciar a comunicação com o **mundo externo**.
A sub-camada de comunicação implementa a lógica por trás dos métodos do *serviço web* implementado na camada anterior. Essa camada é responsável por traduzir esses métodos em comandos específicos para a *coisa*, permitindo que ela, assim, se comunique com o mundo real.


Em alguns casos, dispositivos IoT podem possuir pilhas de comunicação **TCP/IP embarcadas**, permitindo sua conexão direta à Internet. Entretanto, em muitos cenários essa abstração é realizada por meio de **gateways ou proxies**, que atuam como intermediários responsáveis por traduzir diferentes protocolos de comunicação.

##### 2.1.6 Confiança, Privacidade e Segurança

A comunicação automática entre objetos no contexto da Internet das Coisas introduz diversos desafios relacionados a segurança e a privacidade dos usuários. 

>[!NOTE]
>Dispositivos conectados podem coletar e transmitir informações continuamente, muitas vezes sem que o usuário tenha plena consciência desse processo.

Dessa forma, o *middleware* também deve incluir mecanismos responsáveis por garantir:

- **Confiança entre dispositivos e serviços**
- **Proteção da privacidade dos usuários**
- **Segurança na comunicação e no armazenamento de dados**

Esses mecanismos podem ser implementados em uma camada específica ou distribuídos ao longo de toda a arquitetura do *middleware*. O objetivo é garantir que as informações trocadas entre dispositivos e aplicações permaneçam protegidas sem comprometer o **desempenho do sistema.**

