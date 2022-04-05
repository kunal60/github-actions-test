# github-actions-test

Course:   Udemy - The Complete GitHub Actions & Workflows Guide


Setting up project for the first time

Manually adding a .vscode folder
Using GUI might be cumbersome in some circumstances if you work in a team and every member has to use the same configuration. In this case, you can manually create a “.vscode” folder at the root of your project. After that, add a new “settings.json” and declare your settings here. Now you can easily share your settings with others by pushing to a git server or copying/pasting by hand.

https://www.kindacode.com/article/vs-code-how-to-use-custom-settings-for-a-project/

We also have .prettierc file. It allows you to format your code.
https://stackoverflow.com/questions/50975264/prettier-settings-for-vscode


1. Github workflows are written in the yaml format

To learn more about yaml, 
see this video: 002. a-brief-introduction-to-writing-in-yaml-format

2. In order to create a workflow, create q yaml inside .github/workflows folder.
We a creating a file name simple.yaml
