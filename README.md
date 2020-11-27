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
code --install-extension bmewburn.vscode-intelephense-client
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension fabiospampinato.vscode-diff
code --install-extension felixfbecker.php-debug
code --install-extension felixfbecker.php-intellisense
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension hollowtree.vue-snippets
code --install-extension HvyIndustries.crane
code --install-extension Ionide.Ionide-fsharp
code --install-extension janisdd.vscode-edit-csv
code --install-extension kokororin.vscode-phpfmt
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-dotnettools.csharp
code --install-extension ms-vscode-remote.remote-containers
code --install-extension neilbrayfield.php-docblocker
code --install-extension octref.vetur
code --install-extension onecentlin.laravel-blade
code --install-extension pajdziu.trailingwhitespacehighlighter
code --install-extension redhat.vscode-yaml
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension vaughan.rdoc-readme
code --install-extension dart-code.flutter
```

```
atlassian.atlascode
bmewburn.vscode-intelephense-client
dbaeumer.vscode-eslint
eamodio.gitlens
fabiospampinato.vscode-diff
felixfbecker.php-debug
felixfbecker.php-intellisense
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
hollowtree.vue-snippets
HvyIndustries.crane
Ionide.Ionide-fsharp
janisdd.vscode-edit-csv
kokororin.vscode-phpfmt
ms-azuretools.vscode-docker
ms-dotnettools.csharp
ms-vscode-remote.remote-containers
neilbrayfield.php-docblocker
octref.vetur
onecentlin.laravel-blade
pajdziu.trailingwhitespacehighlighter
redhat.vscode-yaml
streetsidesoftware.code-spell-checker
vaughan.rdoc-readme
dart-code.flutter
```
