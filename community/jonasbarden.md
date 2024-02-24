Olá,

Me chamo Jonas Barden, atualmente atuo como coordenador de TI mas estou sempre em busca de novas experiências.
Estou melhorando meu portfólio estudando cada dia mais.

# Resumos Git Github

Alguns códigos necessários para o git que poderei ustilizar

## Comandos
- Criar readme -- readme.so
- comando para salvar alterações -- git add nome_do_arquivo
- comando para ver as alterações -- git status
- comando para enviar os arquivos -- git commit -m"dados_alteraos"
- arquivos ignorados -- echo > .gitignore
- comnado para enviar tudo -- git add .
- comando para restaurar -- git restore nome_do_arquivo
- comando para alterar nome do log -- git commit --amend
- comando todos logs -- git reflog
- Comando conectar remoto -- add remote origin URL
- comando subir arquivos -- git push -u origin master
- comando abrir o editor -- segurar o ponto e apertar em code
- comando para colocar gif -- tecla win + ponto
- comando para baixar remoto para local - git pull

## Branches
### Ela serve para que podemos alterar o projeto com uma ramificação do principal(main/master)

![image](https://github.com/jonasbarden/repo-local/assets/35454758/dd02c1e3-53cc-45bd-bc12-8a75e7f25e20)

### Quando utilizar ela vou alterando os códigos diferentes do principal, assim posso ter mais confiança e segurança no meu trablaho.

![image](https://github.com/jonasbarden/repo-local/assets/35454758/606a29f6-0384-4076-90ae-d8633d4fab07)

### Sempre que for codificar um novo, criar uma branch nova para mim, para depois commitar para a principal.

- Comando para criar uma nova branch -- git checkout -b nome_branch_secundaria

### Depois de codificar preciso enviar tudo para a banch principal.
 
 - comando para alterar para a pranch principal -- git checkout nome_branch_principal
 - comando para visualizar os commits de cada branch -- git branch -v
 - comando para enviar as alterações para a branch principal -- git merge nome_branch_secundaria
 - comando para listar as branch -- git branch
 - comando para  excluir a branch -- git branch -d nome_branch_secundaria