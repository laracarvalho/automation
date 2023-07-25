# Automation

Almost every program and runtime I need everytime I format my computer is in these files.

I've separated each file regarding where and how I want to install them.

I install chocolatey separately for troubleshooting.

Since I want to divide some programs based on which harddrive I have, the files are separated as well.


## Allow scripts in Powershell:
- Open PowerShell as Administrator;
- Add `set-executionpolicy unrestricted`;
- Check with `get-executionpolicy`;

## Installation:
- Open PowerShell as Administrator;
- Go to repo location;
- Run `.\chocolatey_install`;
- Run `.\c_install`;
- If needed, run `\.d_install`;

## Steps:
- Install Node with `nvm install latest` && `nvm use (latest_version)`;
- VS Code Settings Sync;
- Install WSL2 with `wsl --install`;
  - Create account;
  - Run `sudo apt update && sudo apt upgrade`;
  - Install Make inside WSL2 with `sudo apt install gcc build-essential make -y`; 
- Install Docker through the [website](https://docs.docker.com/desktop/windows/install/);
- Open Jackett to update qBit listings;

## Configs:
- Grab .dotfiles and drop them into `~`

## TODO:
- Automatize Docker installation;
- Automatize WSL2 and Make;
- Generate config for games (modlist, etc)