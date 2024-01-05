#Descrição
O Git é um sistema de controle de versão distribuído amplamente utilizado para o rastreamento de alterações em projetos de software. Ele foi criado por Linus Torvalds em 2005 para o desenvolvimento do kernel do Linux, mas desde então tornou-se uma ferramenta essencial em muitos projetos de software em todo o mundo.

O Git permite que vários desenvolvedores colaborem em um projeto, mantendo um histórico completo das alterações feitas no código-fonte. Ele oferece recursos poderosos, como ramificação (branching), mesclagem (merging), e histórico de alterações eficiente. Com o Git, os desenvolvedores podem trabalhar em diferentes partes de um projeto simultaneamente, sem interferir no trabalho um do outro.

#Principais comandos:

##Configuração Inicial:

git config --global user.name "Seu Nome": Define o nome do usuário globalmente.
git config --global user.email "seu@email.com": Define o e-mail do usuário globalmente.

##Iniciar um Repositório:

git init: Inicia um novo repositório Git.

##Clonar um Repositório:

git clone <URL do repositório>: Clona um repositório remoto para o seu sistema local.

##Trabalhar com Alterações Locais:

git status: Mostra o status das alterações no seu diretório de trabalho.
git add <nome do arquivo>: Adiciona um arquivo ao próximo commit.
git add .: Adiciona todas as alterações ao próximo commit.
git commit -m "Mensagem do commit": Registra as alterações no repositório.

##Visualizar Histórico:

git log: Mostra o histórico de commits.
git log --oneline: Mostra o histórico de commits de forma resumida.

##Branches:

git branch: Lista as branches no repositório.
git branch <nome da branch>: Cria uma nova branch.
git checkout <nome da branch>: Muda para uma branch específica.
git merge <nome da branch>: Mescla uma branch na branch atual.
git branch -d <nome da branch>: Deleta uma branch local.

##Atualizar e Publicar Alterações:

git pull: Obtém as alterações do repositório remoto.
git push: Envia as alterações locais para o repositório remoto.

##Resolver Conflitos:

Durante um merge, pode haver conflitos. Use um editor ou ferramentas gráficas para resolver.

##Desfazer Alterações:

git reset --hard: Desfaz todas as alterações no diretório de trabalho.
git revert <hash do commit>: Cria um novo commit que desfaz as alterações de um commit específico.

##Outros Comandos Úteis:

git remote -v: Lista os repositórios remotos.
git diff: Mostra as diferenças entre o diretório de trabalho e a versão mais recente do repositório.
git stash: Salva as alterações locais temporariamente para poder mudar de branch.
