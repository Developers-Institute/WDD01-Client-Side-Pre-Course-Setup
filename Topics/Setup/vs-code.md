# Customise VS Code

<details>
   <summary>Disable VS-Code from auto-accepting code suggestions</summary>

Disable VS-Code from auto-accepting code suggestions (as it's suggestions are often wrong):

![Disable VS-Code from auto-accepting code suggestions](img/vscode%20tips%20-%20disable%20auto-accept%20suggestions.png)

</details>

<details>
   <summary>Set Visual Studio Code as Gits' default merge editor</summary>

Save yourself the hassle of having to learn terminal text editors (like vim) by running these 4 commands:

```bash
git config --global merge.tool vscode
git config --global mergetool.vscode.cmd "code --wait $MERGED"
git config --global diff.tool vscode
git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE"
```

`Note:` copy, paste and run the commands inside your terminal.

![Copy past terminal commands](../../img/copy_past_terminal.gif)

</details>

<details>
   <summary>Launching Visual Studio Code from the command line</summary>

You can also run VS Code from the terminal by typing 'code' after adding it to the path:

- Launch VS Code.
- Open the Command Palette (cmd + shift + p) and type `shell command` to find the Shell Command: `Install 'code' command in PATH` command.

  ![shell command](../../img/shell-command.png)

- Restart the terminal for the new \$PATH value to take effect. You'll be able to type 'code .' in any folder to start editing files in that folder.

</details>
