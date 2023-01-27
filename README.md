<a href="https://gitpod.io/#https://github.com/ConcaveFi/bashcave">
  <img
    src="https://img.shields.io/badge/Contribute%20with-Gitpod-908a85?logo=gitpod"
    alt="Contribute with Gitpod"
  />
</a>

# Bashcave

## **Disclamer**
> “Please read and understand any scripts before running them on your machine.
> *Or click on the Git Pod link above to run them*


## Install

Copie Past the scripts you want to use into a directory of your choice.
Then add the folder to your `$PATH`

```sh
# make any script executalbe
cd /path/to/my_script_folder
chomd +x copied_bash_script

# add this line at the end of your bash-profile
export PATH=$PATH:/path/to/my_script_folder
```

## Usage

All bash scripts inside the folder `scripts/` do not need to be edited. Other folders may require you to edit them to enter your API key. Most of the scripts will require you to have at least`curl` installed, but some may also require `jq`. If a script needs it, it will check if that CLI tool exists on your machine first.

```sh
sudo apt install curl jq
```