# Choosing and using a workflow template

1. On GitHub, navigate to the main page of the repository.

2. Under your repository name, click  Actions.
   Screenshot of the tabs for the "github/docs" repository. The "Actions" tab is highlighted with an orange outline.

3. If you already have a workflow in your repository, click New workflow.

4. The "Choose a workflow" page shows a selection of recommended workflow templates. 
   Find the workflow template that you want to use, then click Configure. 
   To help you find the workflow template that you want, you can search for keywords or filter by category.

5. If the workflow template contains comments detailing additional setup steps, follow these steps.

6. There are guides to accompany many of the workflow templates for building and testing projects. For more information, see "Building and testing."

7. Some workflow templates use secrets. For example, ${{ secrets.npm_token }}. If the workflow template uses a secret, store the value described in the secret name as a secret in your repository. For more information, see "Using secrets in GitHub Actions."

8. Optionally, make additional changes. For example, you might want to change the value of on to change when the workflow runs.

9. Click Start commit.

10. Write a commit message and decide whether to commit directly to the default branch or to open a pull request.