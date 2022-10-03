# git-comandos

## Lista com alguns comandos para controlar no GIT:

<strong>git status</strong> >> Mostra o status atual dos arquivos<br>
<strong>git add nome-arquivo</strong> >> Adiciona todos os arquivos listados ao commit<br>
<strong>git commit -m "Meu primeiro commit"</strong> >> Criação de um commit<br>
<strong>git add .</strong> >> Adiciona todos os arquivos listados ao commit<br>
<strong>git commit -a</strong> >> Commita tudo que tiver<br>
<strong>git commit -am "Mensagem"</strong> >> Atalho para commitar um arquivo modificado, sem usar o "git add"<br>
<strong>git log -p</strong> >> Mostra as alterações que ocorreram nos arquivos<br>
<strong>git log -p -2</strong> >> Mostra as alterações que ocorreram nos últimos 2 arquivos (Podemos alterar o número conforme a necessidade)<br>
<strong>git log --stat</strong> >> Mostra as estatísticas das últimas alterações<br>
<strong>git log --oneline</strong> >> Log de 1 linha<br>
<strong>git log --pretty=oneline</strong> >> Mostra os logs de maneira mais amigável<br>
<strong>git log --pretty=format:"%h - %an, %ar : %s"</strong> >> Lista os comitts com suas respectivas datas<br>
<strong>git log --since=2.days ou git log --since=2021-01-22</strong> >> Commits feitos a partir do momento informado<br>
<strong>git log --until=2022-09-18</strong> >> Commits feitos até o momento informado<br>
<strong>git log --author=Davi</strong> >> Commits feitos por esse autor (Útil para projetos com mais de 1 dev) (editado)<br>
<strong>git log --grep="palavra-chave"</strong> >> Busca commits que tenham a palavra-chave informada<br>
<strong>git restore --staged teste2.txt</strong> >> Retorna o arquivo para o estágio anterior<br>
<strong>git restore nome_do_arquivo.txt</strong> >> Restaura o arquivo para o último estado<br>
<strong>git checkout</strong> >> Restaura a versão do último commit realizado<br>
<strong>git checkout -b Funcionalidade1</strong> >> Cria um novo branch com o nome de Funcionalidade1<br>
<strong>git checkout 'nomeDaBranch'</strong> >> Retorna para a branch informada<br>
<strong>git branch</strong> >> Lista os branchs existentes<br>
<strong>git merge Funcionalidade1</strong> >> Realiza um merge entre a branch atual e a branch Funcionalidade1<br>
<strong>git rebase Funcionalidade1</strong> >> Organiza os commits em ordem linear, trazendo os commits para o branch atual<br>
<strong>git diff</strong> >> Compara o que tem no working directory com o que tem no repositório<br>
<strong>git diff --staged</strong> >> Compara o que tem no stage area com o repositório<br>
<strong>git diff --color-words</strong> >> Mostra as palavras que foram alteradas<br>
<strong>git mv nome-do-arquivo outro-nome-do-arquivo</strong> >> Altera o nome do arquivo e prepara para o commit<br>
<strong>git push --force-with-lease origin master</strong> >> 
