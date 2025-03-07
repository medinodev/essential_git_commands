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

cat .gitignore
 *.[oa]
 *~

- ignorar arquivos com extensão .a
 *.a
- mas rastrear o arquivo lib.a, mesmo que você esteja ignorando os arquivos .a acima
 !lib.a
- ignorar o arquivo TODO apenas no diretório atual, mas não em subdir/TODO
 /TODO
- ignorar todos os arquivos no diretório build/
 build/
- ignorar doc/notes.txt, mas não doc/server/arch.txt
 doc/*.txt
- ignorar todos os arquivos .pdf no diretório doc/
 doc/**/*.pdf

- Saber exatamente as alterações que foram realizadas
(O que você alterou mas ainda não mandou para o stage (estado preparado)? E o que está no stage, pronto para o commit? )

```
git diff
```

- Se você quiser ver as alterações que você mandou para o stage e que entrarão no seu próximo commit

```
git diff --staged
```



