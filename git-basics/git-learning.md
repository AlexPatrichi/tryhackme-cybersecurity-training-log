Git & Bash Learning Log

This file documents my hands-on learning of Git, GitHub, and Bash commands.  
It shows progression, workflow practices, and lessons learned while building my cybersecurity training portfolio.  

------

Entry 1: Repository Setup

>Created a GitHub repository for my portfolio  
>Cloned the repository locally  
>Learned the difference between local repository and remote repository  
>Learned how Git tracks files, not empty folders  
>
>Key Commands
>git clone https://github.com/AlexPatrichi/tryhackme-cybersecurity-training-log.git  
>pwd  
>ls

------

Entry 2: Adding Files & Folders

>Created /tryhackme folder for lab files  
>Learned Git ignores empty folders, so I added a .gitkeep file  
>Created first lab file world-wide-web.md to track lab work  
>
>Key Commands
>mkdir tryhackme  
>touch tryhackme/.gitkeep  
>touch tryhackme/world-wide-web.md  
>git status  
>git add tryhackme  
>git commit -m "Add tryhackme folder"  
>git push  

------

Entry 3: Markdown Syntax & Documentation Skills

> 1. Learned Markdown syntax for technical documentation
> 2. Used headings, lists, code blocks, and inline code
> 3. Structured content for clarity and readability
> 4. GitHub-friendly layout
> 5. Understood the importance of documentation in tech and cybersecurity

------

Entry 4: README.md Updates

>Learned to pull latest changes before editing (git pull)  
>Edited README.md to include updates  
>Learned proper Markdown formatting:  
>	-Code blocks for folder structure  
>	-Headings for sections  
>	-Bullets for readability  
>
>Key Commands
>git pull origin main  
>git add README.md  
>git commit -m "Update formatting"  
>git push  

------

Entry 5: Merge Conflicts

>Experienced a merge conflict in README.md  
>Learned to resolve by:  
>	-Identifying conflict markers <<<<<<< HEAD, =======, >>>>>>> origin/main  
>	-Deciding which changes to keep  
>	-Saving, staging, and committing the resolved file  
>
>Key Commands  
>git add README.md  
>git commit -m "Resolve merge conflict in README.md"  
>git push  

------

Entry 6: GitHub Desktop vs Git Bash

> - Learned the differences between using GitHub Desktop and Git Bash  
> - Desktop is easier for beginners; Bash is more flexible and professional  
> - Bash enables advanced workflows, scripting, and working on servers  