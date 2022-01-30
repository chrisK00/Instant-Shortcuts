 ## Open
 | Title                               | Command              |
 | ----------------------------------- | -------------------- |
 | Open in VSCode                      | **code .**           |
 | Open in file explorer               | **start .**          |
 | Open new window/open specified file | **start [fileName]** |

  ## General
 | Title                              | Command                   |
 | ---------------------------------- | ------------------------- |
 | Go back 1 folder                   | **cd..**                  |
 | Go in to folder                    | **cd**                    |
 | list files in open directory (win) | **dir**                   |
 | list files in open directory       | **ls**                    |
 | Create folder                      | **mkdir**                 |
 | Remove folder                      | **rmdir**                 |
 | pwd                                | **get current path**      |
 | shutdown in x seconds              | **shutdown -s -t [time]** |

## Git
 | Title                                                                          | Command                     |
 | ------------------------------------------------------------------------------ | --------------------------- |
 | initialize a local repo                                                        | **git init**                |
 | Track all files                                                                | **git add .**               |
 | Commit staged changes                                                          | **git commit -m**           |
 | Commit all changes                                                             | **git commit -am**          |
 | Reset changes in current branch                                                | **git reset --hard**        |
 | New branch and check it out                                                    | **git checkout -b**         |
 | New branch or view branches                                                    | **git branch**              |
 | Push branch to remote                                                          | **git push**                |
 | Rename branch                                                                  | **git branch -m**           |
 | Remove branch                                                                  | **git branch -d [name]**    |
 | List branches                                                                  | **git branch -l**           |
 | Reset last commit but keep changes                                             | **git reset HEAD~**         |
 | Remove changes                                                                 | **git reset --hard**        |
 | Unstage last commit but keep changes                                           | **git reset HEAD~1 --soft** |
 | Branch status                                                                  | **git merge [from] [to]**   |
 | Merge branch                                                                   | **git status**              |
 | save changes so you can checkout another branch                                | **git stash**               |
 | get back changes                                                               | **git stash pop**           |
 | Merge conflict. Switch to the new branch, merge master in to it, fix conflicts |                             |

 ## dotnet cli
 | Title                                         | Command                                                      |
 | --------------------------------------------- | ------------------------------------------------------------ |
 | New app                                       | **dotnet new console/classlib**                              |
 | add package                                   | **dotnet add package [name]**                                |
 | New app with name                             | **dotnet new console/classlib --name**                       |
 | Run and track code changes                    | **dotnet watch run**                                         |
 | run tests                                     | **dotnet test**                                              |
 | list templates                                | **dotnet new -l**                                            |
 | build project (becomes IL files .dll)         | **dotnet build**                                             |
 | restore dependencies                          | **dotnet restore**                                           |
 | list tools                                    | **dotnet tool list -g**                                      |
 | remove tool                                   | **dotnet tool uninstall packageName -g**                     |
 | New solution                                  | **dotnet new sln -o [name]**                                 |
 | add project to sln                            | **dotnet sln [name] add [name]**                             |
 | add a user secrets file                       | **dotnet user-secrets init**                                 |
 | add a key to user secrets and specify project | **dotnet user-secrets set "Class:Property" "Key" --project** |

 ## Angular CLI
 | Title                        | Command                                   |
 | ---------------------------- | ----------------------------------------- |
 | Run                          | **ng serve**                              |
 | Run and open                 | **ng serve --open**                       |
 | Add Service                  | **ng g s --skip-tests**                   |
 | Add Component                | **ng g c --skip-tests**                   |
 | Add bootstrap                | **ng add ngx-bootstrap**                  |
 | Add schematics for bootstrap | **npm install @schematics/angular@9.1.0** |
 | Install CLI                  | **npm install -g @angular/cli**           |
 | Add Interface                | **ng g interface**                        |


## Node CLI
| Title                    | Command                     |
| ------------------------ | --------------------------- |
| Init                     | **npm init**                |
| run tests                | **npm test**                |
| run app                  | **npm run**                 |
| install package          | **npm i [name]**            |
| uninstall package        | **npm un [name]**           |
| update package           | **npm up [name]**           |
| install package dev mode | **npm i [name] --save-dev** |
| install globally         | **npm i -g [name]**         |


## docker in Powershell
| Title                   | Command              |
| ----------------------- | -------------------- |
| list running containers | **docker ps**        |
| attach to console       | **docker attach**    |
| list images             | **docker images**    |
| run image               | **docker run**       |
| view network tasks      | **netstat -a -n -o** |
| kill task               | **-f /pid [number]** |

#### Resources
- [common git commands]( http://guides.beanstalkapp.com/version-control/common-git-commands.html)

