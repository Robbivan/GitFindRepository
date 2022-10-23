# Git Find Repository

## :computer: About 

Find the local repository via the name of the remote repository git 

*Shell (Bash) utility for MacOS and Linux*

___
## :exclamation: More Info
Use the utility name `gitfdir`

The utility has the ability to issue recommendations for similar names of local repositories by the name of the remote repository

Both Camel Case, Snake Case and their sharing are supported

![](https://github.com/robbivan/dirt/blob/main/image.png)

___
## :gear: Install
:hammer: An easy way
```bash
  # Clone a repository
  git clone https://github.com/robbivan/GitFindRepository
  cd GitFindRepository

  #installation via the installer
  ./installer

```
:hand: Manually

```bash
  # Clone a repository
  git clone https://github.com/robbivan/GitFindRepository

  #creating a soft link to the utility and change owner
  sudo ln -s "`pwd`/gitfdir" /usr/local/bin
  sudo chown -Rh $USER /usr/local/bin/gitfdir

```
___
## :broken_heart: Uninstall
:sweat_drops: In the folder where the utility is installed
```bash
  ./uninstaller
```
___
### Author

**Ivan Vasilyev (robbivan)**

* [GitHub Profile](https://github.com/robbivan)


### License

Copyright © 2022, [Ivan Vasilyev](https://github.com/robbivan).  
Released under the [MIT License](LICENSE).



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
