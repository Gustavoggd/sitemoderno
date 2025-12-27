# sitewolverenio

Site de demonstração "Enio TV Alternativa" — site em Flask com templates Jinja2, CSS responsivo e scripts de frontend para menu móvel e modal de imagens.

Como publicar (no seu PC):

1. Abra o terminal na pasta do projeto:
   cd "c:\Users\gusta\OneDrive\Área de Trabalho\projetos\sitemodernoenio"

2. Inicialize (se necessário), comite e faça o push:

```powershell
# inicializar repositório (se ainda não existe)
git init

git add .

git commit -m "Initial commit: preparar para publicação"

git branch -M main

git remote add origin https://github.com/Gustavoggd/sitewolverenio.git

git push -u origin main
```

3. Se houver solicitação de credenciais ao usar HTTPS, gere um Personal Access Token (PAT) e use-o como senha, ou configure o GitHub CLI:

```powershell
# Instale e faça login com gh (opcional)
choco install gh -y  # Windows/Chocolatey (ou https://cli.github.com/)
gh auth login
```

Se preferir, posso instruir passo a passo para configurar autenticação com PAT ou SSH.
