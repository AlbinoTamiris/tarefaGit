# Aprendizado de Git e GitHub

Este repositório documenta o aprendizado e a execução de comandos no **Git** e **GitHub** para controle de versão e publicação de sites.

## O que eu aprendi:

1. **Git Basics**:
   - Inicialização de repositórios:  
     ```bash
     git init
     ```
   - Adição de arquivos para commit:  
     ```bash
     git add .
     ```
   - Registro de alterações (commit):  
     ```bash
     git commit -m "mensagem do commit"
     ```
   - Sincronização com repositório remoto:  
     ```bash
     git push origin master
     git pull origin master
     ```

2. **GitHub Pages**:
   - Criação de uma branch `gh-pages` para deploy:
     ```bash
     git branch gh-pages
     git checkout gh-pages
     ```
   - Publicação de um arquivo `index.html`:
     ```bash
     git add index.html
     git commit -m "Criar index.html"
     git push origin gh-pages
     ```

3. **Gerenciamento de Branches**:
   - Criação e alternância entre branches:
     ```bash
     git branch <nome-da-branch>
     git checkout <nome-da-branch>
     ```
   - Exclusão de uma branch:
     ```bash
     git branch -D <nome-da-branch>
     ```

4. **Pull Requests**:
   - Criação de Pull Requests no GitHub para comparar e integrar mudanças entre branches.
   
Acesse minha página no GitHub:  
[Minha Página GitHub](https://AlbinoTamiris.github.io/tarefaGit/)

