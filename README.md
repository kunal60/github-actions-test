# github-actions-test

Course:   Udemy - The Complete GitHub Actions & Workflows Guide


Setting up project for the first time

Manually adding a .vscode folder
Using GUI might be cumbersome in some circumstances if you work in a team and every member has to use the same configuration. In this case, you can manually create a “.vscode” folder at the root of your project. After that, add a new “settings.json” and declare your settings here. Now you can easily share your settings with others by pushing to a git server or copying/pasting by hand.

https://www.kindacode.com/article/vs-code-how-to-use-custom-settings-for-a-project/

We also have .prettierc file. It allows you to format your code.
https://stackoverflow.com/questions/50975264/prettier-settings-for-vscode


Video:2 
Github workflows are written in the yaml format

To learn more about yaml, 
see this video: 002. a-brief-introduction-to-writing-in-yaml-format

Video:3
In order to create a workflow, create a yaml inside .github/workflows folder.
We a creating a file name simple.yaml
See Example: Examples/Chapter1.yaml

Video:4
These are the different shells supported per OS in Github
https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#jobsjob_idstepsshell

1. In this video, we will add a  python shell.
2. We are going to use bash in windows machine. We are going to do it in a new job because we need a need OS, which
is windows. Each job will run parallel on its own virtual machine.
So, we need to add a new job (run-windows-commands) in the same file, same as we did for the previous job name: run-shell-command:
