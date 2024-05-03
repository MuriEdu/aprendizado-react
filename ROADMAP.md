# Mapa de aprendizado para React
---
#### Alguns pontos importantes sobre o React:

O React é um framework, desenvolvido e mantido pela *Meta*, para auxiliar no desenvolvimento de páginas web e baseado em JavaScript. Portanto, é interessante que se tenha alguma base na linguagem, em HTML e CSS.

***Para se aprofundar um pouquinho nesses tópicos bases:***

- **Curso *Gustavo Guanabara* de HTML5 e CSS3**
	- Material super completo no entanto bastante longo, recomendo, caso não tiver tempo, assistir apenas o módulo 1.
	- Vou deixar o link da playlist do módulo 1 e a recomendação dos vídeos mais importantes.
	- [Módulo 1](https://youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&si=3vDhl_3w9qRPaqgZ)
	- [A diferença entre HTML, CSS e JavaScript](https://www.youtube.com/watch?v=B4FU3NFRTDw&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=9)
	- [Seu primeiro código HTML](https://www.youtube.com/watch?v=E6CdIawPTh0&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=12)
	- [Hierarquia de Títulos](https://www.youtube.com/watch?v=aiOEBhozEOg&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=20)
	- [Estilos CSS externos](https://www.youtube.com/watch?v=-i1JVMspDJQ&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n&index=40)
- **Curso *Gustavo Guanabara* de JavaScript**
	- Assim como o material anterior, é um material longo e completo, tenha em mente que o JavaScript é uma linguagem tal qual C que você já aprendeu na faculdade, então basta ter em mente as estruturas classicas de qualquer outa linguagem (estruturas condicionais, laços de repetição, funções, entre outras) e buscar qual a sintaxe específica em JavaScript. Caso deseje se aprofundar em tópicos específicos ou realizar exercícios para se familiarizar com a linguagem há muito conteúdo neste curso.
	- [Curso Grátis de JavaScript e ECMAScript para Iniciantes](https://youtube.com/playlist?list=PLHz_AreHm4dlsK3Nr9GVvXCbpQyHQl1o1&si=WT4e8u75UtvQtx8N)
- **Documentação**
	- Além do material em vídeo, tenha sempre a documentação oficial das tecnologias utilizadas. Nelas sempre terá as funcionalidades mais atualizadas e as práticas e usos corretos de cada recurso.
	- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
	- [W3 Schools - HTML](https://www.w3schools.com/tags/)
	- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
	- [W3 Schools - CSS](https://www.w3schools.com/cssref/index.php)
	- [MDN Web Docs - JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
	- [W3 Schools - JS](https://www.w3schools.com/jsrEF/default.asp)
---
## React

Dada a base do desenvolvimento web para o front-end, podemos avançar para a utilização de ferramentas que auxiliem e permitam maiores funcionalidades no desenvolvimento da página. A ferramenta em questão neste documento é o **React**.

A ideia do React é muito simples. Quando estávamos criando as páginas utilizando HTML puro, compunhamos o documento utilizando diferentes tags. No entanto, ao fazer isso, não tínhamos controle sobre o que, internamente, a tag fazia. Pense nas tags como uma máquina. Agora, com o React, teremos acesso ao motor dessa máquina e vamos poder criar nossas próprias tags, às quais damos o nome de **COMPONENTES**.
## Estrutura do Projeto em React

Basicamente, todo projeto criado com React possui o `App.js` como o arquivo principal. Esse arquivo é responsável por "Iniciar a aplicação", ou seja, fornecer um componente inicial para ser carregado, ou uma rota para a página inicial.

Os arquivos/códigos fonte do projeto são colocados dentro da pasta _**src**_, inclusive o `App.js`.

Dentro de `src`, temos as pastas _**componentes**_ e _**pages**_. Dentro de `componentes`, devem ser colocados os códigos dos componentes que serão utilizados para compor as páginas. Cada componente deve conter sua própria pasta, incluindo o arquivo **.js** e o arquivo **.css**. Na pasta `pages`, similarmente aos componentes, cada página deve ter sua própria pasta contendo o arquivo **.js** e o arquivo **.css**.
## Componentes
Os componentes são basicamente funções que retornam um código JSX, extremamente similar a um HTML, mas que mescla código em JavaScript. Componentes são a essência do React, portanto, vou deixar os materiais que considero interessantes para o estudo dos componentes. Antes dos materiais, algumas coisas importantes para ter em mente quando forem criar seus componentes:
- *Quanto mais componentizado, melhor. Isto é, crie componentes pequenos que possam ser reutilizados em diversas páginas. Um botão pode ser um componente, uma janela de mensagem outro e assim por diante. Dessa forma, caso haja a necessidade de alterar algum componente, todo o site e as páginas que o utilizam serão atualizadas junto.*
**Materias sobre Componentes em React:**
- **Documentação**
	- Como já disse nesse material, a documenteção da tecnologia em quetstão sempre será sua maior aliada, portanto vou deixar aqui a documentação oficial sobre compponentes.
		- [Documentação do React sobre Componentes](https://react.dev/learn/your-first-component)
- **Aula do Curso de React do *Matheus Battisti***
	- O curso de React do Matheus é bastante completo e interessante, com os tópicos abordados nele ja é possível construir basicamente qualquer projeto. Aqui vou deixar apenas o link para a aula sobre a criação de componentes.
		- [Curso React: Criando componentes no React](https://www.youtube.com/watch?v=-wrsG0IGc-M&list=PLnDvRpP8BneyVA0SZ2okm-QBojomniQVO&index=4)

Quanto ao assunto de componentes, é evidente que existem muitos tópicos e possibilidades, além de habilidades importantes, para aprender, visto que o componente é o principal conceito do desenvolvimento com React. Por isso, vou deixar listados tópicos importantes sobre os componentes. Recomendo novamente o curso do _**Matheus Battisti**_, mas sintam-se à vontade para procurarem outras fontes sobre esse tópico.
- Estilização dos componentes com arquivos .css
- Trabalhar com as props dos componentes
- Eventos (onClick, onChange, onSubmit)
	- EEste tópico está mais relacionado com a árvore DOM da página web. Este conceito faz parte do aprendizado de HTML e será reutilizado em React.
---
## React Hooks
Os _React Hooks_ permitem que os componentes tenham funcionalidades, ou seja, que armazenem estados, realizem conexões ou sincronizações com funcionalidades externas, entre outras. Os hooks são o segundo pilar do desenvolvimento em React e permitem, principalmente, interatividade com os componentes. Seguem abaixo os materiais mais interessantes, na minha opinião, sobre os Hooks.

**Materiais sobre React Hooks**
- **Documentação**
	- Documentação oficial sobre os hooks, antes da utilização de qualquer hook é importante a leitura dessa documentação, aqui existem informações sobre boas práticas e, principalmente, usos incorretos que podem causar bugs e problemas de performance.
	- [Documentação do React sobre os Hooks](https://react.dev/reference/react/hooks)
- **Aula do *Felipe Rocha***
	- Aula de 50 minutos com explicações bem completa sobre os Hooks mais importantes.
	- [React Hooks: Aprenda os MAIS IMPORTANTES em 50 Minutos!](https://www.youtube.com/watch?v=MA3Ngo32qiI)
- **Aula da *Fernanda Kipper***
	- Aula de 30 minutos sobre os principais hooks (menos hooks do que a aula anterios) e sobre a criação dos seus próprios Hooks.
	- [Aprenda REACT HOOKS em 30 minutos | Tutorial sobre Hooks](https://www.youtube.com/watch?v=Fc-___dblSI)
---
## Considerações finais
Os conteúdos passados e selecionados acima são as principais e mais utilizadas ferramentas que compõem o React. É claro que ainda existem muitas técnicas e soluções a aprender, mas com o que foi passado já é possível construir muita coisa interessante. Recomendo que vocês coloquem a mão na massa para se depararem com problemas e situações que levem ao aprendizado. Vou deixar aqui embaixo alguns repositórios e alguns vídeos com projetos simples ou com aulas mais abrangentes que vocês podem fazer para praticar. Estou à disposição para ajudar, reconheço que não sou o maior especialista, mas podemos aprender juntos =)

- **Material para praticar**.
	- **Aula de 18 minutos do *Felipe Deschamps***
	- [Se Você Passar Por Esses 5 Desafios, Você Aprendeu React JS](https://www.youtube.com/watch?v=aJR7f45dBNs&t=572s)
	- **Aula de 1h do *Matheus Battisti***
	- [PROJETO de React JS para INICIANTES - Faça uma To Do List do zero!](https://www.youtube.com/watch?v=YVEVrigByKY)
	- **Repositório *30-Days-Of-React***
	- [30-Days-Of-React on GitHub](https://github.com/Asabeneh/30-Days-Of-React/tree/master)
---
