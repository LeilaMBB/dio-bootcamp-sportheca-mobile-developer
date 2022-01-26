# Anotações úteis para utilização do Git e GitHub

## Links úteis

- Git download - [Git - Downloads (git-scm.com)](https://git-scm.com/downloads)

- Acesso GitHub - https://github.com

- Editor Markdown TYPORA - [Typora download (softonic.com.br)](https://typora.softonic.com.br/download)

- Guia Markdown - https://www.markdownguide.org/basic-syntax

  ​

## Informações importantes

Algoritmo de encriptação dos arquivos: SHA1 (Secure Hash Algorithm)

Objetos internos do Git: Blobs, Trees, Commits - contêm metadados

Para alterar cores do Git Bash - clicar na barra branca com o botão direito e escolher Options, looks  e escolher o tema.

Para configurar Chaves SSH e Tokens - no GitHub, clicar na imagem do usuário e depois em Settings / SSH & GPG Keys / New SSH keys. No Git Bash: ssh -keygen -t ed25519 -C <email>



## Comandos úteis - via Terminal

git init

git add <nome do arquivo>

git add *

git add .

git status

git commit -m "<descrição>"

git config --global <nome propriedade a ser alterada> "<novo valor>"  

git restore --staged <nome do arquivo>   - "para retirar arquivo da área de stage"

git config --list  - "exibe configuração do reposiório local"

git remote add origin <endereço do repositório>

git remote -v   - "lista respositório"

git push origin main - "empurra arquivos do repositório local para o remoto"

git pull origin main - "traz arquivos do repositório remoto para o local"

git clone <endereço do repositório remoto - https ou ssh>