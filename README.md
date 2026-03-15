# compilation-commands-vim

> 🇧🇷 [Português](#português) | 🇺🇸 [English](#english)

![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## Português

Compilado completo de comandos e modos do Vi/Vim para o dia a dia de DevOps e SRE.

### Modos de Inserção

| Comando | Descrição |
|---------|-----------|
| `o` | Entra no modo inserção na linha abaixo |
| `O` | Entra no modo inserção na linha acima |
| `i` | Inserir na posição do cursor |
| `I` | Inserir no início da linha atual |
| `a` | Modo inserção um caractere à frente do cursor |
| `A` | Modo inserção no final da linha |
| `ESC` | Retorna ao modo comando |

### Salvar e Sair

| Comando | Descrição |
|---------|-----------|
| `:w` | Salvar |
| `:q` | Sair |
| `:qa` | Sair de todos os arquivos abertos |
| `:q!` | Sair forçando sem salvar |
| `:wq` | Salvar e sair |
| `:x` | Salvar e sair (igual ao `:wq`) |
| `ZZ` | Sair e salvar |
| `ZQ` | Sair sem salvar |

### Copiar, Colar e Recortar

| Comando | Descrição |
|---------|-----------|
| `yy` | Copia a linha inteira |
| `y8y` | Copia 8 linhas |
| `p` | Cola na linha abaixo |
| `P` | Cola na linha acima |
| `dd` | Apaga/recorta a linha inteira |
| `d8d` | Apaga 8 linhas |
| `dw` | Apaga uma palavra |
| `dG` | Apaga do cursor até o final do arquivo |
| `dgg` | Apaga do cursor até o início do arquivo |
| `cw` | Recorta uma palavra |
| `yw` | Copia uma palavra |
| `x` | Apaga um caractere (Delete) |
| `X` | Apaga um caractere antes do cursor (Backspace) |
| `r` | Substitui o caractere atual |

### Modo Visual

| Comando | Descrição |
|---------|-----------|
| `v` | Modo visual (seleciona trecho) |
| `CTRL+v` | Visual block (seleciona bloco em linha reta) |
| `V` | Visual line (seleciona linhas) |

### Desfazer e Refazer

| Comando | Descrição |
|---------|-----------|
| `u` | Desfazer (CTRL+Z) |
| `CTRL+r` | Refazer (CTRL+SHIFT+Z) |

### Busca e Navegação

| Comando | Descrição |
|---------|-----------|
| `/<palavra>` | Busca descendo no arquivo |
| `?<palavra>` | Busca subindo no arquivo |
| `n` | Próximo resultado (descendo) |
| `N` | Próximo resultado (subindo) |
| `gg` | Vai para a primeira linha |
| `G` | Vai para a última linha |
| `M` | Vai para o meio da tela |
| `H` | Vai para o topo da tela |
| `L` | Vai para o final da tela |

### Substituição

| Comando | Descrição |
|---------|-----------|
| `:<linha>s/antigo/novo` | Substitui na linha especificada |
| `:%s/antigo/novo` | Substitui a primeira ocorrência por linha |
| `:%s/antigo/novo/g` | Substitui todas as ocorrências no arquivo |

### Comandos set

| Comando | Descrição |
|---------|-----------|
| `:set number` | Numera as linhas |
| `:set hlsearch` | Habilita highlight nas buscas |
| `:set tabstop=4` | Define tamanho do TAB |
| `:set expandtab` | Converte TAB em espaços |
| `:set bg=dark` | Muda esquema de cor |
| `:split <arquivo>` | Divide a tela horizontalmente |
| `:vsplit <arquivo>` | Divide a tela verticalmente |
| `:! <comando>` | Executa comando no shell |

---

## English

Complete reference of Vi/Vim commands and modes for daily DevOps and SRE use.

### Insert Modes

| Command | Description |
|---------|-------------|
| `o` | Enter insert mode on the line below |
| `O` | Enter insert mode on the line above |
| `i` | Insert at cursor position |
| `I` | Insert at the beginning of the line |
| `a` | Insert one character ahead of the cursor |
| `A` | Insert at the end of the line |
| `ESC` | Return to command mode |

### Save and Quit

| Command | Description |
|---------|-------------|
| `:w` | Save |
| `:q` | Quit |
| `:qa` | Quit all open files |
| `:q!` | Force quit without saving |
| `:wq` | Save and quit |
| `:x` | Save and quit (same as `:wq`) |
| `ZZ` | Save and quit |
| `ZQ` | Quit without saving |

### Copy, Paste and Cut

| Command | Description |
|---------|-------------|
| `yy` | Copy entire line |
| `y8y` | Copy 8 lines |
| `p` | Paste below |
| `P` | Paste above |
| `dd` | Delete/cut entire line |
| `d8d` | Delete 8 lines |
| `dw` | Delete a word |
| `dG` | Delete from cursor to end of file |
| `dgg` | Delete from cursor to beginning of file |
| `cw` | Cut a word |
| `yw` | Copy a word |
| `x` | Delete character (Delete key) |
| `X` | Delete character before cursor (Backspace) |
| `r` | Replace current character |

### Visual Mode

| Command | Description |
|---------|-------------|
| `v` | Visual mode (select text) |
| `CTRL+v` | Visual block (column selection) |
| `V` | Visual line (select lines) |

### Undo and Redo

| Command | Description |
|---------|-------------|
| `u` | Undo (CTRL+Z) |
| `CTRL+r` | Redo (CTRL+SHIFT+Z) |

### Search and Navigation

| Command | Description |
|---------|-------------|
| `/<word>` | Search forward |
| `?<word>` | Search backward |
| `n` | Next match (forward) |
| `N` | Next match (backward) |
| `gg` | Go to first line |
| `G` | Go to last line |
| `M` | Go to middle of screen |
| `H` | Go to top of screen |
| `L` | Go to bottom of screen |

### Substitution

| Command | Description |
|---------|-------------|
| `:<line>s/old/new` | Replace on specified line |
| `:%s/old/new` | Replace first occurrence per line |
| `:%s/old/new/g` | Replace all occurrences in file |

### Set Commands

| Command | Description |
|---------|-------------|
| `:set number` | Show line numbers |
| `:set hlsearch` | Highlight search results |
| `:set tabstop=4` | Set tab size |
| `:set expandtab` | Convert tabs to spaces |
| `:set bg=dark` | Change color scheme |
| `:split <file>` | Split screen horizontally |
| `:vsplit <file>` | Split screen vertically |
| `:! <command>` | Execute shell command |
