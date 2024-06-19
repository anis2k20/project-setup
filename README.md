How to clone specific folder from git repository?

1. `git init <local-repo>`
2. `cd <local-repo>`
3. `git remote add -f origin <url>`
4. `git config core.sparseCheckout true`
5. `git sparse-checkout set <folder-name>`
6. `git pull origin main/master`
7. `git sparse-checkout disable`
