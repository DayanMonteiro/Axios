# Axios

Axios é um cliente HTTP baseado em promessa para node.js e o navegador.

É isomórfico - poder executado no navegador e no NodeJs com a mesma base de código

No lado do servidor ele usa o módulo HTTP NodeJS nativo, enquanto no cliente (navegador) ele usa XMLHttpRequests.

#### Principais Funcionalidades
- EXMLHttpRequests a partir do navegador ( AJAX significa Asynchronous JavaScript and XML, ou JavaScript e XML Assíncronos - Em poucas palavras, é o uso do objeto XMLHttpRequest para se comunicar com os scripts do lado do servidor. Ele pode enviar bem como receber informações em uma variedade de formatos, incluindo JSON, XML, HTML, e até mesmo arquivos de texto).
- Requisições HTTP no NodeJs.
- Suporta a API Promise.
- Interceptar requisições e respostas.
- Transformação de dados da requisição e resposta.
- Cancelamento de requisições.
- Transformações automáticas para dados JSON.
- Suporte do lado do cliente para proteção contra XSRF (A falsificação de solicitação entre sites (também conhecida como XSRF ou CSRF) é um ataque contra aplicativos hospedados na Web em que um aplicativo Web mal-intencionado pode influenciar a interação entre um navegador cliente e um aplicativo Web que confia nesse navegador. Esses ataques são possíveis porque os navegadores da Web enviam alguns tipos de tokens de autenticação automaticamente com cada solicitação para um site. Essa forma de exploração também é conhecida como um ataque de um clique ou uma corrida de sessão porque o ataque aproveita a sessão autenticada anteriormente do usuário).

O Projeto será desenvolvido usando Tailwindcss e PrismJs, o projeto realizara requisições do tipo GET, POST, PUT, PATCH e DELETE. 
Faz múltiplas requisições ao mesmo tempo.
Criar interceptadores etc...
