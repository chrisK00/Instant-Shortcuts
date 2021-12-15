 ## Open
 | Title                       | Command     |
 | --------------------------- | ----------- |
 | Open in VSCode              | **code .**  |
 | Open in file explorer       | **start .** |
 | Open in new terminal window | **start**   |

  ## General
 | Title                              | Command   |
 | ---------------------------------- | --------- |
 | Go back 1 folder                   | **cd..**  |
 | Go in to folder                    | **cd**    |
 | list files in open directory (win) | **dir**   |
 | list files in open directory       | **ls**    |
 | Create folder                      | **mkdir** |
 | Remove folder                      | **rmdir** |

## Git
 | Title                                                                          | Command                   |
 | ------------------------------------------------------------------------------ | ------------------------- |
 | initialize a local repo                                                        | **git init**              |
 | Track all files                                                                | **git add .**             |
 | Commit staged changes                                                          | **git commit -m**         |
 | Commit all changes                                                             | **git commit -am**        |
 | Reset changes in current branch                                                | **git reset --hard**      |
 | New branch and check it out                                                    | **git checkout -b**       |
 | New branch or view branches                                                    | **git branch**            |
 | Push branch to remote                                                          | **git push**              |
 | Rename branch                                                                  | **git branch -m**         |
 | Reset branch commits                                                           | **git reset HEAD~**       |
 | Remove changes                                                                 | **git reset --hard**      |
 | Branch status                                                                  | **git status** |
 | Merge branch                                                                   |  **git merge [from] [to]**          |
 | Merge conflict. Switch to the new branch, merge master in to it, fix conflicts |                           |

 ## dotnet cli
 | Title                                         | Command                                                      |
 | --------------------------------------------- | ------------------------------------------------------------ |
 | New app                                       | **dotnet new console/classlib**                              |
 | New app with name                             | **dotnet new console/classlib --name**                       |
 | Run and track code changes                    | **dotnet watch run**                                         |
 | run tests                                     | **dotnet test**                                              |
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

