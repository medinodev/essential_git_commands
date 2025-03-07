# Comandos GIT

Relembrando os comando utilizados no GIT

- Add commit sem passar pelo "git add"

```
git commit -a -m "Seu comentário de commit"
```

- Ver as configurações 
```
git config --list
```

```
git status (Status completo)

$ git status -s (Status curto)
 M README                (arquivo modificado)
 MM Rakefile             (arquivo modificado > stage > modificado)
 A  lib/git.rb           (arquivo stage)
 M  lib/simplegit.rb     (arquivo modificado)
 ?? LICENSE.txt          (arquivo não rastreado)
```

- Criando arquivos gitignore

