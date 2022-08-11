# Instalação e Configuração do Visual Studio Code
## 1. Instalando o VSCode:
### 1.1. Apresentação do Curso
### 1.2. Instalação
- Em **Selecionar Tarefas Adicionais** marcar *Adicione em PATH(disponível após reiniciar)*

## 2. Recursos Básicos
### 2.1 Recursos Básicos

A página inicial de *Welcome* tem os seguintes items de acesso rápido: 
- **Start:** 
	 New file , Open folder , clone repository
- **Recent:** Ficam seus arquivos recentemente usados.
- **Help:** Mais auxílios para usar o VSCode, como dicas e truques(Tips and Tricks), os fóruns do Stack Overflow e videos introdutórios(Introductory videos).


Abas: 

   **EXPLORADOR:** 
   - O **Open Editors** exibe os arquivos abertos no momento, ajuda em casos em que há muitas pastas abertas para poder navegar por elas e localizar o que você procura.
   - Na segunda parte do explorador, após os botões de criar arquivo e pasta tem um botão para atualizar o explorador. 

   **SEARCH:**
   - Para pesquisas de palavras-chave dentro dos seus arquivos.
   - Para substituir palavras pesquisadas dentro dos seus arquivos com o *replace*.

   **SOURCE CONTROL:** 
   - Trata-se de uma integração com o GitHub a partir de botões para inicializar repositórios(o *Initialize Repository*) e para publicar, fazer um push para o GitHub(o *Publish to Github*)
   
   **RUN AND DEBUG:**
   - Para debugar e rodar alguns programas, mais voltado para códigos usados no Terminal.


Configurações(*Settings*):(Fica em File => Preferences)

- *Editor: Font Size* = Aumenta e diminue o tamanho da fonte do texto no Editor.
- *Editor: Tab Size* = Para pre-determinar o tamanho do espaço que a tecla *Tab* imprimirá quando acionada. (Necessário que feche-se o arquivo e abra-o de novo para que as mudanças realizadas tenham efeito).
- O tamanho usado em *Tab* será avisado pelos colaboradores do projeto que você faça parte.
- *Files: Auto Save* = Para salvar sozinho. Opções: desligado, salvar depois de um tempo, salvar quando mudar o foco dentro do Editor, salvar quando mudar de janela.
- *Editor: Font Family* = As fontes que você quer usar.
- *Editor: Cursor Style* = Para mudar o tipo, pode ser por exemplo do tipo *underline*.
- *Editor: Multi Cursor Modifier* = Faz com que ao clicar a tecla *ALT* eu possa selecionar simultaneamente várias linhas, clicando e escolhendo quais delas, e editá-las ao mesmo tempo.
- *Editor: Word Wrap* = Ativa a quebra de linha com a opção *Editor: Word Wrap* configurada.
- *Editor: Word Wrap Column* = Cada espaço no Editor representa uma coluna, assim como acontece com as linhas, então com essa opção é possível configurar quantas linhas serão escritas até a quebra de linha automática, precisa estar conectada à opção *Editor: Word Wrap*.
- Em Settings é possivel usar a barra de buscas para encontrar a configuração desejada.


Alguns comandos: 
- Para procurar por arquivos(digite o nome e ENTER e ele abrirá no Editor): *CTRL + p*
- Para procurar por comandos(do VSCode e de extensões instaladas, ao selecioná-los e ENTER insere o comando no Editor, mostra também atalhos associados a eles, é possível configurar estes): *CTRL + Shift + p*.
- Para ver todos os possíveis atalhos para teclado(*Keyboard Shortcuts*): *CTRL+k*, *CTRL + s* e File => Preferences => Keyboard Shortcuts
- No x de fechar cada arquivo aparece uma bolinha preenchida se você ainda não salvou o arquivo.

EMMET:(Atalhos para estruturas de código - aumento de produtividade)

- **html:5** (cria o esqueleto de um documento HTML5), depois pressionando *Tab* é possível navegar pelas palavras selecionadas para edição mais rápida.
- **div2** (cria 2 *divs*)
- **div>p>a** (cria uma *div* com um *p* dentro e um *a* dentro do parágrafo. Para criar estruturas aninhadas automaticamente)
- **div>h1+p** (*div* com um *p* dentro e um *h1* e *p* de mesmo nível)
- **p{Conteúdo}** (p com conteúdo Conteúdo)
- **nav.menu>ul>li * 5>a:link** (Um *nav* com uma *class* menu com uma *ul* com 5 *li* dentro, dentro de cada *a* com *href*)
- Para voltar atrás o *CTRL + Z*
- **nav.menu>ul>li#item$ * 5>a** (o mesmo exemplo acima mas acrescentando um id para cada *li* numa iteração, ou seja, item1, item2, item3...)
- **section * 5#secao$>article.conteudo>h1+p{Texto}|c** (5 seções com o *id* seção e a iteração, e em seguida dentro de cada uma dessas seções, um *article* com a *class* conteudo e dentro de cada um desses um *h1* com um *p* com o conteúdo Texto e + um comment filter |c que acrescenta um comentário a cada fim de *section* e começo delas com a numeração da iteração).



