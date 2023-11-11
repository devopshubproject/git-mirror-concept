## Follow these straightforward steps to set up GitLab and GitHub repository mirroring:


![gitlab_github](docs/images/gitlab_github.png)

### Choose a Name:

Select a name for your repository, e.g., __*git-mirror-concept*__.

### Create GitLab Repository:

Set up a new repository on GitLab for your project.

### Create GitHub Repository:

Establish a corresponding repository on GitHub for seamless mirroring.

### Generate GitHub Token:

Generate a GitHub personal access token with the 'public_repo' option enabled. Save this token for later use.

### Configure GitLab Repository:

In your GitLab repository, navigate to Settings → Repository → Mirroring repositories.

### Fill in URL and Token:

Enter the GitHub repository URL and the token you generated. Set mirror direction to 'push,' and choose 'password' as the authentication method, then input the token.

### GitHub Repository URL Format:

Use the following format for the GitHub repository URL:
https://<your_github_username>@github.com/<your_github_username>/<your_github_project>.git
Example: __*https://premkumar-palanichamy@github.com/devopshubproject/git-mirror-concept.git*__

### Completion:

Your GitLab repository is now mirrored to GitHub successfully.

Follow these steps for a seamless setup of Git repository mirroring between GitLab and GitHub.