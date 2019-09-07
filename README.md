# demo-repo
Udemy practice repo.
This repo is for the practice purpose of udemy lectures on git.

## How to install git
In this section, we'll see how to install git on ubuntu 18.04.1 LTS \(bionic\) x86_64 processor

[Online link](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-18-04-quickstart)

Follow below steps,

1. Update default packages <br>
   `sudo apt update`
2. Install Git <br>
   `sudo apt install git`
3. Verify Git version <br>
   `git --version`
4. Configure Git <br>
   `git config --global user.name "Steve Jobs"` <br>
   `git config --global user.email "stevejobs@apple.com"` <br>
   This will configure our name and email address across all git local repositories, as we used the `--global` option. All our commits will have this `user.name` and `user.email` associated with them. Also, this information is recorded in `~/.gitconfig` file which can be edited later to add more custom settings for git.
