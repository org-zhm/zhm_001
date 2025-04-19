## Introduction
You only need a GitHub repository to create and run a GitHub Actions workflow. In this guide, you'll add a workflow that demonstrates some of the essential features of GitHub Actions.

The following example shows you how GitHub Actions jobs can be automatically triggered, where they run, and how they can interact with the code in your repository.

### Creating your first workflow
Create a .github/workflows directory in your repository on GitHub if this directory does not already exist.

In the .github/workflows directory, create a file named github-actions-demo.yml. For more information, see "Creating new files."

Copy the following YAML contents into the github-actions-demo.yml file:

提交这些更改并将其推送到您的 GitHub 仓库。

您的新 GitHub Actions 工作流程文件现在安装在您的仓库中，每次有人推送更改到仓库时都会自动运行。 若要查看关于工作流执行历史记录的详细信息，请参阅“查看工作流运行的活动”。
