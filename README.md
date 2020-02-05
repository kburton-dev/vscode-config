# VSCode Settings

My personal Visual Studio Code settings.

_The purpose is to keep my machines in sync with one another._

## Syncing (using Symlink)

```
ln -s ~/projects/vscode-config/settings.json ~/.config/Code/User/settings.json
ln -s ~/projects/vscode-config/keybindings.json ~/.config/Code/User/keybindings.json
ln -s ~/projects/vscode-config/snippets ~/.config/Code/User/
```

### Windows
```
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\settings.json settings.json
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\keybindings.json keybindings.json
mklink /J %HOMEPATH%\AppData\Roaming\Code\User\snippets snippets
```

## Installed Extensions

```
code --install-extension atlassian.atlascode
code --install-extension batisteo.vscode-django
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension dbaeumer.vscode-eslint
code --install-extension donjayamanne.python-extension-pack
code --install-extension eamodio.gitlens
code --install-extension fabiospampinato.vscode-diff
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension janisdd.vscode-edit-csv
code --install-extension kokororin.vscode-phpfmt
code --install-extension magicstack.MagicPython
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-python.python
code --install-extension msjsdiag.vscode-react-native
code --install-extension neilbrayfield.php-docblocker
code --install-extension octref.vetur
code --install-extension pajdziu.trailingwhitespacehighlighter
code --install-extension redhat.vscode-yaml
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension tushortz.python-extended-snippets
code --install-extension vaughan.rdoc-readme
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension wholroyd.jinja
```
