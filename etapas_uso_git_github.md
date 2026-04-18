ETAPAS GIT E GITHUB

1. Criar uma pasta do projeto
2. Criar um arquivo markdown no R ou CodeVS Readme.md
3. Colocar no Git Bash o caminho da pasta do projeto com cd + caminho da pasta entre aspas
4. Escrever git init no git bash: isso deixará o projeto dentro da branch Master
5. Aparecerá uma pasta dentro da pasta do projeto chamada .git
6. git add:indica qual arquivo quer enviar para área de stading
7. git status: status do novo arquivo enviado, ou seja, o Readme.md
8. git commit -m: escreve entre aspas o que quer adicionar no arquivo enviado,
após isso ocorrerá uma modificação dentro do arquivo
9. git status: vai dizer que não tem nada novo para fazer commit
10. git branch -M "main": transferir o arquivo da branch principal Master para branch main
11. Criar um repositório no GitHub do que já foi criado na nossa pasta do computador pessoal
12. Mandar os arquivos do repositório da máquina pessoal para o GitHub
13. git remote add origin https://github.com/francojra/ProjetoGit.git  
14. O nome origin é um padrão que indica a origem do repositório, no caso, do GitHub
15. git push -u origin main : faz o empurrão dos commits do repositório local para o GitHub
16. Criar novo arquivo .md na pasta do computador pessoal
17. git add . para subir todos os arquivos para a área stading, para comitar um unico arquivo, coloca
o nome do arquivo após o git add
18. git status
19. git commit -m "criação do projeto": esse commit -m vai apenas para o repositorio da máquina
e não do GitHub
20. git push origin main
21. O remote só é necessário fazer uma vez
22. Ao clicar no nome do arquivo que aparece no github "criacao projeto", vai mostrar todas as alterações, 
em vermelho o que foi retirado e em verde o que foi adicionado.
23. Em "commits" aparece quem fez o commit, a hora e data.
24. git checkout -b "novo-botao": cria nova branch
25. git checkout main: volta para a branch principal
26. git checkout novo-botao: volta para a branch criada
27. git merge novo-botao: une a branch criada a principal main

