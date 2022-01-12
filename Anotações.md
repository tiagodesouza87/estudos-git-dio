#Gerar chave SSH para Github

No git Bash:
 ssh-keygen -t ed25519 -C email

Ler chave pública:
cd /c/Users/3159021/.ssh (Linux: /home/usuario/.ssh)
cat id_ed25519.pub

Ir na sessão SSH and GPG Keys, criar nova chave SSH e colar conteúdo do arquivo de chave pública.

Associando chave privada ao SSH:

$ eval $(ssh-agent -s)
 ssh-add id_ed25519

Token de acesso pessoal:

SSH and GPG Keys > New Personal Token

Salvar token na máquina

Primeiros passos com git

git init - Cria repositório
git config --global user.email "email"
git config --global user.name nome

git config --global –unset user.name

git add > adiciona arquivo ao repositório

git commit

Criar repositório git-hub: Meus repositórios > Novo

Subir repositório
git push repositório_remoto branch

Obs: typora - Editor de arquivos md. Git formata por padrão arquivos .md.

git clone

git pull - Juntar versões,puxando alterações do gt-hub

