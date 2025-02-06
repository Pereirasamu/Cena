Configuração Inicial
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
Configura seu nome e email para os commits.
Criando ou Obtendo um Repositório
Copiar Editar
git init
Inicializa um novo repositório Git.
Copiar Editar
git clone URL_DO_REPOSITORIO
Clona um repositório remoto para sua máquina.
Trabalhando com Arquivos
Copiar Editar
git status
Verifica o status dos arquivos no repositório.
Copiar Editar
git add .
Adiciona todos os arquivos modificados para o commit.
Copiar Editar
git commit -m "Mensagem do commit"
Salva as mudanças no histórico do Git.
Copiar Editar
git log --oneline --graph --all
Exibe um histórico resumido dos commits.
Trabalhando com Branches
Copiar Editar
git branch nome-da-branch
Cria uma nova branch.
Copiar Editar
git switch nome-da-branch
# ou
git checkout nome-da-branch
Muda para outra branch.
Copiar Editar
git merge nome-da-branch
Mescla uma branch na branch atual.

Enviando e Buscando Alterações
Copiar Editar
git pull origin main
Baixa as últimas atualizações do repositório remoto.
Copiar Editar
git push origin main
Envia seus commits para o repositório remoto.
Desfazendo Alterações
Copiar Editar
git reset --soft HEAD~1
Desfaz o último commit, mas mantém as alterações.
Copiar Editar
git reset --hard HEAD~1
Desfaz o último commit e as alterações no código.
Copiar Editar
git checkout -- nome-do-arquivo
Restaura um arquivo para sua última versão confirmada.
