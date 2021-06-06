# VS Code

A Microsoft lançou em 2015 um editor de código destinado ao desenvolvimento de aplicações web chamado **Visual Studio Code** (daqui em diante, apenas **VSCode**).

Trata-se de uma ferramenta leve e multiplataforma que esta disponível para Windows, Mac OS e Linux, sendo executada nativamente em cada plataforma.

O VSCode atende a uma quantidade enorme de projetos (ASP .NET, Node.js) e oferece suporte para mais de 30 linguagens de programação, como JavaScript, C#, C++, PHP, Java, HTML, R, CSS, SQL, Markdown, TypeScript, LESS, SASS, JSON, XML e Python, assim como muitos outros formatos de arquivos comuns.

Ele é gratuito e open source, com seu código disponibilizado no GitHub, e isso permite que você contribua com seu desenvolvimento.

#### Download
Você pode baixar a versão correspondente do VSCode para a sua plataforma neste link : https://code.visualstudio.com/download.

A seguir, um resumo dos principais recursos desta ferramenta (retirada de https://www.visualstudio.com/pt-br/products/code-vs.aspx):

 - Edição focalizada em código: Um editor leve de primeira classe, com gestos centralizados no teclado, significa que você nunca precisa alcançar o mouse. Abra arquivos grandes ou pequenos instantaneamente no seu código sem distrações. Aproveite os recursos de edição avançados, tais como cursores múltiplos, salvamento automático e muito mais.
 - Navegação de código: Permaneça no contexto enquanto você se move através de grandes arquivos de código e através da sua base de código. A barra de rolagem aprimorada realça os problemas no arquivo atual, a localização integrada suporta expressões regulares. Estrutura de tópicos de código, navegação e definição de inspeção o ajudam a obter onde você precisa para ser rápido.
 - Compreensão de código: O IntelliSense descreve as APIs enquanto você digita, com preenchimento automático para aumentar a velocidade e a precisão. As ferramentas de informações rápidas permitem que você inspecione definições de API, e os “rabiscos” informam sobre problemas enquanto você digita.
 Depuração: Diagnostique problemas em seu aplicativo com as ferramentas de depuração integradas para Node.js, TypeScript e JavaScript. Defina pontos de interrupção no seu código, interrompa exceções, inspecione variáveis, percorra o seu código, navegue pela pilha de chamadas – e conecte-se aos processos locais em execução.
- Controle de versão do Git: Adote fluxos de trabalho modernos com o poder e a flexibilidade do Git. Veja arquivos alterados, compare e faça confirmações direto do editor. Conecte-se ao o universo Git inteiro extraindo e enviando código para qualquer editor remoto – GitHub, Azure Web Apps, Visual Studio Team Services e muito mais.
- ASP.NET 5 e Node.js: O VSCode suporta o fluxo de trabalho de desenvolvimento de ponta a ponta para aplicativos em ASP.NET 5 e Node.js, IntelliSense completo, suporte para depuração e muito mais – em todos os sistemas operacionais compatíveis, incluindo muitos dos seus frameworks favoritos como D3, JQuery, Express, Angular, grunt, gulp e muito mais.

#### Trip

Dica: Um site muito legal contendo diversas extensões para o VSCode pode ser acessado aqui: https://marketplace.visualstudio.com/.

## Usando o Visual Studio Code

O VSCode é um editor de código e adota uma interface de usuário comum com um leiaute de um explorador à esquerda, exibindo todos os arquivos e pastas a que você tem acesso, e um editor à direita, mostrando o conteúdo dos arquivos que você abriu.

Em seu layot, a interface do usuário está dividida em quatro áreas:

1. Editor – a área principal para editar seus arquivos. Você pode abrir até três editores lado a lado;
Barra lateral – contém diferentes visões, como o Explorer, para ajudá-lo enquanto você trabalha em seu projeto;
2. Barra de status – Indica informações sobre o projeto aberto e os arquivos que você editar;
Barra de visão – permite alternar entre visões e lhe dá indicadores de contexto específico adicionais, como o número de alterações de saída quando Git está habilitado;
Após baixar e instalar o VSCode, a sua primeira execução vai apresentar a seguinte visão:

– À esquerda, temos uma barra de ferramentas com as seguintes opções :

- Explore – exibe e oculta os arquivos abertos;
- Search – realiza buscas nos arquivos;
- Git – permite realizar commits para o repositório do projeto;
- Debug – permite a depuração;

Cada vez que iniciar o VSCode, ele vai abrir no estado em que estava quando da última vez que você o fechou. A pasta, o layout e os arquivos abertos são preservados.

Em vez de colocar os arquivos em guias separadas, o VSCode permite até três editores visíveis a qualquer momento, permitindo-lhe colocar até três arquivos juntos lado a lado.

Isso ajuda a reduzir a sobrecarga de guias, mas não restringe o número de arquivos com os quais você pode trabalhar. A exibição do Explorer mantém uma lista de arquivos de trabalho, permitindo-lhe acesso rápido aos arquivos que você precisa.

Para abrir mais de um editor você pode usar as seguintes opções:

Ctrl (Mac: ‘Cmd’) e clicar em um arquivo no Explorer
 Ctrl+\  para dividir o editor ativo em dois

Opção Open to the Side: a partir do menu de contexto do Explorer

### Explorer

O Explorer é usado para procurar, abrir e gerenciar todos os arquivos e pastas em seu projeto. Depois de abrir uma pasta no VSCode, o conteúdo da pasta é mostrado no Explorer. Você pode fazer muitas coisas, como:

- criar, excluir e renomear arquivos e pastas
- mover arquivos e pastas com arrastar e soltar
- usar o menu de contexto para explorar todas as opções
- Working Files (Arquivos de trabalho)

No topo do Explorer, existe uma seção chamada WORKING FILES que exibe uma lista de arquivos ativos que são arquivos anteriormente abertos no VSCode. Por exemplo, um arquivo será listado na seção de arquivos de trabalho, se você:

- Fizer uma alteração em um arquivo
- Clicar duas vezes em um arquivo no Explorador
- Abrir um arquivo que não faz parte da pasta atual

### Configurando o editor

O VSCode lhe dá muitas opções para configurar o editor. Você pode definir opções globalmente através de configurações de usuário ou por projeto/pasta através de configurações de espaço de trabalho. Os valores de configurações são mantidos em um arquivo de settings.json.

Selecione Files->Preferences->User Settings (ou pressione F1, digite user e trecla Enter) para editar o arquivo settings.json do usuário.
Selecione Files->Preferences->Workspace Settings (ou pressione F1, digite worksp e tecle Enter) para editar o arquivo settings.json do worksapce.
Você verá as configurações padrão de VSCode na janela à esquerda e seu arquivo settings.json editável à direita. Você pode facilmente analisar e copiar as configurações a partir da configurações padrão.

Depois de editar as configurações, digite Ctrl+S para salvar as alterações. As alterações entrarão em vigor imediatamente.

Save/Auto Save
Por padrão, o VSCode requer uma ação explícita para salvar suas alterações em disco, uma telas é teclar Ctrl+S.

No entanto, é fácil habilitar o Auto Save, que vai salvar as alterações após um atraso configurado ou quando o foco deixar o editor. Com essa opção ativada, não há nenhuma necessidade explicita de salvar o arquivo.

Para configurar o Auto Save, abra User Settings ou Workspace Settings e encontre as configurações associadas:

files.autoSave pode ter os valores:

 off – para desativar o auto save
afterDelay – para salvar arquivos após um atraso
onFocusChange – configurado para salvar os arquivos quando o foco se move para fora do editor do arquivo
files.autoSaveDelay configura o atraso em milissegundos quando files.autoSave está configurado para afterDelay.

### Pesquisar em todos os arquivos

O VSCode lhe permite procurar rapidamente sobre todos os arquivos na pasta atualmente aberta. Basta digitar Ctrl+Shift+F e a sua pesquisa.

Os resultados da pesquisa são agrupados em arquivos que contêm o termo de pesquisa, com a indicação dos acessos em cada arquivo e sua localização.

Expanda um arquivo para ver uma visualização de todos os hits dentro desse arquivo. Em seguida, dê um clique único em um dos acessos para visualizá-lo no editor.

Você pode configurar opções avançadas de Procura teclando Ctrl+Shift+J.

### Navegação rápida de arquivos

O Explorer é ótimo para navegar entre os arquivos quando você está explorando um projeto. No entanto, quando você está trabalhando em um projeto, vai estar rapidamente saltando entre o mesmo conjunto de arquivos. O VSCode fornece dois comandos poderosos para navegar em e através de arquivos com teclas de fácil utilização.

Segure Ctrl e pressione Tab para ver uma lista de todos os arquivos que foram abertos desde que o VSCode foi iniciado.

Para abrir um desses arquivos, use Tab novamente para escolher o arquivo que você deseja navegar, em seguida, solte a tecla Ctrl para abri-lo.

### Iniciando a partir da linha de comando

Você pode iniciar o VSCode a partir da linha de comando para abrir rapidamente um arquivo, pasta ou projeto.

Normalmente, você abre o VSCode dentro do contexto de uma pasta. A melhor forma de fazer isso é digitar