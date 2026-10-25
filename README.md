# Sitewright
A simple website creator that hosts on GitHub.

1. Create the repo first
On github.com, click New repository, name it (for example my-site), and tick Add a README so the repo has a main branch. Fine-grained tokens can only be limited to repos that already exist.

2. Open token settings
Click your profile photo, then Settings. At the bottom of the left sidebar choose Developer settings, then Personal access tokens, then Fine-grained tokens.

3. Generate new token
Click Generate new token. Give it a name like Sitewright, and set an expiry (30 to 90 days is a sensible choice).

4. Limit it to your site repo
Under Repository access, choose Only select repositories and pick the repo from step 1. This keeps the token from touching anything else on your account.

5. Set the permissions
Under Permissions, open Repository permissions and set Contents to Read and write, and Pages to Read and write. Metadata (read) is added automatically. You don't need Administration unless you want the tool to create repos.

6. Generate and copy it
Click Generate token, then copy the token that starts with github_pat_. GitHub only shows it once. Paste it into Sitewright's GitHub settings along with yourname/my-site.
