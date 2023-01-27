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

All bash scripts inside the foler `scripts` do not need to be edited.
Other folder myght need you to edite then to enter your api key.
Most of the script will require your to have at least `curl` installed but also `jq`.
If some script need it they will check if that cli-tool exist on your machine first.

```sh
sudo apt install curl jq
```