# Comandos, atalhos e configurações do VIM

`:w NOVO_NOME` = salva com novo nome

`:r ARQUIVO` = copia o conteudo do para ARQUIVO o arquivo atual

`:e outroarquivo` = sai do arquivo presente e vai para outro arquivo

### Comandos de edição

`i` = insert

`esc` sai modo inserção

`yy` = copia a linha

`y(numero de linhas)` = copia a quantidade de linhas

`p` = colar linha 

`dd` = recorta a linha

`(numero de linha)dd` = recorta a quantidade de linhas

`/palavra` = busca palavra (cima para baixo)

`/\cpalavra` = busca palavra eliminando o case sensitive (cima para baixo)

`?palavra` = busca palavra (baixo para cima)

`n` = proxima palavra da busca

`:split OUTRO_ARQUIVO` = divide a tela em duas

`CRTL WW` = altera de tela

`:%s/palavraantiga/palavranova` = altera todas as palavras

`:%s/palavraantiga/palavranova/g` =  muda uma por linha

`u` = desfaz as alterações no arquivo

`crtl r` = refaz

#### Atalhos

`a` = insere um caracter a frente

`I` = insere no começo da linha

`A` = insere no final da linha 

`o` = insere na linha de baixo

`O` = insere na linha acima

`yw` = copia uma palavra

`(numero de palavras)yw` = copia numero de palavras

`S` = apaga a linha e insere

`x` = apaga um caracter (backspace) 

`X` = apaga um caracter (delete) 

### Salvar

`:w` = apenas salva

`:wq` = salva e sai do arquivo

`:x` = salva e sai do arquivo

`:q` = apenas sai

`!` = quando existe alguma alteração no documento

#### Atalhos

`shift zz` ou `shift ZZ` = salva e sai do arquivo

### Modo Visual

`ESC + v` = ativa o modo visual e permite usar o cursor

`y` = copia

`p` = colar

`crtl + v` = copia verticalmente

### Formato do VIM (.vimrc)
As alterações são feitas no arquivo .vimrc `vim ~/.vimrc`

`:ab pal palavraquevocequerabreviar` = abreviar palavras para uma menor - inserindo texto (clicar pal) palabrasquevocequerabreviar

`:syntax on or off` = reconhece sintaxe

`:set number` = aparece os numeros das linhas

`:set nonu` = retira numeros

`:set ai` = auto identação

`:set noai` = retira auto identação

`:set ic` = ignore case

`:set noic` = retira ignore case 

`:set bg=dark` or `bg=light` == `background=dark` ou `background=light` = altera cor do background 

`:set tabstop=4` = aumenta o espaço do tab para 4

`:set showmatch` = mostra onde esta fechando as experessoes (chave. colchete, parentes)

`:.,$!sort `= ordena a lista por ordem alfabetica

`:.,$!sort pr -2t` = ordena e divide em 2 colunas/tabelas

`syntax on` = permite ativar a sintaxe

`set shiftwidth` = 4

`set expandtab`

`set softtabstop` = 4

`set smarttab`

`set showcmd` = mostra o ultimo comando digitado

`set cursorline` = destaca linha

`set hlsearch` = destaca palavra na pesquisa

`set ignorecase` = ignora maiuscula ou minuscula 

`colorscheme blue` = define cor 

`:!"comando linux"` = executa o comando e volta para o doc

`:r!"comando linux"` = copia a saida do comando e retorna para o doc

`:r!pwd` =  copia o caminho da execução

### Matematica no VIM 

`-l` retonar os numeros reais em divisoes (4/10=0 com -l 0.4000)

`:r !bc -l <<< operação matematica` = função calculadora


### Upando

`https://github.com/paulojp-dev/my-vim`
