i = insert

esc = sai modo inserção

a = insere um caracter a frente

I = insere no começo da linha

A = insere no final da linha 

o = insere na linha de baixo

O = insere na linha acima

S = apaga a linha e insere

#salvar

:w = apenas salva

:wq = salva e sai do arquivo

:q = apenas sai

! = quando existe alguma alteração no documento

#atalhos

:x = salva e sai do arquivo

shift zz ou shift ZZ = salva e sai do arquivo

yy = copia a linha 

p = colar linha 

y(numero de linhas) = copia a quantidade de linhas

dd = recorta a linha

(numero de linha)dd = recorta a quantidade de linhas

ESC + v = ativa o modo visual e permite usar o cursor

#Modo visual

Selecione o texto com o cursos

y = copia
p = colar

crtl + v = copia verticalmente

yw = copia uma palavra
(numero de palavras)yw = copia numero de palavras

x = apaga um caracter (backspace) 
X = apaga um caracter (delete) 

:w NOVO_NOME = salva com novo nome

:split OUTRO_ARQUIVO = divide a tela em duas

CRTL WW = altera de tela

:r ARQUIVO = copia o conteudo do para ARQUIVO o arquivo atual

/palavra = busca palavra (cima para baixo)

n = proxima palavra da busca

?palavra = busca palavra (baixo para cima)

:%s/palavraantiga/palavranova = altera todas as palavras

:1,10 altera nestas linhas

:%s/palavraantiga/palavranova/g =  muda uma por linha

:e outroarquivo = sai do arquivo presente e vai para outro arquivo

#reconhecendo sintaxe
:syntax on or off = reconhece sintaxe

:set number = aparece os numeros das linhas

:set nonu

#abreviações
:ab pal palavraquevocequerabreviar

inserindo texto (clicar pal) palabrasquevocequerabreviar

:set ai = auto identação

:set noai = retira auto identação

:set ic = ignore case

:set noic = 

:set bg=dark or bg=light = background = dark ou light 

:set tabstop=4

:set showmatch = mostra onde esta fechando as experessoes (chave. colchete, parentes)

:.,$!sort = ordena a lista por ordem alfabetica

:.,$!sort pr -2t = ordena e divide em 2 colunas/tabelas

u = desfaz as alterações no arquivo

crtl r = refaz

#Opções ativas no VIM
vim ~/.vimrc

# Número de linhas
set number

# Cor de sintaxe
syntax on

# Correção de tabs
set shiftwidth=4
set expandtab
set softtabstop=4
set smarttab
set showcmd = mostra o ultimo comando digitado
set cursorline = destaca linha
set hlsearch = destaca palavra na pesquisa
set ignorecase = ignora maiuscula ou minuscula 

colorscheme blue = define cor 






























