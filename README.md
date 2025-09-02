# neovim-windows
Minimal setup of Neovim for Windows

## Scoop
install [scoop](https://scoop.sh/) as your package manager for Windows just in case your computer lab has Admin password 
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Install NodeJS via Scoop
Enabled Scoop First (ignore if prompt 'main' is already there)
```
scoop bucket add main
```
Copy this command to install nodejs
```
scoop install main/nodejs
```

## Install Neovim via Scoop
```
scoop install main/neovim
```

## Clone Repository
Open your favorite terminal and go to this directory
```
cd AppData/Local
```
Clone the repo
```
git clone https://github.com/yncy0/neovim-windows.git nvim
```
