# GITHUB Actions and Powershell scripts
Quick setup for GitHub Actions using PowerShell scripts to interact with the Umbraco Cloud CI/CD Flow endpoints.

1. Place the [`cloud.zipignore`](../../../cloud.zipignore) from the root of this repository, in the root of your repository.
2. Copy the yaml-scripts from this folder into your `.github/workflows` folder.
3. Powershell scripts should be placed in `.github/powershell`.
    - Feel free to place scripts somewhere else, but you need to update the paths in the `cloud-sync.yml` and `cloud-deployment.yml`
4. Make a copy of the `.gitignore` from the Cloud Project Repository (not from this sample repository)
    1. Call the copy `cloud.gitignore`
    2. place both files in the root of your repository
