# vscode-bug-demo
code sample of issue: https://github.com/microsoft/vscode/issues/114521

Steps to Reproduce:

1. Clone code to WSL (e.g. `/home/user/portal`), and connect to Ubuntu18.04 subsystem using `remote - WSL`,open `portal` folder.

2. add `modules/a` to workspace.

3. open `modules` in left file explorer, just keep `modules/a` folder closed.

4. When I add or delete files in the workspace, the outside `a` folder is automatically closed.

![image](https://github.com/grant-ymy/vscode-bug-demo/blob/main/pics/5.gif)
