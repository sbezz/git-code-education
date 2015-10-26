# Instalação OK
# Comando:
# mkdir aulagit (criar diretório)
# cd aulagit (acessar diretório)
# git init (inicializar a pasta)
# É criado um diretório .git/ (diretório oculto)
# Para visualizar comando -> ls –la
# Este diretório .git/ é o diretório responsável pelo controle de versão.
# touch – Comando usado para criar arquivos.
# Comando:
# touch arquivo.txt 
# Editar o arquivo
# git status (verificar status do controle).

# Estágios do commit.

# 1° Estágio – Arquivos não untracked (sem controle de versão).
# 2° Estágio – Comando: git add nomedoarquivo
	O arquivo fica pronto para o controle de versão após commit.
# 3° Estágio – Comando: git commit –m “meu Primeiro commit”
	Agora o arquivo esta fazendo parte do controle de versão.
	Comando: git log (apresenta o log)

# Comando: 
# git commit – irá abrir um arquivo de texto para descrever todas as alterações efetuadas nos arquivos.
# git add . – Irá adicionar todos os arquivos alterados.
# git commit -a –m “commitando arquivos”
# 	-a insere os arquivos para commitar

# Comandos Git log:
# *para sair da visualização “q”
# git log -p – mostra as diferenças executadas entre o commit dos arquivos.
# git log -p -2 – mostra somente os 2 últimos commits.
# git log --stat – mostra o git log e as estatísticas dos arquivos.
# git log --pretty=oneline
# git log --pretty=format:”%h - %an, %ar : %s”
