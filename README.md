Codeowner Instructions:-

1) go to settings --> branches --> add bracnch protection --> specify your branch --> select checkboxes 1. require a pull before merging 2. require approvals

2) Make CODEOWNER file
   specify the reviewer in the file eg. (* @aditya0660) to review everything before commit.

3) configure pre-commit

  pip install pre-commit

  Create a file named .pre-commit-config.yaml in the root of your repository. 

  Run the following command to install the pre-commit hooks defined in the configuration file:

  Create a .github/workflows/pre-commit.yml file in your repository

  Commit the changes made

  then push the changes to your GitHub repository.
