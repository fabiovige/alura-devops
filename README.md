# Curso de Git

## comandos

### Como eu inicio um novo repositório git no meu projeto
```
$ git init
```

### Como eu seu que o git esta monitorando meu projeto
```
$ git status
```

### Como informar ao git o autor das alterações no projeto
```
$ git config --local user.name "Fabio Vige"
$ git config --local user.email "fabiovige@gmail.com"
```

### Como adicionar arquivos para que o git possa monitorá-los e serem salvas
```
$ git add .
$ git add <nome_do_arquivo>
```

### Como para de monitorar um arquivo
```
$ git rm --cached <nome_do_arquivo>
```

### Como salvar as modificações e arquivos no git
```
$ git commit -m "<mensagem_aqui>"
```

## Log
### Como utilizar o comando log
```
$ git log
```

### Como visualizar todos os commits onde cada um ocupa apenas uma linha
```
$ git log --oneline
```

### Como visualizar mais detalhes das alterações dos commits
```
$ git log -p
```

### Exibindo log formatado
```
Exibe somente os hash
$ git log --pretty="format:%H"

Exibe hash de forma resumida
$ git log --pretty="format:%h"

Exibe mensagem do commit
$ git log --pretty="format:%h %s"

Exibe e-mail do autor
$ git log --pretty="format:%h %s"

```

### Ignorando arquivos e diretórios com .gitignore
Adicione o arquivo .gitignore para que o git não monitores arquivos específicos

### Como enviar os dados para um servidor remoto
```
git push <para_onde> <de_onde>
```

### Como receber os dados de um servidor remoto
```
$ git pull <de_onde> <para_onde>
```

### Adicionando repositorio remoto do Github

```
$ git remote add <nome_repositorio> <endereço_repositorio>
$ git remote add origin git@github.com:usuario/repo.git
```