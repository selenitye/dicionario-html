# Dicionário HTML

Tags e Termos usados no HTML

## Estrutura básica

| ELEMENTO | DEFINIÇÃO |
| ------ | ------ |
| ! | O VS Code utiliza por padrão o Emmet Abbreviations, que traz o aparecimento automático de linhas de código que fazem parte da estrutura básica do HTML ao digitar o ponto de exclamação. Dessa forma |
| < !DOCTYPE html > | No HTML, o doctype é a introdução “<!DOCTYPE html>” encontrada no topo de todos os documentos. Seu único propósito é evitar que o browser mude para os chamados “quirks mode” quando renderizar um documento; isto é, o “<!DOCTYPE html>” doctype garante que o browser faça um esforço na tentativa de seguir as especificações relevantes, em vez de usar um modo de renderização diferente e que seja incompatível com algumas especificações. |
| < html > | Representa a raiz do documento, serve com um container que engloba todos os outros elementos HTML. |
| < head > | Compreende as informações do documento que serão interpretadas pelo navegador (metadados). Como por exemplo, título do documento, links para folhas de estilo etc. |
| < body > | É onde fica todo o conteúdo de texto, imagem e vídeos, em que o usuário vê e interage, nele os conteúdos são estruturados pelas demais tags do HTML. |
| < meta > | Define metadados, ou seja, informações sobre dados de um documento HTML. As <meta> tags vão dentro do elemento <head> e são usadas para especificar o conjunto de caracteres, o autor do documento, as configurações da janela de visualização etc. |
| < title > | [plugins/googleanalytics/README.md][PlGa] |
| < script > | Esse elemento contém instruções de script ou aponta para um arquivo de script externo por meio do atributo src. |
| < style > | Essa tag é usada para declarar estilos (CSS) para um documento. |
| < link > | É uma tag vazia, que contém apenas atributos e faz a relação do documento HTML com recursos externos, é comumente usado para vincular uma folha de estilo externa, também é usada para definir o favicon da página (ícone da aba do navegador), como outros recursos. |

## Tags semânticas  
  
  Tags semânticas são tags que possuem um significado, que dão sentido a informação de texto ao navegador e buscadores, como por exemplo, utilizar a tag < header > para cabeçalhos ou < article > para dar um significado de artigo para aquele bloco de texto, até mesmo < p > para indicar que aquele texto é um parágrafo, é uma boa prática tentar sempre utilizar essas tags semânticas para ajudar no entendimento do código, além de ajudar muito no SEO do site (Otimização para motores de busca, é o que ajuda o seu site a se rankear melhor nos motores de buscas como o Google). 
  
| ELEMENTO | DEFINIÇÃO |
| ------ | ------ |
| < header> | Representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, sessões de cabeçalho, formulário de pesquisa, e outros. |
| < main> | O elemento <main> define o conteúdo principal dentro do <body> em seu documento ou aplicação. |
| < footer> | O elemento HTML de Rodapé (<footer>) representa um rodapé. Normalmente um rodapé contém informações sobre o autor da seção de dados, direitos autorais ou links para documentos relacionados. |
| < section> | representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo. |
| < article> | representa uma composição independente em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sindicação. Este poderia ser o post de um fórum, um artigo de revista ou jornal, um post de um blog, um comentário enviado por um usuário, um gadget ou widget interativos, ou qualquer outra forma de conteúdo independente. |
| < aside> | Representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem explicações laterais, como a definição de um glossário; conteúdo vagamente relacionado, como avisos; a biografia do autor; ou, em aplicações web, informações de perfil ou links de blogs relacionados. |
| < nav> | Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação. |
| < ol> | Define lista de itens ordenada |
| < ul> | Define uma lista desordenada. |
| < li> | Define os itens da lista. |

### Exemplo de estruturação com tags semânticas:
<p align="center">
  <img src="https://raw.githubusercontent.com/selenitye/dicionario-html/main/estrutura-html.jpeg" height="800"/>
</p>
  
## Tags sem semântica
As tags que não possuem semântica não definem um significado para aquele texto, normalmente são utilizadas apenas para fins de separação e estilização. Veja logo abaixo a lista de algumas tags sem semântica:
  
| ELEMENTO | DEFINIÇÃO |
| ------ | ------ |
| < div> | É um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos(usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica(tal como article ou nav). |
| < span> | Muito parecido com a tag sem semântica < div>, porém é um elemento em linha que atua como um container genérico para agrupar conteúdos de texto. |
| < b> | Deixar o texto em negrito |
| < i> | Deixar o texto em itálico |
| < mark> | Para destacar o texto |
| < small> | É utilizado para reduzir o tamanho da fonte num intervalo definido de um texto. |
| < align> | Para o alinhamento da imagem, que pode ser ainda top (topo), middle (meio), bottom (alinha a imagem com a base dos outros elementos da linha), left (à esquerda) ou right (à direita) |

  
## Comentários
Comentários no HTML ou em qualquer outra linguagem são notas que podem ser incluídas no código fonte para descrever o que se quiser. Assim, não modificam o programa executado e servem somente para ajudar a pessoa que está desenvolvendo a melhor organizar os seus códigos. Para comentar algum código no HTML você deve envolvê-lo entre *< !-- Seu código aqui – >.*

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  
As tags podem ser categorizadas inicialmente em dois tipos, em “nível de bloco” (block-level) e “em linha” (inline). Um elemento em nível de bloco ocupa toda a largura de seu elemento pai, que também chamamos de elemento container, criando assim um “bloco”. Já os elementos inline, geralmente usamos para demarcação de conteúdos de texto. 
  
## Elementos inline
"Inline" é uma categorização dos elementos do HTML, os elementos inline podem ser exibidos em nível de bloco ou outros elementos inline. Eles ocupam somente a largura de seu conteúdo.
  
  
| ELEMENTO | DEFINIÇÃO |
| ------ | ------- |
| < br> | Essa tag produz uma quebra de linha em um determinado ponto do documento. |
| < a> | É um elemento âncora que define um hiperlink, que vincula páginas web, arquivos, endereços de emails, ligações na mesma página. Essa tag com o atributo href, indica o destino do link. Também é possível criar âncoras para textos na mesma página com o href informando o id do elemento destino. |
| < img> | Utilizada para colocar imagens no site, deve-se utilizar o atributo src, colocando entre as aspas o link ou caminho do arquivo. |
| < audio> | Utilizada para inserir áudios no site, tendo como principais atributos: src, recebendo como valor o link ou diretório do audio, controls caso queira que seja possível controlar o áudio, autoplay para definir que o áudio de tocar automaticamente quando entrar no site, type recebendo como valor o tipo do áudio. |

Também nessa categoria: < span>  
  
## Elementos block level
Os elementos em “nível de bloco” ocupam todo o espaço do seu elemento pai (container).  
  
| ELEMENTO | DEFINIçÂO |
| ------ | ------- |
| < header> | Define o cabeçalho da página, geralmente no cabeçalho identificamos o site, com a logo. |
| < main> | Compreende o conteúdo principal do corpo da página. |
| < footer> | Define o final da página ou conteúdo, o rodapé, geralmente colocamos contatos, redes sociais, endereço, informações “institucionais” no geral. |
| < section> | Dentro do conteúdo principal, essa tag compreende uma seção da página. |
| < article> | Inclui um artigo da página, muito utilizado em blogs e páginas de criação de conteúdo, também indica o principal conteúdo de texto da página. |
| < aside> | Representa uma seção que faz referência a outro conteúdo da página, como uma definição, uma explicação extra, avisos, biografia do autor, ou seja um conteúdo complementar |
| < nav> | Contempla o menu de navegação das páginas do site, e dentro inserimos a listas e links com a tag < a href=””></a>. |
| < div> | Assim como as outras tags, também funciona como um container, porém a grande diferença é que a div não tem valor semântico, é apenas uma divisão na página para fins de layout. |
| < p> | Representa um parágrafo. |
| < h1> ...<h6> | A família de cabeçalhos ou headings, define os títulos da página. Esse grupo de elementos possuem um alto valor semântico e uma organização hierárquica, indo de < h1> até < h6>, sendo o h1 de maior valor semântico e o h6 de menor valor semântico. |
| < hr> | Essa tag constrói uma linha horizontal entre elementos, representa semanticamente uma quebra de conteúdo. |
| < video> | Utilizada para inserir vídeos no site, a tag possui atributos como width recebendo como valor a largura do vídeo em pixels, height recebendo como valor a altura do video em píxeis, caso não for informada esses atributos, será utilizado a largura e altura padrão do vídeo, controls (quando presente nos permite controlar o video), src recebendo como valor o link ou diretório do arquivo de vídeo. |

## Formulário  
O que são e quais elementos compõem um formulário. 
  
| ELEMENTO | DEFINIÇÃO |
| ------ | ------- |
| < form> | Essa tag indica que estamos iniciando um formulário, recebe como principais atributos method que recebe como valor o método http que esse formulário irá executar (get, post) e action que especifica para onde enviar os dados do formulário quando um formulário é enviado. |
| < input> | Um campo para que o usuário possa inserir algum texto, data, número, cor, etc… possui como principais atributos type, que recebe como valor o tipo do input. |
| < textarea> | Representa uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre, como um comentário ou formulário de retorno. |
| < button> | Um botão clicável, possui como principais atributos type, que caso receba submit como valor e esteja dentro de um formulário, irá submeter o formulário. |
| < label> | A tag label é importante para os campos de formulários. Ela especifica qual o "rótulo" do input (a que se refere o input, como por exemplo envolvê-la em um texto “Nome completo”), e ajuda na experiência do usuário durante a utilização e preenchimento do formulário. |

## Atributos das Tags
Atributos HTML são palavras especiais usadas dentro da tag de abertura para controlar o comportamento do elemento. Os atributos HTML são um modificador de um tipo de elemento HTML. Com eles podemos identificar melhor um elemento, informar qual arquivo aquela tag deve utilizar, indicar o tipo de um campo de texto, etc…
  No CSS ( é colocado um . (ponto) antes para identificar o atributo.
Há dois tipos:

- GLOBAIS: são aceitos por todas as tags, como por exemplo: class, id, lang, style, etc 
- ESPECIFICOS: somente algumas tags possuem, como src, disabled, href, label, etc… 

| ELEMENTO | DEFINIÇÃO |
| ------ | ------- |
| class=”NomeDaClasse” | Classes são como classificações de uma tag/elemento, para que no CSS estilizar uma tag específica, ou um conjunto de tags. Também é possível usar no JavaScript para selecionar uma tag específica ou no CSS  |
| id=”NomeDoId” | Identificar de forma única um elemento naquela página HTML... É utilizado para identificar destino de âncoras, labels e outras funcionalidades neste sentido. |
| src=”Link ou diretório da mídia" | Comumente utilizado para indicar para a tag qual arquivo ou mídia utilizar. Recebe valores como links (https://google.com/minhaimagem.jpeg) ou o nome de um arquivo já presente no projeto (/minhaimagem.jpeg). |
| alt=”Texto alternativo” | O atributo alt fornece informações alternativas para uma imagem se um usuário por algum motivo não puder visualizá-la (devido à conexão lenta, um erro no atributo src ou se o usuário usar um leitor de tela). |
| href=”Url” | Para a tag <a>, o atributo href especifica a URL da página para a qual o link vai. |
| lang=”Linguagem” | O atributo lang especifica o idioma do conteúdo da tag. |
| target=”blank” | Esse atributo abre o link do documento em uma nova janela ou aba. |

  
  Junho de 2023 , Em breve mais atualizações (ou não🤪) XX 
  
  
