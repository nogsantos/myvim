# Vim

## Plugins

#### Gerenciador de plugins 

[vim-pathogen](https://github.com/tpope/vim-pathogen) 

#### Eplorer

[NerdTree](https://github.com/scrooloose/nerdtree)

##### Comandos

- `:NERDtree` Abre o explorer
- `seleciona o arquivo + s` abre o arquivo em split
- `ctrl + w + [h, l, j, k]` Navega entre os arquivos abertos 

## Modos

### Visual

Tecla | descrição
------|----------
:v | Seleção por character
:shift + v| seleção por linha
:ctrl + v | Seleção por coluna

#### Copiar e colar

Tecla | descrição
------|----------
y | Copia o texto selecionado
x | Recorta todo o texto selecionado
p | cola o texto copiado

#### Editar texto selecionado

Tecla | descrição
------|----------
o | Transforma todo o texto selecionado para minúsculo

### Inserção

Tecla | descrição
------|----------
:i | iniciar modo de inserção 
:o | abre modo de edição na linha de baixo respeitando a identação
:u | desfaz a última ação

### Comandos

Iniciar modo de comando `esc + :`

Comando | Descrição
------|----------
:q | Fechar
:w | Salvar
:wq | Salvar e fechar
:e! | Desfazer alterações

## Navegação

Tecla | Combinação | Descrição
------|------------|----------
:k | [num] + k | sobre o cursor uma linha ou n linhas
:j | [num] + j | desce o cursor uma ou n linhas
:j | [num] + l | na linha, avança o cursor para a esquerda uma coluna ou n colunas
:h | [num] + h | na linha, retorna o cursor para a direita uma coluna ou n colunas
gg| Vai para o início do arquivo
shift + g | vai para o final do arquivo

## Split da tela

- :vs + [caminho e nome do arquivo] - vertical
- :sp + [caminho e nome do arquivo] - horizontal

Navegação: `:ctrl + ww`

## Busca

esc + /[termo] para confirmar <enter>

#### Navegação entre os termos

- `n` para avançar
- `shift + n` para voltar

## Replace

:%s /[nome do termo]/[temo de substituição]/gc
