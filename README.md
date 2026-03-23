# Proj-Font-End-Prof-Weslegit log


O Git é uma ferramenta indispensável para desenvolvedores de software, e aprender seus comandos principais pode transformar seu fluxo de trabalho e a maneira como você gerencia projetos. Aqui está um guia para ajudá-lo a entender e dominar os comandos mais úteis do Git.

1. Inicializando e Clonando Repositórios

git init: Inicializa um novo repositório Git em seu diretório local. É o ponto de partida para começar a usar o Git.
Exemplo: git init
git clone: Faz o download de um repositório remoto para o seu computador. Ideal para começar a trabalhar em um projeto existente.
Exemplo: git clone https://github.com/usuario/repo.git
2. Rastreando Alterações

git status: Exibe o estado atual do repositório, mostrando arquivos modificados, adicionados ou não rastreados.
Exemplo: git status
git add: Adiciona alterações ao índice para serem incluídas no próximo commit.
Exemplo: git add arquivo.txt ou git add . (para todos os arquivos)
git commit: Salva as alterações realizadas no repositório com uma mensagem explicativa.
Exemplo: git commit -m "Adicionei um novo recurso"
3. Trabalhando com Branches

git branch: Mostra todas as ramificações existentes no repositório e permite criar novas.
Exemplo: git branch ou git branch nova-branch
git checkout: Permite alternar entre branches ou restaurar arquivos.
Exemplo: git checkout nova-branch
git switch: Alterna entre branches (versão mais moderna que checkout).
Exemplo: git switch nova-branch
4. Sincronizando com Repositórios Remotos

git push: Envia as alterações locais para o repositório remoto.
Exemplo: git push origin main
git pull: Baixa alterações feitas no repositório remoto para o repositório local.
Exemplo: git pull origin main
git fetch: Busca as alterações do repositório remoto sem mesclá-las imediatamente.
Exemplo: git fetch origin
5. Lidando com Conflitos e Histórico

git merge: Mescla alterações de uma branch com outra.
Exemplo: git merge nova-branch
git log: Mostra o histórico de commits do repositório.
Exemplo: git log
git diff: Exibe diferenças entre versões de arquivos.
Exemplo: git diff
6. Configurações Básicas

git config: Configura informações globais como nome de usuário e e-mail.
Exemplo:
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@dominio.com"
7. Restaurando Alterações

git reset: Remove alterações do índice ou reverte commits.
Exemplo: git reset HEAD arquivo.txt
git restore: Restaura arquivos modificados para seu estado original.
Exemplo: git restore arquivo.txt