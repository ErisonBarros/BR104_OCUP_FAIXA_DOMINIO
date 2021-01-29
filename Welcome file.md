# Bem-vindo ao StackEdit!

Oi! Sou seu primeiro arquivo Markdown em ** StackEdit ** . Se você quiser aprender sobre StackEdit, você pode me ler. Se você quiser jogar com Markdown, você pode me editar. Depois de terminar comigo, você pode criar novos arquivos abrindo o ** explorador de arquivos ** no canto esquerdo da barra de navegação.


# Arquivos

StackEdit armazena seus arquivos em seu navegador, o que significa que todos os seus arquivos são salvos automaticamente localmente e estão recuperados ** offline! **

## Crie arquivos e pastas

O explorador de arquivos pode ser acessado usando o botão no canto esquerdo da barra de navegação. Você pode criar um novo arquivo clicando no botão ** Novo arquivo ** no explorador de arquivos. Você também pode criar pastas clicando no botão ** Nova pasta ** .

## Mudar para outro arquivo

Todos os seus arquivos e pastas são alternativos como uma árvore no explorador de arquivos. Você pode alternar de um para outro clicando em um arquivo na árvore.

## Renomear um arquivo

Você pode renomear o arquivo atual clicando no nome do arquivo na barra de navegação ou clicando no botão ** Renomear ** no explorador de arquivos.

## Excluir um arquivo

Você pode excluir o arquivo atual clicando no botão ** Remover ** no explorador de arquivos. O arquivo será movido para o ** Lixo ** macarrão e automaticamente excluído 7 dias de inatividade.

## Exportar um arquivo

Você pode exportar o arquivo atual clicando em ** Exportar para disco ** no menu. Você pode escolher exportar o arquivo como Markdown simples, como HTML usando um modelo de barras de guia ou como um PDF.


# Sincronização

A sincronização é um dos maiores recursos do StackEdit. Ele permite sincronizar qualquer arquivo no seu espaço de trabalho com outros arquivos armazenados em seu ** Google Drive ** , seu ** Dropbox ** e seu ** GitHub ** contas. Isso permite que você continue criando em outros dispositivos, colabore com as pessoas com quem você compartilha o arquivo, integre-se facilmente ao seu fluxo de trabalho ... O mecanismo de sincronização ocorre a cada minuto em segundo plano, baixando, mesclando e carregando modificações de arquivo.

Existem dois tipos de sincronização e podem se complementar:

- A sincronização do espaço de trabalho irá sincronizar todos os seus arquivos, massas e automaticamente. Isso permitirá que você busque seu espaço de trabalho em qualquer outro dispositivo. > Para começar a sincronizar seu espaço de trabalho, basta fazer login com o Google no menu. - A sincronização de arquivos manterá um arquivo do espaço de trabalho sincronizado com um ou vários arquivos no ** Google Drive ** , ** Dropbox ** ou ** GitHub ** . > Antes de Começar a sincronizar Arquivos, Rápido rápido Você DEVE vincular Uma Conta nenhum submenu ** Sincronizar ** .





## Abra um arquivo

Você pode abrir um arquivo a partir do ** Google Drive ** , ** Dropbox ** ou ** GitHub ** abrindo o submenu ** Sincronizar ** e clicar ** Aberto de ** . Depois de aberto na área de trabalho, qualquer modificação no arquivo será sincronizada automaticamente.

## Salvar um arquivo

Você pode salvar qualquer arquivo do espaço de trabalho para ** Google Drive ** , ** Dropbox ** ou ** GitHub ** abrindo o submenu ** Sincronizar ** e clicar ** Economize em ** . Mesmo se um arquivo na área de trabalho já estiver sincronizado, você pode salvá-lo em outro local. StackEdit pode sincronizar um arquivo com vários locais e contas.

## Sincronizar um arquivo

Uma vez que seu arquivo está vinculado a um sincronizado local, StackEdit irá sincronizá-lo periodicamente baixando / carregando qualquer modificação. Uma fusão será realizada se necessário e os conflitos serão resolvidos.

Se você acabou de modificar seu arquivo e deseja forçar uma sincronização, clique no botão ** Sincronizar agora ** na barra de navegação.

> ** Nota: ** O botão ** Sincronizar agora ** será desabilitado se você não tiver nenhum arquivo para sincronizar. 

## Gerenciar sincronização de arquivos

Uma vez Que hum Arquivo PODE Ser sincronizado com Vários LOCAIS, rápido Você PODE listar e gerenciar OS LOCAIS sincronizadas Clicando ** Submenu Sincronização de arquivos ** não ** Sincronizar ** . Isso permite que você liste e remova os locais sincronizados que estão vinculados ao seu arquivo.


# Publicação

Publicar no StackEdit torna simples para você publicar seus arquivos online. Quando estiver satisfeito com um arquivo, você pode publicá-lo em diferentes plataformas de hospedagem, como ** Blogger ** , ** Dropbox ** , ** Gist ** , ** GitHub ** , ** Google Drive ** , *                 * WordPress ** e ** Zendesk **. Com [modelos de barras de guia] ( http://handlebarsjs.com/) , você tem controle total sobre o que exporta.

> Antes de Começar um PUBLICAR, rápido Você DEVE vincular Uma Conta nenhum submenu ** A Publicar ** .

## Publicar um arquivo

Você pode publicar seu arquivo abrindo o submenu ** Publicar ** e clicar ** Publicar ** . Para alguns locais, você pode escolher entre os seguintes formatos:

- Markdown: publique o texto do Markdown em um site que pode interpretá-lo ( ** GitHub ** por exemplo), - HTML: publique o arquivo convertido em HTML por meio de um template Handlebars (em um blog, por exemplo).


## Atualizar uma publicação

Após a publicação, StackEdit mantém seu arquivo vinculado a essa publicação, o que torna mais fácil para você publicá-lo novamente. Depois de modificar seu arquivo e desejar atualizar sua publicação, clique no botão ** Publicar agora ** na barra de navegação.

> ** Nota: ** O botão ** Publicar agora ** está desabilitado se o seu arquivo ainda não foi publicado. 

## Gerenciar publicar de arquivo

Uma vez que um arquivo pode ser publicado em vários locais, você pode listar e gerenciar publicar locais clicando ** publicar Arquivo ** no ** Publicar ** submenu. Isso permite que você liste e remova os locais de publicação vinculados ao seu arquivo.


# Extensões de Markdown

StackEdit estende uma sintaxe Markdown padrão, adicionando adicional ** incorporando ** , proporcionando-lhe algumas características interessantes.

> ** Protip: ** Você pode desativar qualquer ** extensão Markdown ** no ** As propriedades do arquivo ** diálogo. 


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

`` `
 seqüência de sereiaDiagrama 
Alice - >> Bob: Olá Bob, como vai você? 
Bob - >> John: E você John? 
Bob - x Alice: Estou bem, obrigado! 
Bob-x John: Estou bem, obrigado! 
Nota à direita de John: Bob pensa muito <br/> muito tempo, tanto <br/> que o texto <br/> não cabe em uma linha. Bob -> Alice: Checando com John ... Alice-> John: Sim ... John, como você está? `` `





E isso produzirá um fluxograma:

`` `
 Gráfico sereia LR 
A [Retângulo] - Texto do link -> B ((Círculo)) 
A -> C (Retângulo redondo) 
B -> D {Rhombus} 
C -> D` ``

<!--stackedit_data:
eyJoaXN0b3J5IjpbMzQ5MzkzNjE5XX0=
-->