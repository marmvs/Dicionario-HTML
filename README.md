# Dicionario HTML

<h1 class="code-line" data-line-start=1 data-line-end=2 ><a id="HTML_1"></a>HTML</h1>
<h4 class="code-line" data-line-start=3 data-line-end=4 ><a id="Tags_e_termos_usados_no_HTML_3"></a>Tags e termos usados no HTML.</h4>
<table class="table table-striped table-bordered">
<thead>
<tr>
<th>Elementos</th>
<th>Definição</th>
</tr>
</thead>
<tbody>
<tr>
<td>&lt;!DOCTYPE html&gt;</td>
<td>No HTML, o doctype é a introdução “&lt;!DOCTYPE html&gt;” encontrada no topo de todos os documentos. Seu único propósito é evitar que o browser mude para os chamados “quirks mode” quando renderizar um documento; isto é, o “&lt;!DOCTYPE html&gt;” doctype garante que o browser faça um esforço na tentativa de seguir as especificações relevantes, em vez de usar um modo de renderização diferente e que seja incompatível com algumas especificações.</td>
</tr>
<tr>
<td>&lt;html&gt;</td>
<td>O elemento HTML &lt;html&gt; (ou HTML root element) representa a raiz de um HTML ou XHTML documento. Todos os outros elementos devem ser descendentes desse elemento.</td>
</tr>
<tr>
<td>&lt;head&gt;</td>
<td>Elemento providencia informações gerais (metadados) sobre documento, incluindo seu título e links para scripts e folhas de estilos.</td>
</tr>
<tr>
<td>&lt;link&gt;</td>
<td>Especifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo.</td>
</tr>
<tr>
<td>&lt;meta&gt;</td>
<td>Define qualquer informação de metadados que não podem ser definidos por outros elementos HTML. (&lt;base&gt;, &lt;link&gt;, &lt;script&gt;, &lt;style&gt; ou &lt;title&gt;).</td>
</tr>
<tr>
<td>&lt;title&gt;</td>
<td>Elemento HTML Título define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas.</td>
</tr>
<tr>
<td>&lt;body&gt;</td>
<td>Representa o conteúdo de um documento HTML. É permitido apenas um &lt;body&gt; por documento.</td>
</tr>
<tr>
<td>&lt;header&gt;</td>
<td>Representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, sessões de cabeçalho, formulário de pesquisa, e outros.</td>
</tr>
<tr>
<td>&lt;h1&gt;</td>
<td>Os elementos HTML &lt;h1&gt;–&lt;h6&gt; representam seis níveis de título de sessão. &lt;h1&gt; é o nível de sessão mais alto e &lt;h6&gt; é o mais baixo.</td>
</tr>
<tr>
<td>&lt;nav&gt;</td>
<td>Representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.</td>
</tr>
<tr>
<td>&lt;a&gt;</td>
<td>O elemento HTML &lt;a&gt; (ou o Elemento Ancora HTML define uma hiperligação (hyperlink), o destino de uma hiperligação, ou ambos.</td>
</tr>
<tr>
<td>atributos da tag</td>
<td>São características que estamos adicionando à nossa tag. Sempre dentro da tag de abertura. Por exemplo a tag <code>a</code> tem o atributo <code>href</code>, então escrevemos assim: &lt;a href=”outrapagina.html”&gt;Olá mundo!&lt;/a&gt;</td>
</tr>
<tr>
<td>&lt;p&gt;</td>
<td>Tag para definir um parágrafo</td>
</tr>
<tr>
<td>&lt;button&gt;</td>
<td>Representa um botão clicável</td>
</tr>
<tr>
<td>div</td>
<td>É um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos(usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica(tal como article ou nav).</td>
</tr>
<tr>
<td>&lt;dl&gt; description list</td>
<td>Engloba uma lista de pares de termos e descrições. Um uso comum para este elemento é para implementar um glossário ou exibir metadados(uma lista de pares chave e valor)</td>
</tr>
<tr>
<td>&lt;dt&gt; description title</td>
<td>Identifica um termo na lista de definição. Este elemento pode ocorrer somente em um elemento filho de dl. Geralmente seguido por um elemento dd, ou multiplos dt na mesma linha indicam vários termos sendo definidos pelo próximo elemento.</td>
</tr>
<tr>
<td>&lt;dd&gt; define description</td>
<td>Fornece detalhes ou uma definição mais completa do termo precedente (definido por dt) numa lista de descrições (dl).</td>
</tr>
<tr>
<td>&lt;strong&gt;</td>
<td>Dá ao texto uma forte importância, e é tipicamente mostrado em negrito.</td>
</tr>
<tr>
<td>&lt;figure&gt;</td>
<td>Representa o conteúdo independente, frequentemente com uma legenda (figcaption), e é normalmente referido com uma única unidade. Enquanto ela está relacionada com o fluxo principal, sua posição independente do fluxo principal. Normalmente, isso é uma imagem, uma ilustração, um diagrama, um techo de código ou uma esquema que é referenciado no texto principal, mas que pode ser movido para outra página ou para um apêndice, sem afetar o fluxo principal.</td>
</tr>
<tr>
<td>&lt;img&gt;</td>
<td>Representa a inserção de imagem no documento, sendo implementado também pelo HTML 5 para uma melhor experiência com o elemento (&lt;figure&gt;) e(&lt;figcaption&gt;).</td>
</tr>
<tr>
<td>&lt;section&gt;</td>
<td>Representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.</td>
</tr>
<tr>
<td>&lt;input&gt;</td>
<td>É usado para criar controles interativos para formulários baseados na web para receber dados do usuário. A semântica de um input varia consideravelmente dependendo do valor de seu atributo <code>type</code>. Estudar os atributos que aparecer no curso.</td>
</tr>
<tr>
<td>type=search</td>
<td>Um campo de texto com uma só linha para digitar termos de busca; Quebras de linha são automaticamente removidas do valor entrado.</td>
</tr>
<tr>
<td>&lt;ul&gt;</td>
<td>Define uma lista desordenada.</td>
</tr>
<tr>
<td>&lt;li&gt;</td>
<td>Define os itens da lista.</td>
</tr>
<tr>
<td>&lt;sub&gt;</td>
<td>É utilizado para escrever um texto com letras menores e com o alinhamento abaixo das que do resto do conteúdo.</td>
</tr>
<tr>
<td>&lt;sup&gt;</td>
<td>É utilizado para escrever um texto com letras menores e com o alinhamento acima das que do resto do conteúdo</td>
</tr>
<tr>
<td>&lt;table&gt;</td>
<td>Define uma tabela</td>
</tr>
<tr>
<td>&lt;td&gt;</td>
<td>Define uma célula da tabela</td>
</tr>
<tr>
<td>&lt;th&gt;</td>
<td>Define o cabeçalho da tabela</td>
</tr>
<tr>
<td>&lt;tr&gt;</td>
<td>Define uma linha da tabela</td>
</tr>
<tr>
<td>&lt;b&gt;</td>
<td>Deixar o texto em negrito</td>
</tr>
<tr>
<td>&lt;i&gt;</td>
<td>Deixar o texto em itálico</td>
</tr>
<tr>
<td>&lt;mark&gt;</td>
<td>Para destacar o texto</td>
</tr>
<tr>
<td>&lt;small&gt;</td>
<td>É utilizado para reduzir o tamanho da fonte num intervalo definido de um texto.</td>
</tr>
<tr>
<td>&lt;align&gt;</td>
<td>Éé o alinhamento da imagem, que pode ser ainda top (topo), middle (meio), bottom (alinha a imagem com a base dos outros elementos da linha), left (à esquerda) ou right (à direita)</td>
</tr>
<tr>
<td>src</td>
<td>sinaliza a URL da imagem.</td>
</tr>
<tr>
<td>Google Analytics</td>
<td>[plugins/googleanalytics/README.md][PlGa]</td>
</tr>
<tr>
<td>Google Analytics</td>
<td>[plugins/googleanalytics/README.md][PlGa]</td>
</tr>
</tbody>
</table>
