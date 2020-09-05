# primeiropjto
esse foi o primeiro projeto em GitHub
===================================================================
******RESUMO DOS RECURSOS DO GITHUB************
----------------------------------------------
#)-> Baixar o GitBach https://git-scm.com
#)-> [Inciar o Download]
#)-> Obs.: Observe que existe a opcao de
#)1 Baixar e instalar 32bits ou portable
#)-> [Next] .....
------------------------------------------
:~$ git version
gir version XXXX.windows.x
#)-> Configuracoes iniciais:
:~$ git config --global user.name "nome"
:~$ git config --global user.email "email"
:~$ git config user.name
:~$ git config user.email
#)-> Para verificar qual e' o editor padra'o:
:~$ git config core.editor
'C:\Users\...\VSCodium.exe' --wait
#)-> Procure o caminho do atalho.
#)-> Para configurar um editor:
:~$ git config --global core.editor "C:\Users\...<caminho_do_...
...atalho para o editor>.exe"
#)->Painel De Controle/Sistemas/Configuracoes de sistemas/
.../Variavel de Ambiente/Varia'vel do Sistema
<Nome>: <nome_do_editor_de_codigo>
<Valor>:"C:\Users\....\<editor.exe>
:~$ <nome_do_editor>
#)-> Ele abre o editor
:~$ pwd
:~$ cd /c
#)-> Para o diretorio C:
:~$ pwd
:~$ ls
#)-> No direto'rio C: crie uma pasta de projeto
ou em outro lugar que queira
:~$ mkdir <diretorio_criado>
:~$ ls
#)-> Diretorio criado
:~$ touch <direto_criado>/codigo.txt
#)-> Buscando no diretorio voce encontra codigo.txt
:~$ cd <diretorio_criado>/
:~$ ls
#)-> Verifique o diretorio de projeto e abra o GitBash nele
:~$ git init
#)-> Vai cria um arquivo .git
:~$ ls -a
:~$ git status
:~$ touch a.txt b.txt
:~$ ls
:~$ git status
Sem commits e sem add
:~$ git add a.txt b.txt
ou
:~$ git add *
:~$ git commit -m "comentario"
:~$ ls
:~$ git status
:~$ git log
Autor
Data
	Ultimo comentario
#)-> alteracoes
:~$ touch c.txt
:~$ git status
:~$ git add *
:~$ git status
:~$ git commit -m "Nova alteracao"
:~$ git status
:~$ git log
Listas os commits
#)-> Novas alteracoes
Exibe os commits de uma maneira mais simples
:~$ git log --oneline
==========================================================
* RASTREAR MUDAN�AS
* DESFAZER ALTERA��ES
* RECUPERAR VERSOES
AULA 4
---------------------------------------------------------
:~$ git log
commit jffnfjnkfjnsfnskfjn(HEAD -> master)
Author
Date
	Comentario
commit dfasf�fkjs�lfkjas�
Author
Date
	Comentario
:~$ git log --oneline
jffnfj (HEAD -> master)
dfasf�
:~$ git log --graph
*commit 
|
|
*commit
git log --oneline --graph
*commit
*commit
:~$ VSCodium .
#)-> Abre o editor no diretorio do projeto
#)-> Faco alguma alteracao
:~$ git status
fica em vermelho
:~$ git log
:~$ git commit -am "a.txt adcione uma linha"
#)-> Adicionou um arquivo ao mesmo tempo
em que criou um commit
:~$ git log --graph
:~$ git --oneline --graph
:~$ git branch
* master
#)-> Fazer nova alteração
:~$ git log --oneline
#)-> Fazendo rastreio das mudanças
*
*
*
:~$ git checkout jffnfj
#)-> O editor padrão do git retornou a versão anterior
... Assim eu posso fazer uma cópia.
:~$ git logo --oneline
jffnfj (HEAD) está no ponto onde eu direcionei
dfasf os arquivos anteriores
#)-> É necessário instalar o VSCodium no linux
e no Windows e colocar o GitHub como editor
padrão nele.
Veja como fica para o Linux que não possui 
instalação aparente.
:~$ git branch
* (HEAD detectado com jffnfj)
  master
:~$ git checkout master
#)-> O editor retorna automaticamente a ultima versão
:~$ git branch
#)-> Tudo normal
#) Desfazendo alterações
#)-> Vá para o editor; apague uma linha;
... coloque outra.
:~$ git diff
diff --
:~$ git status
Vai parecer arquivo que tem código modificados
:~$ git checkout a.txt
#)-> e obeserve que foi desfeito as alterações
:~$ git status
#)-> Fazer alteração
;^$ git diff
:~$ git status
:~$ git add a.txt
:~$ git status
:~$ git diff
#)-> para desfazer essa alteraçõa
:~$ git reset HEAD
:~$ git status
#)-> Observe que ele removel as alterações feitas
#)-> Elas não foram commitadas
:~$ git status
:~$ git diff
#)-> Vamos removendo o commit
:~$ git status
:~$ git commit -am "remover commit"
:~$ git log --oneline
#)-> Cria um novo node no grafico de commites
#)-> Removendo o commit e voltando a versao anterior
:~$ git reset --hard d302bab
                       ^
Esse é o hash de um node anterior
:~$ git log --oneline
#)-> Commit foi removido
...					   



