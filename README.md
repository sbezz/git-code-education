# Instala��o OK
# Comando:
# mkdir aulagit (criar diret�rio)
# cd aulagit (acessar diret�rio)
# git init (inicializar a pasta)
# � criado um diret�rio .git/ (diret�rio oculto)
# Para visualizar comando -> ls �la
# Este diret�rio .git/ � o diret�rio respons�vel pelo controle de vers�o.
# touch � Comando usado para criar arquivos.
# Comando:
# touch arquivo.txt 
# Editar o arquivo
# git status (verificar status do controle).

# Est�gios do commit.

# 1� Est�gio � Arquivos n�o untracked (sem controle de vers�o).
# 2� Est�gio � Comando: git add nomedoarquivo
	O arquivo fica pronto para o controle de vers�o ap�s commit.
# 3� Est�gio � Comando: git commit �m �meu Primeiro commit�
	Agora o arquivo esta fazendo parte do controle de vers�o.
	Comando: git log (apresenta o log)

# Comando: 
# git commit � ir� abrir um arquivo de texto para descrever todas as altera��es efetuadas nos arquivos.
# git add . � Ir� adicionar todos os arquivos alterados.
# git commit -a �m �commitando arquivos�
# 	-a insere os arquivos para commitar

# Comandos Git log:
# *para sair da visualiza��o �q�
# git log -p � mostra as diferen�as executadas entre o commit dos arquivos.
# git log -p -2 � mostra somente os 2 �ltimos commits.
# git log --stat � mostra o git log e as estat�sticas dos arquivos.
# git log --pretty=oneline
# git log --pretty=format:�%h - %an, %ar : %s�
