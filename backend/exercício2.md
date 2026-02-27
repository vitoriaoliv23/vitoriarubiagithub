**1.** O que é o **Node.js**?
Explique sua finalidade e por que ele é considerado um ambiente de execução e não uma linguagem de programação.

Node.js é um ambiente de tempo de execução (runtime) de código aberto, construído sobre o motor V8 do Chrome, que permite executar JavaScript no lado do servidor, fora do navegador. Sua finalidade é criar aplicações de rede escaláveis, como APIs e serviços em tempo real, usando uma arquitetura orientada a eventos e não bloqueante. É um ambiente, não uma linguagem, pois utiliza o JavaScript (a linguagem) para interagir com o sistema operacional, gerenciar arquivos e conexões.

**2.** Qual a diferença entre **Node.js** e **JavaScript executado no navegador**?
Cite pelo menos **duas diferenças**.

A principal diferença é que o Node.js é um ambiente de execução (runtime) para o lado do servidor (backend), permitindo acessar o sistema operacional e arquivos. Já o JavaScript no navegador (client-side) é voltado para interações na interface do usuário (DOM) e manipulação do navegador.

**3.** O que é o **V8 Engine** e qual sua importância para o funcionamento do Node.js?

O V8 Engine é um motor JavaScript de alto desempenho, de código aberto, desenvolvido pelo Google em C++ e usado no navegador Chrome e no Node.js. Ele compila JavaScript diretamente em código de máquina nativo usando compilação Just-In-Time (JIT), permitindo execução rápida sem depender de interpretadores lentos. 

**4.** Explique o conceito de **I/O não bloqueante** no Node.js.
Por que isso melhora o desempenho de aplicações?

O I/O (Input/Output) não bloqueante é um dos pilares fundamentais do Node.js, permitindo que o ambiente de execução manipule múltiplas operações simultaneamente (como leitura de arquivos, requisições de banco de dados ou chamadas de rede) sem pausar a execução do código principal. 

**5.** O que é o **Event Loop**?
Descreva, de forma resumida, como ele funciona.

O Event Loop (Loop de Eventos) é um mecanismo fundamental no JavaScript (e Node.js) que permite a execução de operações assíncronas e não bloqueantes, mesmo sendo uma linguagem de thread única (single-threaded). Sua principal função é monitorar a Call Stack (pilha de execução) e as filas de tarefas (filas de callbacks), garantindo que funções assíncronas sejam executadas apenas quando a pilha estiver vazia. 

**6.** O que são **módulos** no Node.js?
Explique a diferença entre: 

são arquivos JavaScript independentes que agrupam código, funções e objetos, permitindo sua reutilização e organização em aplicações, mantendo o escopo encapsulado.

* Módulos internos: São módulos nativos, embutidos no Node.js no momento da instalação. Não precisam ser instalados via npm e fornecem funcionalidades básicas.
* Módulos externos:  São bibliotecas desenvolvidas por terceiros (comunidade) e instaladas no projeto via npm (Node Package Manager). Eles residem na pasta node_modules.
* Módulos criados pelo desenvolvedor: São arquivos JavaScript criados pelo próprio desenvolvedor para organizar o código do projeto. São importados usando o caminho relativo do arquivo


**7.** Para que serve o arquivo **package.json** em um projeto Node.js?
Cite pelo menos **três informações** que ele pode conter.

é fundamental em projetos Node.js, funcionando como um "manifesto" ou "certidão de nascimento" da aplicação. Ele serve para gerenciar as configurações do projeto, rastrear dependências (bibliotecas externas), definir scripts de automação e metadados como nome e versão. Ele pode conter Identificação do Projeto, Gerenciamento de Dependências, Automação de Scripts.

**8.** O que é o **npm**?
Explique sua função no desenvolvimento de aplicações Node.js.

O npm (Node Package Manager) é o gerenciador de pacotes padrão para o ambiente de execução Node.js e o maior registro de software de código aberto do mundo. Sua principal função no desenvolvimento de aplicações Node.js é automatizar a instalação, o compartilhamento, a atualização e o gerenciamento de bibliotecas e dependências de código.

**9.** O que é uma **API REST** e como o Node.js pode ser usado para desenvolvê-la?

é um estilo de arquitetura de software que utiliza o protocolo HTTP para permitir que diferentes sistemas troquem informações de forma padronizada, eficiente e flexível. O Node.js, combinado com o framework Express.js, é a escolha popular para criar APIs REST devido à sua natureza "non-blocking" (assíncrona) e leveza. 

**10.** Cite **duas vantagens** e **duas desvantagens** do uso do Node.js em aplicações web.

Vantagens: Rápido em I/O (tempo real), Full-stack JavaScript.
Desvantagens: Ruim para CPU, complexidade em código assíncrono. 
