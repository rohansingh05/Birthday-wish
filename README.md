# How to deploy using GitHub Pages
## Changes the GitHub Pages Source Setting
- On GitHub, navigate to your repository's main page
- Click on the `Settings` tab located near the top navigation bar.
- In the left Sidebar, under the `Code, planning and automation` section, click on Pages.
- Under `Build and deployment`, look for the source dropdown and change it from `Deploy from a branch` to `GitHub Actions`.
## Create the Workflow File
- In the root directory of your local project, create a folder structure named `.github/workflows/`.
- Inside that folder, create a new file named `deploy.yml`
- Copy and paste one of the starter templates below depending on your project type.
## Commit and Push
Once your setting is updated and your workflow file is saved, commit your changes and push them to your repository.
