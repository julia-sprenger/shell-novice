---
title: Setup
---

## Download files

You need to download some files to follow this lesson.

1. Download [shell-lesson-data.zip][zip-file] and move the file to your Desktop.
2. Unzip/extract the file.
  **Let your instructor know if you need help with this step**.
  You should end up with a new folder called **`shell-lesson-data`** on your Desktop.

## Install software

In this workshop we will use the `git bash` shell within Visual Studio Code. See instructions on how to install both tools on the dedicated workshop page.

## Open a new shell

After installing the software

3. Open the VSCode Terminal view
  Use `View` > `Terminal` to open the terminal view in VSCode
  ![](fig/VSCode_open_terminal.png){alt='Open the terminal panel via `View` > `Terminal`'}
4. Open a Git Bash panel
  Use the `+` option in the terminal view to open a git bash terminal.
  ![](fig/VSCode_open_git_bash.png){alt='Open the terminal panel via `+` > `Git Bash`'}

5. In the terminal type `cd ~` then press the <kbd>Return</kbd> key.
  This step will make sure you start with your home folder as your working directory.

In the lesson, you will find out how to access the data files in this folder.

:::::::::::::::::::::::::::::::::::::::::  callout

## Where to type commands: How to open a new shell

The shell is a program that enables us to send commands to the computer and receive output.
It is also referred to as the terminal or command line.

Different types of shell programs exist. The default on OECD Windows is `Powershell`, but for compatibility with `git` and other Unix based tools we will use the `Git Bash` as default in this workshop. Note that most Unix-based shells behave very similar, so many commands you learn here will also apply on most Unix-based systems and shells. `Powershell` and other Windows based systems however share only a very small set of common commands. We recommend for shell based work to rely on Unix-based shells, here `Bash`, which we installed together with git as `Git Bash`.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::: solution

### Windows {#windows}

Computers with Windows operating systems do not automatically have a Unix Shell program
installed.
In this lesson, we encourage you to use an emulator included in [Git for Windows][install_shell],
which gives you access to both Bash shell commands and Git.

Once installed, you can open a terminal by running the program Git Bash from the Windows start
menu.

**For advanced users:**

As an alternative to Git for Windows you may wish to [Install the Windows Subsystem for Linux][wsl]
which gives access to a Bash shell command-line tool in Windows 10 and above.

Please note that commands in the Windows Subsystem for Linux (WSL) may differ slightly
from those shown in the lesson or presented in the workshop.

::::::::::::


[zip-file]: data/shell-lesson-data.zip
[install_shell]: https://carpentries.github.io/workshop-template/install_instructions/#shell
[wsl]: https://learn.microsoft.com/en-us/windows/wsl/install
[gnome-terminal]: https://help.gnome.org/users/gnome-terminal/stable/
[kde-konsole]: https://konsole.kde.org/
[xterm]: https://en.wikipedia.org/wiki/Xterm



