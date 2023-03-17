#SOLinux
## configuração do repositório no GitHub
### Exemplo...
git init <project directory>

cd /path/to/project
echo "test content for git tutorial" >>
git add CommitTest.txt 
git commit -m "added CommitTest.txt to the repo"
git remote add <remote_name> <remote_repo_url>
git push -u <remote_name> <local_branch_name>

Este comando vai colocar a ramificação do
repositório local sob < local_branch_name >
no repositório remoto em < remote_name >.



